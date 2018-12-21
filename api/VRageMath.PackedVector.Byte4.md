← [Index](index)
# Byte4 Struct
**Namespace:** [`VRageMath.PackedVector`](VRageMath.PackedVector)  
**Assembly:** VRage.Math.dll  
**Implements:**
* [`VRageMath.PackedVector.IPackedVector`](VRageMath.PackedVector.IPackedVector)
## Summary
Packed vector type containing four 8-bit unsigned integer values, ranging from 0 to 255.
### Properties
|Member|Description|
|---|---|
|[`uint PackedValue`](VRageMath.PackedVector.PackedValue)|Directly gets or sets the packed representation of the value.|
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector4 ToVector4()`](VRageMath.PackedVector.ToVector4)|Expands the packed representation into a Vector4.|
|[`VRageMath.Vector4UByte ToVector4UByte()`](VRageMath.PackedVector.ToVector4UByte)||
|[`string ToString()`](VRageMath.PackedVector.ToString)|Returns a string representation of the current instance.|
|[`int GetHashCode()`](VRageMath.PackedVector.GetHashCode)|Gets the hash code for the current instance.|
|[`bool Equals(System.Object)`](VRageMath.PackedVector.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`bool Equals(VRageMath.PackedVector.Byte4)`](VRageMath.PackedVector.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`VRageMath.Vector4 ToVector4()`](VRageMath.PackedVector.ToVector4)|Expands the packed representation into a Vector4.<br/><br/>_Inherited from [`IPackedVector`](VRageMath.PackedVector.Byte4)_|
|[`void PackFromVector4(VRageMath.Vector4)`](VRageMath.PackedVector.PackFromVector4)|Sets the packed representation from a Vector4.<br/><br/>_Inherited from [`IPackedVector`](VRageMath.PackedVector.Byte4)_|
