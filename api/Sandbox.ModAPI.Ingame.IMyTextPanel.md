← [Index](index)
# IMyTextPanel Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.CurrentlyShownImage"><code>string CurrentlyShownImage</code></a>_</td><td>The image that is currently shown on the screen. Returns NULL if there are no images selected OR the screen is in text mode.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowOnScreen"><code>ShowTextOnScreenFlag ShowOnScreen</code></a>_</td><td>Indicates what should be shown on the screen, none being an image.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowText"><code>bool ShowText</code></a>_</td><td>Returns true if the ShowOnScreen flag is set to either PUBLIC or PRIVATE</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.FontSize"><code>float FontSize</code></a>_</td><td>Gets or sets font size</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.FontColor"><code>Color FontColor</code></a>_</td><td>Gets or sets font color</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.BackgroundColor"><code>Color BackgroundColor</code></a>_</td><td>Gets or sets background color</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ChangeInterval"><code>float ChangeInterval</code></a>_</td><td>Gets or sets the change interval for selected textures</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Font"><code>string Font</code></a>_</td><td>Gets or sets the font</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Components"><code>MyEntityComponentContainer Components</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.EntityId"><code>long EntityId</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Name"><code>string Name</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisplayName"><code>string DisplayName</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.HasInventory"><code>bool HasInventory</code></a>_</td><td>Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.InventoryCount"><code>int InventoryCount</code></a>_</td><td>Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldAABB"><code>BoundingBoxD WorldAABB</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldAABBHr"><code>BoundingBoxD WorldAABBHr</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldMatrix"><code>MatrixD WorldMatrix</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldVolume"><code>BoundingSphereD WorldVolume</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldVolumeHr"><code>BoundingSphereD WorldVolumeHr</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.BlockDefinition"><code>SerializableDefinitionId BlockDefinition</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CheckConnectionAllowed"><code>bool CheckConnectionAllowed</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CubeGrid"><code>IMyCubeGrid CubeGrid</code></a>_</td><td>Grid in which the block is placed<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText"><code>string DefinitionDisplayNameText</code></a>_</td><td>Definition name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisassembleRatio"><code>float DisassembleRatio</code></a>_</td><td>Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisplayNameText"><code>string DisplayNameText</code></a>_</td><td>Translated block name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsBeingHacked"><code>bool IsBeingHacked</code></a>_</td><td>Hacking of the block is in progress<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsFunctional"><code>bool IsFunctional</code></a>_</td><td>True if integrity is above breaking threshold<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsWorking"><code>bool IsWorking</code></a>_</td><td>True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Max"><code>Vector3I Max</code></a>_</td><td>Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Mass"><code>float Mass</code></a>_</td><td>Block mass<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Min"><code>Vector3I Min</code></a>_</td><td>Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.NumberInGrid"><code>int NumberInGrid</code></a>_</td><td>Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Orientation"><code>MyBlockOrientation Orientation</code></a>_</td><td>Returns block orientation in base 6 directions<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.OwnerId"><code>long OwnerId</code></a>_</td><td>Id of player owning block (not steam Id)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Position"><code>Vector3I Position</code></a>_</td><td>Position in grid coordinates<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.CustomName"><code>string CustomName</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.CustomNameWithFaction"><code>string CustomNameWithFaction</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.DetailedInfo"><code>string DetailedInfo</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.CustomInfo"><code>string CustomInfo</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.CustomData"><code>string CustomData</code></a>_</td><td>Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowOnHUD"><code>bool ShowOnHUD</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowInTerminal"><code>bool ShowInTerminal</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowInToolbarConfig"><code>bool ShowInToolbarConfig</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowInInventory"><code>bool ShowInInventory</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Enabled"><code>bool Enabled</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyFunctionalBlock"><code>IMyFunctionalBlock</code></a>_</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.WritePublicText"><code>bool WritePublicText(string value, bool append)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetPublicText"><code>string GetPublicText()</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.WritePublicText"><code>bool WritePublicText(StringBuilder value, bool append)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ReadPublicText"><code>void ReadPublicText(StringBuilder buffer, bool append)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.WritePublicTitle"><code>bool WritePublicTitle(string value, bool append)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetPublicTitle"><code>string GetPublicTitle()</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.WritePrivateText"><code>bool WritePrivateText(string value, bool append)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetPrivateText"><code>string GetPrivateText()</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.WritePrivateTitle"><code>bool WritePrivateTitle(string value, bool append)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetPrivateTitle"><code>string GetPrivateTitle()</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.AddImageToSelection"><code>void AddImageToSelection(string id, bool checkExistence)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.AddImagesToSelection"><code>void AddImagesToSelection(List<string> ids, bool checkExistence)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.RemoveImageFromSelection"><code>void RemoveImageFromSelection(string id, bool removeDuplicates)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.RemoveImagesFromSelection"><code>void RemoveImagesFromSelection(List<string> ids, bool removeDuplicates)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ClearImagesFromSelection"><code>void ClearImagesFromSelection()</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetSelectedImages"><code>void GetSelectedImages(List<string> output)</code></a>_</td><td>Outputs the selected image ids to the specified list. NOTE: List is not cleared internally.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowPublicTextOnScreen"><code>void ShowPublicTextOnScreen()</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowPrivateTextOnScreen"><code>void ShowPrivateTextOnScreen()</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ShowTextureOnScreen"><code>void ShowTextureOnScreen()</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.SetShowOnScreen"><code>void SetShowOnScreen(ShowTextOnScreenFlag set)</code></a>_</td><td></td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetFonts"><code>void GetFonts(List<string> fonts)</code></a>_</td><td>Gets a list of available fonts</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory()</code></a>_</td><td>Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory(int index)</code></a>_</td><td>Search for inventory component with maching index.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetPosition"><code>Vector3D GetPosition()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetOwnerFactionTag"><code>string GetOwnerFactionTag()</code></a>_</td><td>Tag of faction owning block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner"><code>MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetUserRelationToOwner"><code>MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.UpdateIsWorking"><code>void UpdateIsWorking()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.UpdateVisual"><code>void UpdateVisual()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.HasLocalPlayerAccess"><code>bool HasLocalPlayerAccess()</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.HasPlayerAccess"><code>bool HasPlayerAccess(long playerId)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.SetCustomName"><code>void SetCustomName(string text)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.SetCustomName"><code>void SetCustomName(StringBuilder text)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetActions"><code>void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.SearchActionsOfName"><code>void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetActionWithName"><code>ITerminalAction GetActionWithName(string name)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetProperty"><code>ITerminalProperty GetProperty(string id)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetProperties"><code>void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.IsSameConstructAs"><code>bool IsSameConstructAs(IMyTerminalBlock other)</code></a>_</td><td>Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyTerminalBlock"><code>IMyTerminalBlock</code></a>_</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.RequestEnable"><code>void RequestEnable(bool enable)</code></a>_</td><td>_Inherited from <a href="Sandbox.ModAPI.Ingame.IMyFunctionalBlock"><code>IMyFunctionalBlock</code></a>_</td></tr>
</table>
