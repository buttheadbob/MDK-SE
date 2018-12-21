← [Index](index)
# MyIni Class
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
A configuration class to parse and create a text string resembling the old fashioned INI format, but with support for multiline values.
Do not forget that parsing is a time-consuming task. Keep your parsing to a minimum.

## Example
Using MyIni to deal with CustomData end-user configuration:
The CustomData:
```csharp
[kernel]
output=DebugTextPanel
bootText=
|-- HAL9000 --
|Good morning, Dave.
```
The code:
```csharp
MyIni _ini = new MyIni();
IMyTextPanel _outputTextPanel;

public Program() 
{
    MyIniParseResult result;
    if (!_ini.TryParse(Me.CustomData, out result) 
    {
        Echo($"CustomData error:\nLine {result}");
    }

    // Get the kernel section's output value. If this value is set, the system attempts
    // to retrieve a text panel with the value set. Otherwise output is ignored.
    var name = _ini.Get("kernel", "output").ToString();
    if (name != null) 
    {
        _outputTextPanel = GridTerminalSystem.GetBlockWithName<IMyTextPanel>(name);
        if (_outputTextPanel == null)
            Echo($"No text panel named {name}");
    }

    // Get the kernel section's boottext value. If no value is given, a default value will be returned.
    var bootText = _ini.Get("kernel", "bootText").ToString("Kernel is starting up...");
    _outputTextPanel?.WritePublicText(bootText);
}

public void Main() {
    // Do your stuff. Only parse the configuration when you have to.
}
```
Using MyIni to deal with internal storage:
```csharp
MyIni _storage = new MyIni();
Vector3D _startupPosition;
bool _hasTarget;
Vector3D _currentTarget;

public Program() 
{
    // You only need to parse here in the constructor.
    if (_ini.TryParse(Storage) 
    {
        var str = _ini.Get("state", "startupPosition").ToString();
        Vector3D.TryParse(str, out _startupPosition);
        str = _ini.Get("state", "currentTarget").ToString();
        Vector3D.TryParse(str, out _currentTarget);
        _hasTarget = _ini.Get("state", "hasTarget").ToBoolean();
    } 
    else 
    {
        // Set up defaults, the storage is nonexistent or corrupt
        _startupPosition = Me.CubeGrid.Position;
    }
}

public void Save()
{
    // You only need to update Storage when the Save method is called.
    _ini.Set("state", "startupPosition", _startupPosition);
    _ini.Set("state", "currentTarget", _currentTarget);
    Storage = _ini.ToString();
}

public void Main() {
    // Do your stuff
}
```

## Remarks
This class is NOT THREAD SAFE as it's optimized for programmable block use.
### Properties
|Member|Description|
|---|---|
|[`string&nbsp;EndContent`](VRage.Game.ModAPI.Ingame.Utilities.EndContent)|You can terminate a configuration stream by entering "---" on a separate line. This property will contain all the content after this line.|
|[`string&nbsp;EndComment`](VRage.Game.ModAPI.Ingame.Utilities.EndComment)|Get or set a comment to be placed after the last section or item. Is`null`if the section does not exist or has no comment.|
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`bool&nbsp;HasSection(string&nbsp;config,&nbsp;string&nbsp;section)`](VRage.Game.ModAPI.Ingame.Utilities.HasSection)|Determines if the given configuration contains what looks like the given section. It does not verify that the content is actually in a valid format, just if there's a line starting with [section].|
|[`bool&nbsp;ContainsSection(string&nbsp;section)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsSection)|Determines whether a section of a given name exists in the currently parsed configuration.|
|[`bool&nbsp;ContainsKey(string&nbsp;section,&nbsp;string&nbsp;name)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsKey)|Determines whether a configuration key (section/key) exists in the currently parsed configuration.|
|[`bool&nbsp;ContainsKey(MyIniKey&nbsp;key)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsKey)|Determines whether a configuration key (section/key) exists in the currently parsed configuration.|
|[`void&nbsp;GetKeys(string&nbsp;section,&nbsp;List<MyIniKey>&nbsp;keys)`](VRage.Game.ModAPI.Ingame.Utilities.GetKeys)|Fills the provided list with the configuration keys within the given section.|
|[`void&nbsp;GetKeys(List<MyIniKey>&nbsp;keys)`](VRage.Game.ModAPI.Ingame.Utilities.GetKeys)|Fills the provided list with all configuration keys within the currently parsed configuration.|
|[`void&nbsp;GetSections(List<string>&nbsp;names)`](VRage.Game.ModAPI.Ingame.Utilities.GetSections)|Fills the provided list with the names of all the sections in the currently parsed configuration.|
|[`void&nbsp;SetEndComment(string&nbsp;comment)`](VRage.Game.ModAPI.Ingame.Utilities.SetEndComment)|Sets a comment to be placed after the last section or item. Set the comment to`null`to remove it.|
|[`string&nbsp;GetSectionComment(string&nbsp;section)`](VRage.Game.ModAPI.Ingame.Utilities.GetSectionComment)|Get any comment that might be associated with the given section. Returns`null`if the section does not exist or has no comment.|
|[`void&nbsp;SetSectionComment(string&nbsp;section,&nbsp;string&nbsp;comment)`](VRage.Game.ModAPI.Ingame.Utilities.SetSectionComment)|Sets a comment on a given section. The section must already exist. Set the comment to`null`to remove it.|
|[`string&nbsp;GetComment(string&nbsp;section,&nbsp;string&nbsp;name)`](VRage.Game.ModAPI.Ingame.Utilities.GetComment)|Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.|
|[`string&nbsp;GetComment(MyIniKey&nbsp;key)`](VRage.Game.ModAPI.Ingame.Utilities.GetComment)|Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.|
|[`void&nbsp;SetComment(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;string&nbsp;comment)`](VRage.Game.ModAPI.Ingame.Utilities.SetComment)|Sets a comment on a given item. The item must already exist. Set the comment to`null`to remove it.|
|[`void&nbsp;SetComment(MyIniKey&nbsp;key,&nbsp;string&nbsp;comment)`](VRage.Game.ModAPI.Ingame.Utilities.SetComment)|Sets a comment on a given item. The item must already exist. Set the comment to`null`to remove it.|
|[`MyIniValue&nbsp;Get(string&nbsp;section,&nbsp;string&nbsp;name)`](VRage.Game.ModAPI.Ingame.Utilities.Get)|Gets the [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) of the given configuration key.|
|[`MyIniValue&nbsp;Get(MyIniKey&nbsp;key)`](VRage.Game.ModAPI.Ingame.Utilities.Get)|Gets the [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) of the given configuration key.|
|[`void&nbsp;Delete(string&nbsp;section,&nbsp;string&nbsp;name)`](VRage.Game.ModAPI.Ingame.Utilities.Delete)|Deletes the given configuration key.|
|[`void&nbsp;Delete(MyIniKey&nbsp;key)`](VRage.Game.ModAPI.Ingame.Utilities.Delete)|Deletes the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;string&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;string&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;bool&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;bool&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;byte&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;byte&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;sbyte&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;sbyte&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;ushort&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;ushort&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;short&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;short&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;uint&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;uint&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;int&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;int&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;ulong&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;ulong&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;long&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;long&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;float&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;float&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;double&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;double&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(string&nbsp;section,&nbsp;string&nbsp;name,&nbsp;decimal&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Set(MyIniKey&nbsp;key,&nbsp;decimal&nbsp;value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`void&nbsp;Clear()`](VRage.Game.ModAPI.Ingame.Utilities.Clear)|Empties this configuration|
|[`bool&nbsp;TryParse(string&nbsp;content)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file.|
|[`bool&nbsp;TryParse(string&nbsp;content,&nbsp;ref&nbsp;MyIniParseResult&nbsp;result)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file.|
|[`bool&nbsp;TryParse(string&nbsp;content,&nbsp;string&nbsp;section,&nbsp;ref&nbsp;MyIniParseResult&nbsp;result)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [string ToString()](VRage.Game.ModAPI.Ingame.Utilities.ToString) , you will only get the parsed section, the rest will be discarded.|
|[`bool&nbsp;TryParse(string&nbsp;content,&nbsp;string&nbsp;section)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [string ToString()](VRage.Game.ModAPI.Ingame.Utilities.ToString) , you will only get the parsed section, the rest will be discarded.|
|[`void&nbsp;Invalidate()`](VRage.Game.ModAPI.Ingame.Utilities.Invalidate)|Forces regeneration of the ini content. Only really useful if you want to reformat the configuration file.|
|[`string&nbsp;ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Generates a configuration file from the currently parsed configuration|
