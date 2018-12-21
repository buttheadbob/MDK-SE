← [Index](index)
# MyWaypointInfo Struct
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Represents a GPS coordinate
### Fields
|Member|Description|
|---|---|
|[`string Name`](Sandbox.ModAPI.Ingame.Name)|The name of this GPS coordinate|
|[`Vector3D Coords`](Sandbox.ModAPI.Ingame.Coords)|Gets the target coordinate as a [Vector3D](VRageMath.Vector3D)|
|static [`MyWaypointInfo Empty`](Sandbox.ModAPI.Ingame.Empty)|Returns an empty (undefined) GPS coordinate|
### Methods
|Member|Description|
|---|---|
|static [`void FindAll(string source, List<MyWaypointInfo> gpsList)`](Sandbox.ModAPI.Ingame.FindAll)|Searches for all GPS coordinates in the given text.|
|static [`bool TryParse(string text, ref MyWaypointInfo gps)`](Sandbox.ModAPI.Ingame.TryParse)|Attempts to parse a GPS coordinate from the given text. The text cannot contain anything but the GPS coordinate.<br/>A GPS coordinate has the format GPS:Name:X:Y:Z:|
|[`bool IsEmpty()`](Sandbox.ModAPI.Ingame.IsEmpty)|Determines whether this coordinate is empty (undefined)|
|[`string ToString()`](Sandbox.ModAPI.Ingame.ToString)|Converts this GPS coordinate to its string equivalent|
|[`bool Equals(MyWaypointInfo other)`](Sandbox.ModAPI.Ingame.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`bool Equals(MyWaypointInfo other, double epsilon)`](Sandbox.ModAPI.Ingame.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`bool Equals(Object obj)`](Sandbox.ModAPI.Ingame.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`int GetHashCode()`](Sandbox.ModAPI.Ingame.GetHashCode)|Gets the hashcode of this coordinate|
