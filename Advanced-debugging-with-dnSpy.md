How to debug PB (programmable block), mod and even game exceptions.

**dnSpy** has a **debugger** that can attach to the game process and catch exceptions (even if they're already caught by the code) and pause the code so you can go through it step by step, look at variables, etc.

**dnSpy** is also a **decompiler** which you can look at the game's code and even at compiled PB/mod scripts in order to see how the game's compiler alters them. For this in particular see [Looking at the compiled code](#looking-at-the-compiled-code).



## Getting dnSpy

- Get it from https://github.com/0xd4d/dnSpy/releases.

- Extract anywhere (e.g. `C:\Program Files\dnSpy\`).

- Run `dnSpy.exe` for the 64bit version.



## Catching errors (exceptions)

The basic steps for attaching dnSpy to the game and to monitor for an exception.

1. Start the game and dnSpy.

2. dnSpy: `Debug -> Attach to process (Ctrl+Alt+P)` and double click SpaceEngineers.exe from that list.

3. dnSpy: `Debug -> Windows -> Exception settings (Ctrl+Alt+E)` and pick what exceptions you want to catch.

   For example: search `null` and check `NullReferenceException`, the most common exception.

4. In-game: Recompile the script (if it's a mod, reload the world to recompile).

   (This is only needed once after you attach. Details at [Seeing local variables when code is paused](advanced-dnspy-tips-and-tricks#seeing-local-variables-when-code-is-paused))

5. In-game: Run the script until it throws errors (exceptions).

6. Once the error occurs dnSpy will pause code execution, now proceed to [Navigating paused code](#navigating-paused-code).



## Navigating paused code

When dnSpy is attached to the game and you're monitoring for an exception or breakpoint (advanced topic: [Breakpoints](advanced-dnspy-tips-and-tricks#breakpoints)), then the game's code is paused and self-navigates to the exact line the exception or breakpoint occured.

Some things you can do here (in dnSpy):

- The top-center toolbar has some buttons with arrows and stuff: step-into, step-over or step-out to navigate the code flow.

- `Debug -> Windows -> Locals (Alt+4)` can show values from variables and fields from the current pause context.

  (Advanced topic: [Seeing local variables when code is paused](advanced-dnspy-tips-and-tricks#seeing-local-variables-when-code-is-paused))

- `Debug -> Windows -> Call Stack (Ctrl+Alt+C)` shows the exception stacktrace which you can double-click in to navigate to the mentioned code.

- Use the `Continue` button to resume the game (or exit, if that would happen normally, dnSpy does not handle exceptions, it catches them).



## Looking at the compiled code

Since dnSpy is also a decompiler, you can look at the game code.

This doesn't require the game running.

1. `File -> Open` navigate to `<Steam>/steamapps/common/SpaceEngineers/Bin64`

2. Select all .dll and .exe files and click `Open`.

3. `Edit -> Search Assemblies (Ctrl+Shift+K)` and search away!

After that:

- What to search really depends on what you're looking for, if you want to know what properties an API interface has, then simply type that interface's name, maybe also set `Search for:` to `Type` to be more specific.

- `Right click anything -> Analyze` to see where it's used, implemented, raised, etc.

- For multiple projects (e.g. also having Medieval Engineers' libraries), see `File -> Open List`