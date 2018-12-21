← [Index](index.md)
#MyWaypointInfo Struct
**Namespace:** Sandbox.ModAPI.Ingame  
**Assembly:** Sandbox.Common.dll  
##Summary
Represents a GPS coordinate
###Fields
|Member|Description|
|---|---|
|[`string Name`](Sandbox.ModAPI.Ingame.Name.md)||
|[`Vector3D Coords`](Sandbox.ModAPI.Ingame.Coords.md)||
|[`MyWaypointInfo Empty`](Sandbox.ModAPI.Ingame.Empty.md)||
###Methods
|Member|Description|
|---|---|
|[`void FindAll(string source, List<MyWaypointInfo> gpsList)`](Sandbox.ModAPI.Ingame.FindAll.md)||
|[`bool TryParse(string text, ref MyWaypointInfo gps)`](Sandbox.ModAPI.Ingame.TryParse.md)||
|[`bool IsEmpty()`](Sandbox.ModAPI.Ingame.IsEmpty.md)||
|[`string ToString()`](Sandbox.ModAPI.Ingame.ToString.md)||
|[`bool Equals(MyWaypointInfo other)`](Sandbox.ModAPI.Ingame.Equals.md)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`bool Equals(MyWaypointInfo other, double epsilon)`](Sandbox.ModAPI.Ingame.Equals.md)||
|[`bool Equals(Object obj)`](Sandbox.ModAPI.Ingame.Equals.md)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[`int GetHashCode()`](Sandbox.ModAPI.Ingame.GetHashCode.md)||
