← [Index](Api-Index)
# MyWaypointInfo Struct
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Represents a GPS coordinate
### Fields
|Member|Description|
|---|---|
|[`Name`](Sandbox.ModAPI.Ingame.Name)|The name of this GPS coordinate|
|[`Coords`](Sandbox.ModAPI.Ingame.Coords)|Gets the target coordinate as a [Vector3D](VRageMath.Vector3D)|
|[`Empty`](Sandbox.ModAPI.Ingame.Empty)|Returns an empty (undefined) GPS coordinate|
### Methods
|Member|Description|
|---|---|
|[`FindAll(string, List<MyWaypointInfo>)`](Sandbox.ModAPI.Ingame.FindAll)|Searches for all GPS coordinates in the given text.|
|[`TryParse(string, ref MyWaypointInfo)`](Sandbox.ModAPI.Ingame.TryParse)|Attempts to parse a GPS coordinate from the given text. The text cannot contain anything but the GPS coordinate.<br/>A GPS coordinate has the format GPS:Name:X:Y:Z:|
|[`IsEmpty()`](Sandbox.ModAPI.Ingame.IsEmpty)|Determines whether this coordinate is empty (undefined)|
|[`ToString()`](Sandbox.ModAPI.Ingame.ToString)|Converts this GPS coordinate to its string equivalent|
|[`Equals(MyWaypointInfo)`](Sandbox.ModAPI.Ingame.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`Equals(MyWaypointInfo, double)`](Sandbox.ModAPI.Ingame.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`Equals(Object)`](Sandbox.ModAPI.Ingame.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`GetHashCode()`](Sandbox.ModAPI.Ingame.GetHashCode)|Gets the hashcode of this coordinate|
