← [Index](Api-Index)

#Rectangle Struct

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

###Fields

|Member|Description|
|---|---|
|[X](VRageMath.Rectangle.X)|Specifies the x-coordinate of the rectangle.|
|[Y](VRageMath.Rectangle.Y)|Specifies the y-coordinate of the rectangle.|
|[Width](VRageMath.Rectangle.Width)|Specifies the width of the rectangle.|
|[Height](VRageMath.Rectangle.Height)|Specifies the height of the rectangle.|

###Properties

|Member|Description|
|---|---|
|[Left](VRageMath.Rectangle.Left)|Returns the x-coordinate of the left side of the rectangle.|
|[Right](VRageMath.Rectangle.Right)|Returns the x-coordinate of the right side of the rectangle.|
|[Top](VRageMath.Rectangle.Top)|Returns the y-coordinate of the top of the rectangle.|
|[Bottom](VRageMath.Rectangle.Bottom)|Returns the y-coordinate of the bottom of the rectangle.|
|[Location](VRageMath.Rectangle.Location)|Gets or sets the upper-left value of the Rectangle.|
|[Center](VRageMath.Rectangle.Center)|Gets the Point that specifies the center of the rectangle.|

###Methods

|Member|Description|
|---|---|
|[Offset(Point)](VRageMath.Rectangle.Offset)|Changes the position of the Rectangle.|
|[Offset(int, int)](VRageMath.Rectangle.Offset)|Changes the position of the Rectangle.|
|[Inflate(int, int)](VRageMath.Rectangle.Inflate)|Pushes the edges of the Rectangle out by the horizontal and vertical values specified.|
|[Contains(int, int)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified point represented by its x- and y-coordinates.|
|[Contains(Point)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified Point.|
|[Contains(ref Point, ref bool)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle contains a specified Point.|
|[Contains(Rectangle)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[Contains(ref Rectangle, ref bool)](VRageMath.Rectangle.Contains)|Determines whether this Rectangle entirely contains a specified Rectangle.|
|[Intersects(Rectangle)](VRageMath.Rectangle.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|[Intersects(ref Rectangle, ref bool)](VRageMath.Rectangle.Intersects)|Determines whether a specified Rectangle intersects with this Rectangle.|
|[Intersect(Rectangle, Rectangle)](VRageMath.Rectangle.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|[Intersect(ref Rectangle, ref Rectangle, ref Rectangle)](VRageMath.Rectangle.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|[Union(Rectangle, Rectangle)](VRageMath.Rectangle.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|[Union(ref Rectangle, ref Rectangle, ref Rectangle)](VRageMath.Rectangle.Union)|Creates a new Rectangle that exactly contains two other rectangles.|
|[Equals(Rectangle)](VRageMath.Rectangle.Equals)|Determines whether the specified Object is equal to the Rectangle.|
|[Equals(object)](VRageMath.Rectangle.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[ToString()](VRageMath.Rectangle.ToString)|Retrieves a string representation of the current object.|
|[GetHashCode()](VRageMath.Rectangle.GetHashCode)|Gets the hash code for this object.|

