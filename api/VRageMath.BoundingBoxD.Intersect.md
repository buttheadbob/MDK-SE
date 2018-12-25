← [Index](Api-Index) ← [BoundingBoxD](VRageMath.BoundingBoxD)

### Summary

```csharp
public BoundingBoxD Intersect(BoundingBoxD box)
```

Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)

### Returns

[BoundingBoxD](VRageMath.BoundingBoxD)

### Parameters

* [BoundingBoxD](VRageMath.BoundingBoxD) box
### Summary

```csharp
public bool Intersect(ref LineD line, ref LineD intersectedLine)
```

### Returns

[bool](System.Boolean)

### Parameters

* [LineD](VRageMath.LineD) line
* [LineD](VRageMath.LineD) intersectedLine
### Summary

```csharp
public bool Intersect(ref LineD line, ref double t1, ref double t2)
```

### Returns

[bool](System.Boolean)

### Parameters

* [LineD](VRageMath.LineD) line
* [double](System.Double) t1
* [double](System.Double) t2
### Summary

```csharp
public bool Intersect(ref RayD ray, ref double tmin, ref double tmax)
```

### Returns

[bool](System.Boolean)

### Parameters

* [RayD](VRageMath.RayD) ray
* [double](System.Double) tmin
* [double](System.Double) tmax
