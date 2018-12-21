← [Index](index.md)
#IMyTextPanel Interface
**Namespace:** Sandbox.ModAPI.Ingame  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.md)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock.md)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity.md)
###Properties
|Member|Description|
|---|---|
|[`string CurrentlyShownImage`](Sandbox.ModAPI.Ingame.CurrentlyShownImage.md)||
|[`ShowTextOnScreenFlag ShowOnScreen`](Sandbox.ModAPI.Ingame.ShowOnScreen.md)||
|[`bool ShowText`](Sandbox.ModAPI.Ingame.ShowText.md)||
|[`float FontSize`](Sandbox.ModAPI.Ingame.FontSize.md)||
|[`Color FontColor`](Sandbox.ModAPI.Ingame.FontColor.md)||
|[`Color BackgroundColor`](Sandbox.ModAPI.Ingame.BackgroundColor.md)||
|[`float ChangeInterval`](Sandbox.ModAPI.Ingame.ChangeInterval.md)||
|[`string Font`](Sandbox.ModAPI.Ingame.Font.md)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool Enabled`](Sandbox.ModAPI.Ingame.Enabled.md)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
###Methods
|Member|Description|
|---|---|
|[`bool WritePublicText(string value, bool append)`](Sandbox.ModAPI.Ingame.WritePublicText.md)||
|[`string GetPublicText()`](Sandbox.ModAPI.Ingame.GetPublicText.md)||
|[`bool WritePublicText(StringBuilder value, bool append)`](Sandbox.ModAPI.Ingame.WritePublicText.md)||
|[`void ReadPublicText(StringBuilder buffer, bool append)`](Sandbox.ModAPI.Ingame.ReadPublicText.md)||
|[`bool WritePublicTitle(string value, bool append)`](Sandbox.ModAPI.Ingame.WritePublicTitle.md)||
|[`string GetPublicTitle()`](Sandbox.ModAPI.Ingame.GetPublicTitle.md)||
|[`bool WritePrivateText(string value, bool append)`](Sandbox.ModAPI.Ingame.WritePrivateText.md)||
|[`string GetPrivateText()`](Sandbox.ModAPI.Ingame.GetPrivateText.md)||
|[`bool WritePrivateTitle(string value, bool append)`](Sandbox.ModAPI.Ingame.WritePrivateTitle.md)||
|[`string GetPrivateTitle()`](Sandbox.ModAPI.Ingame.GetPrivateTitle.md)||
|[`void AddImageToSelection(string id, bool checkExistence)`](Sandbox.ModAPI.Ingame.AddImageToSelection.md)||
|[`void AddImagesToSelection(List<string> ids, bool checkExistence)`](Sandbox.ModAPI.Ingame.AddImagesToSelection.md)||
|[`void RemoveImageFromSelection(string id, bool removeDuplicates)`](Sandbox.ModAPI.Ingame.RemoveImageFromSelection.md)||
|[`void RemoveImagesFromSelection(List<string> ids, bool removeDuplicates)`](Sandbox.ModAPI.Ingame.RemoveImagesFromSelection.md)||
|[`void ClearImagesFromSelection()`](Sandbox.ModAPI.Ingame.ClearImagesFromSelection.md)||
|[`void GetSelectedImages(List<string> output)`](Sandbox.ModAPI.Ingame.GetSelectedImages.md)|Outputs the selected image ids to the specified list. NOTE: List is not cleared internally.|
|[`void ShowPublicTextOnScreen()`](Sandbox.ModAPI.Ingame.ShowPublicTextOnScreen.md)||
|[`void ShowPrivateTextOnScreen()`](Sandbox.ModAPI.Ingame.ShowPrivateTextOnScreen.md)||
|[`void ShowTextureOnScreen()`](Sandbox.ModAPI.Ingame.ShowTextureOnScreen.md)||
|[`void SetShowOnScreen(ShowTextOnScreenFlag set)`](Sandbox.ModAPI.Ingame.SetShowOnScreen.md)||
|[`void GetFonts(List<string> fonts)`](Sandbox.ModAPI.Ingame.GetFonts.md)|Gets a list of available fonts|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory.md)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs.md)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
|[`void RequestEnable(bool enable)`](Sandbox.ModAPI.Ingame.RequestEnable.md)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyTextPanel.md)_|
