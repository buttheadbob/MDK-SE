← [Index](index)
# IMyAirVent Interface
**Namespace:** [`SpaceEngineers.Game.ModAPI.Ingame`](SpaceEngineers.Game.ModAPI.Ingame)  
**Assembly:** SpaceEngineers.Game.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
## Summary
AirVent block for pressurizing and depresurizing rooms
### Properties
|Member|Description|
|---|---|
|[`bool CanPressurize`](SpaceEngineers.Game.ModAPI.Ingame.CanPressurize)||
|[`bool IsDepressurizing`](SpaceEngineers.Game.ModAPI.Ingame.IsDepressurizing)||
|[`bool Depressurize`](SpaceEngineers.Game.ModAPI.Ingame.Depressurize)||
|[`VentStatus Status`](SpaceEngineers.Game.ModAPI.Ingame.Status)||
|[`bool PressurizationEnabled`](SpaceEngineers.Game.ModAPI.Ingame.PressurizationEnabled)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
### Methods
|Member|Description|
|---|---|
|[`bool IsPressurized()`](SpaceEngineers.Game.ModAPI.Ingame.IsPressurized)||
|[`float GetOxygenLevel()`](SpaceEngineers.Game.ModAPI.Ingame.GetOxygenLevel)||
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
|[`void RequestEnable(bool enable)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)_|
