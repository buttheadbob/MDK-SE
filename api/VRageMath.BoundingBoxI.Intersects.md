← [Index](Api-Index) ← [BoundingBoxI](VRageMath.BoundingBoxI)

### Summary

```csharp
public bool Intersects(BoundingBoxI box)
```

Checks whether the current BoundingBoxI intersects another BoundingBoxI.

### Returns

[bool](System.Boolean)

### Parameters

* [BoundingBoxI](VRageMath.BoundingBoxI) box
### Summary

```csharp
public bool Intersects(ref BoundingBoxI box)
```

### Returns

[bool](System.Boolean)

### Parameters

* [BoundingBoxI](VRageMath.BoundingBoxI) box
### Summary

```csharp
public void Intersects(ref BoundingBoxI box, ref bool result)
```

Checks whether the current BoundingBoxI intersects another BoundingBoxI.

### Parameters

* [BoundingBoxI](VRageMath.BoundingBoxI) box
* [bool](System.Boolean) result
### Summary

```csharp
public PlaneIntersectionType Intersects(Plane plane)
```

Checks whether the current BoundingBoxI intersects a Plane.

### Returns

[PlaneIntersectionType](VRageMath.PlaneIntersectionType)

### Parameters

* [Plane](VRageMath.Plane) plane
### Summary

```csharp
public void Intersects(ref Plane plane, ref PlaneIntersectionType result)
```

Checks whether the current BoundingBoxI intersects a Plane.

### Parameters

* [Plane](VRageMath.Plane) plane
* [PlaneIntersectionType](VRageMath.PlaneIntersectionType) result
### Summary

```csharp
public bool Intersects(Line line, ref float distance)
```

### Returns

[bool](System.Boolean)

### Parameters

* [Line](VRageMath.Line) line
* [float](System.Single) distance
### Summary

```csharp
public Nullable<T> Intersects(Ray ray)
```

Checks whether the current BoundingBoxI intersects a Ray.

### Returns

[Nullable<T>](System.Nullable`1)

### Parameters

* [Ray](VRageMath.Ray) ray
### Summary

```csharp
public void Intersects(ref Ray ray, ref Nullable<T> result)
```

### Parameters

* [Ray](VRageMath.Ray) ray
* [Nullable<T>](System.Nullable`1) result
