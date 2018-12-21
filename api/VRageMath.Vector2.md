← [Index](index)
# Vector2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`float Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|static [`Vector2 Zero`](VRageMath.Zero)||
|static [`Vector2 One`](VRageMath.One)||
|static [`Vector2 UnitX`](VRageMath.UnitX)||
|static [`Vector2 UnitY`](VRageMath.UnitY)||
|static [`Vector2 PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(Vector2 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of the vector object.|
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`float Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`float Distance(Vector2 value1, Vector2 value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`float DistanceSquared(Vector2 value1, Vector2 value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`float Dot(Vector2 value1, Vector2 value2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`void Dot(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`void Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector2 Normalize(Vector2 value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`void Normalize(ref Vector2 value, ref Vector2 result)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector2 Reflect(Vector2 vector, Vector2 normal)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`void Reflect(ref Vector2 vector, ref Vector2 normal, ref Vector2 result)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`Vector2 Min(Vector2 value1, Vector2 value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Vector2 Max(Vector2 value1, Vector2 value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Vector2 Clamp(Vector2 value1, Vector2 min, Vector2 max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref Vector2 value1, ref Vector2 min, ref Vector2 max, ref Vector2 result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Vector2 ClampToSphere(Vector2 vector, float radius)`](VRageMath.ClampToSphere)||
|static [`void ClampToSphere(ref Vector2 vector, float radius)`](VRageMath.ClampToSphere)||
|static [`Vector2 Lerp(Vector2 value1, Vector2 value2, float amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Vector2 Barycentric(Vector2 value1, Vector2 value2, Vector2 value3, float amount1, float amount2)`](VRageMath.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`void Barycentric(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, float amount1, float amount2, ref Vector2 result)`](VRageMath.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`Vector2 SmoothStep(Vector2 value1, Vector2 value2, float amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`Vector2 CatmullRom(Vector2 value1, Vector2 value2, Vector2 value3, Vector2 value4, float amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, ref Vector2 value4, float amount, ref Vector2 result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Vector2 Hermite(Vector2 value1, Vector2 tangent1, Vector2 value2, Vector2 tangent2, float amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref Vector2 value1, ref Vector2 tangent1, ref Vector2 value2, ref Vector2 tangent2, float amount, ref Vector2 result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Vector2 Transform(Vector2 position, Matrix matrix)`](VRageMath.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|static [`void Transform(ref Vector2 position, ref Matrix matrix, ref Vector2 result)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`Vector2 TransformNormal(Vector2 normal, Matrix matrix)`](VRageMath.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|static [`void TransformNormal(ref Vector2 normal, ref Matrix matrix, ref Vector2 result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`Vector2 Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)|Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector2 result)`](VRageMath.Transform)|Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`void Transform(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|static [`void Transform(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|static [`void TransformNormal(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)`](VRageMath.TransformNormal)|Transforms an array of Vector2 vector normals by a specified Matrix.|
|static [`void TransformNormal(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)|Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|static [`void Transform(Vector2[] sourceArray, ref Quaternion rotation, Vector2[] destinationArray)`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|static [`void Transform(Vector2[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|static [`Vector2 Negate(Vector2 value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref Vector2 value, ref Vector2 result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Vector2 Add(Vector2 value1, Vector2 value2)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Add)|Adds two vectors.|
|static [`Vector2 Subtract(Vector2 value1, Vector2 value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Vector2 Multiply(Vector2 value1, Vector2 value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Vector2 Multiply(Vector2 value1, float scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`void Multiply(ref Vector2 value1, float scaleFactor, ref Vector2 result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Vector2 Divide(Vector2 value1, Vector2 value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Vector2 Divide(Vector2 value1, float divider)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref Vector2 value1, float divider, ref Vector2 result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`bool Between(ref Vector2 start, ref Vector2 end)`](VRageMath.Between)||
|static [`Vector2 Floor(Vector2 position)`](VRageMath.Floor)||
|[`void Rotate(double angle)`](VRageMath.Rotate)||
|static [`bool IsZero(ref Vector2 value)`](VRageMath.IsZero)||
|static [`bool IsZero(ref Vector2 value, float epsilon)`](VRageMath.IsZero)||
|static [`bool IsZero(Vector2 value, float epsilon)`](VRageMath.IsZero)||
|static [`Vector2 SignNonZero(Vector2 value)`](VRageMath.SignNonZero)||
