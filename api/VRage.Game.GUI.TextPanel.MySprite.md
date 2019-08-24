← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MySprite Struct

```csharp
public struct MySprite: IEquatable<VRage.Game.GUI.TextPanel.MySprite>
```

**Namespace:** [VRage.Game.GUI.TextPanel](VRage.Game.GUI.TextPanel)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IEquatable<VRage.Game.GUI.TextPanel.MySprite>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Type](VRage.Game.GUI.TextPanel.MySprite.Type)|Type of the render layer|
|[Position](VRage.Game.GUI.TextPanel.MySprite.Position)|Render position for this layer. If not set, it will be placed in the center|
|[Size](VRage.Game.GUI.TextPanel.MySprite.Size)|Render size for this layer. If not set, it will be sized to take up the whole texture|
|[Color](VRage.Game.GUI.TextPanel.MySprite.Color)|Color mask to be used when rendering this layer. If not set, white will be used|
|[Data](VRage.Game.GUI.TextPanel.MySprite.Data)|Data to be rendered, depending on what the layer type is. This can be text or a texture path|
|[FontId](VRage.Game.GUI.TextPanel.MySprite.FontId)|In case we are rendering text, what font to use.|
|[Alignment](VRage.Game.GUI.TextPanel.MySprite.Alignment)|Alignment for the text and sprites.|
|[RotationOrScale](VRage.Game.GUI.TextPanel.MySprite.RotationOrScale)|Rotation of sprite in radians. Used as scale for text.|

#### Constructors

|Member|Description|
|---|---|
|[MySprite(SpriteType, string, Nullable, Nullable, Nullable, string, TextAlignment, float)](VRage.Game.GUI.TextPanel.MySprite..ctor)||

#### Methods

|Member|Description|
|---|---|
|[CreateSprite(string, Vector2, Vector2)](VRage.Game.GUI.TextPanel.MySprite.CreateSprite)||
|[CreateText(string, string, Color, float, TextAlignment)](VRage.Game.GUI.TextPanel.MySprite.CreateText)||
|[Equals(MySprite)](VRage.Game.GUI.TextPanel.MySprite.Equals)||
|[Equals(object)](VRage.Game.GUI.TextPanel.MySprite.Equals)||
|[GetHashCode()](VRage.Game.GUI.TextPanel.MySprite.GetHashCode)||

