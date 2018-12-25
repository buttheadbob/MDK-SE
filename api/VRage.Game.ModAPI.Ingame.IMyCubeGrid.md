← [Index](Api-Index)

#### IMyCubeGrid Interface

```csharp
private public abstract IMyCubeGrid
```

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)

#### Example

#### Remarks

#### Properties

|Member|Description|
|---|---|
|[CustomName](VRage.Game.ModAPI.Ingame.IMyCubeGrid.CustomName)|Display name of the grid (as seen in Info terminal tab)|
|[GridSize](VRage.Game.ModAPI.Ingame.IMyCubeGrid.GridSize)|Grid size in meters|
|[GridSizeEnum](VRage.Game.ModAPI.Ingame.IMyCubeGrid.GridSizeEnum)|Grid size enum|
|[IsStatic](VRage.Game.ModAPI.Ingame.IMyCubeGrid.IsStatic)|Determines if the grid is static (unmoveable)|
|[Max](VRage.Game.ModAPI.Ingame.IMyCubeGrid.Max)|Maximum coordinates of blocks in grid|
|[Min](VRage.Game.ModAPI.Ingame.IMyCubeGrid.Min)|Minimum coordinates of blocks in grid|
|[Components](VRage.Game.ModAPI.Ingame.IMyEntity.Components)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[EntityId](VRage.Game.ModAPI.Ingame.IMyEntity.EntityId)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[Name](VRage.Game.ModAPI.Ingame.IMyEntity.Name)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[DisplayName](VRage.Game.ModAPI.Ingame.IMyEntity.DisplayName)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[HasInventory](VRage.Game.ModAPI.Ingame.IMyEntity.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[InventoryCount](VRage.Game.ModAPI.Ingame.IMyEntity.InventoryCount)|Returns the count of the number of inventories this entity has.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldAABB](VRage.Game.ModAPI.Ingame.IMyEntity.WorldAABB)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldAABBHr](VRage.Game.ModAPI.Ingame.IMyEntity.WorldAABBHr)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldMatrix](VRage.Game.ModAPI.Ingame.IMyEntity.WorldMatrix)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldVolume](VRage.Game.ModAPI.Ingame.IMyEntity.WorldVolume)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldVolumeHr](VRage.Game.ModAPI.Ingame.IMyEntity.WorldVolumeHr)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|

#### Methods

|Member|Description|
|---|---|
|[CubeExists(Vector3I)](VRage.Game.ModAPI.Ingame.IMyCubeGrid.CubeExists)|Returns true if there is any block occupying given position|
|[GetCubeBlock(Vector3I)](VRage.Game.ModAPI.Ingame.IMyCubeGrid.GetCubeBlock)|Get cube block at given position|
|[GridIntegerToWorld(Vector3I)](VRage.Game.ModAPI.Ingame.IMyCubeGrid.GridIntegerToWorld)|Converts grid coordinates to world space|
|[WorldToGridInteger(Vector3D)](VRage.Game.ModAPI.Ingame.IMyCubeGrid.WorldToGridInteger)|Converts world coordinates to grid space cell coordinates|
|[IsSameConstructAs(IMyCubeGrid)](VRage.Game.ModAPI.Ingame.IMyCubeGrid.IsSameConstructAs)|Determines whether this grid is mechanically connected to the other. This is any grid connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br /><br />Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.|
|[GetInventory()](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetInventory(int)](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Search for inventory component with maching index.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetPosition()](VRage.Game.ModAPI.Ingame.IMyEntity.GetPosition)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|

