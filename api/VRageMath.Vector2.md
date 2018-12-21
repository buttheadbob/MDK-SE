← [Index](index)
# Vector2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`float Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|static [`VRageMath.Vector2 Zero`](VRageMath.Zero)||
|static [`VRageMath.Vector2 One`](VRageMath.One)||
|static [`VRageMath.Vector2 UnitX`](VRageMath.UnitX)||
|static [`VRageMath.Vector2 UnitY`](VRageMath.UnitY)||
|static [`VRageMath.Vector2 PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(VRageMath.Vector2)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of the vector object.|
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`float Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`float Distance(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref VRageMath.Vector2, ref VRageMath.Vector2, ref float)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`float DistanceSquared(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref VRageMath.Vector2, ref VRageMath.Vector2, ref float)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`float Dot(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`void Dot(ref VRageMath.Vector2, ref VRageMath.Vector2, ref float)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`void Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector2 Normalize(VRageMath.Vector2)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`void Normalize(ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector2 Reflect(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`void Reflect(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`VRageMath.Vector2 Min(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`VRageMath.Vector2 Max(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`VRageMath.Vector2 Clamp(VRageMath.Vector2, VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`VRageMath.Vector2 ClampToSphere(VRageMath.Vector2, float)`](VRageMath.ClampToSphere)||
|static [`void ClampToSphere(ref VRageMath.Vector2, float)`](VRageMath.ClampToSphere)||
|static [`VRageMath.Vector2 Lerp(VRageMath.Vector2, VRageMath.Vector2, float)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref VRageMath.Vector2, ref VRageMath.Vector2, float, ref VRageMath.Vector2)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`VRageMath.Vector2 Barycentric(VRageMath.Vector2, VRageMath.Vector2, VRageMath.Vector2, float, float)`](VRageMath.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`void Barycentric(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2, float, float, ref VRageMath.Vector2)`](VRageMath.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`VRageMath.Vector2 SmoothStep(VRageMath.Vector2, VRageMath.Vector2, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref VRageMath.Vector2, ref VRageMath.Vector2, float, ref VRageMath.Vector2)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`VRageMath.Vector2 CatmullRom(VRageMath.Vector2, VRageMath.Vector2, VRageMath.Vector2, VRageMath.Vector2, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2, float, ref VRageMath.Vector2)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`VRageMath.Vector2 Hermite(VRageMath.Vector2, VRageMath.Vector2, VRageMath.Vector2, VRageMath.Vector2, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2, float, ref VRageMath.Vector2)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`VRageMath.Vector2 Transform(VRageMath.Vector2, VRageMath.Matrix)`](VRageMath.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|static [`void Transform(ref VRageMath.Vector2, ref VRageMath.Matrix, ref VRageMath.Vector2)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`VRageMath.Vector2 TransformNormal(VRageMath.Vector2, VRageMath.Matrix)`](VRageMath.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|static [`void TransformNormal(ref VRageMath.Vector2, ref VRageMath.Matrix, ref VRageMath.Vector2)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`VRageMath.Vector2 Transform(VRageMath.Vector2, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`void Transform(ref VRageMath.Vector2, ref VRageMath.Quaternion, ref VRageMath.Vector2)`](VRageMath.Transform)|Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`void Transform(VRageMath.Vector2[], ref VRageMath.Matrix, VRageMath.Vector2[])`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|static [`void Transform(VRageMath.Vector2[], int, ref VRageMath.Matrix, VRageMath.Vector2[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|static [`void TransformNormal(VRageMath.Vector2[], ref VRageMath.Matrix, VRageMath.Vector2[])`](VRageMath.TransformNormal)|Transforms an array of Vector2 vector normals by a specified Matrix.|
|static [`void TransformNormal(VRageMath.Vector2[], int, ref VRageMath.Matrix, VRageMath.Vector2[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|static [`void Transform(VRageMath.Vector2[], ref VRageMath.Quaternion, VRageMath.Vector2[])`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|static [`void Transform(VRageMath.Vector2[], int, ref VRageMath.Quaternion, VRageMath.Vector2[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|static [`VRageMath.Vector2 Negate(VRageMath.Vector2)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`VRageMath.Vector2 Add(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Add)|Adds two vectors.|
|static [`VRageMath.Vector2 Subtract(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`VRageMath.Vector2 Multiply(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`VRageMath.Vector2 Multiply(VRageMath.Vector2, float)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`void Multiply(ref VRageMath.Vector2, float, ref VRageMath.Vector2)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`VRageMath.Vector2 Divide(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`VRageMath.Vector2 Divide(VRageMath.Vector2, float)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref VRageMath.Vector2, float, ref VRageMath.Vector2)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`bool Between(ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Between)||
|static [`VRageMath.Vector2 Floor(VRageMath.Vector2)`](VRageMath.Floor)||
|[`void Rotate(double)`](VRageMath.Rotate)||
|static [`bool IsZero(ref VRageMath.Vector2)`](VRageMath.IsZero)||
|static [`bool IsZero(ref VRageMath.Vector2, float)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.Vector2, float)`](VRageMath.IsZero)||
|static [`VRageMath.Vector2 SignNonZero(VRageMath.Vector2)`](VRageMath.SignNonZero)||
