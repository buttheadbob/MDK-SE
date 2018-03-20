** WARNING : DESCRIBES CURRENTLY UNRELEASED FEATURE! **

The simplest way to configure blocks and behavior in scripts is simply to hard-code the behavior. However some times - especially if you're planning to release your script for public use - there's a need to allow for user configuration of behavior. Keen introduced the Custom Data field specifically for this reason. This is a field available in the terminal of most (if not all) terminal blocks, where users can enter any text. Scripters can use this to their advantage by using this to have users enter configuration there instead of having to open the script and editing code.

This field is accessed as a simple `String CustomData` property. For example, as you know, the currently running programmable block is accessed by the script property `Me`. So, to get to the custom data of the programmable block, you do this:

```csharp
public void Program() 
{
    var customData = Me.CustomData;
}
``` 

However just a string is not very useful. In order to help dealing with configuration information more easily, we introduce the `MyIni` class. This class helps you parse and read strings in the old fashioned INI format:

```ini
[FirstDataSection]
#This is a comment. It is not parsed by the class.
SomeKey=The value of this key
AnotherKey=Another value

[AnotherSection]
SomeKey=15
```

You get the idea. This is a very simple format, and it's easy to learn even for those without any coding skills. `MyIni` adds a little extra to this format though:
```ini
[Section]
#The following line is a special format which allows for multiline text in a single key:
MultiLine=
|The first line of the value
|The second line of the value
|And so on

#The next line terminates the ini stream, allowing for further custom content in customdata if desired:
---
```

### The Basics

To read this data you first need to instantiate an instance of the `MyIni` class. As always it's recommended to make a single instance, and reuse this instance throughout your script's lifetime.

Place down a programmable block. Open the Custom Data editor and add the following configuration:
```ini
[demo]
outputNow=true
output=LCD Panel
textToOutput=This text will be copied onto the target LCD.
```
Now add an LCD panel too, make sure it's called "LCD Panel" - or change the name in the custom data above to match.

Open the code editor of the programmable block and enter the following piece of code:

```cs
// Instantiate a shared instance of the parser
MyIni _ini = new MyIni();

bool _outputNow;
string _textToOutput;
string _outputName;
IMyTextPanel _outputPanel;

public Program()
{
    if (!_ini.TryParse(Me.CustomData, out var result)) 
        throw new Exception(result.ToString());

    // Get the value of the "outputNow" key under the "demo" section.
    // Then, by calling ToBoolean(), we try to convert it into a
    // bool value.
    _outputNow = cfg.Get("demo", "outputNow").ToBoolean();
    
    // Get the value of the "output" key. This time we just want the
    // string.
    _outputName = cfg.Get("demo", "output").ToString();

    // Then the final value
    _textToOutput = cfg.Get("demo", "textToOutput").ToString();

    // If the configuration says that the text should be added immediately
    if (_outputNow) 
    {
        Output();
    }
}

void Output() 
{
    // If the output text panel has not yet been retrieved, retrieve it now.
    if (_outputPanel == null) 
    {
        // Get the output panel as configured by the CustomData
        _outputPanel = GridTerminalSystem.GetBlockWithName(_outputName);
    }
    if (_outputPanel == null) {
        // No output panel could be found, so we'll just have to exit.
        Echo("No output panel");
        return;
    }

    // Append the configured text to the text panel
    _outputPanel.WritePublicText(_textToOutput, true);
    // And then add a newline
    _outputPanel.WritePublicText("\n", true);
}

public void Main() 
{
    // Output the configured text every time the script is run
    Output();
}

```

There are several type conversion methods are available for the configuration values. Each type has two variants: The To* and the TryGet*. The former will attempt to 
convert the value, and if it fails, it will simply fall back to the default value. The second will return a boolean which tells you if the conversion was successful or
not. Use whichever suits your script best.

* `bool ToBoolean(bool defaultValue = default(bool))`
* `bool TryGetBoolean(out bool value)`

* `char ToChar(char defaultValue = default(char))`
* `bool TryGetChar(out char value)`

* `sbyte ToSByte(sbyte defaultValue = default(sbyte))`
* `bool TryGetSByte(out sbyte value)`

* `byte ToByte(byte defaultValue = default(byte))`
* `bool TryGetByte(out byte value)`

* `ushort ToUInt16(ushort defaultValue = default(ushort))`
* `bool TryGetUInt16(out ushort value)`

* `short ToInt16(short defaultValue = default(short))`
* `bool TryGetInt16(out short value)`

* `uint ToUInt32(uint defaultValue = default(uint))`
* `bool TryGetUInt32(out uint value)`

* `int ToInt32(int defaultValue = default(int))`
* `bool TryGetInt32(out int value)`

* `ulong ToUInt64(ulong defaultValue = default(ulong))`
* `bool TryGetUInt64(out ulong value)`

* `long ToInt64(long defaultValue = default(long))`
* `bool TryGetInt64(out long value)`

* `float ToSingle(float defaultValue = default(float))`
* `bool TryGetSingle(out float value)`

* `double ToDouble(double defaultValue = default(double))`
* `bool TryGetDouble(out double value)`

* `decimal ToDecimal(decimal defaultValue = 0)`
* `bool TryGetDecimal(out decimal value)`

* `string ToString(string defaultValue = default(string))`
* `bool TryGetString(out string value)`

There's also the `void GetLines(List<string> lines)` method, which fills the given list with the individual lines of the configuration value.

### Find Blocks With Sections

My favorite way of using CustomData configuration now is to use _it_ to retrieve blocks for my scripts rather than using hard coded custom names. What I do is use the ini sections to indicate if a certain block is to be included in a certain script module. For example, my airlock script looks for an `[airlock]` configuration in blocks like for example doors and air vents, which configures how those blocks should behave in relation to a given air lock. It allows for the adding and removal of new air locks without the need to manually add code to the script, I simply press a "reset" button and the script finds any new airlocks and discards old ones. Easy - and requires no coding knowledge.

To support this use case there's a fast search method in `MyIni` which searches a string quickly to see if it has the desired section. This allows you to quickly reject blocks which are not relevant for the current model. The method is designed to be performance- and memory friendly.

```csharp
GridTerminalSystem.GetBlocksOfType<IMyDoor>(doors, door => MyIni.HasSection(door.CustomData, "airlock"));
```

