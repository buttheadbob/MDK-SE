← [Index](index)
# Vector4 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`float Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`float Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|[`float W`](VRageMath.W)|Gets or sets the w-component of the vector.|
|static [`Vector4 Zero`](VRageMath.Zero)||
|static [`Vector4 One`](VRageMath.One)||
|static [`Vector4 UnitX`](VRageMath.UnitX)||
|static [`Vector4 UnitY`](VRageMath.UnitY)||
|static [`Vector4 UnitZ`](VRageMath.UnitZ)||
|static [`Vector4 UnitW`](VRageMath.UnitW)||
### Properties
|Member|Description|
|---|---|
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static [`Vector4 PackOrthoMatrix(Vector3 position, Vector3 forward, Vector3 up)`](VRageMath.PackOrthoMatrix)||
|static [`Vector4 PackOrthoMatrix(ref Matrix matrix)`](VRageMath.PackOrthoMatrix)||
|static [`Matrix UnpackOrthoMatrix(ref Vector4 packed)`](VRageMath.UnpackOrthoMatrix)||
|static [`void UnpackOrthoMatrix(ref Vector4 packed, ref Matrix matrix)`](VRageMath.UnpackOrthoMatrix)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(Vector4 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`float Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`float Distance(Vector4 value1, Vector4 value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref Vector4 value1, ref Vector4 value2, ref float result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`float DistanceSquared(Vector4 value1, Vector4 value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref float result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`float Dot(Vector4 vector1, Vector4 vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|static [`void Dot(ref Vector4 vector1, ref Vector4 vector2, ref float result)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`void Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector.|
|static [`Vector4 Normalize(Vector4 vector)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|static [`void Normalize(ref Vector4 vector, ref Vector4 result)`](VRageMath.Normalize)|Returns a normalized version of the specified vector.|
|static [`Vector4 Min(Vector4 value1, Vector4 value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Vector4 Max(Vector4 value1, Vector4 value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Vector4 Clamp(Vector4 value1, Vector4 min, Vector4 max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref Vector4 value1, ref Vector4 min, ref Vector4 max, ref Vector4 result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Vector4 Lerp(Vector4 value1, Vector4 value2, float amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Vector4 Barycentric(Vector4 value1, Vector4 value2, Vector4 value3, float amount1, float amount2)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|static [`void Barycentric(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, float amount1, float amount2, ref Vector4 result)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|static [`Vector4 SmoothStep(Vector4 value1, Vector4 value2, float amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`Vector4 CatmullRom(Vector4 value1, Vector4 value2, Vector4 value3, Vector4 value4, float amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, ref Vector4 value4, float amount, ref Vector4 result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Vector4 Hermite(Vector4 value1, Vector4 tangent1, Vector4 value2, Vector4 tangent2, float amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref Vector4 value1, ref Vector4 tangent1, ref Vector4 value2, ref Vector4 tangent2, float amount, ref Vector4 result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Vector4 Transform(Vector2 position, Matrix matrix)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`void Transform(ref Vector2 position, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`Vector4 Transform(Vector3 position, Matrix matrix)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`void Transform(ref Vector3 position, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`Vector4 Transform(Vector4 vector, Matrix matrix)`](VRageMath.Transform)|Transforms a Vector4 by the specified Matrix.|
|static [`void Transform(ref Vector4 vector, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)|Transforms a Vector4 by the given Matrix.|
|static [`Vector4 Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`Vector4 Transform(Vector3 value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`Vector4 Transform(Vector4 value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`void Transform(ref Vector4 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`void Transform(Vector4[] sourceArray, ref Matrix matrix, Vector4[] destinationArray)`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|static [`void Transform(Vector4[] sourceArray, int sourceIndex, ref Matrix matrix, Vector4[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|static [`void Transform(Vector4[] sourceArray, ref Quaternion rotation, Vector4[] destinationArray)`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|static [`void Transform(Vector4[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|static [`Vector4 Negate(Vector4 value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref Vector4 value, ref Vector4 result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Vector4 Add(Vector4 value1, Vector4 value2)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Add)|Adds two vectors.|
|static [`Vector4 Subtract(Vector4 value1, Vector4 value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Vector4 Multiply(Vector4 value1, Vector4 value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Vector4 Multiply(Vector4 value1, float scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar.|
|static [`void Multiply(ref Vector4 value1, float scaleFactor, ref Vector4 result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Vector4 Divide(Vector4 value1, Vector4 value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Vector4 Divide(Vector4 value1, float divider)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref Vector4 value1, float divider, ref Vector4 result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
