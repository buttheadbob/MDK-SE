← [Index](index)
# RectangleF Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Structure using the same layout than [System.Drawing.RectangleF](https://docs.microsoft.com/en-us/dotnet/api/system.drawing.rectanglef?view=netframework-4.6) 
### Fields
|Member|Description|
|---|---|
|[`Vector2 Position`](VRageMath.Position)|The Position.|
|[`Vector2 Size`](VRageMath.Size)|The Size.|
### Properties
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)|Left coordinate.|
|[`float Y`](VRageMath.Y)|Top coordinate.|
|[`float Width`](VRageMath.Width)|Width of this rectangle.|
|[`float Height`](VRageMath.Height)|Height of this rectangle.|
### Methods
|Member|Description|
|---|---|
|[`bool Contains(int x, int y)`](VRageMath.Contains)||
|[`bool Contains(float x, float y)`](VRageMath.Contains)||
|[`bool Contains(Vector2 vector2D)`](VRageMath.Contains)||
|[`bool Contains(Point point)`](VRageMath.Contains)||
|[`bool Equals(RectangleF other)`](VRageMath.Equals)|Determines whether the specified [System.Object](https://docs.microsoft.com/en-us/dotnet/api/system.object?view=netframework-4.6) is equal to this instance.|
|static [`bool Intersect(ref RectangleF value1, ref RectangleF value2, ref RectangleF result)`](VRageMath.Intersect)|Creates a Rectangle defining the area where one rectangle overlaps with another rectangle.|
|[`bool Equals(Object obj)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
