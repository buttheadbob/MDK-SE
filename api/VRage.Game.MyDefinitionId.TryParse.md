← [Index](Api-Index) ← [MyDefinitionId](VRage.Game.MyDefinitionId)

```csharp[bool](System.Boolean) TryParse([string](System.String) id, ref [MyDefinitionId](VRage.Game.MyDefinitionId) definitionId)```##### Summary

Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type, while the second (the subtype) is not enforced.

##### Returns



```csharp[bool](System.Boolean) TryParse([string](System.String) type, [string](System.String) subtype, ref [MyDefinitionId](VRage.Game.MyDefinitionId) definitionId)```