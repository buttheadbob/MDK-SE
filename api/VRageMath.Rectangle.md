← [Index](index)
# Rectangle Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a rectangle.
### Fields
|Member|Description|
|---|---|
|[`int X`](VRageMath.X)|Specifies the x-coordinate of the rectangle.|
|[`int Y`](VRageMath.Y)|Specifies the y-coordinate of the rectangle.|
|[`int Width`](VRageMath.Width)|Specifies the width of the rectangle.|
|[`int Height`](VRageMath.Height)|Specifies the height of the rectangle.|
### Properties
|Member|Description|
|---|---|
|[`int Left`](VRageMath.Left)|Returns the x-coordinate of the left side of the rectangle.|
|[`int Right`](VRageMath.Right)|Returns the x-coordinate of the right side of the rectangle.|
|[`int Top`](VRageMath.Top)|Returns the y-coordinate of the top of the rectangle.|
|[`int Bottom`](VRageMath.Bottom)|Returns the y-coordinate of the bottom of the rectangle.|
|[`Point Location`](VRageMath.Location)|Gets or sets the upper-left value of the Rectangle.|
|[`Point Center`](VRageMath.Center)|Gets the Point that specifies the center of the rectangle.|
### Methods
|Member|Description|
|---|---|
|[`void Offset(Point amount)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`void Offset(int offsetX, int offsetY)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`void Inflate(int horizontalAmount, int verticalAmount)`](VRageMath.Inflate)|Pushes the edges of the Rectangle out by the horizontal and vertical values specified.|
|[`bool Contains(int x, int y)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.|
|[`bool Contains(Point value)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`void Contains(ref Point value, ref bool result)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`bool Contains(Rectangle value)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`void Contains(ref Rectangle value, ref bool result)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`bool Intersects(Rectangle value)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|[`void Intersects(ref Rectangle value, ref bool result)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|static [`Rectangle Intersect(Rectangle value1, Rectangle value2)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|static [`void Intersect(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|static [`Rectangle Union(Rectangle value1, Rectangle value2)`](VRageMath.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|static [`void Union(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)`](VRageMath.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|[`bool Equals(Rectangle other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Rectangle.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
