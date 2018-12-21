← [Index](index)
# MyDefinitionId Struct
**Namespace:** [`VRage.Game`](VRage.Game)  
**Assembly:** VRage.Game.dll  
## Summary
Prefer getting definition ID using object builder used to create the item. If you have automatic rifle, in its Init method create new MyDefinitionId using TypeId and SubtypeName of object builder. Do not write specific values in code, as data comes from XML and if those change, code needs to change as well.
### Fields
<table style="width: 100%">
<tr><td>[`MyObjectBuilderType TypeId`](VRage.Game.TypeId)</td><td></td></tr>
<tr><td>[`MyStringHash SubtypeId`](VRage.Game.SubtypeId)</td><td></td></tr>
<tr><td>static [`DefinitionIdComparerType Comparer`](VRage.Game.Comparer)</td><td></td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`string SubtypeName`](VRage.Game.SubtypeName)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>static [`MyDefinitionId FromContent(MyObjectBuilder_Base content)`](VRage.Game.FromContent)</td><td>Creates a new definition ID from a given content.</td></tr>
<tr><td>static [`MyDefinitionId Parse(string id)`](VRage.Game.Parse)</td><td>Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type. If it does not, an exception will be thrown. The second (the subtype) is not enforced. See [bool TryParse(string id, ref MyDefinitionId definitionId)](VRage.Game.TryParse) for a parsing method that does not throw an exception.</td></tr>
<tr><td>static [`bool TryParse(string id, ref MyDefinitionId definitionId)`](VRage.Game.TryParse)</td><td>Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type, while the second (the subtype) is not enforced.</td></tr>
<tr><td>static [`bool TryParse(string type, string subtype, ref MyDefinitionId definitionId)`](VRage.Game.TryParse)</td><td></td></tr>
<tr><td>[`int GetHashCode()`](VRage.Game.GetHashCode)</td><td></td></tr>
<tr><td>[`long GetHashCodeLong()`](VRage.Game.GetHashCodeLong)</td><td>Safer hash code. It is unique in more situations than GetHashCode would be, but it may still require full check.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRage.Game.Equals)</td><td></td></tr>
<tr><td>[`string ToString()`](VRage.Game.ToString)</td><td></td></tr>
<tr><td>[`bool Equals(MyDefinitionId other)`](VRage.Game.Equals)</td><td></td></tr>
</table>
