← [Index](Api-Index) ← [MyDefinitionId](VRage.Game.MyDefinitionId)

### Summary

```csharp
public bool TryParse(string id, ref MyDefinitionId definitionId)
```

Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type, while the second (the subtype) is not enforced.

### Returns

[bool](System.Boolean)



### Parameters

* [string](System.String) id
* [MyDefinitionId](VRage.Game.MyDefinitionId) definitionId
### Summary

```csharp
public bool TryParse(string type, string subtype, ref MyDefinitionId definitionId)
```

### Returns

[bool](System.Boolean)

### Parameters

* [string](System.String) type
* [string](System.String) subtype
* [MyDefinitionId](VRage.Game.MyDefinitionId) definitionId
