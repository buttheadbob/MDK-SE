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
|[`string EndContent`](VRage.Game.ModAPI.Ingame.Utilities.EndContent)||
|[`string EndComment`](VRage.Game.ModAPI.Ingame.Utilities.EndComment)||
### Methods
|Member|Description|
|---|---|
|[`bool HasSection(string config, string section)`](VRage.Game.ModAPI.Ingame.Utilities.HasSection)||
|[`bool ContainsSection(string section)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsSection)|Determines whether a section of a given name exists in the currently parsed configuration.|
|[`bool ContainsKey(string section, string name)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsKey)||
|[`bool ContainsKey(MyIniKey key)`](VRage.Game.ModAPI.Ingame.Utilities.ContainsKey)|Determines whether a configuration key (section/key) exists in the currently parsed configuration.|
|[`void GetKeys(string section, List<MyIniKey> keys)`](VRage.Game.ModAPI.Ingame.Utilities.GetKeys)||
|[`void GetKeys(List<MyIniKey> keys)`](VRage.Game.ModAPI.Ingame.Utilities.GetKeys)|Fills the provided list with all configuration keys within the currently parsed configuration.|
|[`void GetSections(List<string> names)`](VRage.Game.ModAPI.Ingame.Utilities.GetSections)|Fills the provided list with the names of all the sections in the currently parsed configuration.|
|[`void SetEndComment(string comment)`](VRage.Game.ModAPI.Ingame.Utilities.SetEndComment)|Sets a comment to be placed after the last section or item. Set the comment to`null`to remove it.|
|[`string GetSectionComment(string section)`](VRage.Game.ModAPI.Ingame.Utilities.GetSectionComment)|Get any comment that might be associated with the given section. Returns`null`if the section does not exist or has no comment.|
|[`void SetSectionComment(string section, string comment)`](VRage.Game.ModAPI.Ingame.Utilities.SetSectionComment)||
|[`string GetComment(string section, string name)`](VRage.Game.ModAPI.Ingame.Utilities.GetComment)||
|[`string GetComment(MyIniKey key)`](VRage.Game.ModAPI.Ingame.Utilities.GetComment)|Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.|
|[`void SetComment(string section, string name, string comment)`](VRage.Game.ModAPI.Ingame.Utilities.SetComment)||
|[`void SetComment(MyIniKey key, string comment)`](VRage.Game.ModAPI.Ingame.Utilities.SetComment)||
|[`MyIniValue Get(string section, string name)`](VRage.Game.ModAPI.Ingame.Utilities.Get)||
|[`MyIniValue Get(MyIniKey key)`](VRage.Game.ModAPI.Ingame.Utilities.Get)|Gets theT:VRage.Game.ModAPI.Ingame.Utilities.MyIniValueof the given configuration key.|
|[`void Delete(string section, string name)`](VRage.Game.ModAPI.Ingame.Utilities.Delete)||
|[`void Delete(MyIniKey key)`](VRage.Game.ModAPI.Ingame.Utilities.Delete)|Deletes the given configuration key.|
|[`void Set(string section, string name, string value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, string value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, bool value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, bool value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, byte value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, byte value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, sbyte value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, sbyte value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, ushort value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, ushort value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, short value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, short value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, uint value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, uint value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, int value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, int value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, ulong value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, ulong value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, long value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, long value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, float value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, float value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, double value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, double value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(string section, string name, decimal value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Set(MyIniKey key, decimal value)`](VRage.Game.ModAPI.Ingame.Utilities.Set)||
|[`void Clear()`](VRage.Game.ModAPI.Ingame.Utilities.Clear)||
|[`bool TryParse(string content)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given content as a configuration file.|
|[`bool TryParse(string content, ref MyIniParseResult result)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)||
|[`bool TryParse(string content, string section, ref MyIniParseResult result)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)||
|[`bool TryParse(string content, string section)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)||
|[`void Invalidate()`](VRage.Game.ModAPI.Ingame.Utilities.Invalidate)||
|[`string ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)||
