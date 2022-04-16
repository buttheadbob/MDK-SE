← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### StringSegmentIgnoreCaseComparer Class

```csharp
public class StringSegmentIgnoreCaseComparer: IEqualityComparer<StringSegment>
```

A comparer designed to compare [StringSegment](VRage.Game.ModAPI.Ingame.Utilities.StringSegment) instances in a case insensitive manner. Use [DEFAULT](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentIgnoreCaseComparer.DEFAULT) for a default instance

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IEqualityComparer<StringSegment>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEqualityComparer-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\[static StringSegmentIgnoreCaseComparer DEFAULT](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentIgnoreCaseComparer.DEFAULT)|A default instance of [StringSegmentIgnoreCaseComparer](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentIgnoreCaseComparer) |

#### Constructors

|Member|Description|
|---|---|
|\[StringSegmentIgnoreCaseComparer()](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentIgnoreCaseComparer..ctor)||

#### Methods

|Member|Description|
|---|---|
|\[bool Equals(StringSegment, StringSegment)](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentIgnoreCaseComparer.Equals)|Determines whether the specified objects are equal.|
|\[int GetHashCode(StringSegment)](VRage.Game.ModAPI.Ingame.Utilities.StringSegmentIgnoreCaseComparer.GetHashCode)|Returns a hash code for the specified object.|

