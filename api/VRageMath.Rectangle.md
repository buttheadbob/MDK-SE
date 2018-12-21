← [Index](index)
# Rectangle Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a rectangle.
### Fields
<table style="width: 100%">
<tr><td>[`int X`](VRageMath.X)</td><td>Specifies the x-coordinate of the rectangle.</td></tr>
<tr><td>[`int Y`](VRageMath.Y)</td><td>Specifies the y-coordinate of the rectangle.</td></tr>
<tr><td>[`int Width`](VRageMath.Width)</td><td>Specifies the width of the rectangle.</td></tr>
<tr><td>[`int Height`](VRageMath.Height)</td><td>Specifies the height of the rectangle.</td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`int Left`](VRageMath.Left)</td><td>Returns the x-coordinate of the left side of the rectangle.</td></tr>
<tr><td>[`int Right`](VRageMath.Right)</td><td>Returns the x-coordinate of the right side of the rectangle.</td></tr>
<tr><td>[`int Top`](VRageMath.Top)</td><td>Returns the y-coordinate of the top of the rectangle.</td></tr>
<tr><td>[`int Bottom`](VRageMath.Bottom)</td><td>Returns the y-coordinate of the bottom of the rectangle.</td></tr>
<tr><td>[`Point Location`](VRageMath.Location)</td><td>Gets or sets the upper-left value of the Rectangle.</td></tr>
<tr><td>[`Point Center`](VRageMath.Center)</td><td>Gets the Point that specifies the center of the rectangle.</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`void Offset(Point amount)`](VRageMath.Offset)</td><td>Changes the position of the Rectangle.</td></tr>
<tr><td>[`void Offset(int offsetX, int offsetY)`](VRageMath.Offset)</td><td>Changes the position of the Rectangle.</td></tr>
<tr><td>[`void Inflate(int horizontalAmount, int verticalAmount)`](VRageMath.Inflate)</td><td>Pushes the edges of the Rectangle out by the horizontal and vertical values specified.</td></tr>
<tr><td>[`bool Contains(int x, int y)`](VRageMath.Contains)</td><td>Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.</td></tr>
<tr><td>[`bool Contains(Point value)`](VRageMath.Contains)</td><td>Determines whether this Rectangle contains a specified Point.</td></tr>
<tr><td>[`void Contains(ref Point value, ref bool result)`](VRageMath.Contains)</td><td>Determines whether this Rectangle contains a specified Point.</td></tr>
<tr><td>[`bool Contains(Rectangle value)`](VRageMath.Contains)</td><td>Determines whether this Rectangle entirely contains a specified Rectangle.</td></tr>
<tr><td>[`void Contains(ref Rectangle value, ref bool result)`](VRageMath.Contains)</td><td>Determines whether this Rectangle entirely contains a specified Rectangle.</td></tr>
<tr><td>[`bool Intersects(Rectangle value)`](VRageMath.Intersects)</td><td>Determines whether a specified Rectangle intersects with this Rectangle.</td></tr>
<tr><td>[`void Intersects(ref Rectangle value, ref bool result)`](VRageMath.Intersects)</td><td>Determines whether a specified Rectangle intersects with this Rectangle.</td></tr>
<tr><td>static [`Rectangle Intersect(Rectangle value1, Rectangle value2)`](VRageMath.Intersect)</td><td>Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.</td></tr>
<tr><td>static [`void Intersect(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)`](VRageMath.Intersect)</td><td>Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.</td></tr>
<tr><td>static [`Rectangle Union(Rectangle value1, Rectangle value2)`](VRageMath.Union)</td><td>Creates a new Rectangle that exactly contains two other rectangles.</td></tr>
<tr><td>static [`void Union(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)`](VRageMath.Union)</td><td>Creates a new Rectangle that exactly contains two other rectangles.</td></tr>
<tr><td>[`bool Equals(Rectangle other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Rectangle.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this object.</td></tr>
</table>
