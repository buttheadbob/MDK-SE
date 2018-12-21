← [Index](index)
# Vector3UByte Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`byte X`](VRageMath.X)||
|[`byte Y`](VRageMath.Y)||
|[`byte Z`](VRageMath.Z)||
|static [`EqualityComparer Comparer`](VRageMath.Comparer)||
|static [`Vector3UByte Zero`](VRageMath.Zero)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool Equals(Object obj)`](VRageMath.Equals)||
|static [`Vector3UByte Round(Vector3 vec)`](VRageMath.Round)||
|static [`Vector3UByte Floor(Vector3 vec)`](VRageMath.Floor)||
|[`int LengthSquared()`](VRageMath.LengthSquared)||
|static [`bool IsMiddle(Vector3UByte vec)`](VRageMath.IsMiddle)|Returns true when all components are 127|
|static [`Vector3UByte Normalize(Vector3 vec, float range)`](VRageMath.Normalize)|Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";|
|static [`Vector3 Denormalize(Vector3UByte vec, float range)`](VRageMath.Denormalize)|Unpacks Vector3 from Vector3UByte, scales vector from (0, 255) to (-range, range)|
