← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### StringSegment Struct

```csharp
public struct StringSegment
```

Represents a segment of a string.

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

#### Fields

|Member|Description|
|---|---|
|[Text](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Text)|The original text string|
|[Start](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Start)|Where the segment starts|
|[Length](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Length)|The length of the segment|

#### Properties

|Member|Description|
|---|---|
|[IsEmpty { get; }](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.IsEmpty)|Determines whether this is an empty/undefined string segment|
|[IsCached { get; }](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.IsCached)|Determines whether this segment has been pre-cached in such a way that no allocation will occur when using [ToString()](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.ToString) |
|[Item { get; }](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Item)||

#### Constructors

|Member|Description|
|---|---|
|[StringSegment(string)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment..ctor)||
|[StringSegment(string, int, int)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment..ctor)||

#### Methods

|Member|Description|
|---|---|
|[IndexOf(char)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.IndexOf)|Reports the zero-based index of the first occurence of the specified character, relative to [Start](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Start) . Returns -1 if nothing was found.|
|[IndexOf(char, int)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.IndexOf)|Reports the zero-based index of the first occurence of the specified character, relative to [Start](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Start) . Returns -1 if nothing was found.|
|[IndexOfAny(Char[])](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.IndexOfAny)|Reports the zero-based index of the first occurence of one of the provided characters, relative to [Start](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Start) . Returns -1 if nothing was found.|
|[Equals(object)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Equals)|Indicates whether this instance and a specified object are equal.|
|[GetHashCode()](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.GetHashCode)|Returns the hash code for this instance.|
|[Equals(string)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Equals)|Compares this string segment with the given string in a case sensitive manner.|
|[Equals(StringSegment)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.Equals)|Compares this string segment with another in a case sensitive manner.|
|[EqualsIgnoreCase(string)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.EqualsIgnoreCase)|Compares this string segment with the given string in a case insensitive manner.|
|[EqualsIgnoreCase(StringSegment)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.EqualsIgnoreCase)|Compares this string segment with another in a case insensitive manner.|
|[ToString()](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.ToString)|Returns a string containing just this segment.|
|[GetLines(List)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.GetLines)|Fills a list with individual string segments representing the lines of text within this string segment, separated by newlines.|
|[GetLines(List)](VRage.Game.ModAPI.Ingame.Utilities.StringSegment.GetLines)|Fills a list with individual strings representing the lines of text within this string segment, separated by newlines.|

