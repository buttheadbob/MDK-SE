← [Index](index)
# Vector3UByte Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`byte&nbsp;X`](VRageMath.X)||
|[`byte&nbsp;Y`](VRageMath.Y)||
|[`byte&nbsp;Z`](VRageMath.Z)||
|static&nbsp;[`EqualityComparer&nbsp;Comparer`](VRageMath.Comparer)||
|static&nbsp;[`Vector3UByte&nbsp;Zero`](VRageMath.Zero)||
### Methods
|Member|Description|
|---|---|
|[`string&nbsp;ToString()`](VRageMath.ToString)||
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)||
|static&nbsp;[`Vector3UByte&nbsp;Round(Vector3&nbsp;vec)`](VRageMath.Round)||
|static&nbsp;[`Vector3UByte&nbsp;Floor(Vector3&nbsp;vec)`](VRageMath.Floor)||
|[`int&nbsp;LengthSquared()`](VRageMath.LengthSquared)||
|static&nbsp;[`bool&nbsp;IsMiddle(Vector3UByte&nbsp;vec)`](VRageMath.IsMiddle)|Returns true when all components are 127|
|static&nbsp;[`Vector3UByte&nbsp;Normalize(Vector3&nbsp;vec,&nbsp;float&nbsp;range)`](VRageMath.Normalize)|Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";|
|static&nbsp;[`Vector3&nbsp;Denormalize(Vector3UByte&nbsp;vec,&nbsp;float&nbsp;range)`](VRageMath.Denormalize)|Unpacks Vector3 from Vector3UByte, scales vector from (0, 255) to (-range, range)|
