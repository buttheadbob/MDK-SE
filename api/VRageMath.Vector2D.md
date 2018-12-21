← [Index](index)
# Vector2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`double Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|static [`VRageMath.Vector2D Zero`](VRageMath.Zero)||
|static [`VRageMath.Vector2D One`](VRageMath.One)||
|static [`VRageMath.Vector2D UnitX`](VRageMath.UnitX)||
|static [`VRageMath.Vector2D UnitY`](VRageMath.UnitY)||
|static [`VRageMath.Vector2D PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`double Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(VRageMath.Vector2D)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2D.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of the vector object.|
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`double Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`double Distance(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref double)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`double DistanceSquared(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref double)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`double Dot(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`void Dot(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref double)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`void Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector2D Normalize(VRageMath.Vector2D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`void Normalize(ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector2D Reflect(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`void Reflect(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`VRageMath.Vector2D Min(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`VRageMath.Vector2D Max(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`VRageMath.Vector2D Clamp(VRageMath.Vector2D, VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`VRageMath.Vector2D ClampToSphere(VRageMath.Vector2D, double)`](VRageMath.ClampToSphere)||
|static [`void ClampToSphere(ref VRageMath.Vector2D, double)`](VRageMath.ClampToSphere)||
|static [`VRageMath.Vector2D Lerp(VRageMath.Vector2D, VRageMath.Vector2D, double)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref VRageMath.Vector2D, ref VRageMath.Vector2D, double, ref VRageMath.Vector2D)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`VRageMath.Vector2D Barycentric(VRageMath.Vector2D, VRageMath.Vector2D, VRageMath.Vector2D, double, double)`](VRageMath.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`void Barycentric(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D, double, double, ref VRageMath.Vector2D)`](VRageMath.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`VRageMath.Vector2D SmoothStep(VRageMath.Vector2D, VRageMath.Vector2D, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref VRageMath.Vector2D, ref VRageMath.Vector2D, double, ref VRageMath.Vector2D)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`VRageMath.Vector2D CatmullRom(VRageMath.Vector2D, VRageMath.Vector2D, VRageMath.Vector2D, VRageMath.Vector2D, double)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D, double, ref VRageMath.Vector2D)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`VRageMath.Vector2D Hermite(VRageMath.Vector2D, VRageMath.Vector2D, VRageMath.Vector2D, VRageMath.Vector2D, double)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D, double, ref VRageMath.Vector2D)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`VRageMath.Vector2D Transform(VRageMath.Vector2D, VRageMath.Matrix)`](VRageMath.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|static [`void Transform(ref VRageMath.Vector2D, ref VRageMath.Matrix, ref VRageMath.Vector2D)`](VRageMath.Transform)|Transforms a Vector2D by the given Matrix.|
|static [`VRageMath.Vector2D TransformNormal(VRageMath.Vector2D, VRageMath.Matrix)`](VRageMath.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|static [`void TransformNormal(ref VRageMath.Vector2D, ref VRageMath.Matrix, ref VRageMath.Vector2D)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`VRageMath.Vector2D Transform(VRageMath.Vector2D, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`void Transform(ref VRageMath.Vector2D, ref VRageMath.Quaternion, ref VRageMath.Vector2D)`](VRageMath.Transform)|Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`void Transform(VRageMath.Vector2D[], ref VRageMath.Matrix, VRageMath.Vector2D[])`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|static [`void Transform(VRageMath.Vector2D[], int, ref VRageMath.Matrix, VRageMath.Vector2D[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|static [`void TransformNormal(VRageMath.Vector2D[], ref VRageMath.Matrix, VRageMath.Vector2D[])`](VRageMath.TransformNormal)|Transforms an array of Vector2D vector normals by a specified Matrix.|
|static [`void TransformNormal(VRageMath.Vector2D[], int, ref VRageMath.Matrix, VRageMath.Vector2D[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of Vector2D vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|static [`void Transform(VRageMath.Vector2D[], ref VRageMath.Quaternion, VRageMath.Vector2D[])`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|static [`void Transform(VRageMath.Vector2D[], int, ref VRageMath.Quaternion, VRageMath.Vector2D[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|static [`VRageMath.Vector2D Negate(VRageMath.Vector2D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`VRageMath.Vector2D Add(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Add)|Adds two vectors.|
|static [`VRageMath.Vector2D Subtract(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`VRageMath.Vector2D Multiply(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`VRageMath.Vector2D Multiply(VRageMath.Vector2D, double)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`void Multiply(ref VRageMath.Vector2D, double, ref VRageMath.Vector2D)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`VRageMath.Vector2D Divide(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`VRageMath.Vector2D Divide(VRageMath.Vector2D, double)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref VRageMath.Vector2D, double, ref VRageMath.Vector2D)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`bool Between(ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Between)||
|static [`VRageMath.Vector2D Floor(VRageMath.Vector2D)`](VRageMath.Floor)||
|[`void Rotate(double)`](VRageMath.Rotate)||
