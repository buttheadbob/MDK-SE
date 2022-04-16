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
|\[int Height](VRageMath.Rectangle.Height)|Specifies the height of the rectangle.|
|\[int Width](VRageMath.Rectangle.Width)|Specifies the width of the rectangle.|
|\[int X](VRageMath.Rectangle.X)|Specifies the x-coordinate of the rectangle.|
|\[int Y](VRageMath.Rectangle.Y)|Specifies the y-coordinate of the rectangle.|

#### Properties

|Member|Description|
|---|---|
|\[int Bottom { get; }](VRageMath.Rectangle.Bottom)|Returns the y-coordinate of the bottom of the rectangle.|
|\[Point Center { get; }](VRageMath.Rectangle.Center)|Gets the Point that specifies the center of the rectangle.|
|\[int Left { get; }](VRageMath.Rectangle.Left)|Returns the x-coordinate of the left side of the rectangle.|
|\[Point Location { get; set; }](VRageMath.Rectangle.Location)|Gets or sets the upper-left value of the Rectangle.|
|\[int Right { get; }](VRageMath.Rectangle.Right)|Returns the x-coordinate of the right side of the rectangle.|
|\[int Top { get; }](VRageMath.Rectangle.Top)|Returns the y-coordinate of the top of the rectangle.|

#### Constructors

|Member|Description|
|---|---|
|\[Rectangle(int, int, int, int)](VRageMath.Rectangle..ctor)||

#### Methods

|Member|Description|
|---|---|
|\[static Rectangle Intersect(Rectangle, Rectangle)](VRageMath.Rectangle.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|\[static void Intersect(ref Rectangle, ref Rectangle, out Rectangle)](VRageMath.Rectangle.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|\[static Rectangle Union(Rectangle, Rectangle)](VRageMath.Rectangle.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|\[static void Union(ref Rectangle, ref Rectangle, out Rectangle)](VRageMath.Rectangle.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|\[bool Contains(int, int)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.|
|\[bool Contains(Point)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified Point.|
|\[void Contains(ref Point, out bool)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified Point.|
|\[bool Contains(Rectangle)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|\[void Contains(ref Rectangle, out bool)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|\[bool Equals(Rectangle)](VRageMath.Rectangle.Equals)|Determines whether the specified Object is equal to the Rectangle.|
|\[bool Equals(object)](VRageMath.Rectangle.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\[int GetHashCode()](VRageMath.Rectangle.GetHashCode)|Gets the hash code for this object.|
|\[void Inflate(int, int)](VRageMath.Rectangle.Inflate)|Pushes the edges of the Rectangle out by the horizontal and vertical values specified.|
|\[bool Intersects(Rectangle)](VRageMath.Rectangle.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|\[void Intersects(ref Rectangle, out bool)](VRageMath.Rectangle.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|\[void Offset(Point)](VRageMath.Rectangle.Offset)|Changes the position of the Rectangle.|
|\[void Offset(int, int)](VRageMath.Rectangle.Offset)|Changes the position of the Rectangle.|
|\[string ToString()](VRageMath.Rectangle.ToString)|Retrieves a string representation of the current object.|

