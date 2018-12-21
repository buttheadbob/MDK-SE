← [Index](index)
# Rectangle Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a rectangle.
### Fields
|Member|Description|
|---|---|
|[`int&nbsp;X`](VRageMath.X)|Specifies the x-coordinate of the rectangle.|
|[`int&nbsp;Y`](VRageMath.Y)|Specifies the y-coordinate of the rectangle.|
|[`int&nbsp;Width`](VRageMath.Width)|Specifies the width of the rectangle.|
|[`int&nbsp;Height`](VRageMath.Height)|Specifies the height of the rectangle.|
### Properties
|Member|Description|
|---|---|
|[`int&nbsp;Left`](VRageMath.Left)|Returns the x-coordinate of the left side of the rectangle.|
|[`int&nbsp;Right`](VRageMath.Right)|Returns the x-coordinate of the right side of the rectangle.|
|[`int&nbsp;Top`](VRageMath.Top)|Returns the y-coordinate of the top of the rectangle.|
|[`int&nbsp;Bottom`](VRageMath.Bottom)|Returns the y-coordinate of the bottom of the rectangle.|
|[`Point&nbsp;Location`](VRageMath.Location)|Gets or sets the upper-left value of the Rectangle.|
|[`Point&nbsp;Center`](VRageMath.Center)|Gets the Point that specifies the center of the rectangle.|
### Methods
|Member|Description|
|---|---|
|[`void&nbsp;Offset(Point&nbsp;amount)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`void&nbsp;Offset(int&nbsp;offsetX,&nbsp;int&nbsp;offsetY)`](VRageMath.Offset)|Changes the position of the Rectangle.|
|[`void&nbsp;Inflate(int&nbsp;horizontalAmount,&nbsp;int&nbsp;verticalAmount)`](VRageMath.Inflate)|Pushes the edges of the Rectangle out by the horizontal and vertical values specified.|
|[`bool&nbsp;Contains(int&nbsp;x,&nbsp;int&nbsp;y)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.|
|[`bool&nbsp;Contains(Point&nbsp;value)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`void&nbsp;Contains(ref&nbsp;Point&nbsp;value,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Contains)|Determines whether this Rectangle contains a specified Point.|
|[`bool&nbsp;Contains(Rectangle&nbsp;value)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`void&nbsp;Contains(ref&nbsp;Rectangle&nbsp;value,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[`bool&nbsp;Intersects(Rectangle&nbsp;value)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|[`void&nbsp;Intersects(ref&nbsp;Rectangle&nbsp;value,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|static&nbsp;[`Rectangle&nbsp;Intersect(Rectangle&nbsp;value1,&nbsp;Rectangle&nbsp;value2)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|static&nbsp;[`void&nbsp;Intersect(ref&nbsp;Rectangle&nbsp;value1,&nbsp;ref&nbsp;Rectangle&nbsp;value2,&nbsp;ref&nbsp;Rectangle&nbsp;result)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|static&nbsp;[`Rectangle&nbsp;Union(Rectangle&nbsp;value1,&nbsp;Rectangle&nbsp;value2)`](VRageMath.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|static&nbsp;[`void&nbsp;Union(ref&nbsp;Rectangle&nbsp;value1,&nbsp;ref&nbsp;Rectangle&nbsp;value2,&nbsp;ref&nbsp;Rectangle&nbsp;result)`](VRageMath.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|[`bool&nbsp;Equals(Rectangle&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Rectangle.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
