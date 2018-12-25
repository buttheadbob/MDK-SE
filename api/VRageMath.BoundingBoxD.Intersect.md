← [Index](Api-Index) ← [BoundingBoxD](VRageMath.BoundingBoxD)

```csharp[BoundingBoxD](VRageMath.BoundingBoxD) Intersect([BoundingBoxD](VRageMath.BoundingBoxD) box)```##### Summary

Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)

```csharp[bool](System.Boolean) Intersect(ref [LineD](VRageMath.LineD) line, ref [LineD](VRageMath.LineD) intersectedLine)``````csharp[bool](System.Boolean) Intersect(ref [LineD](VRageMath.LineD) line, ref [double](System.Double) t1, ref [double](System.Double) t2)``````csharp[bool](System.Boolean) Intersect(ref [RayD](VRageMath.RayD) ray, ref [double](System.Double) tmin, ref [double](System.Double) tmax)```