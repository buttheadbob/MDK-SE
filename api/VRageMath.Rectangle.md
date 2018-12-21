← [Index](index.md)
# Rectangle Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a rectangle.
### Fields
|Member|Description|
|---|---|
|[`int X`](VRageMath.X)||
|[`int Y`](VRageMath.Y)||
|[`int Width`](VRageMath.Width)||
|[`int Height`](VRageMath.Height)||
### Properties
|Member|Description|
|---|---|
|[`int Left`](VRageMath.Left)||
|[`int Right`](VRageMath.Right)||
|[`int Top`](VRageMath.Top)||
|[`int Bottom`](VRageMath.Bottom)||
|[`Point Location`](VRageMath.Location)||
|[`Point Center`](VRageMath.Center)||
### Methods
|Member|Description|
|---|---|
|[`void Offset(Point amount)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`void Offset(int offsetX, int offsetY)`](VRageMath.Offset)||
|[`void Inflate(int horizontalAmount, int verticalAmount)`](VRageMath.Inflate)||
|[`bool Contains(int x, int y)`](VRageMath.Contains)||
|[`bool Contains(Point value)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`void Contains(ref Point value, ref bool result)`](VRageMath.Contains)||
|[`bool Contains(Rectangle value)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`void Contains(ref Rectangle value, ref bool result)`](VRageMath.Contains)||
|[`bool Intersects(Rectangle value)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|[`void Intersects(ref Rectangle value, ref bool result)`](VRageMath.Intersects)||
|[`Rectangle Intersect(Rectangle value1, Rectangle value2)`](VRageMath.Intersect)||
|[`void Intersect(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)`](VRageMath.Intersect)||
|[`Rectangle Union(Rectangle value1, Rectangle value2)`](VRageMath.Union)||
|[`void Union(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)`](VRageMath.Union)||
|[`bool Equals(Rectangle other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Rectangle.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`string ToString()`](VRageMath.ToString)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
