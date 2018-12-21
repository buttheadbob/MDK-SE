← [Index](index.md)
#Rectangle Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Defines a rectangle.
###Fields
|Member|Description|
|---|---|
|[`int X`](VRageMath.X.md)||
|[`int Y`](VRageMath.Y.md)||
|[`int Width`](VRageMath.Width.md)||
|[`int Height`](VRageMath.Height.md)||
###Properties
|Member|Description|
|---|---|
|[`int Left`](VRageMath.Left.md)||
|[`int Right`](VRageMath.Right.md)||
|[`int Top`](VRageMath.Top.md)||
|[`int Bottom`](VRageMath.Bottom.md)||
|[`Point Location`](VRageMath.Location.md)||
|[`Point Center`](VRageMath.Center.md)||
###Methods
|Member|Description|
|---|---|
|[`void Offset(Point amount)`](VRageMath.Offset.md)|Changes the position of the Rectangle.|
|[`void Offset(int offsetX, int offsetY)`](VRageMath.Offset.md)||
|[`void Inflate(int horizontalAmount, int verticalAmount)`](VRageMath.Inflate.md)||
|[`bool Contains(int x, int y)`](VRageMath.Contains.md)||
|[`bool Contains(Point value)`](VRageMath.Contains.md)|Determines whether this Rectangle contains a specified Point.|
|[`void Contains(ref Point value, ref bool result)`](VRageMath.Contains.md)||
|[`bool Contains(Rectangle value)`](VRageMath.Contains.md)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`void Contains(ref Rectangle value, ref bool result)`](VRageMath.Contains.md)||
|[`bool Intersects(Rectangle value)`](VRageMath.Intersects.md)|Determines whether a specified Rectangle intersects with this Rectangle.|
|[`void Intersects(ref Rectangle value, ref bool result)`](VRageMath.Intersects.md)||
|[`Rectangle Intersect(Rectangle value1, Rectangle value2)`](VRageMath.Intersect.md)||
|[`void Intersect(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)`](VRageMath.Intersect.md)||
|[`Rectangle Union(Rectangle value1, Rectangle value2)`](VRageMath.Union.md)||
|[`void Union(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)`](VRageMath.Union.md)||
|[`bool Equals(Rectangle other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Rectangle.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`string ToString()`](VRageMath.ToString.md)||
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
