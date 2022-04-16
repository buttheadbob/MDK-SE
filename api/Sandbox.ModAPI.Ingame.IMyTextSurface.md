← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyTextSurface Interface

```csharp
public interface IMyTextSurface
```

Describes one of block LCDs where you can write text or draw things (PB scripting interface)

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Inheritors:**  
* [IMyTextPanel](Sandbox.ModAPI.Ingame.IMyTextPanel)

#### Properties

|Member|Description|
|---|---|
|\$1TextAlignment Alignment { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Alignment)|How should the text be aligned|
|\$1byte BackgroundAlpha { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundAlpha)|Value for offscreen texture alpha channel - for PBR material it is metalness (should be 0) - for transparent texture it is opacity|
|\$1Color BackgroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundColor)|Gets or sets background color|
|\$1float ChangeInterval { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ChangeInterval)|Gets or sets the change interval for selected textures|
|\$1ContentType ContentType { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ContentType)|Type of content to be displayed on the screen.|
|\$1string CurrentlyShownImage { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.CurrentlyShownImage)|Gets image that is currently shown on the screen. Returns NULL if there are no images selected OR the screen is in text mode.|
|\$1string DisplayName { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.DisplayName)|Get localized name of this surface.|
|\$1string Font { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Font)|Gets or sets the font|
|\$1Color FontColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.FontColor)|Gets or sets font color|
|\$1float FontSize { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.FontSize)|Gets or sets font size|
|\$1string Name { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Name)|Gets identifier name of this surface.|
|\$1bool PreserveAspectRatio { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.PreserveAspectRatio)|Gets or sets preserve aspect ratio of images.|
|\$1string Script { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Script)|Currently running script|
|\$1Color ScriptBackgroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptBackgroundColor)|Gets or sets background color used for scripts.|
|\$1Color ScriptForegroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptForegroundColor)|Gets or sets foreground color used for scripts.|
|\$1Vector2 SurfaceSize { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.SurfaceSize)|Gets size of the drawing surface.|
|\$1float TextPadding { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.TextPadding)|Gets or sets text padding from all sides of the panel.|
|\$1Vector2 TextureSize { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.TextureSize)|Gets size of the texture the drawing surface is rendered to.|

#### Methods

|Member|Description|
|---|---|
|\$1void AddImagesToSelection(List\$1string\>, \$1bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImagesToSelection)|Adds image to list of shown images. You can get image ids by [GetSelectedImages(List<string\>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages) |
|\$1void AddImageToSelection(string, \$1bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImageToSelection)|Adds image to list of shown images. You can get image ids by [GetSelectedImages(List<string\>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages) |
|\$1void ClearImagesFromSelection()](Sandbox.ModAPI.Ingame.IMyTextSurface.ClearImagesFromSelection)|Removes images from shown images.|
|\$1MySpriteDrawFrame DrawFrame()](Sandbox.ModAPI.Ingame.IMyTextSurface.DrawFrame)|Creates a new draw frame where you can add sprites to be rendered.|
|\$1void GetFonts(List\$1string\>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetFonts)|Gets a list of available fonts|
|\$1void GetScripts(List\$1string\>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetScripts)|Gets a list of available scripts|
|\$1void GetSelectedImages(List\$1string\>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages)|Outputs the selected image ids to the specified list. NOTE: List is not cleared internally.|
|\$1void GetSprites(List\$1string\>)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSprites)|Gets a list of available sprites|
|\$1string GetText()](Sandbox.ModAPI.Ingame.IMyTextSurface.GetText)|Gets current text that is written on surface. Allocates memory (StringBuilder.ToString())! This method doesn't allocate memory [ReadText(StringBuilder, [bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.ReadText) |
|\$1Vector2 MeasureStringInPixels(StringBuilder, string, float)](Sandbox.ModAPI.Ingame.IMyTextSurface.MeasureStringInPixels)|Calculates how many pixels a string of a given font and scale will take up.|
|\$1void ReadText(StringBuilder, \$1bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.ReadText)|Gets current text that is written on surface.|
|\$1void RemoveImageFromSelection(string, \$1bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImageFromSelection)|Removes image from shown images.|
|\$1void RemoveImagesFromSelection(List\$1string\>, \$1bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImagesFromSelection)|Removes images from shown images.|
|\$1bool WriteText(string, \$1bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.WriteText)|Writes text to surface. If somebody opened LCD text in popup dialog, text can no longer be added to the surface. Resulting text must is capped with 100000 symbols|
|\$1bool WriteText(StringBuilder, \$1bool])](Sandbox.ModAPI.Ingame.IMyTextSurface.WriteText)|Writes text to surface. If somebody opened LCD text in popup dialog, text can no longer be added to the surface. Resulting text must is capped with 100000 symbols|

