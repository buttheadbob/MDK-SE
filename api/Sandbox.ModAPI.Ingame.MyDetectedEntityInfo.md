← [Index](index)
# MyDetectedEntityInfo Struct
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
### Fields
|Member|Description|
|---|---|
|[`long EntityId`](Sandbox.ModAPI.Ingame.EntityId)|The entity's EntityId|
|[`string Name`](Sandbox.ModAPI.Ingame.Name)|The entity's display name if it is friendly, or a generic descriptor if it is not|
|[`MyDetectedEntityType Type`](Sandbox.ModAPI.Ingame.Type)|Enum describing the type of entity|
|[`Nullable<Vector3D> HitPosition`](Sandbox.ModAPI.Ingame.HitPosition)|Position where the raycast hit the entity. (can be null if the sensor didn't use a raycast)|
|[`MatrixD Orientation`](Sandbox.ModAPI.Ingame.Orientation)|The entity's absolute orientation at the time it was detected|
|[`Vector3 Velocity`](Sandbox.ModAPI.Ingame.Velocity)|The entity's absolute velocity at the time it was detected|
|[`MyRelationsBetweenPlayerAndBlock Relationship`](Sandbox.ModAPI.Ingame.Relationship)|Relationship between the entity and the owner of the sensor|
|[`BoundingBoxD BoundingBox`](Sandbox.ModAPI.Ingame.BoundingBox)|The entity's world-aligned bounding box|
|[`long TimeStamp`](Sandbox.ModAPI.Ingame.TimeStamp)|Time when the entity was detected. This field counts milliseconds, compensated for simspeed|
### Properties
|Member|Description|
|---|---|
|[`Vector3D Position`](Sandbox.ModAPI.Ingame.Position)|The entity's position (center of the Bounding Box)|
### Methods
|Member|Description|
|---|---|
|[`bool IsEmpty()`](Sandbox.ModAPI.Ingame.IsEmpty)|Determines if this structure is empty; meaning it does not contain any meaningful data|
