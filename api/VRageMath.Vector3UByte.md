← [Index](index)
# Vector3UByte Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`byte X`](VRageMath.X)||
|[`byte Y`](VRageMath.Y)||
|[`byte Z`](VRageMath.Z)||
|static [`VRageMath.EqualityComparer Comparer`](VRageMath.Comparer)||
|static [`VRageMath.Vector3UByte Zero`](VRageMath.Zero)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool Equals(System.Object)`](VRageMath.Equals)||
|static [`VRageMath.Vector3UByte Round(VRageMath.Vector3)`](VRageMath.Round)||
|static [`VRageMath.Vector3UByte Floor(VRageMath.Vector3)`](VRageMath.Floor)||
|[`int LengthSquared()`](VRageMath.LengthSquared)||
|static [`bool IsMiddle(VRageMath.Vector3UByte)`](VRageMath.IsMiddle)|Returns true when all components are 127|
|static [`VRageMath.Vector3UByte Normalize(VRageMath.Vector3, float)`](VRageMath.Normalize)|Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";|
|static [`VRageMath.Vector3 Denormalize(VRageMath.Vector3UByte, float)`](VRageMath.Denormalize)|Unpacks Vector3 from Vector3UByte, scales vector from (0, 255) to (-range, range)|
