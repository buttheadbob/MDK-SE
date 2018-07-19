MDK deployment works by taking all your .cs files and packing them into a single file that Space Engineers understands. You can control where each individual .cs files are placed in relation to each other by adding
```cs
// <mdk sortorder="100" />
```
at the _very top_ of the code files you wish to control, even above the `using` statements. The sortorder number will be used to determine the orders of the files. You can also use negative sortorders to force files above the Program class. Of course, certain rules will be above even the sortorder: The `readme.cs` file will always be on top no matter what, and classes that is not inside a `partial class Program` will by necessity have to be at the bottom simply due to how such classes work.
