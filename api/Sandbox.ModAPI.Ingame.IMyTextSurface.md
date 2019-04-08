← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyTextSurface Interface

```csharp
public interface IMyTextSurface
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Inheritors:**  
* [IMyTextPanel](Sandbox.ModAPI.Ingame.IMyTextPanel)

#### Properties

|Member|Description|
|---|---|
|[CurrentlyShownImage](Sandbox.ModAPI.Ingame.IMyTextSurface.CurrentlyShownImage)|The image that is currently shown on the screen. Returns NULL if there are no images selected OR the screen is in text mode.|
|[FontSize](Sandbox.ModAPI.Ingame.IMyTextSurface.FontSize)|Gets or sets font size|
|[FontColor](Sandbox.ModAPI.Ingame.IMyTextSurface.FontColor)|Gets or sets font color|
|[BackgroundColor](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundColor)|Gets or sets background color|
|[BackgroundAlpha](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundAlpha)|Value for offscreen texture alpha channel - for PBR material it is metalness (should be 0) - for transparent texture it is opacity|
|[ChangeInterval](Sandbox.ModAPI.Ingame.IMyTextSurface.ChangeInterval)|Gets or sets the change interval for selected textures|
|[Font](Sandbox.ModAPI.Ingame.IMyTextSurface.Font)|Gets or sets the font|
|[Alignment](Sandbox.ModAPI.Ingame.IMyTextSurface.Alignment)|How should the text be aligned|
|[Script](Sandbox.ModAPI.Ingame.IMyTextSurface.Script)|Currently running script|
|[ContentType](Sandbox.ModAPI.Ingame.IMyTextSurface.ContentType)|Type of content to be displayed on the screen.|
|[SurfaceSize](Sandbox.ModAPI.Ingame.IMyTextSurface.SurfaceSize)|Size of the drawing surface.|
|[TextureSize](Sandbox.ModAPI.Ingame.IMyTextSurface.TextureSize)|Size of the texture the drawing surface is rendered to.|
|[PreserveAspectRatio](Sandbox.ModAPI.Ingame.IMyTextSurface.PreserveAspectRatio)|Preserve aspect ratio of images.|
|[TextPadding](Sandbox.ModAPI.Ingame.IMyTextSurface.TextPadding)|Text padding from all sides of the panel.|
|[ScriptBackgroundColor](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptBackgroundColor)|Background color used for scripts.|
|[ScriptForegroundColor](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptForegroundColor)|Foreground color used for scripts.|
|[Name](Sandbox.ModAPI.Ingame.IMyTextSurface.Name)|Identifier name of this surface.|
|[DisplayName](Sandbox.ModAPI.Ingame.IMyTextSurface.DisplayName)|Localized name of this surface.|

#### Methods

|Member|Description|
|---|---|
|[WriteText(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.WriteText)||
|[GetText()](Sandbox.ModAPI.Ingame.IMyTextSurface.GetText)||
|[WriteText(StringBuilder, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.WriteText)||
|[ReadText(StringBuilder, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.ReadText)||
|[AddImageToSelection(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImageToSelection)||
|[AddImagesToSelection(List, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImagesToSelection)||
|[RemoveImageFromSelection(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImageFromSelection)||
|[RemoveImagesFromSelection(List, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImagesFromSelection)||
|[ClearImagesFromSelection()](Sandbox.ModAPI.Ingame.IMyTextSurface.ClearImagesFromSelection)||
|[GetSelectedImages(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages)||
|[GetFonts(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetFonts)||
|[GetSprites(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSprites)||
|[GetScripts(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetScripts)||
|[DrawFrame()](Sandbox.ModAPI.Ingame.IMyTextSurface.DrawFrame)|Creates a new draw frame where you can add sprites to be rendered.|
|[MeasureStringInPixels(StringBuilder, string, float)](Sandbox.ModAPI.Ingame.IMyTextSurface.MeasureStringInPixels)|Calculates how many pixels a string of a given font and scale will take up.|

