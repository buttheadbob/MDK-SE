← [Index](Api-Index) ← [MyDefinitionId](VRage.Game.MyDefinitionId)

### Summary

```csharp
private public private public sealed struct.MyDefinitionId Parse(string id)
```

Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type. If it does not, an exception will be thrown. The second (the subtype) is not enforced. See [TryParse(string, ref MyDefinitionId)](VRage.Game.MyDefinitionId.TryParse) for a parsing method that does not throw an exception.

### Returns



### Example

### Remarks

