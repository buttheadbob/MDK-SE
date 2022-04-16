← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyDefinitionId Struct

```csharp
public struct MyDefinitionId: IEquatable<MyDefinitionId\>
```

Prefer getting definition ID using object builder used to create the item. If you have automatic rifle, in its Init method create new MyDefinitionId using TypeId and SubtypeName of object builder. Do not write specific values in code, as data comes from XML and if those change, code needs to change as well.

**Namespace:** [VRage.Game](VRage.Game)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IEquatable<MyDefinitionId\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1static DefinitionIdComparerType Comparer](VRage.Game.MyDefinitionId.Comparer)||
|\$1MyStringHash SubtypeId](VRage.Game.MyDefinitionId.SubtypeId)||
|\$1MyObjectBuilderType TypeId](VRage.Game.MyDefinitionId.TypeId)||

#### Properties

|Member|Description|
|---|---|
|\$1string SubtypeName { get; }](VRage.Game.MyDefinitionId.SubtypeName)||

#### Constructors

|Member|Description|
|---|---|
|\$1MyDefinitionId(MyObjectBuilderType)](VRage.Game.MyDefinitionId..ctor)||
|\$1MyDefinitionId(MyObjectBuilderType, string)](VRage.Game.MyDefinitionId..ctor)||
|\$1MyDefinitionId(MyObjectBuilderType, MyStringHash)](VRage.Game.MyDefinitionId..ctor)||
|\$1MyDefinitionId(MyRuntimeObjectBuilderId, MyStringHash)](VRage.Game.MyDefinitionId..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static MyDefinitionId FromContent(MyObjectBuilder_Base)](VRage.Game.MyDefinitionId.FromContent)|Creates a new definition ID from a given content.|
|\$1static MyDefinitionId Parse(string)](VRage.Game.MyDefinitionId.Parse)|Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type. If it does not, an exception will be thrown. The second (the subtype) is not enforced. See TryParse for a parsing method that does not throw an exception.|
|\$1static bool TryParse(string, out MyDefinitionId)](VRage.Game.MyDefinitionId.TryParse)|Attempts to create a definition ID from a definition string, which has the form (using ores as an example) "MyObjectBuilder_Ore/Iron". The first part must represent an existing type, while the second (the subtype) is not enforced.|
|\$1static bool TryParse(string, string, out MyDefinitionId)](VRage.Game.MyDefinitionId.TryParse)||
|\$1bool Equals(object)](VRage.Game.MyDefinitionId.Equals)||
|\$1bool Equals(MyDefinitionId)](VRage.Game.MyDefinitionId.Equals)||
|\$1int GetHashCode()](VRage.Game.MyDefinitionId.GetHashCode)||
|\$1long GetHashCodeLong()](VRage.Game.MyDefinitionId.GetHashCodeLong)|Safer hash code. It is unique in more situations than GetHashCode would be, but it may still require full check.|
|\$1string ToString()](VRage.Game.MyDefinitionId.ToString)||

