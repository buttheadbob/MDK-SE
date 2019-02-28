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
|[ShowOnScreen](Sandbox.ModAPI.Ingame.IMyTextSurface.ShowOnScreen)|Indicates what should be shown on the screen, none being an image.|
|[ShowText](Sandbox.ModAPI.Ingame.IMyTextSurface.ShowText)|Returns true if the ShowOnScreen flag is set to either PUBLIC or PRIVATE|
|[FontSize](Sandbox.ModAPI.Ingame.IMyTextSurface.FontSize)|Gets or sets font size|
|[FontColor](Sandbox.ModAPI.Ingame.IMyTextSurface.FontColor)|Gets or sets font color|
|[BackgroundColor](Sandbox.ModAPI.Ingame.IMyTextSurface.BackgroundColor)|Gets or sets background color|
|[ChangeInterval](Sandbox.ModAPI.Ingame.IMyTextSurface.ChangeInterval)|Gets or sets the change interval for selected textures|
|[Font](Sandbox.ModAPI.Ingame.IMyTextSurface.Font)|Gets or sets the font|

#### Methods

|Member|Description|
|---|---|
|[WritePublicText(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.WritePublicText)||
|[GetPublicText()](Sandbox.ModAPI.Ingame.IMyTextSurface.GetPublicText)||
|[WritePublicText(StringBuilder, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.WritePublicText)||
|[ReadPublicText(StringBuilder, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.ReadPublicText)||
|[AddImageToSelection(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImageToSelection)||
|[AddImagesToSelection(List, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.AddImagesToSelection)||
|[RemoveImageFromSelection(string, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImageFromSelection)||
|[RemoveImagesFromSelection(List, bool)](Sandbox.ModAPI.Ingame.IMyTextSurface.RemoveImagesFromSelection)||
|[ClearImagesFromSelection()](Sandbox.ModAPI.Ingame.IMyTextSurface.ClearImagesFromSelection)||
|[GetSelectedImages(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetSelectedImages)||
|[ShowPublicTextOnScreen()](Sandbox.ModAPI.Ingame.IMyTextSurface.ShowPublicTextOnScreen)||
|[ShowTextureOnScreen()](Sandbox.ModAPI.Ingame.IMyTextSurface.ShowTextureOnScreen)||
|[SetShowOnScreen(ShowTextOnScreenFlag)](Sandbox.ModAPI.Ingame.IMyTextSurface.SetShowOnScreen)||
|[GetFonts(List)](Sandbox.ModAPI.Ingame.IMyTextSurface.GetFonts)||

