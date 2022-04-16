← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [Vector3D](VRageMath.Vector3D)

### Summary

```csharp
public static Vector3D Transform(Vector3D value, Quaternion rotation)
```

Transforms a Vector3 by a specified Quaternion rotation.

### Returns

[Vector3D](VRageMath.Vector3D)

### Parameters

* [Vector3D](VRageMath.Vector3D) value
* [Quaternion](VRageMath.Quaternion) rotation
### Summary

```csharp
public static void Transform(ref Vector3D value, ref Quaternion rotation, out Vector3D result)
```

Transforms a Vector3 by a specified Quaternion rotation.

### Parameters

* [Vector3D](VRageMath.Vector3D) value
* [Quaternion](VRageMath.Quaternion) rotation
* [Vector3D](VRageMath.Vector3D) result
### Summary

```csharp
public static void Transform(Vector3D[] sourceArray, ref MatrixD matrix, Vector3D[] destinationArray)
```

Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.

### Parameters

* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) sourceArray
* [MatrixD](VRageMath.MatrixD) matrix
* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) destinationArray
### Summary

```csharp
public static void Transform(Vector3D[] sourceArray, ref MatrixD matrix, *Vector3D destinationArray)
```

### Parameters

* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) sourceArray
* [MatrixD](VRageMath.MatrixD) matrix
* [Vector3D](VRageMath.Vector3D) destinationArray
### Summary

```csharp
public static void Transform(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)
```

Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.

### Parameters

* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) sourceArray
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) sourceIndex
* [Matrix](VRageMath.Matrix) matrix
* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) destinationArray
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) destinationIndex
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) length
### Summary

```csharp
public static void Transform(Vector3D[] sourceArray, ref Quaternion rotation, Vector3D[] destinationArray)
```

Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.

### Parameters

* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) sourceArray
* [Quaternion](VRageMath.Quaternion) rotation
* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) destinationArray
### Summary

```csharp
public static void Transform(Vector3D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3D[] destinationArray, int destinationIndex, int length)
```

Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.

### Parameters

* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) sourceArray
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) sourceIndex
* [Quaternion](VRageMath.Quaternion) rotation
* [Vector3D&#91&#93;](VRageMath.Vector3D&#91&#93;) destinationArray
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) destinationIndex
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) length
### Summary

```csharp
public static Vector3D Transform(Vector3D position, MatrixD matrix)
```

Transforms a 3D vector by the given matrix.

### Returns

[Vector3D](VRageMath.Vector3D)

### Parameters

* [Vector3D](VRageMath.Vector3D) position
* [MatrixD](VRageMath.MatrixD) matrix
### Summary

```csharp
public static Vector3D Transform(Vector3 position, MatrixD matrix)
```

### Returns

[Vector3D](VRageMath.Vector3D)

### Parameters

* [Vector3](VRageMath.Vector3) position
* [MatrixD](VRageMath.MatrixD) matrix
### Summary

```csharp
public static Vector3D Transform(Vector3D position, Matrix matrix)
```

Transforms a 3D vector by the given matrix.

### Returns

[Vector3D](VRageMath.Vector3D)

### Parameters

* [Vector3D](VRageMath.Vector3D) position
* [Matrix](VRageMath.Matrix) matrix
### Summary

```csharp
public static Vector3D Transform(Vector3D position, ref MatrixD matrix)
```

### Returns

[Vector3D](VRageMath.Vector3D)

### Parameters

* [Vector3D](VRageMath.Vector3D) position
* [MatrixD](VRageMath.MatrixD) matrix
### Summary

```csharp
public static void Transform(ref Vector3D position, ref MatrixD matrix, out Vector3D result)
```

Transforms a Vector3 by the given Matrix.

### Parameters

* [Vector3D](VRageMath.Vector3D) position
* [MatrixD](VRageMath.MatrixD) matrix
* [Vector3D](VRageMath.Vector3D) result
### Summary

```csharp
public static void Transform(ref Vector3 position, ref MatrixD matrix, out Vector3D result)
```

### Parameters

* [Vector3](VRageMath.Vector3) position
* [MatrixD](VRageMath.MatrixD) matrix
* [Vector3D](VRageMath.Vector3D) result
### Summary

```csharp
public static void Transform(ref Vector3D position, ref MatrixI matrix, out Vector3D result)
```

### Parameters

* [Vector3D](VRageMath.Vector3D) position
* [MatrixI](VRageMath.MatrixI) matrix
* [Vector3D](VRageMath.Vector3D) result
