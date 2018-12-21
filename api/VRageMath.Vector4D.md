← [Index](index)
# Vector4D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`double Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`double Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|[`double W`](VRageMath.W)|Gets or sets the w-component of the vector.|
|static [`Vector4D Zero`](VRageMath.Zero)||
|static [`Vector4D One`](VRageMath.One)||
|static [`Vector4D UnitX`](VRageMath.UnitX)||
|static [`Vector4D UnitY`](VRageMath.UnitY)||
|static [`Vector4D UnitZ`](VRageMath.UnitZ)||
|static [`Vector4D UnitW`](VRageMath.UnitW)||
### Methods
|Member|Description|
|---|---|
|static [`Vector4D PackOrthoMatrix(Vector3D position, Vector3D forward, Vector3D up)`](VRageMath.PackOrthoMatrix)||
|static [`Vector4D PackOrthoMatrix(ref MatrixD matrix)`](VRageMath.PackOrthoMatrix)||
|static [`MatrixD UnpackOrthoMatrix(ref Vector4D packed)`](VRageMath.UnpackOrthoMatrix)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(Vector4 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`double Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`double Distance(Vector4 value1, Vector4 value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref Vector4 value1, ref Vector4 value2, ref double result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`double DistanceSquared(Vector4 value1, Vector4 value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref double result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`double Dot(Vector4 vector1, Vector4 vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|static [`void Dot(ref Vector4 vector1, ref Vector4 vector2, ref double result)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`void Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector.|
|static [`Vector4D Normalize(Vector4D vector)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|static [`void Normalize(ref Vector4D vector, ref Vector4D result)`](VRageMath.Normalize)|Returns a normalized version of the specified vector.|
|static [`Vector4 Min(Vector4 value1, Vector4 value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Vector4 Max(Vector4 value1, Vector4 value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Vector4D Clamp(Vector4D value1, Vector4D min, Vector4D max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref Vector4D value1, ref Vector4D min, ref Vector4D max, ref Vector4D result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Vector4D Lerp(Vector4D value1, Vector4D value2, double amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Vector4D Barycentric(Vector4D value1, Vector4D value2, Vector4D value3, double amount1, double amount2)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|static [`void Barycentric(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, double amount1, double amount2, ref Vector4D result)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|static [`Vector4D SmoothStep(Vector4D value1, Vector4D value2, double amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`Vector4D CatmullRom(Vector4D value1, Vector4D value2, Vector4D value3, Vector4D value4, double amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, ref Vector4D value4, double amount, ref Vector4D result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Vector4D Hermite(Vector4D value1, Vector4D tangent1, Vector4D value2, Vector4D tangent2, double amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref Vector4D value1, ref Vector4D tangent1, ref Vector4D value2, ref Vector4D tangent2, double amount, ref Vector4D result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Vector4D Transform(Vector2 position, MatrixD matrix)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`void Transform(ref Vector2 position, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`Vector4D Transform(Vector3D position, MatrixD matrix)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`Vector4D Transform(Vector4D vector, MatrixD matrix)`](VRageMath.Transform)|Transforms a Vector4 by the specified Matrix.|
|static [`void Transform(ref Vector4D vector, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)|Transforms a Vector4 by the given Matrix.|
|static [`Vector4D Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`Vector4D Transform(Vector3D value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`Vector4D Transform(Vector4D value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`void Transform(ref Vector4D value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`void Transform(Vector4D[] sourceArray, ref MatrixD matrix, Vector4D[] destinationArray)`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|static [`void Transform(Vector4D[] sourceArray, int sourceIndex, ref MatrixD matrix, Vector4D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|static [`void Transform(Vector4D[] sourceArray, ref Quaternion rotation, Vector4D[] destinationArray)`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|static [`void Transform(Vector4D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|static [`Vector4D Negate(Vector4D value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref Vector4D value, ref Vector4D result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Vector4D Add(Vector4D value1, Vector4D value2)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Add)|Adds two vectors.|
|static [`Vector4 Subtract(Vector4 value1, Vector4 value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Vector4D Multiply(Vector4D value1, Vector4D value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Vector4D Multiply(Vector4D value1, double scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar.|
|static [`void Multiply(ref Vector4D value1, double scaleFactor, ref Vector4D result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Vector4D Divide(Vector4D value1, Vector4D value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Vector4D Divide(Vector4D value1, double divider)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref Vector4D value1, double divider, ref Vector4D result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
