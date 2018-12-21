← [Index](index)
# MyDetectedEntityInfo Struct
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>[`long EntityId`](Sandbox.ModAPI.Ingame.EntityId)</td><td>The entity's EntityId</td></tr>
<tr><td>[`string Name`](Sandbox.ModAPI.Ingame.Name)</td><td>The entity's display name if it is friendly, or a generic descriptor if it is not</td></tr>
<tr><td>[`MyDetectedEntityType Type`](Sandbox.ModAPI.Ingame.Type)</td><td>Enum describing the type of entity</td></tr>
<tr><td>[`Nullable<Vector3D> HitPosition`](Sandbox.ModAPI.Ingame.HitPosition)</td><td>Position where the raycast hit the entity. (can be null if the sensor didn't use a raycast)</td></tr>
<tr><td>[`MatrixD Orientation`](Sandbox.ModAPI.Ingame.Orientation)</td><td>The entity's absolute orientation at the time it was detected</td></tr>
<tr><td>[`Vector3 Velocity`](Sandbox.ModAPI.Ingame.Velocity)</td><td>The entity's absolute velocity at the time it was detected</td></tr>
<tr><td>[`MyRelationsBetweenPlayerAndBlock Relationship`](Sandbox.ModAPI.Ingame.Relationship)</td><td>Relationship between the entity and the owner of the sensor</td></tr>
<tr><td>[`BoundingBoxD BoundingBox`](Sandbox.ModAPI.Ingame.BoundingBox)</td><td>The entity's world-aligned bounding box</td></tr>
<tr><td>[`long TimeStamp`](Sandbox.ModAPI.Ingame.TimeStamp)</td><td>Time when the entity was detected. This field counts milliseconds, compensated for simspeed</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`Vector3D Position`](Sandbox.ModAPI.Ingame.Position)</td><td>The entity's position (center of the Bounding Box)</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`bool IsEmpty()`](Sandbox.ModAPI.Ingame.IsEmpty)</td><td>Determines if this structure is empty; meaning it does not contain any meaningful data</td></tr>
</table>
