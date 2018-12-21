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
|static [`VRageMath.Vector4D Zero`](VRageMath.Zero)||
|static [`VRageMath.Vector4D One`](VRageMath.One)||
|static [`VRageMath.Vector4D UnitX`](VRageMath.UnitX)||
|static [`VRageMath.Vector4D UnitY`](VRageMath.UnitY)||
|static [`VRageMath.Vector4D UnitZ`](VRageMath.UnitZ)||
|static [`VRageMath.Vector4D UnitW`](VRageMath.UnitW)||
### Methods
|Member|Description|
|---|---|
|static [`VRageMath.Vector4D PackOrthoMatrix(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.PackOrthoMatrix)||
|static [`VRageMath.Vector4D PackOrthoMatrix(ref VRageMath.MatrixD)`](VRageMath.PackOrthoMatrix)||
|static [`VRageMath.MatrixD UnpackOrthoMatrix(ref VRageMath.Vector4D)`](VRageMath.UnpackOrthoMatrix)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(VRageMath.Vector4)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`double Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`double Distance(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref VRageMath.Vector4, ref VRageMath.Vector4, ref double)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`double DistanceSquared(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref VRageMath.Vector4, ref VRageMath.Vector4, ref double)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`double Dot(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|static [`void Dot(ref VRageMath.Vector4, ref VRageMath.Vector4, ref double)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`void Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector.|
|static [`VRageMath.Vector4D Normalize(VRageMath.Vector4D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|static [`void Normalize(ref VRageMath.Vector4D, ref VRageMath.Vector4D)`](VRageMath.Normalize)|Returns a normalized version of the specified vector.|
|static [`VRageMath.Vector4 Min(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`VRageMath.Vector4 Max(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`VRageMath.Vector4D Clamp(VRageMath.Vector4D, VRageMath.Vector4D, VRageMath.Vector4D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`VRageMath.Vector4D Lerp(VRageMath.Vector4D, VRageMath.Vector4D, double)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref VRageMath.Vector4D, ref VRageMath.Vector4D, double, ref VRageMath.Vector4D)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`VRageMath.Vector4D Barycentric(VRageMath.Vector4D, VRageMath.Vector4D, VRageMath.Vector4D, double, double)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|static [`void Barycentric(ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D, double, double, ref VRageMath.Vector4D)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|static [`VRageMath.Vector4D SmoothStep(VRageMath.Vector4D, VRageMath.Vector4D, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref VRageMath.Vector4D, ref VRageMath.Vector4D, double, ref VRageMath.Vector4D)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`VRageMath.Vector4D CatmullRom(VRageMath.Vector4D, VRageMath.Vector4D, VRageMath.Vector4D, VRageMath.Vector4D, double)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D, double, ref VRageMath.Vector4D)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`VRageMath.Vector4D Hermite(VRageMath.Vector4D, VRageMath.Vector4D, VRageMath.Vector4D, VRageMath.Vector4D, double)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D, double, ref VRageMath.Vector4D)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`VRageMath.Vector4D Transform(VRageMath.Vector2, VRageMath.MatrixD)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`void Transform(ref VRageMath.Vector2, ref VRageMath.MatrixD, ref VRageMath.Vector4D)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`VRageMath.Vector4D Transform(VRageMath.Vector3D, VRageMath.MatrixD)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`void Transform(ref VRageMath.Vector3D, ref VRageMath.MatrixD, ref VRageMath.Vector4D)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`VRageMath.Vector4D Transform(VRageMath.Vector4D, VRageMath.MatrixD)`](VRageMath.Transform)|Transforms a Vector4 by the specified Matrix.|
|static [`void Transform(ref VRageMath.Vector4D, ref VRageMath.MatrixD, ref VRageMath.Vector4D)`](VRageMath.Transform)|Transforms a Vector4 by the given Matrix.|
|static [`VRageMath.Vector4D Transform(VRageMath.Vector2, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`void Transform(ref VRageMath.Vector2, ref VRageMath.Quaternion, ref VRageMath.Vector4D)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`VRageMath.Vector4D Transform(VRageMath.Vector3D, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`void Transform(ref VRageMath.Vector3D, ref VRageMath.Quaternion, ref VRageMath.Vector4D)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`VRageMath.Vector4D Transform(VRageMath.Vector4D, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`void Transform(ref VRageMath.Vector4D, ref VRageMath.Quaternion, ref VRageMath.Vector4D)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`void Transform(VRageMath.Vector4D[], ref VRageMath.MatrixD, VRageMath.Vector4D[])`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|static [`void Transform(VRageMath.Vector4D[], int, ref VRageMath.MatrixD, VRageMath.Vector4D[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|static [`void Transform(VRageMath.Vector4D[], ref VRageMath.Quaternion, VRageMath.Vector4D[])`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|static [`void Transform(VRageMath.Vector4D[], int, ref VRageMath.Quaternion, VRageMath.Vector4D[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|static [`VRageMath.Vector4D Negate(VRageMath.Vector4D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref VRageMath.Vector4D, ref VRageMath.Vector4D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`VRageMath.Vector4D Add(VRageMath.Vector4D, VRageMath.Vector4D)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D)`](VRageMath.Add)|Adds two vectors.|
|static [`VRageMath.Vector4 Subtract(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`VRageMath.Vector4D Multiply(VRageMath.Vector4D, VRageMath.Vector4D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`VRageMath.Vector4D Multiply(VRageMath.Vector4D, double)`](VRageMath.Multiply)|Multiplies a vector by a scalar.|
|static [`void Multiply(ref VRageMath.Vector4D, double, ref VRageMath.Vector4D)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`VRageMath.Vector4D Divide(VRageMath.Vector4D, VRageMath.Vector4D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref VRageMath.Vector4D, ref VRageMath.Vector4D, ref VRageMath.Vector4D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`VRageMath.Vector4D Divide(VRageMath.Vector4D, double)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref VRageMath.Vector4D, double, ref VRageMath.Vector4D)`](VRageMath.Divide)|Divides a vector by a scalar value.|
