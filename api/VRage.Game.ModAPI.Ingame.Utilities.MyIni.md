← [Index](Api-Index)
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
|[`EndContent`](VRage.Game.ModAPI.Ingame.Utilities.EndContent)|You can terminate a configuration stream by entering "---" on a separate line. This property will contain all the content after this line.|
|[`EndComment`](VRage.Game.ModAPI.Ingame.Utilities.EndComment)|Get or set a comment to be placed after the last section or item. Is`null`if the section does not exist or has no comment.|
### Methods
|Member|Description|
|---|---|
|[`HasSection(string, string)`](VRage.Game.ModAPI.Ingame.Utilities.HasSection)|Determines if the given configuration contains what looks like the given section. It does not verify that the content is actually in a valid format, just if there's a line starting with [section].|
|[`ContainsSection(string)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsSection)|Determines whether a section of a given name exists in the currently parsed configuration.|
|[`ContainsKey(string, string)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsKey)|Determines whether a configuration key (section/key) exists in the currently parsed configuration.|
|[`ContainsKey(MyIniKey)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsKey)|Determines whether a configuration key (section/key) exists in the currently parsed configuration.|
|[`GetKeys(string, List<MyIniKey>)`](VRage.Game.ModAPI.Ingame.Utilities.GetKeys)|Fills the provided list with the configuration keys within the given section.|
|[`GetKeys(List<MyIniKey>)`](VRage.Game.ModAPI.Ingame.Utilities.GetKeys)|Fills the provided list with all configuration keys within the currently parsed configuration.|
|[`GetSections(List<string>)`](VRage.Game.ModAPI.Ingame.Utilities.GetSections)|Fills the provided list with the names of all the sections in the currently parsed configuration.|
|[`SetEndComment(string)`](VRage.Game.ModAPI.Ingame.Utilities.SetEndComment)|Sets a comment to be placed after the last section or item. Set the comment to`null`to remove it.|
|[`GetSectionComment(string)`](VRage.Game.ModAPI.Ingame.Utilities.GetSectionComment)|Get any comment that might be associated with the given section. Returns`null`if the section does not exist or has no comment.|
|[`SetSectionComment(string, string)`](VRage.Game.ModAPI.Ingame.Utilities.SetSectionComment)|Sets a comment on a given section. The section must already exist. Set the comment to`null`to remove it.|
|[`GetComment(string, string)`](VRage.Game.ModAPI.Ingame.Utilities.GetComment)|Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.|
|[`GetComment(MyIniKey)`](VRage.Game.ModAPI.Ingame.Utilities.GetComment)|Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.|
|[`SetComment(string, string, string)`](VRage.Game.ModAPI.Ingame.Utilities.SetComment)|Sets a comment on a given item. The item must already exist. Set the comment to`null`to remove it.|
|[`SetComment(MyIniKey, string)`](VRage.Game.ModAPI.Ingame.Utilities.SetComment)|Sets a comment on a given item. The item must already exist. Set the comment to`null`to remove it.|
|[`Get(string, string)`](VRage.Game.ModAPI.Ingame.Utilities.Get)|Gets the [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) of the given configuration key.|
|[`Get(MyIniKey)`](VRage.Game.ModAPI.Ingame.Utilities.Get)|Gets the [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) of the given configuration key.|
|[`Delete(string, string)`](VRage.Game.ModAPI.Ingame.Utilities.Delete)|Deletes the given configuration key.|
|[`Delete(MyIniKey)`](VRage.Game.ModAPI.Ingame.Utilities.Delete)|Deletes the given configuration key.|
|[`Set(string, string, string)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, string)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, bool)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, bool)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, byte)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, byte)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, sbyte)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, sbyte)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, ushort)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, ushort)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, short)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, short)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, uint)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, uint)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, int)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, int)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, ulong)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, ulong)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, long)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, long)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, float)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, float)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, double)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, double)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(string, string, decimal)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Set(MyIniKey, decimal)`](VRage.Game.ModAPI.Ingame.Utilities.Set)|Sets the value of the given configuration key.|
|[`Clear()`](VRage.Game.ModAPI.Ingame.Utilities.Clear)|Empties this configuration|
|[`TryParse(string)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file.|
|[`TryParse(string, ref MyIniParseResult)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file.|
|[`TryParse(string, string, ref MyIniParseResult)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [string ToString()](VRage.Game.ModAPI.Ingame.Utilities.ToString) , you will only get the parsed section, the rest will be discarded.|
|[`TryParse(string, string)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [string ToString()](VRage.Game.ModAPI.Ingame.Utilities.ToString) , you will only get the parsed section, the rest will be discarded.|
|[`Invalidate()`](VRage.Game.ModAPI.Ingame.Utilities.Invalidate)|Forces regeneration of the ini content. Only really useful if you want to reformat the configuration file.|
|[`ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Generates a configuration file from the currently parsed configuration|
