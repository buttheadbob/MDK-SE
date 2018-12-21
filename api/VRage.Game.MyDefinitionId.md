← [Index](index)
# MyDefinitionId Struct
**Namespace:** [`VRage.Game`](VRage.Game)  
**Assembly:** VRage.Game.dll  
## Summary
Prefer getting definition ID using object builder used to create the item. If you have automatic rifle, in its Init method create new MyDefinitionId using TypeId and SubtypeName of object builder. Do not write specific values in code, as data comes from XML and if those change, code needs to change as well.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.TypeId"><code>MyObjectBuilderType TypeId</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.SubtypeId"><code>MyStringHash SubtypeId</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.Game.Comparer"><code>DefinitionIdComparerType Comparer</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.SubtypeName"><code>string SubtypeName</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRage.Game.FromContent"><code>MyDefinitionId FromContent(MyObjectBuilder_Base content)</code></a>_</td><td>Creates a new definition ID from a given content.</td></tr>
<tr><td>static _<a href="VRage.Game.Parse"><code>MyDefinitionId Parse(string id)</code></a>_</td><td>Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type. If it does not, an exception will be thrown. The second (the subtype) is not enforced. See [bool TryParse(string id, ref MyDefinitionId definitionId)](VRage.Game.TryParse) for a parsing method that does not throw an exception.</td></tr>
<tr><td>static _<a href="VRage.Game.TryParse"><code>bool TryParse(string id, ref MyDefinitionId definitionId)</code></a>_</td><td>Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type, while the second (the subtype) is not enforced.</td></tr>
<tr><td>static _<a href="VRage.Game.TryParse"><code>bool TryParse(string type, string subtype, ref MyDefinitionId definitionId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.GetHashCode"><code>int GetHashCode()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.GetHashCodeLong"><code>long GetHashCodeLong()</code></a>_</td><td>Safer hash code. It is unique in more situations than GetHashCode would be, but it may still require full check.</td></tr>
<tr><td>_<a href="VRage.Game.Equals"><code>bool Equals(Object obj)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ToString"><code>string ToString()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.Equals"><code>bool Equals(MyDefinitionId other)</code></a>_</td><td></td></tr>
</table>
