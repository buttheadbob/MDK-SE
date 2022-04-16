← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyTextPanel Interface

```csharp
public interface IMyTextPanel: IMyTextSurface, IMyFunctionalBlock, IMyTerminalBlock, IMyCubeBlock, IMyEntity
```

Describes LCD block (mods interface)

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)  
* [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)  
* [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)  
* [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)  
* [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)

**Type Definitions:**  
* MyObjectBuilder_TextPanel/LargeBlockCorner_LCD_1  
* MyObjectBuilder_TextPanel/LargeBlockCorner_LCD_2  
* MyObjectBuilder_TextPanel/LargeBlockCorner_LCD_Flat_1  
* MyObjectBuilder_TextPanel/LargeBlockCorner_LCD_Flat_2  
* MyObjectBuilder_TextPanel/LargeLCDPanel  
* MyObjectBuilder_TextPanel/LargeLCDPanel3x3  
* MyObjectBuilder_TextPanel/LargeLCDPanel5x3  
* MyObjectBuilder_TextPanel/LargeLCDPanel5x5  
* MyObjectBuilder_TextPanel/LargeLCDPanelWide  
* MyObjectBuilder_TextPanel/LargeTextPanel  
* MyObjectBuilder_TextPanel/SmallBlockCorner_LCD_1  
* MyObjectBuilder_TextPanel/SmallBlockCorner_LCD_2  
* MyObjectBuilder_TextPanel/SmallBlockCorner_LCD_Flat_1  
* MyObjectBuilder_TextPanel/SmallBlockCorner_LCD_Flat_2  
* MyObjectBuilder_TextPanel/SmallLCDPanel  
* MyObjectBuilder_TextPanel/SmallLCDPanelWide  
* MyObjectBuilder_TextPanel/SmallTextPanel  
* MyObjectBuilder_TextPanel/TransparentLCDLarge  
* MyObjectBuilder_TextPanel/TransparentLCDSmall

#### Properties

|Member|Description|
|---|---|
|[TextAlignment Alignment { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Alignment)|How should the text be aligned<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[byte BackgroundAlpha { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundAlpha)|Value for offscreen texture alpha channel - for PBR material it is metalness (should be 0) - for transparent texture it is opacity<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Color BackgroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundColor)|Gets or sets background color<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[SerializableDefinitionId BlockDefinition { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.BlockDefinition)|Gets definition.Id assigned to this block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[float ChangeInterval { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ChangeInterval)|Gets or sets the change interval for selected textures<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[bool Closed { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.Closed)|True if the block has been removed from the world.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[MyEntityComponentContainer Components { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.Components)|Gets blocks component logic container<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[ContentType ContentType { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ContentType)|Type of content to be displayed on the screen.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[IMyCubeGrid CubeGrid { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.CubeGrid)|Grid in which the block is placed<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[string CurrentlyShownImage { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.CurrentlyShownImage)|Gets image that is currently shown on the screen. Returns NULL if there are no images selected OR the screen is in text mode.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[string CustomData { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[string CustomInfo { get; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomInfo)|Gets information about block status (available from mods) [Sandbox.ModAPI.IMyTerminalBlock.AppendingCustomInfo](https://docs.microsoft.com/en-us/dotnet/api/sandbox.modapi.imyterminalblock.appendingcustominfo?view=netframework-4.6)  [Sandbox.ModAPI.IMyTerminalBlock.RefreshCustomInfo](https://docs.microsoft.com/en-us/dotnet/api/sandbox.modapi.imyterminalblock.refreshcustominfo?view=netframework-4.6) .<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[string CustomName { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomName)|Gets or sets how block is named in Terminal menu<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[string CustomNameWithFaction { get; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomNameWithFaction)|Gets or sets how block is named in Terminal menu. Work only for Cockpit, LaserAntenna RadioAntenna, SpaceBall, Beacon<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[string DefinitionDisplayNameText { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DefinitionDisplayNameText)|Definition name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[string DetailedInfo { get; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.DetailedInfo)|Gets information about block status. In Control panel bottom right text<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[float DisassembleRatio { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding) Bigger values - longer grinding<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[string DisplayName { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.DisplayName)|Gets user friendly name of entity. May be null For block terminal name use [DisplayNameText](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisplayNameText)<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[string DisplayName { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.DisplayName)|Get localized name of this surface.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[string DisplayNameText { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisplayNameText)|Translated block name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[bool Enabled { get; set; }](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.Enabled)|Represents terminal gui toggle. Gets or sets if block is Enabled<br /><br />_Inherited from [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)_|
|[long EntityId { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.EntityId)|Id of entity<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[string Font { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Font)|Gets or sets the font<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Color FontColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.FontColor)|Gets or sets font color<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[float FontSize { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.FontSize)|Gets or sets font size<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[bool HasInventory { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[int InventoryCount { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.InventoryCount)|Returns the count of the number of inventories this entity has.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[bool IsBeingHacked { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsBeingHacked)|Hacking of the block is in progress<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[bool IsFunctional { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsFunctional)|Gets if integrity is above breaking threshold<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[bool IsWorking { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[float Mass { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Mass)|Block mass<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Vector3I Max { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Max)|Maximum coordinates of grid cells occupied by this block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Vector3I Min { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Min)|Minimum coordinates of grid cells occupied by this block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[string Name { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.Name)|Some entities can have uniq name, and game can find them by name [VRage.ModAPI.IMyEntities.TryGetEntityByName(System.String,VRage.ModAPI.IMyEntity@)](https://docs.microsoft.com/en-us/dotnet/api/vrage.modapi.imyentities.trygetentitybyname(system.string,vrage.modapi.imyentity@)?view=netframework-4.6)<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[string Name { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Name)|Gets identifier name of this surface.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[int NumberInGrid { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[MyBlockOrientation Orientation { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Orientation)|Returns block orientation in base 6 directions<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[long OwnerId { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.OwnerId)|IdentityId of player owning block (not steam Id)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Vector3I Position { get; }](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Position)|Position in grid coordinates<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[bool PreserveAspectRatio { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.PreserveAspectRatio)|Gets or sets preserve aspect ratio of images.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[string Script { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Script)|Currently running script<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Color ScriptBackgroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptBackgroundColor)|Gets or sets background color used for scripts.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Color ScriptForegroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptForegroundColor)|Gets or sets foreground color used for scripts.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[bool ShowInInventory { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInInventory)|Represent terminal gui toggle `Show block in Inventory Screen`. Gets or sets its value<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[bool ShowInTerminal { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInTerminal)|Represent terminal gui toggle `Show block in terminal`. Gets or sets its value<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[bool ShowInToolbarConfig { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInToolbarConfig)|Represent terminal gui toggle `Show in toolbar config`. Gets or sets its value<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[bool ShowOnHUD { get; set; }](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowOnHUD)|Represent terminal gui toggle `Show On HUD`. Gets or sets its value<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowTextOnScreenFlag ShowOnScreen { get; }](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowOnScreen)|_**Obsolete:** LCD public text is deprecated_<br /><br />Indicates what should be shown on the screen, none being an image.|
|[bool ShowText { get; }](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowText)|_**Obsolete:** LCD public text is deprecated_<br /><br />Returns true if the ShowOnScreen flag is set to either PUBLIC or PRIVATE|
|[Vector2 SurfaceSize { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.SurfaceSize)|Gets size of the drawing surface.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[float TextPadding { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.TextPadding)|Gets or sets text padding from all sides of the panel.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[Vector2 TextureSize { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.TextureSize)|Gets size of the texture the drawing surface is rendered to.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[BoundingBoxD WorldAABB { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldAABB)|Gets world axis-aligned bounding box<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[BoundingBoxD WorldAABBHr { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldAABBHr)|Gets world axis-aligned bounding box<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[MatrixD WorldMatrix { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldMatrix)|Gets world matrix of this entity<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[BoundingSphereD WorldVolume { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldVolume)|Gets bounding sphere of this entity<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[BoundingSphereD WorldVolumeHr { get; }](VRage.Game.ModAPI.Ingame.IMyEntity.WorldVolumeHr)|Gets bounding sphere of this entity<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|

#### Methods

|Member|Description|
|---|---|
|[void AddImagesToSelection(List\<string>, \[bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImagesToSelection)|Adds image to list of shown images. You can get image ids by [GetSelectedImages(List<string>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages)<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void AddImageToSelection(string, \[bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImageToSelection)|Adds image to list of shown images. You can get image ids by [GetSelectedImages(List<string>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages)<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void ClearImagesFromSelection()](Sandbox.ModAPI.Ingame.IMyTextSurface.ClearImagesFromSelection)|Removes images from shown images.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[MySpriteDrawFrame DrawFrame()](Sandbox.ModAPI.Ingame.IMyTextSurface.DrawFrame)|Creates a new draw frame where you can add sprites to be rendered.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void GetActions(List\<ITerminalAction>, \[Func\<ITerminalAction, bool>])](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetActions)|Get all terminal actions available for block<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ITerminalAction GetActionWithName(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetActionWithName)|Get first found terminal action with name<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[void GetFonts(List\<string>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetFonts)|Gets a list of available fonts<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[IMyInventory GetInventory()](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[IMyInventory GetInventory(int)](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Search for inventory component with maching index.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[string GetOwnerFactionTag()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetOwnerFactionTag)|Tag of faction owning block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetPlayerRelationToOwner)|_**Obsolete:** GetPlayerRelationToOwner() is useless ingame. Mods should use the one in ModAPI.IMyCubeBlock_<br /><br />Relation of local player to the block Should not be called on Dedicated Server.<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Vector3D GetPosition()](VRage.Game.ModAPI.Ingame.IMyEntity.GetPosition)|Gets position in world coordinates<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[string GetPrivateText()](Sandbox.ModAPI.Ingame.IMyTextPanel.GetPrivateText)|_**Obsolete:** LCD private text is deprecated_|
|[string GetPrivateTitle()](Sandbox.ModAPI.Ingame.IMyTextPanel.GetPrivateTitle)|_**Obsolete:** LCD private text is deprecated_|
|[void GetProperties(List\<ITerminalProperty>, \[Func\<ITerminalProperty, bool>])](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetProperties)|Get all terminal actions available for block.<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ITerminalProperty GetProperty(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetProperty)|Finds terminal property with provided id<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[string GetPublicText()](Sandbox.ModAPI.Ingame.IMyTextPanel.GetPublicText)|_**Obsolete:** LCD public text is deprecated_|
|[string GetPublicTitle()](Sandbox.ModAPI.Ingame.IMyTextPanel.GetPublicTitle)|Gets popup dialog title|
|[void GetScripts(List\<string>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetScripts)|Gets a list of available scripts<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void GetSelectedImages(List\<string>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages)|Outputs the selected image ids to the specified list. NOTE: List is not cleared internally.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void GetSprites(List\<string>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSprites)|Gets a list of available sprites<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[string GetText()](Sandbox.ModAPI.Ingame.IMyTextSurface.GetText)|Gets current text that is written on surface. Allocates memory (StringBuilder.ToString())! This method doesn't allocate memory [ReadText(StringBuilder, [bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.ReadText)<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long, \[MyRelationsBetweenPlayerAndBlock])](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetUserRelationToOwner)|Gets relation to owner of block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[bool HasLocalPlayerAccess()](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasLocalPlayerAccess)|Returns if local player can use block. Executes [HasPlayerAccess(long, [MyRelationsBetweenPlayerAndBlock])](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasPlayerAccess) with local player identityId. On Dedicated Server as identityId it is using 0 as playerId<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[bool HasPlayerAccess(long, \[MyRelationsBetweenPlayerAndBlock])](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasPlayerAccess)|Returns if local player can use block. It is also checking for admin access.<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[bool IsSameConstructAs(IMyTerminalBlock)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.IsSameConstructAs)|Determines whether this block is [VRage.Game.ModAPI.GridLinkTypeEnum.Mechanical](https://docs.microsoft.com/en-us/dotnet/api/vrage.game.modapi.gridlinktypeenum.mechanical?view=netframework-4.6) connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br /><br />Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[Vector2 MeasureStringInPixels(StringBuilder, string, float)](Sandbox.ModAPI.Ingame.IMyTextSurface.MeasureStringInPixels)|Calculates how many pixels a string of a given font and scale will take up.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void ReadPublicText(StringBuilder, \[bool])](Sandbox.ModAPI.Ingame.IMyTextPanel.ReadPublicText)|_**Obsolete:** LCD public text is deprecated_|
|[void ReadText(StringBuilder, \[bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.ReadText)|Gets current text that is written on surface.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void RemoveImageFromSelection(string, \[bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImageFromSelection)|Removes image from shown images.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void RemoveImagesFromSelection(List\<string>, \[bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImagesFromSelection)|Removes images from shown images.<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[void RequestEnable(bool)](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.RequestEnable)|_**Obsolete:** Use the setter of Enabled_<br /><br />_Inherited from [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)_|
|[void SearchActionsOfName(string, List\<ITerminalAction>, \[Func\<ITerminalAction, bool>])](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SearchActionsOfName)|Get all terminal actions available for block. NOTE: First called `<br /><br />` and then `<br /><br />` check<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[void SetCustomName(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SetCustomName)|_**Obsolete:** Use the setter of Customname_<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[void SetCustomName(StringBuilder)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SetCustomName)|_**Obsolete:** Use the setter of Customname_<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[void SetShowOnScreen(ShowTextOnScreenFlag)](Sandbox.ModAPI.Ingame.IMyTextPanel.SetShowOnScreen)|_**Obsolete:** LCD public text is deprecated_|
|[void ShowPrivateTextOnScreen()](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowPrivateTextOnScreen)|_**Obsolete:** LCD private text is deprecated_|
|[void ShowPublicTextOnScreen()](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowPublicTextOnScreen)|_**Obsolete:** LCD public text is deprecated_|
|[void ShowTextureOnScreen()](Sandbox.ModAPI.Ingame.IMyTextPanel.ShowTextureOnScreen)|_**Obsolete:** LCD public text is deprecated_|
|[void UpdateIsWorking()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateIsWorking)|_**Obsolete**_<br /><br />Force refresh working state. Call if you change block state that could affect its working status.<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[void UpdateVisual()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateVisual)|_**Obsolete**_<br /><br />Updates block visuals (ie. block emissivity)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[bool WritePrivateText(string, \[bool])](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePrivateText)|_**Obsolete:** LCD private text is deprecated_|
|[bool WritePrivateTitle(string, \[bool])](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePrivateTitle)|_**Obsolete:** LCD private text is deprecated_|
|[bool WritePublicText(string, \[bool])](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePublicText)|_**Obsolete:** LCD public text is deprecated_|
|[bool WritePublicText(StringBuilder, \[bool])](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePublicText)|_**Obsolete:** LCD public text is deprecated_|
|[bool WritePublicTitle(string, \[bool])](Sandbox.ModAPI.Ingame.IMyTextPanel.WritePublicTitle)|Writes LCD popup dialog title If somebody opened LCD text in popup dialog, text can no longer be added.|
|[bool WriteText(string, \[bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.WriteText)|Writes text to surface. If somebody opened LCD text in popup dialog, text can no longer be added to the surface. Resulting text must is capped with 100000 symbols<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|
|[bool WriteText(StringBuilder, \[bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.WriteText)|Writes text to surface. If somebody opened LCD text in popup dialog, text can no longer be added to the surface. Resulting text must is capped with 100000 symbols<br /><br />_Inherited from [IMyTextSurface](Sandbox.ModAPI.Ingame.IMyTextSurface)_|

