← [Index](index)
# MyWaypointInfo Struct
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Represents a GPS coordinate
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Name"><code>string Name</code></a>_</td><td>The name of this GPS coordinate</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Coords"><code>Vector3D Coords</code></a>_</td><td>Gets the target coordinate as a [Vector3D](VRageMath.Vector3D)</td></tr>
<tr><td>static _<a href="Sandbox.ModAPI.Ingame.Empty"><code>MyWaypointInfo Empty</code></a>_</td><td>Returns an empty (undefined) GPS coordinate</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="Sandbox.ModAPI.Ingame.FindAll"><code>void FindAll(string source, List<MyWaypointInfo> gpsList)</code></a>_</td><td>Searches for all GPS coordinates in the given text.</td></tr>
<tr><td>static _<a href="Sandbox.ModAPI.Ingame.TryParse"><code>bool TryParse(string text, ref MyWaypointInfo gps)</code></a>_</td><td>Attempts to parse a GPS coordinate from the given text. The text cannot contain anything but the GPS coordinate.<br/>A GPS coordinate has the format GPS:Name:X:Y:Z:</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.IsEmpty"><code>bool IsEmpty()</code></a>_</td><td>Determines whether this coordinate is empty (undefined)</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ToString"><code>string ToString()</code></a>_</td><td>Converts this GPS coordinate to its string equivalent</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Equals"><code>bool Equals(MyWaypointInfo other)</code></a>_</td><td>Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Equals"><code>bool Equals(MyWaypointInfo other, double epsilon)</code></a>_</td><td>Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hashcode of this coordinate</td></tr>
</table>
