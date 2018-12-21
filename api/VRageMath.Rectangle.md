← [Index](index)
# Rectangle Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a rectangle.
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)|Specifies the x-coordinate of the rectangle.|
|[`Y`](VRageMath.Y)|Specifies the y-coordinate of the rectangle.|
|[`Width`](VRageMath.Width)|Specifies the width of the rectangle.|
|[`Height`](VRageMath.Height)|Specifies the height of the rectangle.|
### Properties
|Member|Description|
|---|---|
|[`Left`](VRageMath.Left)|Returns the x-coordinate of the left side of the rectangle.|
|[`Right`](VRageMath.Right)|Returns the x-coordinate of the right side of the rectangle.|
|[`Top`](VRageMath.Top)|Returns the y-coordinate of the top of the rectangle.|
|[`Bottom`](VRageMath.Bottom)|Returns the y-coordinate of the bottom of the rectangle.|
|[`Location`](VRageMath.Location)|Gets or sets the upper-left value of the Rectangle.|
|[`Center`](VRageMath.Center)|Gets the Point that specifies the center of the rectangle.|
### Methods
|Member|Description|
|---|---|
|[`Offset(Point)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`Offset(int, int)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`Inflate(int, int)`](VRageMath.Inflate)|Pushes the edges of the Rectangle out by the horizontal and vertical values specified.|
|[`Contains(int, int)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.|
|[`Contains(Point)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`Contains(ref Point, ref bool)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`Contains(Rectangle)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`Contains(ref Rectangle, ref bool)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`Intersects(Rectangle)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|[`Intersects(ref Rectangle, ref bool)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|static [`Intersect(Rectangle, Rectangle)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|static [`Intersect(ref Rectangle, ref Rectangle, ref Rectangle)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|static [`Union(Rectangle, Rectangle)`](VRageMath.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|static [`Union(ref Rectangle, ref Rectangle, ref Rectangle)`](VRageMath.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|[`Equals(Rectangle)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Rectangle.|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
