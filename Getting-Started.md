### Step 1
First of all, obviously, you need to make sure you have installed Visual Studio 2017. This will work with all editions, but the Community edition is completely free. You can find instructions on how to install that here. For Space Engineers development you need at least the .NET desktop development workload.  
https://docs.microsoft.com/en-us/visualstudio/install/install-visual-studio  
https://www.visualstudio.com/vs/getting-started/


### Step 2
Download the extension from here:
https://github.com/malware-dev/MDK-SE/releases

In most circumstances you will be interested in downloading the file named **MDK.vsix**. This is a installer package format used by Visual Studio to install extensions.

You should stay away from any pre-release builds unless you know what you're doing, or if you are kind enough to want to help me test. Just be aware that pre-release builds are bound to be particularily buggy, and might even break script projects, so you certainly shouldn't use them for your more complicated scripts.



### Step 3

After installing the extension, you can now start Visual Studio and create your script project. You do this by finding the **File** menu, then **New** and **Project...**

Now make sure you select the correct .NET Framework version.

![Select .NET Framework 4.6.1](https://github.com/malware-dev/MDK-SE/blob/master/images/wiki-newproject-framework.jpg)



After this you can select the Space Engineers category on the left. You will now be able to see the ingame script template.

![Select the Ingame Script template](https://github.com/malware-dev/MDK-SE/blob/master/images/wiki-newproject-template.jpg)



Now you can select your project's location and names in the boxes below.

![Enter your project information](https://github.com/malware-dev/MDK-SE/blob/master/images/wiki-newproject-properties.jpg)

Note the `Location` box. That is where your solution and project will be stored on disk: Visual Studio will add a subfolder there with the name of your solution, and below there it will create a `.sln` file. Make note of this file, because _this_ is the file you need to open when you're going back to your project later, not the individual `.cs` files.

Press **OK** to create your project.

You may now write your script directly in this class if you wish. If your scripts are not too large, this is quite fine. However this extension has another couple of [tricks up its sleeve](https://github.com/malware-dev/MDK-SE/wiki/Utility-Class-or-Extension-Class%3F) for the slightly more advanced users.

Happy Scripting!