← [Index](index)
# MyWaypointInfo Struct
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Represents a GPS coordinate
### Fields
<table style="width: 100%">
<tr><td>[`string Name`](Sandbox.ModAPI.Ingame.Name)</td><td>The name of this GPS coordinate</td></tr>
<tr><td>[`Vector3D Coords`](Sandbox.ModAPI.Ingame.Coords)</td><td>Gets the target coordinate as a [Vector3D](VRageMath.Vector3D)</td></tr>
<tr><td>static [`MyWaypointInfo Empty`](Sandbox.ModAPI.Ingame.Empty)</td><td>Returns an empty (undefined) GPS coordinate</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>static [`void FindAll(string source, List<MyWaypointInfo> gpsList)`](Sandbox.ModAPI.Ingame.FindAll)</td><td>Searches for all GPS coordinates in the given text.</td></tr>
<tr><td>static [`bool TryParse(string text, ref MyWaypointInfo gps)`](Sandbox.ModAPI.Ingame.TryParse)</td><td>Attempts to parse a GPS coordinate from the given text. The text cannot contain anything but the GPS coordinate.<br/>A GPS coordinate has the format GPS:Name:X:Y:Z:</td></tr>
<tr><td>[`bool IsEmpty()`](Sandbox.ModAPI.Ingame.IsEmpty)</td><td>Determines whether this coordinate is empty (undefined)</td></tr>
<tr><td>[`string ToString()`](Sandbox.ModAPI.Ingame.ToString)</td><td>Converts this GPS coordinate to its string equivalent</td></tr>
<tr><td>[`bool Equals(MyWaypointInfo other)`](Sandbox.ModAPI.Ingame.Equals)</td><td>Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.</td></tr>
<tr><td>[`bool Equals(MyWaypointInfo other, double epsilon)`](Sandbox.ModAPI.Ingame.Equals)</td><td>Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.</td></tr>
<tr><td>[`bool Equals(Object obj)`](Sandbox.ModAPI.Ingame.Equals)</td><td>Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.</td></tr>
<tr><td>[`int GetHashCode()`](Sandbox.ModAPI.Ingame.GetHashCode)</td><td>Gets the hashcode of this coordinate</td></tr>
</table>
