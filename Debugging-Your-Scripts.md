_This tutorial is still being written, and certain example code has yet to be properly tested. Thank you for your patience!_

If there's one thing that is certain about being a programmer, it is that you will make mistakes. Bugs are just part of the job. Usually in IDEs like Visual Studio you can enable a "Debug Mode" though, which will give you file names and line numbers, and even breakpoints which enables you to stop at selected points and step-by-step the code to see what went wrong.

_None_ of which is available for Space Engineers ingame scripts.

The reasoning for this is simple: Debuggable scripts run _a lot_ slower than optimized scripts. Because of this the compiled scripts in SE contains no debug information at all. 

So... We're still going to have bugs, how can we trace them?

### Echo
Let's start simple, with the `Echo`. This is a method belonging to the scripts base class, `MyGridProgram` (it's a delegate property actually, but [I'll get back to that](#echo-performance-and-tricks). This method can be used to output text to the programmable block's detail area. For instance, this:

```csharp
public void Main() 
{
    Echo("Hello World");
}
```

results in this:

_pending: example image showing the text in the detail area_

By placing outputs like this at strategic locations in your code, you can figure out how far it goes before your error occurs - and in that way narrow down your search range.

However to provide full coverage you'd need Echo _all over the place_. It'd be nice to be able to narrow down a little more first.

### Stack Trace
A **stack trace** is a description showing you the route a call has made at the error point. There is actually a way to get at least a limited stack trace out of Space Engineers, this should help you narrow down at least what code member was running when the error occurred. You can do this by adding a `try/catch` to the main callback points of your script - those being `Program()`, `Save()`, and most importantly `Main()`.

```csharp
public void ATestMethod()
{
    // Simulate an exception happening by throwing one ourselves
    throw new Exception("Boom!");
}

public void Main() 
{
    try
    {
        // Call the test method.
        ATestMethod();
    }
    catch (Exception e)
    {
        // Dump the exception content to the 
        Echo("An error occurred during script execution.");
        Echo($"Exception: {e}");

        // Rethrow the exception to make the programmable block halt execution properly
        throw;
    }
}
```
As mentioned in the comment, the `throw` statement rethrows the same exception to force the PB to shut down as it normally would. I recommend doing this because it's highly likely your script is in an undefined state at this point, even if you've tried to take errors into account.

When running this script, this is what will be shown in the programmable block's Details view:

_pending: example image showing the text in the detail area_
_pending: explanation of the lines of the stack trace_

Unfortunately even this method is inexact. The compiler optimizer is rather clever. Sometimes it takes some of your smaller methods and bakes them into larger methods, because it deems that to be faster. This means that you'll not see that particular method in the stack trace, because as far as the _compiled_ code goes, it doesn't exist. This _will_ give you a relatively decent idea where to start looking though.

### Echo, performance, and tricks
Unfortunately there's a slight caveat to using `Echo` a lot. In solo play there's little to no issue, but in multiplayer the text needs to be synchronized from the server where the script is running and to your client. This takes time. If a lot of scripts are echoing a lot of text every frame, it's going to have an impact. For this reason you shouldn't Echo everything always. This is where the thing I mentioned earlier comes into play: `Echo` is actually a property. The method called can be replaced with whatever you want. For instance, if you have lots of diagnostic echoes in your script and want to keep it around for later, you can do this:

```csharp
public Program() 
{
    Echo = () => {};
}
```

This will effectively make Echo do _nothing_. Voila, any performance hit by your echoes are now gone - but you can switch it back on simply by removing the line above!

Another neat trick you can do because of this, is to reroute your echo.

```csharp
IMyTextPanel _logOutput;

public Program()
{
    // Replace the Echo
    Echo = EchoToLCD;

    // Fetch a log text panel
    _logOutput = GridTerminalSystem.GetBlockWithName("Log LCD") as IMyTextBlock;
}

public void EchoToLCD(string text)
{
    // Append the text and a newline to the logging LCD
    // A nice little C# trick here:
    // - The ?. after _logOutput means "call only if _logOutput is not null".
    _logOutput?.WritePublicText($"{text}\n", true);
}
```
Putting a $ in front of the string literal makes it a [string interpolation](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/interpolated-strings).
