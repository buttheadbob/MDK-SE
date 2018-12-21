← [Index](Api-Index)
# MyDefinitionId Struct
**Namespace:** [`VRage.Game`](VRage.Game)  
**Assembly:** VRage.Game.dll  
## Summary
Prefer getting definition ID using object builder used to create the item. If you have automatic rifle, in its Init method create new MyDefinitionId using TypeId and SubtypeName of object builder. Do not write specific values in code, as data comes from XML and if those change, code needs to change as well.
### Fields
|Member|Description|
|---|---|
|[`TypeId`](VRage.Game.TypeId)||
|[`SubtypeId`](VRage.Game.SubtypeId)||
|[`Comparer`](VRage.Game.Comparer)||
### Properties
|Member|Description|
|---|---|
|[`SubtypeName`](VRage.Game.SubtypeName)||
### Methods
|Member|Description|
|---|---|
|[`FromContent(MyObjectBuilder_Base)`](VRage.Game.FromContent)|Creates a new definition ID from a given content.|
|[`Parse(string)`](VRage.Game.Parse)|Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type. If it does not, an exception will be thrown. The second (the subtype) is not enforced. See [bool TryParse(string id, ref MyDefinitionId definitionId)](VRage.Game.TryParse) for a parsing method that does not throw an exception.|
|[`TryParse(string, ref MyDefinitionId)`](VRage.Game.TryParse)|Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type, while the second (the subtype) is not enforced.|
|[`TryParse(string, string, ref MyDefinitionId)`](VRage.Game.TryParse)||
|[`GetHashCode()`](VRage.Game.GetHashCode)||
|[`GetHashCodeLong()`](VRage.Game.GetHashCodeLong)|Safer hash code. It is unique in more situations than GetHashCode would be, but it may still require full check.|
|[`Equals(Object)`](VRage.Game.Equals)||
|[`ToString()`](VRage.Game.ToString)||
|[`Equals(MyDefinitionId)`](VRage.Game.Equals)||
