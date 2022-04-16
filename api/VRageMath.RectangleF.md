← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### RectangleF Struct

```csharp
public struct RectangleF: IEquatable<RectangleF>
```

Structure using the same layout than [System.Drawing.RectangleF](https://docs.microsoft.com/en-us/dotnet/api/system.drawing.rectanglef?view=netframework-4.6) 

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable\<RectangleF>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Vector2 Position](VRageMath.RectangleF.Position)|The Position.|
|[Vector2 Size](VRageMath.RectangleF.Size)|The Size.|

#### Properties

|Member|Description|
|---|---|
|[float Bottom { get; }](VRageMath.RectangleF.Bottom)||
|[Vector2 Center { get; }](VRageMath.RectangleF.Center)||
|[float Height { get; set; }](VRageMath.RectangleF.Height)|Height of this rectangle.|
|[float Right { get; }](VRageMath.RectangleF.Right)||
|[float Width { get; set; }](VRageMath.RectangleF.Width)|Width of this rectangle.|
|[float X { get; set; }](VRageMath.RectangleF.X)|Left coordinate.|
|[float Y { get; set; }](VRageMath.RectangleF.Y)|Top coordinate.|

#### Constructors

|Member|Description|
|---|---|
|[RectangleF(Vector2, Vector2)](VRageMath.RectangleF..ctor)||
|[RectangleF(float, float, float, float)](VRageMath.RectangleF..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static bool Intersect(ref RectangleF, ref RectangleF, out RectangleF)](VRageMath.RectangleF.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|[static RectangleF Min(RectangleF?, RectangleF?)](VRageMath.RectangleF.Min)||
|[bool Contains(int, int)](VRageMath.RectangleF.Contains)||
|[bool Contains(float, float)](VRageMath.RectangleF.Contains)||
|[bool Contains(Vector2)](VRageMath.RectangleF.Contains)||
|[bool Contains(Point)](VRageMath.RectangleF.Contains)||
|[bool Equals(RectangleF)](VRageMath.RectangleF.Equals)|Equals to other rectangle|
|[bool Equals(object)](VRageMath.RectangleF.Equals)||
|[int GetHashCode()](VRageMath.RectangleF.GetHashCode)||
|[string ToString()](VRageMath.RectangleF.ToString)||

