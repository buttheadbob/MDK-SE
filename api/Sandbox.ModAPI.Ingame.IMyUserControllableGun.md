← [Index](index)
# IMyUserControllableGun Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
|Member|Description|
|---|---|
|[`bool IsShooting`](Sandbox.ModAPI.Ingame.IsShooting)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
### Methods
|Member|Description|
|---|---|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
|[`void RequestEnable(bool enable)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|
