## Do:
* reuse your lists. You can initialize (`new`) your lists once and reuse them for the rest of the script's lifetime, you don't need to reallocate every time, this is very slow.

* design your own objects to follow the above guideline. Avoid allocation during general runtime.

* consider the fact that scripts take time to execute, leaving less time available for the rest of the game. The more you try to do, the more it will impact the game. If your script is just something you're gonna run in your single player game, you have much more time available than if you are going to use your script on a multiplayer server: Other players are bound to use scripts too. Advanced scripters might want to run their operations over multiple ticks using tricks like [yield-based state machines](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-Easy-and-Powerful-State-Machine-Using-%22yield-return%22).

## Don't:
* store the GridTerminalSystem. It can actually _change_ during runtime. If you store the instance, you'll eventually find yourself in a situation where it simply doesn't work - or worse - crashes your script.

* use `static` fields or properties. Methods are fine, but static fields and properties are a potential source of memory leaks. Pass your instances around, don't be lazy.

* allocate new objects in often running code. Memory allocation is relatively slow, and it will give the [garbage collector](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/) a lot of objects to deal with, slowing down execution.
