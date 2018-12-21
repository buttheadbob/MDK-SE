← [Index](index.md)
# MyDefinitionId Struct
**Namespace:** VRage.Game  
**Assembly:** VRage.Game.dll  
## Summary
Prefer getting definition ID using object builder used to create the item. If you have automatic rifle, in its Init method create new MyDefinitionId using TypeId and SubtypeName of object builder. Do not write specific values in code, as data comes from XML and if those change, code needs to change as well.
### Fields
|Member|Description|
|---|---|
|[`MyObjectBuilderType TypeId`](VRage.Game.TypeId.md)||
|[`MyStringHash SubtypeId`](VRage.Game.SubtypeId.md)||
|[`DefinitionIdComparerType Comparer`](VRage.Game.Comparer.md)||
### Properties
|Member|Description|
|---|---|
|[`string SubtypeName`](VRage.Game.SubtypeName.md)||
### Methods
|Member|Description|
|---|---|
|[`MyDefinitionId FromContent(MyObjectBuilder_Base content)`](VRage.Game.FromContent.md)|Creates a new definition ID from a given content.|
|[`MyDefinitionId Parse(string id)`](VRage.Game.Parse.md)|Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type. If it does not, an exception will be thrown. The second (the subtype) is not enforced. SeeM:VRage.Game.MyDefinitionId.TryParse(System.String,VRage.Game.MyDefinitionId@)for a parsing method that does not throw an exception.|
|[`bool TryParse(string id, ref MyDefinitionId definitionId)`](VRage.Game.TryParse.md)||
|[`bool TryParse(string type, string subtype, ref MyDefinitionId definitionId)`](VRage.Game.TryParse.md)||
|[`int GetHashCode()`](VRage.Game.GetHashCode.md)||
|[`long GetHashCodeLong()`](VRage.Game.GetHashCodeLong.md)||
|[`bool Equals(Object obj)`](VRage.Game.Equals.md)||
|[`string ToString()`](VRage.Game.ToString.md)||
|[`bool Equals(MyDefinitionId other)`](VRage.Game.Equals.md)||
