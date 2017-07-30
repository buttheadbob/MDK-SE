### Advanced 1: Utility Classes

Utility classes are normal classes like any other, but will be merged into your script when deploying so you don't have to keep all your types in a single code file. This makes it a lot easier to manage and maintain your script project, especially once it starts to grow in size. Note that your new class resides within a partial Program class, just like your main script. This is what makes it a utility class, and any code here has the same access as the code in your Program code file. It is also worth noting that a utility class file doesn't have to actually contain a class, it can contain any code just like your Program file. However it is considered prudent to stick to classes.

Right-click on your project and select **Add** and **New Item...**
Once more select the **Space Engineers** category on the left hand side
Select the **Utility Class** template, name it and press **OK**

### Advanced 2: Extension Classes

Extension classes is another advanced concept. It's officially allowed in programmable blocks, but it's a bit tricky to get them to work. The MDK utility helps you by doing that trick for you, you just need to worry about the code. 

[See here for an official explanation on what an extension class is](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/extension-methods).

Note though that code in extension classes reside _outside_ of the Program class. This means that it does _not_ immediately have the same access as the code in your Program code file. Any required information must be passed in.

Right-click on your project and select **Add** and **New Item...**
Once more select the **Space Engineers** category on the left hand side
Select the **Extension Class** template, name it and press **OK**
