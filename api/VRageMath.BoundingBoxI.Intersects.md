← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [BoundingBoxI](VRageMath.BoundingBoxI)

### Summary

```csharp
public bool Intersects(BoundingBoxI box)
```

Checks whether the current BoundingBoxI intersects another BoundingBoxI.

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

### Parameters

* [BoundingBoxI](VRageMath.BoundingBoxI) box
### Summary

```csharp
public bool Intersects(ref BoundingBoxI box)
```

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

### Parameters

* [BoundingBoxI](VRageMath.BoundingBoxI) box
### Summary

```csharp
public void Intersects(ref BoundingBoxI box, ref bool result)
```

Checks whether the current BoundingBoxI intersects another BoundingBoxI.

### Parameters

* [BoundingBoxI](VRageMath.BoundingBoxI) box
* [bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) result
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

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

### Parameters

* [Line](VRageMath.Line) line
* [float](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) distance
### Summary

```csharp
public Nullable<System.Single> Intersects(Ray ray)
```

Checks whether the current BoundingBoxI intersects a Ray.

### Returns

[Nullable<System.Single>](https://docs.microsoft.com/en-us/dotnet/api/system.nullable?view=netframework-4.6)

### Parameters

* [Ray](VRageMath.Ray) ray
### Summary

```csharp
public void Intersects(ref Ray ray, ref Nullable<System.Single> result)
```

### Parameters

* [Ray](VRageMath.Ray) ray
* [Nullable<System.Single>](https://docs.microsoft.com/en-us/dotnet/api/system.nullable?view=netframework-4.6) result
