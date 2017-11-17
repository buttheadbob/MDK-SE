A programmable block can be configured to run itself in given intervals without the use of a timer block; either every tick, every 10 ticks or every 100 ticks. This means that there's _no need for a timer block_ in order to run a script continuously. The trick to this lies in the `Runtime.UpdateFrequency` property.

* `UpdateFrequency.Once`:
  The programmable block is automatically run _once_ next frame and then not again or until you set `Runtime.UpdateFrequency` again.
* `UpdateFrequency.Update1`:
  The programmable block is automatically run every single tick. You should be careful about using this option unless your script is well written, as it might affect game performance.
* `UpdateFrequency.Update10`:
  The programmable block is automatically run every 10 ticks.
* `UpdateFrequency.Update100`:
  The programmable block is automatically run every 100 ticks.

It is recommended that you set this property in the programmable block's constructor, but you are free to alter this flag whenever you need to.

This property is a flag, which means you can combine more than one value in a bitwise manner. [You can read more about enumeration types as bit flags here](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/enumeration-types), about halfway down the page.

```csharp
public Program()
{
  // Configure this program to run the Main method every 100 update ticks
  Runtime.UpdateFrequency = UpdateFrequency.Update100;
}
```

You can also request _multiple frequencies_.

```csharp
public Program()
{
  // Configure this program to run both Once and every 100 update ticks
  Runtime.UpdateFrequency = UpdateFrequency.Once | UpdateFrequency.Update100
}
```



### Important: The number of ticks until next run is _not guaranteed_

Due to how the game engine works, and how the game needs to attempt to schedule out script executions to avoid performance hits, setting these flags does _not guarantee_ that the given number of ticks are skipped before the next time your script is called. This means that you should consider the flag a polite suggestion more than an order. In a worst case scenario, rare but quite possible, the interval _could_ become near-double of your request.


###UpdateType

Of course, there are many ways to run a script. It can be run from a button, a timer, a sensor...  and much more. For this reason it's important to know _how_ your Main function was called, so you can act accordingly. This is where the Main function's `updateType` argument comes into play.

```csharp
public void Main(string argument, UpdateType updateType)
```

* `UpdateType.Trigger`:
  Called from a button, timer, sensor or other simple trigger. An argument will be passed with this flag.

* `UpdateType.Antenna`:
  Called from an antenna. An argument will be passed with this flag.

* `UpdateType.Script`:
  Called from another programmable block. An argument will be passed with this flag.

* `UpdateType.Terminal`:
  Called manually through the Terminal. An argument will be passed with this flag.

* `UpdateType.ModApi`:
  Called from a mod. An argument will be passed with this flag.

* `UpdateType.Once`:
  Called automatically by the programmable block because the `Runtime.UpdateFrequency` was set to `UpdateFrequency.Once`. This flag does not support arguments (but arguments might be passed if another flag is set)

* `UpdateType.Update1`:

  Called automatically by the programmable block because the `Runtime.UpdateFrequency` was set to `UpdateFrequency.Update1`. This flag does not support arguments (but arguments might be passed if another flag is set)

* `UpdateType.Update10`:
  Called automatically by the programmable block because the `Runtime.UpdateFrequency` was set to `UpdateFrequency.Update10`. This flag does not support arguments (but arguments might be passed if another flag is set)

* `UpdateType.Update100`:
  Called automatically by the programmable block because the `Runtime.UpdateFrequency` was set to `UpdateFrequency.Update100`. This flag does not support arguments (but arguments might be passed if another flag is set)
  ​

### More than one `UpdateType` per call

Important consideration: The same way you can set multiple `Runtime.UpdateFrequency` flags, _More than one of the flags_ may be set at any one time. For example, if you have enabled both `Update1` and `Update100`, and they both happen to hit the same tick, `UpdateType` will have _both_ these values. The consequence of this is that we cannot use a simple `switch` to detect our sources. Instead, what we need to do, is to check if any given flag is set before running our logic related to that source.

```csharp
public void Main(string argument, UpdateType updateType)
{
  // If the update source is from a trigger or a terminal,
  // this is an interactive command.
  if ((updateType & (UpdateType.Trigger | UpdateType.Terminal)) != 0)
  {
    RunCommand(argument);
  }
  
  // If the update source has this update flag, it means
  // that it's run from the frequency system, and we should
  // update our continuous logic.
  if ((updateType & UpdateType.Update10) != 0) {
    RunContinuousLogic();
  }
}

void RunCommand(string argument)
{
  // Perform interactive logic
}

void RunContinuousLogic()
{
  // Perform continuous logic, like monitoring, LCD updates and similar
}
```

 An alternative way to check for more than one flag at once:

```csharp
const UpdateType CommandUpdate = UpdateType.Trigger | UpdateType.Terminal;

public void Main(string argument, UpdateType updateType) 
{
  // If the update source is either Trigger or Terminal, run the continuous logic
  if ((updateType & CommandUpdate) != 0) 
  {
    RunCommand(argument);
  }
}

void RunCommand(string argument)
{
  // Perform interactive logic
}
```

You _do_ have the option of using the [`updateType.HasFlag`](https://docs.microsoft.com/en-us/dotnet/api/system.enum.hasflag?view=netframework-4.6.1#System_Enum_HasFlag_System_Enum_) method, but this has a significant performance impact and is not recommended.