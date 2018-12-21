← [Index](index)
# Vector4D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|[`W`](VRageMath.W)|Gets or sets the w-component of the vector.|
|static [`Zero`](VRageMath.Zero)||
|static [`One`](VRageMath.One)||
|static [`UnitX`](VRageMath.UnitX)||
|static [`UnitY`](VRageMath.UnitY)||
|static [`UnitZ`](VRageMath.UnitZ)||
|static [`UnitW`](VRageMath.UnitW)||
### Methods
|Member|Description|
|---|---|
|static [`PackOrthoMatrix(Vector3D, Vector3D, Vector3D)`](VRageMath.PackOrthoMatrix)||
|static [`PackOrthoMatrix(ref MatrixD)`](VRageMath.PackOrthoMatrix)||
|static [`UnpackOrthoMatrix(ref Vector4D)`](VRageMath.UnpackOrthoMatrix)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`Equals(Vector4)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`Distance(Vector4, Vector4)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`Distance(ref Vector4, ref Vector4, ref double)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`DistanceSquared(Vector4, Vector4)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`DistanceSquared(ref Vector4, ref Vector4, ref double)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`Dot(Vector4, Vector4)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|static [`Dot(ref Vector4, ref Vector4, ref double)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector.|
|static [`Normalize(Vector4D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|static [`Normalize(ref Vector4D, ref Vector4D)`](VRageMath.Normalize)|Returns a normalized version of the specified vector.|
|static [`Min(Vector4, Vector4)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Min(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Max(Vector4, Vector4)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Max(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Clamp(Vector4D, Vector4D, Vector4D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Clamp(ref Vector4D, ref Vector4D, ref Vector4D, ref Vector4D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Lerp(Vector4D, Vector4D, double)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Lerp(ref Vector4D, ref Vector4D, double, ref Vector4D)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Barycentric(Vector4D, Vector4D, Vector4D, double, double)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|static [`Barycentric(ref Vector4D, ref Vector4D, ref Vector4D, double, double, ref Vector4D)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|static [`SmoothStep(Vector4D, Vector4D, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`SmoothStep(ref Vector4D, ref Vector4D, double, ref Vector4D)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`CatmullRom(Vector4D, Vector4D, Vector4D, Vector4D, double)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`CatmullRom(ref Vector4D, ref Vector4D, ref Vector4D, ref Vector4D, double, ref Vector4D)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Hermite(Vector4D, Vector4D, Vector4D, Vector4D, double)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Hermite(ref Vector4D, ref Vector4D, ref Vector4D, ref Vector4D, double, ref Vector4D)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Transform(Vector2, MatrixD)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`Transform(ref Vector2, ref MatrixD, ref Vector4D)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`Transform(Vector3D, MatrixD)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`Transform(ref Vector3D, ref MatrixD, ref Vector4D)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`Transform(Vector4D, MatrixD)`](VRageMath.Transform)|Transforms a Vector4 by the specified Matrix.|
|static [`Transform(ref Vector4D, ref MatrixD, ref Vector4D)`](VRageMath.Transform)|Transforms a Vector4 by the given Matrix.|
|static [`Transform(Vector2, Quaternion)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`Transform(ref Vector2, ref Quaternion, ref Vector4D)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`Transform(Vector3D, Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`Transform(ref Vector3D, ref Quaternion, ref Vector4D)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`Transform(Vector4D, Quaternion)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`Transform(ref Vector4D, ref Quaternion, ref Vector4D)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`Transform(Vector4D[], ref MatrixD, Vector4D[])`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|static [`Transform(Vector4D[], int, ref MatrixD, Vector4D[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|static [`Transform(Vector4D[], ref Quaternion, Vector4D[])`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|static [`Transform(Vector4D[], int, ref Quaternion, Vector4D[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|static [`Negate(Vector4D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Negate(ref Vector4D, ref Vector4D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Add(Vector4D, Vector4D)`](VRageMath.Add)|Adds two vectors.|
|static [`Add(ref Vector4D, ref Vector4D, ref Vector4D)`](VRageMath.Add)|Adds two vectors.|
|static [`Subtract(Vector4, Vector4)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Subtract(ref Vector4D, ref Vector4D, ref Vector4D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Multiply(Vector4D, Vector4D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Multiply(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Multiply(Vector4D, double)`](VRageMath.Multiply)|Multiplies a vector by a scalar.|
|static [`Multiply(ref Vector4D, double, ref Vector4D)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Divide(Vector4D, Vector4D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Divide(ref Vector4D, ref Vector4D, ref Vector4D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Divide(Vector4D, double)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`Divide(ref Vector4D, double, ref Vector4D)`](VRageMath.Divide)|Divides a vector by a scalar value.|
