← [Index](index)
# Rectangle Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a rectangle.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>int X</code></a>_</td><td>Specifies the x-coordinate of the rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Y"><code>int Y</code></a>_</td><td>Specifies the y-coordinate of the rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Width"><code>int Width</code></a>_</td><td>Specifies the width of the rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Height"><code>int Height</code></a>_</td><td>Specifies the height of the rectangle.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Left"><code>int Left</code></a>_</td><td>Returns the x-coordinate of the left side of the rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Right"><code>int Right</code></a>_</td><td>Returns the x-coordinate of the right side of the rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Top"><code>int Top</code></a>_</td><td>Returns the y-coordinate of the top of the rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Bottom"><code>int Bottom</code></a>_</td><td>Returns the y-coordinate of the bottom of the rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Location"><code>Point Location</code></a>_</td><td>Gets or sets the upper-left value of the Rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Center"><code>Point Center</code></a>_</td><td>Gets the Point that specifies the center of the rectangle.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Offset"><code>void Offset(Point amount)</code></a>_</td><td>Changes the position of the Rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Offset"><code>void Offset(int offsetX, int offsetY)</code></a>_</td><td>Changes the position of the Rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>void Inflate(int horizontalAmount, int verticalAmount)</code></a>_</td><td>Pushes the edges of the Rectangle out by the horizontal and vertical values specified.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>bool Contains(int x, int y)</code></a>_</td><td>Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>bool Contains(Point value)</code></a>_</td><td>Determines whether this Rectangle contains a specified Point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Point value, ref bool result)</code></a>_</td><td>Determines whether this Rectangle contains a specified Point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>bool Contains(Rectangle value)</code></a>_</td><td>Determines whether this Rectangle entirely contains a specified Rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Rectangle value, ref bool result)</code></a>_</td><td>Determines whether this Rectangle entirely contains a specified Rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(Rectangle value)</code></a>_</td><td>Determines whether a specified Rectangle intersects with this Rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Rectangle value, ref bool result)</code></a>_</td><td>Determines whether a specified Rectangle intersects with this Rectangle.</td></tr>
<tr><td>static _<a href="VRageMath.Intersect"><code>Rectangle Intersect(Rectangle value1, Rectangle value2)</code></a>_</td><td>Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.</td></tr>
<tr><td>static _<a href="VRageMath.Intersect"><code>void Intersect(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)</code></a>_</td><td>Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.</td></tr>
<tr><td>static _<a href="VRageMath.Union"><code>Rectangle Union(Rectangle value1, Rectangle value2)</code></a>_</td><td>Creates a new Rectangle that exactly contains two other rectangles.</td></tr>
<tr><td>static _<a href="VRageMath.Union"><code>void Union(ref Rectangle value1, ref Rectangle value2, ref Rectangle result)</code></a>_</td><td>Creates a new Rectangle that exactly contains two other rectangles.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Rectangle other)</code></a>_</td><td>Determines whether the specified Object is equal to the Rectangle.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this object.</td></tr>
</table>
