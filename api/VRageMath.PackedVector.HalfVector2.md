← [Index](index)
# HalfVector2 Struct
**Namespace:** [`VRageMath.PackedVector`](VRageMath.PackedVector)  
**Assembly:** VRage.Math.dll  
**Implements:**
* [`VRageMath.PackedVector.IPackedVector`](VRageMath.PackedVector.IPackedVector)
## Summary
Packed vector type containing two 16-bit floating-point values.
### Properties
|Member|Description|
|---|---|
|[`uint PackedValue`](VRageMath.PackedVector.PackedValue)|Directly gets or sets the packed representation of the value.|
### Methods
|Member|Description|
|---|---|
|[`Vector2 ToVector2()`](VRageMath.PackedVector.ToVector2)|Expands the HalfVector2 to a Vector2.|
|[`string ToString()`](VRageMath.PackedVector.ToString)|Returns a string representation of the current instance.|
|[`int GetHashCode()`](VRageMath.PackedVector.GetHashCode)|Gets the hash code for the current instance.|
|[`bool Equals(Object obj)`](VRageMath.PackedVector.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`bool Equals(HalfVector2 other)`](VRageMath.PackedVector.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`Vector4 ToVector4()`](VRageMath.PackedVector.ToVector4)|Expands the packed representation into a Vector4.<br/><br/>_Inherited from [`IPackedVector`](VRageMath.PackedVector.HalfVector2)_|
|[`void PackFromVector4(Vector4 vector)`](VRageMath.PackedVector.PackFromVector4)|Sets the packed representation from a Vector4.<br/><br/>_Inherited from [`IPackedVector`](VRageMath.PackedVector.HalfVector2)_|
