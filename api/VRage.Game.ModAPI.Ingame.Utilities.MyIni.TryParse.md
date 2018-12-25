← [Index](Api-Index) ← [MyIni](VRage.Game.ModAPI.Ingame.Utilities.MyIni)

### Summary

```csharp
public bool TryParse(string content)
```

Attempts to parse the given content as a configuration file.

### Returns

[bool](System.Boolean)

`true`if the parse succeeds,`false`otherwise

### Parameters

* [string](System.String) content
### Summary

```csharp
public bool TryParse(string content, ref MyIniParseResult result)
```

Attempts to parse the given content as a configuration file.

### Returns

[bool](System.Boolean)

`true`if the parse succeeds,`false`otherwise

### Parameters

* [string](System.String) content
* [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) result
### Summary

```csharp
public bool TryParse(string content, string section, ref MyIniParseResult result)
```

Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString) , you will only get the parsed section, the rest will be discarded.

### Returns

[bool](System.Boolean)

`true`if the parse succeeds,`false`otherwise

### Parameters

* [string](System.String) content
* [string](System.String) section
* [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) result
### Summary

```csharp
public bool TryParse(string content, string section)
```

Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString) , you will only get the parsed section, the rest will be discarded.

### Returns

[bool](System.Boolean)

`true`if the parse succeeds,`false`otherwise

### Parameters

* [string](System.String) content
* [string](System.String) section
