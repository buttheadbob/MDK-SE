There is a significant difference between an [extension class](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/extension-methods) and a utility class. For the absolute majority of your uses, you're going to want a utility class. Extension classes are a special construct which actually uses an officially sanctioned exploit to function.

```csharp
public void Main()
{
    // Some cool code...
}

} // Forcefully close the wrapper Program class that SE uses around your script

public static class ExtensionClass
{
    // Extension code...
// } Deliberately remove the closing brace of the last extension class, because Space Engineers will add it back in