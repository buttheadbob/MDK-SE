The [yielding enumerator](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/yield) enables some really powerful state machine programming. Before you continue, you should read about the keyword so you understand what it's _true_ purpose is. We're gonna exploit it in a somewhat unintended way!

To begin; place a programmable block, a timer block (simply named Timer Block) set up only to run the programmable block with no argument (don't use "with default argument"), an interior light (simply named Interior Light) and an LCD Panel set up to display its public text.

Copy the following script into the programmable block. The comments explain what is happening.

**Remember to dispose your `IEnumerator` after use or it will come back to haunt you!**

```csharp
IMyTimerBlock _timer;
IMyInteriorLight _panelLight;
IMyTextPanel _textPanel;
IEnumerator<bool> _stateMachine;

public Program() 
{
    // Retrieve the blocks we're going to use.
    _timer = GridTerminalSystem.GetBlockWithName("Timer Block") as IMyTimerBlock;
    _panelLight = GridTerminalSystem.GetBlockWithName("Interior Light") as IMyInteriorLight;
    _textPanel = GridTerminalSystem.GetBlockWithName("LCD Panel") as IMyTextPanel;

    // Initialize our state machine
    _stateMachine = RunStuffOverTime();

    // Start the timer to run the first instruction set. Depending on your script, you may want to use
    // TriggerNow rather than Start. Just be very careful with that, you can easily bog down your
    // game that way.
    _timer.ApplyAction("Start");
}

public void Main(string argument) 
{
    // Usually I verify that the argument is empty or a predefined value before running the state
    // machine. This way we can use arguments to control the script without disturbing the
    // state machine and its timing. For the purpose of this example however, I will omit this.

    // ***MARKER: State Machine Execution
    // If there is an active state machine, run its next instruction set.
    if (_stateMachine != null) 
    {
        // If there are no more instructions, we stop and release the state machine.
        if (!_stateMachine.MoveNext())
        {
            _stateMachine.Dispose();

            // In our case we just want to run this once, so we set the state machine
            // variable to null. But if we wanted to continously run the same method, we
            // could as well do
            // _stateMachine = RunStuffOverTime();
            // instead.
            _stateMachine = null;
        } 
        else 
        {
            // The state machine has more work to do. Restart the timer. Again you might choose
            // to use TriggerNow.
            _timer.ApplyAction("Start");
        }
    }
}

// ***MARKER: State Machine Program
public IEnumerator<bool> RunStuffOverTime() 
{
    // For the very first instruction set, we will just switch on the light.
    _panelLight.RequestEnable(true);

    // Then we will tell the script to stop execution here and let the game do it's
    // thing. The time until the code continues on the next line after this yield return
    // depends  on your State Machine Execution and the timer setup.
    // The `true` portion is there simply because an enumerator needs to return a value
    // per item, in our case the value simply has no meaning at all. You _could_ utilize
    // it for a more advanced scheduler if you want, but that is beyond the scope of this
    // tutorial.
    yield return true;

    int i = 0;
    // The following would seemingly be an illegal operation, because the script would
    // keep running until the instruction count overflows. However, using yield return,
    // you can get around this limitation.
    while (true) 
    {
        _textPanel.WritePublicText(i.ToString());
        i++;
        // Like before, when this statement is executed, control is returned to the game.
        // This way you can have a continuously polling script with complete state
        // management, with very little effort.
        yield return true;
    }
}
```
