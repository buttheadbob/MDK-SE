← [Index](Api-Index) ← [MyIni](VRage.Game.ModAPI.Ingame.Utilities.MyIni)

### Summary

```csharp
public bool TryParse(string content)
```

Attempts to parse the given content as a configuration file.

### Returns

`true`if the parse succeeds,`false`otherwise

### Example

### Remarks

### Summary

```csharp
public bool TryParse(string content, ref public sealed struct MyIniParseResult result)
```

Attempts to parse the given content as a configuration file.

### Returns

`true`if the parse succeeds,`false`otherwise

### Example

### Remarks

### Summary

```csharp
public bool TryParse(string content, string section, ref public sealed struct MyIniParseResult result)
```

Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString) , you will only get the parsed section, the rest will be discarded.

### Returns

`true`if the parse succeeds,`false`otherwise

### Example

### Remarks

### Summary

```csharp
public bool TryParse(string content, string section)
```

Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString) , you will only get the parsed section, the rest will be discarded.

### Returns

`true`if the parse succeeds,`false`otherwise

### Example

### Remarks

