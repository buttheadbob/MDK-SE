← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### StringSegmentComparer Class

```csharp
public class StringSegmentComparer: IEqualityComparer<StringSegment>
```

A comparer designed to compare [StringSegment](VRage.Game.ModAPI.Ingame.Utilities.StringSegment) instances in a case sensitive manner. Use [DEFAULT](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentComparer.DEFAULT) for a default instance

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IEqualityComparer&lt;StringSegment&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEqualityComparer-1?view=netframework-4.6)

#### Fields

[static StringSegmentComparer DEFAULT](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentComparer.DEFAULT)

> A default instance of [StringSegmentComparer](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentComparer) 

#### Constructors

[StringSegmentComparer()](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentComparer..ctor)

> 

#### Methods

[bool Equals(StringSegment x, StringSegment y)](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentComparer.Equals)

> Determines whether the specified objects are equal.

[int GetHashCode(StringSegment obj)](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentComparer.GetHashCode)

> Returns a hash code for the specified object.

