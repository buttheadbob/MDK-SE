← [Index](index)
# Rectangle Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a rectangle.
### Fields
|Member|Description|
|---|---|
|[`int X`](VRageMath.X)|Specifies the x-coordinate of the rectangle.|
|[`int Y`](VRageMath.Y)|Specifies the y-coordinate of the rectangle.|
|[`int Width`](VRageMath.Width)|Specifies the width of the rectangle.|
|[`int Height`](VRageMath.Height)|Specifies the height of the rectangle.|
### Properties
|Member|Description|
|---|---|
|[`int Left`](VRageMath.Left)|Returns the x-coordinate of the left side of the rectangle.|
|[`int Right`](VRageMath.Right)|Returns the x-coordinate of the right side of the rectangle.|
|[`int Top`](VRageMath.Top)|Returns the y-coordinate of the top of the rectangle.|
|[`int Bottom`](VRageMath.Bottom)|Returns the y-coordinate of the bottom of the rectangle.|
|[`VRageMath.Point Location`](VRageMath.Location)|Gets or sets the upper-left value of the Rectangle.|
|[`VRageMath.Point Center`](VRageMath.Center)|Gets the Point that specifies the center of the rectangle.|
### Methods
|Member|Description|
|---|---|
|[`void Offset(VRageMath.Point)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`void Offset(int, int)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`void Inflate(int, int)`](VRageMath.Inflate)|Pushes the edges of the Rectangle out by the horizontal and vertical values specified.|
|[`bool Contains(int, int)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.|
|[`bool Contains(VRageMath.Point)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`void Contains(ref VRageMath.Point, ref bool)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`bool Contains(VRageMath.Rectangle)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`void Contains(ref VRageMath.Rectangle, ref bool)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`bool Intersects(VRageMath.Rectangle)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|[`void Intersects(ref VRageMath.Rectangle, ref bool)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|static [`VRageMath.Rectangle Intersect(VRageMath.Rectangle, VRageMath.Rectangle)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|static [`void Intersect(ref VRageMath.Rectangle, ref VRageMath.Rectangle, ref VRageMath.Rectangle)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|static [`VRageMath.Rectangle Union(VRageMath.Rectangle, VRageMath.Rectangle)`](VRageMath.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|static [`void Union(ref VRageMath.Rectangle, ref VRageMath.Rectangle, ref VRageMath.Rectangle)`](VRageMath.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|[`bool Equals(VRageMath.Rectangle)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Rectangle.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
