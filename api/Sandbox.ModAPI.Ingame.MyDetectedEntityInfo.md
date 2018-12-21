← [Index](index)
# MyDetectedEntityInfo Struct
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.EntityId"><code>long EntityId</code></a>_</td><td>The entity's EntityId</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Name"><code>string Name</code></a>_</td><td>The entity's display name if it is friendly, or a generic descriptor if it is not</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Type"><code>MyDetectedEntityType Type</code></a>_</td><td>Enum describing the type of entity</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.HitPosition"><code>Nullable<Vector3D> HitPosition</code></a>_</td><td>Position where the raycast hit the entity. (can be null if the sensor didn't use a raycast)</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Orientation"><code>MatrixD Orientation</code></a>_</td><td>The entity's absolute orientation at the time it was detected</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Velocity"><code>Vector3 Velocity</code></a>_</td><td>The entity's absolute velocity at the time it was detected</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Relationship"><code>MyRelationsBetweenPlayerAndBlock Relationship</code></a>_</td><td>Relationship between the entity and the owner of the sensor</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.BoundingBox"><code>BoundingBoxD BoundingBox</code></a>_</td><td>The entity's world-aligned bounding box</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.TimeStamp"><code>long TimeStamp</code></a>_</td><td>Time when the entity was detected. This field counts milliseconds, compensated for simspeed</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Position"><code>Vector3D Position</code></a>_</td><td>The entity's position (center of the Bounding Box)</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.IsEmpty"><code>bool IsEmpty()</code></a>_</td><td>Determines if this structure is empty; meaning it does not contain any meaningful data</td></tr>
</table>
