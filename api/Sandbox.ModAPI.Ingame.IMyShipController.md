← [Index](index)
# IMyShipController Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
<table style="width:100%;display:table">
<tr><td>[`bool CanControlShip`](Sandbox.ModAPI.Ingame.CanControlShip)</td><td>Determines whether this specific ship controller is capable of controlling the ship it's installed on.</td></tr>
<tr><td>[`bool IsUnderControl`](Sandbox.ModAPI.Ingame.IsUnderControl)</td><td>Indicates whether a block is locally or remotely controlled.</td></tr>
<tr><td>[`bool HasWheels`](Sandbox.ModAPI.Ingame.HasWheels)</td><td>Determines whether there are any wheels on this ship.</td></tr>
<tr><td>[`bool ControlWheels`](Sandbox.ModAPI.Ingame.ControlWheels)</td><td>Gets or sets whether wheels are being controlled by this controller.</td></tr>
<tr><td>[`bool ControlThrusters`](Sandbox.ModAPI.Ingame.ControlThrusters)</td><td>Gets or sets whether thrusters are being controlled by this controller.</td></tr>
<tr><td>[`bool HandBrake`](Sandbox.ModAPI.Ingame.HandBrake)</td><td>Gets or sets the current state of the handbrake.</td></tr>
<tr><td>[`bool DampenersOverride`](Sandbox.ModAPI.Ingame.DampenersOverride)</td><td>Gets or sets whether dampeners are currently enabled.</td></tr>
<tr><td>[`bool ShowHorizonIndicator`](Sandbox.ModAPI.Ingame.ShowHorizonIndicator)</td><td>Gets or sets whether the horizon indicator should be displayed for this block.</td></tr>
<tr><td>[`Vector3 MoveIndicator`](Sandbox.ModAPI.Ingame.MoveIndicator)</td><td>Directional input from user/autopilot. Values can be very large with high controller sensitivity</td></tr>
<tr><td>[`Vector2 RotationIndicator`](Sandbox.ModAPI.Ingame.RotationIndicator)</td><td>Pitch, yaw input from user/autopilot. Values can be very large with high controller sensitivity</td></tr>
<tr><td>[`float RollIndicator`](Sandbox.ModAPI.Ingame.RollIndicator)</td><td>Roll input from user/autopilot. Values can be very large with high controller sensitivity</td></tr>
<tr><td>[`Vector3D CenterOfMass`](Sandbox.ModAPI.Ingame.CenterOfMass)</td><td>Center of mass in world coordinates</td></tr>
<tr><td>[`bool IsMainCockpit`](Sandbox.ModAPI.Ingame.IsMainCockpit)</td><td>Gets or sets if this controller is the main one.</td></tr>
<tr><td>[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>MyEntityComponentContainer Components</code></a>_</td></tr>
<tr><td>[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>long EntityId</code></a>_</td></tr>
<tr><td>[`string Name`](VRage.Game.ModAPI.Ingame.Name)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>string Name</code></a>_</td></tr>
<tr><td>[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>string DisplayName</code></a>_</td></tr>
<tr><td>[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)</td><td>Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>bool HasInventory</code></a>_</td></tr>
<tr><td>[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)</td><td>Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>int InventoryCount</code></a>_</td></tr>
<tr><td>[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>BoundingBoxD WorldAABB</code></a>_</td></tr>
<tr><td>[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>BoundingBoxD WorldAABBHr</code></a>_</td></tr>
<tr><td>[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>MatrixD WorldMatrix</code></a>_</td></tr>
<tr><td>[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>BoundingSphereD WorldVolume</code></a>_</td></tr>
<tr><td>[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>BoundingSphereD WorldVolumeHr</code></a>_</td></tr>
<tr><td>[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>SerializableDefinitionId BlockDefinition</code></a>_</td></tr>
<tr><td>[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>bool CheckConnectionAllowed</code></a>_</td></tr>
<tr><td>[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)</td><td>Grid in which the block is placed<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeGrid CubeGrid</code></a>_</td></tr>
<tr><td>[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)</td><td>Definition name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>string DefinitionDisplayNameText</code></a>_</td></tr>
<tr><td>[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)</td><td>Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>float DisassembleRatio</code></a>_</td></tr>
<tr><td>[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)</td><td>Translated block name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>string DisplayNameText</code></a>_</td></tr>
<tr><td>[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)</td><td>Hacking of the block is in progress<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>bool IsBeingHacked</code></a>_</td></tr>
<tr><td>[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)</td><td>True if integrity is above breaking threshold<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>bool IsFunctional</code></a>_</td></tr>
<tr><td>[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)</td><td>True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>bool IsWorking</code></a>_</td></tr>
<tr><td>[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)</td><td>Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>Vector3I Max</code></a>_</td></tr>
<tr><td>[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)</td><td>Block mass<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>float Mass</code></a>_</td></tr>
<tr><td>[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)</td><td>Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>Vector3I Min</code></a>_</td></tr>
<tr><td>[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)</td><td>Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>int NumberInGrid</code></a>_</td></tr>
<tr><td>[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)</td><td>Returns block orientation in base 6 directions<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>MyBlockOrientation Orientation</code></a>_</td></tr>
<tr><td>[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)</td><td>Id of player owning block (not steam Id)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>long OwnerId</code></a>_</td></tr>
<tr><td>[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)</td><td>Position in grid coordinates<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>Vector3I Position</code></a>_</td></tr>
<tr><td>[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>string CustomName</code></a>_</td></tr>
<tr><td>[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>string CustomNameWithFaction</code></a>_</td></tr>
<tr><td>[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>string DetailedInfo</code></a>_</td></tr>
<tr><td>[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>string CustomInfo</code></a>_</td></tr>
<tr><td>[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData)</td><td>Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>string CustomData</code></a>_</td></tr>
<tr><td>[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>bool ShowOnHUD</code></a>_</td></tr>
<tr><td>[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>bool ShowInTerminal</code></a>_</td></tr>
<tr><td>[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>bool ShowInToolbarConfig</code></a>_</td></tr>
<tr><td>[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>bool ShowInInventory</code></a>_</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`Vector3D GetNaturalGravity()`](Sandbox.ModAPI.Ingame.GetNaturalGravity)</td><td>Gets the detected natural gravity vector and power at the current location.</td></tr>
<tr><td>[`Vector3D GetArtificialGravity()`](Sandbox.ModAPI.Ingame.GetArtificialGravity)</td><td>Gets the detected artificial gravity vector and power at the current location.</td></tr>
<tr><td>[`Vector3D GetTotalGravity()`](Sandbox.ModAPI.Ingame.GetTotalGravity)</td><td>Gets the total accumulated gravity vector and power at the current location, taking both natural and artificial gravity into account.</td></tr>
<tr><td>[`double GetShipSpeed()`](Sandbox.ModAPI.Ingame.GetShipSpeed)</td><td>Gets the basic ship speed in meters per second, for when you just need to know how fast you're going.</td></tr>
<tr><td>[`MyShipVelocities GetShipVelocities()`](Sandbox.ModAPI.Ingame.GetShipVelocities)</td><td>Determines the linear velocities in meters per second and angular velocities in radians per second. Provides a more accurate representation of the directions and axis speeds.</td></tr>
<tr><td>[`MyShipMass CalculateShipMass()`](Sandbox.ModAPI.Ingame.CalculateShipMass)</td><td>Gets information about the current mass of the ship.</td></tr>
<tr><td>[`bool TryGetPlanetPosition(ref Vector3D position)`](Sandbox.ModAPI.Ingame.TryGetPlanetPosition)</td><td>Attempts to get the world position of the nearest planet. This method is only available when a ship is within the gravity well of a planet.</td></tr>
<tr><td>[`bool TryGetPlanetElevation(MyPlanetElevation detail, ref double elevation)`](Sandbox.ModAPI.Ingame.TryGetPlanetElevation)</td><td>Attempts to get the elevation of the ship in relation to the nearest planet. This method is only available when a ship is within the gravity well of a planet.</td></tr>
<tr><td>[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)</td><td>Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyInventory GetInventory()</code></a>_</td></tr>
<tr><td>[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)</td><td>Search for inventory component with maching index.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyInventory GetInventory(int index)</code></a>_</td></tr>
<tr><td>[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>Vector3D GetPosition()</code></a>_</td></tr>
<tr><td>[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)</td><td>Tag of faction owning block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>string GetOwnerFactionTag()</code></a>_</td></tr>
<tr><td>[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()</code></a>_</td></tr>
<tr><td>[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)</code></a>_</td></tr>
<tr><td>[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>void UpdateIsWorking()</code></a>_</td></tr>
<tr><td>[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>void UpdateVisual()</code></a>_</td></tr>
<tr><td>[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>bool HasLocalPlayerAccess()</code></a>_</td></tr>
<tr><td>[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>bool HasPlayerAccess(long playerId)</code></a>_</td></tr>
<tr><td>[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>void SetCustomName(string text)</code></a>_</td></tr>
<tr><td>[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>void SetCustomName(StringBuilder text)</code></a>_</td></tr>
<tr><td>[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)</code></a>_</td></tr>
<tr><td>[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)</code></a>_</td></tr>
<tr><td>[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>ITerminalAction GetActionWithName(string name)</code></a>_</td></tr>
<tr><td>[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>ITerminalProperty GetProperty(string id)</code></a>_</td></tr>
<tr><td>[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties)</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)</code></a>_</td></tr>
<tr><td>[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)</td><td>Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>bool IsSameConstructAs(IMyTerminalBlock other)</code></a>_</td></tr>
</table>
