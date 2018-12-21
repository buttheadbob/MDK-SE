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
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.EndContent"><code>string EndContent</code></a>_</td><td>You can terminate a configuration stream by entering "---" on a separate line. This property will contain all the content after this line.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.EndComment"><code>string EndComment</code></a>_</td><td>Get or set a comment to be placed after the last section or item. Is`null`if the section does not exist or has no comment.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRage.Game.ModAPI.Ingame.Utilities.HasSection"><code>bool HasSection(string config, string section)</code></a>_</td><td>Determines if the given configuration contains what looks like the given section. It does not verify that the content is actually in a valid format, just if there's a line starting with [section].</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.ContainsSection"><code>bool ContainsSection(string section)</code></a>_</td><td>Determines whether a section of a given name exists in the currently parsed configuration.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.ContainsKey"><code>bool ContainsKey(string section, string name)</code></a>_</td><td>Determines whether a configuration key (section/key) exists in the currently parsed configuration.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.ContainsKey"><code>bool ContainsKey(MyIniKey key)</code></a>_</td><td>Determines whether a configuration key (section/key) exists in the currently parsed configuration.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.GetKeys"><code>void GetKeys(string section, List<MyIniKey> keys)</code></a>_</td><td>Fills the provided list with the configuration keys within the given section.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.GetKeys"><code>void GetKeys(List<MyIniKey> keys)</code></a>_</td><td>Fills the provided list with all configuration keys within the currently parsed configuration.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.GetSections"><code>void GetSections(List<string> names)</code></a>_</td><td>Fills the provided list with the names of all the sections in the currently parsed configuration.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.SetEndComment"><code>void SetEndComment(string comment)</code></a>_</td><td>Sets a comment to be placed after the last section or item. Set the comment to`null`to remove it.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.GetSectionComment"><code>string GetSectionComment(string section)</code></a>_</td><td>Get any comment that might be associated with the given section. Returns`null`if the section does not exist or has no comment.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.SetSectionComment"><code>void SetSectionComment(string section, string comment)</code></a>_</td><td>Sets a comment on a given section. The section must already exist. Set the comment to`null`to remove it.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.GetComment"><code>string GetComment(string section, string name)</code></a>_</td><td>Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.GetComment"><code>string GetComment(MyIniKey key)</code></a>_</td><td>Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.SetComment"><code>void SetComment(string section, string name, string comment)</code></a>_</td><td>Sets a comment on a given item. The item must already exist. Set the comment to`null`to remove it.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.SetComment"><code>void SetComment(MyIniKey key, string comment)</code></a>_</td><td>Sets a comment on a given item. The item must already exist. Set the comment to`null`to remove it.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Get"><code>MyIniValue Get(string section, string name)</code></a>_</td><td>Gets the [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Get"><code>MyIniValue Get(MyIniKey key)</code></a>_</td><td>Gets the [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Delete"><code>void Delete(string section, string name)</code></a>_</td><td>Deletes the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Delete"><code>void Delete(MyIniKey key)</code></a>_</td><td>Deletes the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, string value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, string value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, bool value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, bool value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, byte value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, byte value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, sbyte value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, sbyte value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, ushort value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, ushort value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, short value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, short value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, uint value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, uint value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, int value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, int value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, ulong value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, ulong value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, long value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, long value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, float value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, float value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, double value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, double value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(string section, string name, decimal value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Set"><code>void Set(MyIniKey key, decimal value)</code></a>_</td><td>Sets the value of the given configuration key.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Clear"><code>void Clear()</code></a>_</td><td>Empties this configuration</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.TryParse"><code>bool TryParse(string content)</code></a>_</td><td>Attempts to parse the given content as a configuration file.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.TryParse"><code>bool TryParse(string content, ref MyIniParseResult result)</code></a>_</td><td>Attempts to parse the given content as a configuration file.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.TryParse"><code>bool TryParse(string content, string section, ref MyIniParseResult result)</code></a>_</td><td>Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [string ToString()](VRage.Game.ModAPI.Ingame.Utilities.ToString) , you will only get the parsed section, the rest will be discarded.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.TryParse"><code>bool TryParse(string content, string section)</code></a>_</td><td>Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [string ToString()](VRage.Game.ModAPI.Ingame.Utilities.ToString) , you will only get the parsed section, the rest will be discarded.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Invalidate"><code>void Invalidate()</code></a>_</td><td>Forces regeneration of the ini content. Only really useful if you want to reformat the configuration file.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.ToString"><code>string ToString()</code></a>_</td><td>Generates a configuration file from the currently parsed configuration</td></tr>
</table>
