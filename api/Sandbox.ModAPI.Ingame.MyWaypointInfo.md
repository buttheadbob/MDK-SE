← [Index](index)
# MyWaypointInfo Struct
**Namespace:** Sandbox.ModAPI.Ingame  
**Assembly:** Sandbox.Common.dll  
## Summary
Represents a GPS coordinate
### Fields
|Member|Description|
|---|---|
|[`string Name`](Sandbox.ModAPI.Ingame.Name)||
|[`Vector3D Coords`](Sandbox.ModAPI.Ingame.Coords)||
|[`MyWaypointInfo Empty`](Sandbox.ModAPI.Ingame.Empty)||
### Methods
|Member|Description|
|---|---|
|[`void FindAll(string source, List<MyWaypointInfo> gpsList)`](Sandbox.ModAPI.Ingame.FindAll)||
|[`bool TryParse(string text, ref MyWaypointInfo gps)`](Sandbox.ModAPI.Ingame.TryParse)||
|[`bool IsEmpty()`](Sandbox.ModAPI.Ingame.IsEmpty)||
|[`string ToString()`](Sandbox.ModAPI.Ingame.ToString)||
|[`bool Equals(MyWaypointInfo other)`](Sandbox.ModAPI.Ingame.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`bool Equals(MyWaypointInfo other, double epsilon)`](Sandbox.ModAPI.Ingame.Equals)||
|[`bool Equals(Object obj)`](Sandbox.ModAPI.Ingame.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`int GetHashCode()`](Sandbox.ModAPI.Ingame.GetHashCode)||
