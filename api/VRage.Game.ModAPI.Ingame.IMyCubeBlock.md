← [Index](index)
# IMyCubeBlock Interface
**Namespace:** VRage.Game.ModAPI.Ingame  
**Assembly:** VRage.Game.dll  
**Implements:**
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
## Summary
Basic cube interface
### Properties
|Member|Description|
|---|---|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)||
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)||
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)||
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)||
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)||
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)||
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)||
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)||
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)||
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)||
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)||
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)||
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)||
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)||
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)||
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
### Methods
|Member|Description|
|---|---|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)||
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)||
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)||
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)||
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)||
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
