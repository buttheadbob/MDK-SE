← [Index](index)
# IMyCockpit Interface
**Namespace:** Sandbox.ModAPI.Ingame  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyShipController`](Sandbox.ModAPI.Ingame.IMyShipController)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
|Member|Description|
|---|---|
|[`bool IsMainCockpit`](Sandbox.ModAPI.Ingame.IsMainCockpit)||
|[`float OxygenCapacity`](Sandbox.ModAPI.Ingame.OxygenCapacity)||
|[`float OxygenFilledRatio`](Sandbox.ModAPI.Ingame.OxygenFilledRatio)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool CanControlShip`](Sandbox.ModAPI.Ingame.CanControlShip)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsUnderControl`](Sandbox.ModAPI.Ingame.IsUnderControl)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HasWheels`](Sandbox.ModAPI.Ingame.HasWheels)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ControlWheels`](Sandbox.ModAPI.Ingame.ControlWheels)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ControlThrusters`](Sandbox.ModAPI.Ingame.ControlThrusters)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HandBrake`](Sandbox.ModAPI.Ingame.HandBrake)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool DampenersOverride`](Sandbox.ModAPI.Ingame.DampenersOverride)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowHorizonIndicator`](Sandbox.ModAPI.Ingame.ShowHorizonIndicator)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3 MoveIndicator`](Sandbox.ModAPI.Ingame.MoveIndicator)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector2 RotationIndicator`](Sandbox.ModAPI.Ingame.RotationIndicator)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`float RollIndicator`](Sandbox.ModAPI.Ingame.RollIndicator)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D CenterOfMass`](Sandbox.ModAPI.Ingame.CenterOfMass)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsMainCockpit`](Sandbox.ModAPI.Ingame.IsMainCockpit)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
### Methods
|Member|Description|
|---|---|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D GetNaturalGravity()`](Sandbox.ModAPI.Ingame.GetNaturalGravity)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D GetArtificialGravity()`](Sandbox.ModAPI.Ingame.GetArtificialGravity)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D GetTotalGravity()`](Sandbox.ModAPI.Ingame.GetTotalGravity)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`double GetShipSpeed()`](Sandbox.ModAPI.Ingame.GetShipSpeed)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyShipVelocities GetShipVelocities()`](Sandbox.ModAPI.Ingame.GetShipVelocities)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyShipMass CalculateShipMass()`](Sandbox.ModAPI.Ingame.CalculateShipMass)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool TryGetPlanetPosition(ref Vector3D position)`](Sandbox.ModAPI.Ingame.TryGetPlanetPosition)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool TryGetPlanetElevation(MyPlanetElevation detail, ref double elevation)`](Sandbox.ModAPI.Ingame.TryGetPlanetElevation)|_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
