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
|[CurrentlyShownImage { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.CurrentlyShownImage)||
|[FontSize { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.FontSize)||
|[FontColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.FontColor)||
|[BackgroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundColor)||
|[BackgroundAlpha { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundAlpha)||
|[ChangeInterval { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ChangeInterval)||
|[Font { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Font)||
|[Alignment { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Alignment)||
|[Script { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Script)||
|[ContentType { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ContentType)||
|[SurfaceSize { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.SurfaceSize)||
|[TextureSize { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.TextureSize)||
|[PreserveAspectRatio { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.PreserveAspectRatio)||
|[TextPadding { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.TextPadding)||
|[ScriptBackgroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptBackgroundColor)||
|[ScriptForegroundColor { get; set; }](Sandbox.ModAPI.Ingame.IMyTextSurface.ScriptForegroundColor)||
|[Name { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.Name)||
|[DisplayName { get; }](Sandbox.ModAPI.Ingame.IMyTextSurface.DisplayName)||

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
|[DrawFrame()](Sandbox.ModAPI.Ingame.IMyTextSurface.DrawFrame)||
|[MeasureStringInPixels(StringBuilder, string, float)](Sandbox.ModAPI.Ingame.IMyTextSurface.MeasureStringInPixels)||

