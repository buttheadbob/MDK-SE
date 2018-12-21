← [Index](index.md)
# IMyCameraBlock Interface
**Namespace:** Sandbox.ModAPI.Ingame  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.md)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock.md)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity.md)
### Properties
|Member|Description|
|---|---|
|[`bool IsActive`](Sandbox.ModAPI.Ingame.IsActive.md)||
|[`double AvailableScanRange`](Sandbox.ModAPI.Ingame.AvailableScanRange.md)||
|[`bool EnableRaycast`](Sandbox.ModAPI.Ingame.EnableRaycast.md)||
|[`float RaycastConeLimit`](Sandbox.ModAPI.Ingame.RaycastConeLimit.md)||
|[`double RaycastDistanceLimit`](Sandbox.ModAPI.Ingame.RaycastDistanceLimit.md)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool Enabled`](Sandbox.ModAPI.Ingame.Enabled.md)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
### Methods
|Member|Description|
|---|---|
|[`MyDetectedEntityInfo Raycast(double distance, float pitch, float yaw)`](Sandbox.ModAPI.Ingame.Raycast.md)||
|[`MyDetectedEntityInfo Raycast(Vector3D targetPos)`](Sandbox.ModAPI.Ingame.Raycast.md)|Does a raycast to the given point. Will return an empty struct if distance or angle are out of bounds.|
|[`MyDetectedEntityInfo Raycast(double distance, Vector3D targetDirection)`](Sandbox.ModAPI.Ingame.Raycast.md)||
|[`bool CanScan(double distance)`](Sandbox.ModAPI.Ingame.CanScan.md)|Checks if the camera can scan the given distance.|
|[`bool CanScan(double distance, Vector3D direction)`](Sandbox.ModAPI.Ingame.CanScan.md)||
|[`bool CanScan(Vector3D target)`](Sandbox.ModAPI.Ingame.CanScan.md)|Checks if the camera can scan to the given target|
|[`int TimeUntilScan(double distance)`](Sandbox.ModAPI.Ingame.TimeUntilScan.md)|Returns the number of milliseconds until the camera can do a raycast of the given distance.|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory.md)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs.md)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
|[`void RequestEnable(bool enable)`](Sandbox.ModAPI.Ingame.RequestEnable.md)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock.md)_|
