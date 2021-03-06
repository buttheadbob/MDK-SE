← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [Vector2D](VRageMath.Vector2D)

### Summary

```csharp
public static Vector2D Transform(Vector2D position, Matrix matrix)
```

Transforms the vector (x, y, 0, 1) by the specified matrix.

### Returns

[Vector2D](VRageMath.Vector2D)

### Parameters

* [Vector2D](VRageMath.Vector2D) position
* [Matrix](VRageMath.Matrix) matrix
### Summary

```csharp
public static void Transform(ref Vector2D position, ref Matrix matrix, out Vector2D result)
```

Transforms a Vector2D by the given Matrix.

### Parameters

* [Vector2D](VRageMath.Vector2D) position
* [Matrix](VRageMath.Matrix) matrix
* [Vector2D](VRageMath.Vector2D) result
### Summary

```csharp
public static Vector2D Transform(Vector2D value, Quaternion rotation)
```

Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Returns

[Vector2D](VRageMath.Vector2D)

### Parameters

* [Vector2D](VRageMath.Vector2D) value
* [Quaternion](VRageMath.Quaternion) rotation
### Summary

```csharp
public static void Transform(ref Vector2D value, ref Quaternion rotation, out Vector2D result)
```

Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Parameters

* [Vector2D](VRageMath.Vector2D) value
* [Quaternion](VRageMath.Quaternion) rotation
* [Vector2D](VRageMath.Vector2D) result
### Summary

```csharp
public static void Transform(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)
```

Transforms an array of Vector2s by a specified Matrix.

### Parameters

* [Vector2D&#91&#93;](VRageMath.Vector2D&#91&#93;) sourceArray
* [Matrix](VRageMath.Matrix) matrix
* [Vector2D&#91&#93;](VRageMath.Vector2D&#91&#93;) destinationArray
### Summary

```csharp
public static void Transform(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.

### Parameters

* [Vector2D&#91&#93;](VRageMath.Vector2D&#91&#93;) sourceArray
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) sourceIndex
* [Matrix](VRageMath.Matrix) matrix
* [Vector2D&#91&#93;](VRageMath.Vector2D&#91&#93;) destinationArray
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) destinationIndex
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) length
### Summary

```csharp
public static void Transform(Vector2D[] sourceArray, ref Quaternion rotation, Vector2D[] destinationArray)
```

Transforms an array of Vector2s by a specified Quaternion.

### Parameters

* [Vector2D&#91&#93;](VRageMath.Vector2D&#91&#93;) sourceArray
* [Quaternion](VRageMath.Quaternion) rotation
* [Vector2D&#91&#93;](VRageMath.Vector2D&#91&#93;) destinationArray
### Summary

```csharp
public static void Transform(Vector2D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2D[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.

### Parameters

* [Vector2D&#91&#93;](VRageMath.Vector2D&#91&#93;) sourceArray
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) sourceIndex
* [Quaternion](VRageMath.Quaternion) rotation
* [Vector2D&#91&#93;](VRageMath.Vector2D&#91&#93;) destinationArray
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) destinationIndex
* [int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6) length
