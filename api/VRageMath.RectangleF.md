← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### RectangleF Struct

```csharp
public struct RectangleF: IEquatable<RectangleF>
```

Structure using the same layout than [System.Drawing.RectangleF](https://docs.microsoft.com/en-us/dotnet/api/system.drawing.rectanglef?view=netframework-4.6) 

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<RectangleF>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\$1Vector2 Position](VRageMath.RectangleF.Position)|The Position.|
|\\$1Vector2 Size](VRageMath.RectangleF.Size)|The Size.|

#### Properties

|Member|Description|
|---|---|
|\\$1float Bottom { get; }](VRageMath.RectangleF.Bottom)||
|\\$1Vector2 Center { get; }](VRageMath.RectangleF.Center)||
|\\$1float Height { get; set; }](VRageMath.RectangleF.Height)|Height of this rectangle.|
|\\$1float Right { get; }](VRageMath.RectangleF.Right)||
|\\$1float Width { get; set; }](VRageMath.RectangleF.Width)|Width of this rectangle.|
|\\$1float X { get; set; }](VRageMath.RectangleF.X)|Left coordinate.|
|\\$1float Y { get; set; }](VRageMath.RectangleF.Y)|Top coordinate.|

#### Constructors

|Member|Description|
|---|---|
|\\$1RectangleF(Vector2, Vector2)](VRageMath.RectangleF..ctor)||
|\\$1RectangleF(float, float, float, float)](VRageMath.RectangleF..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static bool Intersect(ref RectangleF, ref RectangleF, out RectangleF)](VRageMath.RectangleF.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|\\$1static RectangleF Min(RectangleF?, RectangleF?)](VRageMath.RectangleF.Min)||
|\\$1bool Contains(int, int)](VRageMath.RectangleF.Contains)||
|\\$1bool Contains(float, float)](VRageMath.RectangleF.Contains)||
|\\$1bool Contains(Vector2)](VRageMath.RectangleF.Contains)||
|\\$1bool Contains(Point)](VRageMath.RectangleF.Contains)||
|\\$1bool Equals(RectangleF)](VRageMath.RectangleF.Equals)|Equals to other rectangle|
|\\$1bool Equals(object)](VRageMath.RectangleF.Equals)||
|\\$1int GetHashCode()](VRageMath.RectangleF.GetHashCode)||
|\\$1string ToString()](VRageMath.RectangleF.ToString)||

