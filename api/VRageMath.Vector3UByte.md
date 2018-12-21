← [Index](index)
# Vector3UByte Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)||
|[`Y`](VRageMath.Y)||
|[`Z`](VRageMath.Z)||
|static [`Comparer`](VRageMath.Comparer)||
|static [`Zero`](VRageMath.Zero)||
### Methods
|Member|Description|
|---|---|
|[`ToString()`](VRageMath.ToString)||
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`Equals(Object)`](VRageMath.Equals)||
|static [`Round(Vector3)`](VRageMath.Round)||
|static [`Floor(Vector3)`](VRageMath.Floor)||
|[`LengthSquared()`](VRageMath.LengthSquared)||
|static [`IsMiddle(Vector3UByte)`](VRageMath.IsMiddle)|Returns true when all components are 127|
|static [`Normalize(Vector3, float)`](VRageMath.Normalize)|Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";|
|static [`Denormalize(Vector3UByte, float)`](VRageMath.Denormalize)|Unpacks Vector3 from Vector3UByte, scales vector from (0, 255) to (-range, range)|
