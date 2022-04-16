← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Rectangle Struct

```csharp
public struct Rectangle: IEquatable<Rectangle>
```

Defines a rectangle.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Rectangle>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1int Height](VRageMath.Rectangle.Height)|Specifies the height of the rectangle.|
|\\%1int Width](VRageMath.Rectangle.Width)|Specifies the width of the rectangle.|
|\\%1int X](VRageMath.Rectangle.X)|Specifies the x-coordinate of the rectangle.|
|\\%1int Y](VRageMath.Rectangle.Y)|Specifies the y-coordinate of the rectangle.|

#### Properties

|Member|Description|
|---|---|
|\\%1int Bottom { get; }](VRageMath.Rectangle.Bottom)|Returns the y-coordinate of the bottom of the rectangle.|
|\\%1Point Center { get; }](VRageMath.Rectangle.Center)|Gets the Point that specifies the center of the rectangle.|
|\\%1int Left { get; }](VRageMath.Rectangle.Left)|Returns the x-coordinate of the left side of the rectangle.|
|\\%1Point Location { get; set; }](VRageMath.Rectangle.Location)|Gets or sets the upper-left value of the Rectangle.|
|\\%1int Right { get; }](VRageMath.Rectangle.Right)|Returns the x-coordinate of the right side of the rectangle.|
|\\%1int Top { get; }](VRageMath.Rectangle.Top)|Returns the y-coordinate of the top of the rectangle.|

#### Constructors

|Member|Description|
|---|---|
|\\%1Rectangle(int, int, int, int)](VRageMath.Rectangle..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static Rectangle Intersect(Rectangle, Rectangle)](VRageMath.Rectangle.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|\\%1static void Intersect(ref Rectangle, ref Rectangle, out Rectangle)](VRageMath.Rectangle.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|\\%1static Rectangle Union(Rectangle, Rectangle)](VRageMath.Rectangle.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|\\%1static void Union(ref Rectangle, ref Rectangle, out Rectangle)](VRageMath.Rectangle.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|\\%1bool Contains(int, int)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.|
|\\%1bool Contains(Point)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified Point.|
|\\%1void Contains(ref Point, out bool)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified Point.|
|\\%1bool Contains(Rectangle)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|\\%1void Contains(ref Rectangle, out bool)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|\\%1bool Equals(Rectangle)](VRageMath.Rectangle.Equals)|Determines whether the specified Object is equal to the Rectangle.|
|\\%1bool Equals(object)](VRageMath.Rectangle.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\\%1int GetHashCode()](VRageMath.Rectangle.GetHashCode)|Gets the hash code for this object.|
|\\%1void Inflate(int, int)](VRageMath.Rectangle.Inflate)|Pushes the edges of the Rectangle out by the horizontal and vertical values specified.|
|\\%1bool Intersects(Rectangle)](VRageMath.Rectangle.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|\\%1void Intersects(ref Rectangle, out bool)](VRageMath.Rectangle.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|\\%1void Offset(Point)](VRageMath.Rectangle.Offset)|Changes the position of the Rectangle.|
|\\%1void Offset(int, int)](VRageMath.Rectangle.Offset)|Changes the position of the Rectangle.|
|\\%1string ToString()](VRageMath.Rectangle.ToString)|Retrieves a string representation of the current object.|

