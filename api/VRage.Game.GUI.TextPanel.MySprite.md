← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MySprite Struct

```csharp
public struct MySprite: IEquatable<MySprite>
```

**Namespace:** [VRage.Game.GUI.TextPanel](VRage.Game.GUI.TextPanel)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IEquatable<MySprite>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1TextAlignment Alignment](VRage.Game.GUI.TextPanel.MySprite.Alignment)|Alignment for the text and sprites.|
|\\%1Color? Color](VRage.Game.GUI.TextPanel.MySprite.Color)|Color mask to be used when rendering this layer. If not set, white will be used|
|\\%1string Data](VRage.Game.GUI.TextPanel.MySprite.Data)|Data to be rendered, depending on what the layer type is. This can be text or a texture path|
|\\%1string FontId](VRage.Game.GUI.TextPanel.MySprite.FontId)|In case we are rendering text, what font to use.|
|\\%1Vector2? Position](VRage.Game.GUI.TextPanel.MySprite.Position)|Render position for this layer. If not set, it will be placed in the center|
|\\%1float RotationOrScale](VRage.Game.GUI.TextPanel.MySprite.RotationOrScale)|Rotation of sprite in radians. Used as scale for text.|
|\\%1Vector2? Size](VRage.Game.GUI.TextPanel.MySprite.Size)|Render size for this layer. If not set, it will be sized to take up the whole texture|
|\\%1SpriteType Type](VRage.Game.GUI.TextPanel.MySprite.Type)|Type of the render layer|

#### Constructors

|Member|Description|
|---|---|
|\\%1MySprite(\\%1SpriteType], \\%1string], \\%1Vector2?], \\%1Vector2?], \\%1Color?], \\%1string], \\%1TextAlignment], \\%1float])](VRage.Game.GUI.TextPanel.MySprite..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static MySprite CreateClearClipRect()](VRage.Game.GUI.TextPanel.MySprite.CreateClearClipRect)||
|\\%1static MySprite CreateClipRect(Rectangle)](VRage.Game.GUI.TextPanel.MySprite.CreateClipRect)||
|\\%1static MySprite CreateSprite(string, Vector2, Vector2)](VRage.Game.GUI.TextPanel.MySprite.CreateSprite)||
|\\%1static MySprite CreateText(string, string, Color, \\%1float], \\%1TextAlignment])](VRage.Game.GUI.TextPanel.MySprite.CreateText)||
|\\%1bool Equals(MySprite)](VRage.Game.GUI.TextPanel.MySprite.Equals)||
|\\%1bool Equals(object)](VRage.Game.GUI.TextPanel.MySprite.Equals)||
|\\%1int GetHashCode()](VRage.Game.GUI.TextPanel.MySprite.GetHashCode)||

