← [Index](index.md)
# IMyAttachableTopBlock Interface
** Namespace: ** Sandbox.ModAPI.Ingame  
** Assembly: ** Sandbox.Common.dll  
** Implements: **
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity.md)
### Properties
|Member|Description|
|---|---|
|[`bool IsAttached`](Sandbox.ModAPI.Ingame.IsAttached.md)||
|[`IMyMechanicalConnectionBlock Base`](Sandbox.ModAPI.Ingame.Base.md)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
### Methods
|Member|Description|
|---|---|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory.md)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock.md)_|
