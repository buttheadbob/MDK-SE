
This is a simplistic attempt to explain the various parts of an ingame script and how it works. It is by no means a complete explanation. To get further help, I recommend connecting to [Keen's official Discord](https://discord.gg/0hIE7GirODUqhfIg) and asking in the **#programming-in-game** channel. There's usually plenty of people there to help you. I will be assuming that you're familiar with the game itself, and how to _use_ scripts, and how to load a script into a programmable block via the workshop button.

### The Language

First of all: The programmable block uses the programming language C# in order to provide high-performance automation for your builds. Before continuing you should get a basic grasp of the language itself. There are several tutorials on the web dealing with this, including [Microsoft's own](https://docs.microsoft.com/en-us/dotnet/csharp/csharp). You might be able to find some tutorials which are better at explaining than them though, they tend to be rather obtuse. In the following tutorials I will be assuming at least a basic grasp of C#. If you find I don't explain some things well enough, please let me know - I might try to improve it.

### Writing Your Script
While you _can_ use the ingame editor, it's not very good. Its purpose is really just to be a storage box for the code. A lot of people uses [Visual Studio](https://docs.microsoft.com/en-us/visualstudio/install/install-visual-studio) (you're going to want the Community edition)-  and here I'm obviously going to point out my own extension, [MDK](https://github.com/malware-dev/MDK-SE/releases), which will help you set everything up for scripting with Visual Studio. There are other options though, other IDEs which works. [Visual Studio Code](https://code.visualstudio.com/) is another more lightweight IDE (don't get confused by the name, it's quite different from Visual Studio). Others simply use a plain text editor like Notepad, but obviously that will give no help with the API. Personally I used Visual Studio for scripting long before I made my extension. It's a professional IDE, and the Community edition is completely free and fully featured.

### The tutorials
* [The Anatomy of a Script](https://github.com/malware-dev/MDK-SE/wiki/The-Anatomy-of-a-Script)
* [The Grid Terminal System](https://github.com/malware-dev/MDK-SE/wiki/The-Grid-Terminal-System)
	* [Block Groups](https://github.com/malware-dev/MDK-SE/wiki/Block-Groups)
* [Terminal Properties and Actions](https://github.com/malware-dev/MDK-SE/wiki/Terminal-Properties-and-Actions)
* [The Running Programmable Block](https://github.com/malware-dev/MDK-SE/wiki/The-Running-Programmable-Block)
* [The Runtime](https://github.com/malware-dev/MDK-SE/wiki/The-Runtime)
* [The Storage String](https://github.com/malware-dev/MDK-SE/wiki/The-Storage-String)
* [Your First Script](https://github.com/malware-dev/MDK-SE/wiki/Your-First-Script)
* [Debugging Your Scripts](https://github.com/malware-dev/MDK-SE/wiki/Debugging-Your-Scripts)
* [Do's and Don'ts](https://github.com/malware-dev/MDK-SE/wiki/Do's-and-Don'ts)
* [Advanced: The EntityId](https://github.com/malware-dev/MDK-SE/wiki/The-Entity-Id)
* [Advanced: Easy and Powerful State Machine Using "yield return"](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-Easy-and-Powerful-State-Machine-Using-%22yield-return%22)
