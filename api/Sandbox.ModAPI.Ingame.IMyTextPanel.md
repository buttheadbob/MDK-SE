← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyTextPanel Interface

```csharp
public interface IMyTextPanel: IMyTextSurface, IMyFunctionalBlock, IMyTerminalBlock, IMyCubeBlock, IMyEntity
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)  
* [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)  
* [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)  
* [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)  
* [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)

**Type Definitions:**  
* `MyObjectBuilder_TextPanel/SmallTextPanel`  
* `MyObjectBuilder_TextPanel/SmallLCDPanelWide`  
* `MyObjectBuilder_TextPanel/SmallLCDPanel`  
* `MyObjectBuilder_TextPanel/LargeBlockCorner_LCD_1`  
* `MyObjectBuilder_TextPanel/LargeBlockCorner_LCD_2`  
* `MyObjectBuilder_TextPanel/LargeBlockCorner_LCD_Flat_1`  
* `MyObjectBuilder_TextPanel/LargeBlockCorner_LCD_Flat_2`  
* `MyObjectBuilder_TextPanel/SmallBlockCorner_LCD_1`  
* `MyObjectBuilder_TextPanel/SmallBlockCorner_LCD_2`  
* `MyObjectBuilder_TextPanel/SmallBlockCorner_LCD_Flat_1`  
* `MyObjectBuilder_TextPanel/SmallBlockCorner_LCD_Flat_2`  
* `MyObjectBuilder_TextPanel/LargeTextPanel`  
* `MyObjectBuilder_TextPanel/LargeLCDPanel`  
* `MyObjectBuilder_TextPanel/LargeLCDPanelWide`  
* `MyObjectBuilder_TextPanel/TransparentLCDLarge`  
* `MyObjectBuilder_TextPanel/TransparentLCDSmall`

#### Properties

|Member|Description|
|---|---|
|[ShowOnScreen { get; }](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowOnScreen)|_**Obsolete:** LCD public text is deprecated_|
|[ShowText { get; }](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowText)|_**Obsolete:** LCD public text is deprecated_|
|[Components { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.Components)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[EntityId { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.EntityId)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[Name { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.Name)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[DisplayName { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.DisplayName)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[HasInventory { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[InventoryCount { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.InventoryCount)|Returns the count of the number of inventories this entity has.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldAABB { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldAABB)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldAABBHr { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldAABBHr)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldMatrix { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldMatrix)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldVolume { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldVolume)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldVolumeHr { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldVolumeHr)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[BlockDefinition { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.BlockDefinition)|_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[CheckConnectionAllowed { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.CheckConnectionAllowed)|_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[CubeGrid { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.CubeGrid)|Grid in which the block is placed<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[DefinitionDisplayNameText { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DefinitionDisplayNameText)|Definition name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[DisassembleRatio { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[DisplayNameText { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisplayNameText)|Translated block name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[IsBeingHacked { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsBeingHacked)|Hacking of the block is in progress<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[IsFunctional { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsFunctional)|True if integrity is above breaking threshold<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[IsWorking { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Max { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Max)|Maximum coordinates of grid cells occupied by this block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Mass { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Mass)|Block mass<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Min { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Min)|Minimum coordinates of grid cells occupied by this block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[NumberInGrid { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Orientation { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Orientation)|Returns block orientation in base 6 directions<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[OwnerId { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.OwnerId)|Id of player owning block (not steam Id)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Position { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Position)|Position in grid coordinates<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[CustomName { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomName)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[CustomNameWithFaction { get; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomNameWithFaction)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[DetailedInfo { get; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.DetailedInfo)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[CustomInfo { get; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomInfo)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[CustomData { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomData)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowOnHUD { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowOnHUD)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowInTerminal { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInTerminal)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowInToolbarConfig { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInToolbarConfig)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowInInventory { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInInventory)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[Enabled { get; set; }](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.Enabled)|_Inherited from [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)_|
|[CurrentlyShownImage { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.CurrentlyShownImage)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[FontSize { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.FontSize)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[FontColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.FontColor)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[BackgroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundColor)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[BackgroundAlpha { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundAlpha)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[ChangeInterval { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ChangeInterval)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Font { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Font)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Alignment { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Alignment)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Script { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Script)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[ContentType { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ContentType)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[SurfaceSize { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.SurfaceSize)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[TextureSize { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.TextureSize)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[PreserveAspectRatio { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.PreserveAspectRatio)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[TextPadding { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.TextPadding)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[ScriptBackgroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptBackgroundColor)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[ScriptForegroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptForegroundColor)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Name { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Name)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[DisplayName { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.DisplayName)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|

#### Methods

|Member|Description|
|---|---|
|[WritePublicTitle(string, bool)](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePublicTitle)||
|[GetPublicTitle()](Sandbox.ModAPI.Ingame.IMyTextPanel.GetPublicTitle)||
|[WritePrivateText(string, bool)](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePrivateText)|_**Obsolete:** LCD private text is deprecated_|
|[GetPrivateText()](Sandbox.ModAPI.Ingame.IMyTextPanel.GetPrivateText)|_**Obsolete:** LCD private text is deprecated_|
|[WritePrivateTitle(string, bool)](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePrivateTitle)|_**Obsolete:** LCD private text is deprecated_|
|[GetPrivateTitle()](Sandbox.ModAPI.Ingame.IMyTextPanel.GetPrivateTitle)|_**Obsolete:** LCD private text is deprecated_|
|[ShowPrivateTextOnScreen()](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowPrivateTextOnScreen)|_**Obsolete:** LCD private text is deprecated_|
|[WritePublicText(string, bool)](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePublicText)|_**Obsolete:** LCD public text is deprecated_|
|[GetPublicText()](Sandbox.ModAPI.Ingame.IMyTextPanel.GetPublicText)|_**Obsolete:** LCD public text is deprecated_|
|[WritePublicText(StringBuilder, bool)](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePublicText)|_**Obsolete:** LCD public text is deprecated_|
|[ReadPublicText(StringBuilder, bool)](Sandbox.ModAPI.Ingame.IMyTextPanel.ReadPublicText)|_**Obsolete:** LCD public text is deprecated_|
|[ShowPublicTextOnScreen()](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowPublicTextOnScreen)|_**Obsolete:** LCD public text is deprecated_|
|[ShowTextureOnScreen()](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowTextureOnScreen)|_**Obsolete:** LCD public text is deprecated_|
|[SetShowOnScreen(ShowTextOnScreenFlag)](Sandbox.ModAPI.Ingame.IMyTextPanel.SetShowOnScreen)|_**Obsolete:** LCD public text is deprecated_|
|[GetInventory()](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetInventory(int)](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Search for inventory component with maching index.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetPosition()](VRage.Game.ModAPI.Ingame.IMyEntity.GetPosition)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetOwnerFactionTag()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetOwnerFactionTag)|Tag of faction owning block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[GetPlayerRelationToOwner()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetPlayerRelationToOwner)|_**Obsolete:** GetPlayerRelationToOwner() is useless ingame. Mods should use the one in ModAPI.IMyCubeBlock_<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[GetUserRelationToOwner(long)](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetUserRelationToOwner)|_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[UpdateIsWorking()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateIsWorking)|_**Obsolete**_<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[UpdateVisual()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateVisual)|_**Obsolete**_<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[HasLocalPlayerAccess()](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasLocalPlayerAccess)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[HasPlayerAccess(long)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasPlayerAccess)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[SetCustomName(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SetCustomName)|_**Obsolete:** Use the setter of Customname_<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[SetCustomName(StringBuilder)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SetCustomName)|_**Obsolete:** Use the setter of Customname_<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[GetActions(List, Func)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetActions)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[SearchActionsOfName(string, List, Func)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SearchActionsOfName)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[GetActionWithName(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetActionWithName)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[GetProperty(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetProperty)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[GetProperties(List, Func)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetProperties)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[IsSameConstructAs(IMyTerminalBlock)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.IsSameConstructAs)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[RequestEnable(bool)](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.RequestEnable)|_**Obsolete:** Use the setter of Enabled_<br /><br />_Inherited from [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)_|
|[WriteText(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.WriteText)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[GetText()](Sandbox.ModAPI.Ingame.IMyTextSurface.GetText)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[WriteText(StringBuilder, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.WriteText)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[ReadText(StringBuilder, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.ReadText)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[AddImageToSelection(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImageToSelection)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[AddImagesToSelection(List, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImagesToSelection)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[RemoveImageFromSelection(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImageFromSelection)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[RemoveImagesFromSelection(List, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImagesFromSelection)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[ClearImagesFromSelection()](Sandbox.ModAPI.Ingame.IMyTextSurface.ClearImagesFromSelection)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[GetSelectedImages(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[GetFonts(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetFonts)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[GetSprites(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSprites)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[GetScripts(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetScripts)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[DrawFrame()](Sandbox.ModAPI.Ingame.IMyTextSurface.DrawFrame)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[MeasureStringInPixels(StringBuilder, string, float)](Sandbox.ModAPI.Ingame.IMyTextSurface.MeasureStringInPixels)|_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|

