← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [MyDefinitionId](VRage.Game.MyDefinitionId)

### Summary

```csharp
public static bool TryParse(string id, ref MyDefinitionId definitionId)
```

Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type, while the second (the subtype) is not enforced.

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)



### Parameters

* [string](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) id
* [MyDefinitionId](VRage.Game.MyDefinitionId) definitionId
### Summary

```csharp
public static bool TryParse(string type, string subtype, ref MyDefinitionId definitionId)
```

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

### Parameters

* [string](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) type
* [string](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) subtype
* [MyDefinitionId](VRage.Game.MyDefinitionId) definitionId
