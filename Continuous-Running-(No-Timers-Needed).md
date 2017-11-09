A programmable block can be configured to run itself in given intervals without the use of a timer block; either every tick, every 10 ticks or every 100 ticks. The trick to this lies in the `Runtime.UpdateFrequency` property.

* `UpdateFrequency.Once`:
  The programmable block is automatically run _once_ next frame and then not again.
* `UpdateFrequency.Update1`:
  The programmable block is automatically run every single tick. You should be careful about using this option as unless your script is well written, it might affect game performance.
* `UpdateFrequency.Update10`:
  The programmable block is automatically run every 10 ticks.
* `UpdateFrequency.Update100`:
  The programmable block is automatically run every 100 ticks.

It is recommended that you set this property in the programmable block's constructor, but you are free to alter this flag whenever you need to.

```csharp
public Program()
{
  // Configure this program to run the Main method every 100 update ticks
  Runtime.UpdateFrequency = UpdateFrequency.Update100;
}
```

### The number of ticks until next run is _not guaranteed_

Due to how the game engine works, and how the game needs to attempt to schedule out script executions to avoid performance hits, setting these flags does _not guarantee_ that the given number of ticks are skipped before the next time your script is called. This means that you should consider the flag a polite suggestion more than an order.

###UpdateSource

Of course, there are many ways to run a script. It can be run from a button, a timer, a sensor...  and much more. For this reason it's important to know _how_ your Main function was called, so you can act accordingly. This is where the Main function's `updateSource` argument comes into play.

```csharp
public void Main(string argument, UpdateSource updateSource)
```

* `UpdateSource.Trigger`:
  Called from a button, timer, sensor or other simple trigger.

* `UpdateSource.Antenna`:
  Called from an antenna.

* `UpdateSource.Script`:
  Called from another programmable block.

* `UpdateSource.Terminal`:
  Called manually through the Terminal.

* `UpdateSource.ModApi`:
  Called from a mod.

* `UpdateSource.Once`:
  Called automatically by the programmable block because the `Runtime.UpdateFrequency` was set to `UpdateFrequency.Once`.

* `UpdateSource.Update1`:

  Called automatically by the programmable block because the `Runtime.UpdateFrequency` was set to `UpdateFrequency.Update1`.

* `UpdateSource.Update10`:
  Called automatically by the programmable block because the `Runtime.UpdateFrequency` was set to `UpdateFrequency.Update10`.

* `UpdateSource.Update100`:
  Called automatically by the programmable block because the `Runtime.UpdateFrequency` was set to `UpdateFrequency.Update100`.

### More than one `UpdateSource` per call

Important consideration: _More than one of the flags_ may be set at any one time. For example, if you have enabled both `Update1` and `Update100`, and they both happen to hit the same tick, `updateSource` will have _both_ these values. The consequence of this is that we cannot use a simple `switch` to detect our sources. Instead, what we need to do, is to check if any given flag is set before running our logic related to that source.

```csharp
public void Main(string argument, UpdateSource updateSource)
{
  // If the update source is from a trigger or a terminal,
  // this is an interactive command.
  if (updateSource.HasFlag(UpdateSource.Trigger) ||
      updateSource.HasFlag(UpdateSource.Terminal)) 
  {
    RunCommand(argument);
  }
  
  // If the update source has this update flag, it means
  // that it's run from the frequency system, and we should
  // update our continuous logic.
  if (updateSource.HasFlat(UpdateSource.Update10)) {
    UpdateContinuousLogic();
  }
}

void RunCommand(string argument)
{
  // Perform interactive logic
}

void UpdateContinuousLogic()
{
  // Perform continuous logic, like monitoring, LCD updates and similar
}
```

