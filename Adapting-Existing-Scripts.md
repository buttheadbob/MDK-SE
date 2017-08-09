So you've found that perfect script on the workshop, and you really wanna have a look at it in an MDK project to see what makes it tick. You tried just pasting the thing into a .cs file in the project and get nothing but a whole bunch of compiling errors and squiglies.

The trick is understanding [the anatomy of a script](https://github.com/malware-dev/MDK-SE/wiki/The-Anatomy-of-a-Script). An SE script _needs_ the outside wrapper in order to work. So:

```csharp
// using...

namespace IngameScript
{
    partial class Program : MyGridProgram
    {
      // simply remove all the content in here, and paste the script here instead.
    }
}
```

That's all it takes!