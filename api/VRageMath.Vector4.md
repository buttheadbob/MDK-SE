← [Index](ApiIndex)
# Vector4 Struct
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
|[`Zero`](VRageMath.Zero)||
|[`One`](VRageMath.One)||
|[`UnitX`](VRageMath.UnitX)||
|[`UnitY`](VRageMath.UnitY)||
|[`UnitZ`](VRageMath.UnitZ)||
|[`UnitW`](VRageMath.UnitW)||
### Properties
|Member|Description|
|---|---|
|[`Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`PackOrthoMatrix(Vector3, Vector3, Vector3)`](VRageMath.PackOrthoMatrix)||
|[`PackOrthoMatrix(ref Matrix)`](VRageMath.PackOrthoMatrix)||
|[`UnpackOrthoMatrix(ref Vector4)`](VRageMath.UnpackOrthoMatrix)||
|[`UnpackOrthoMatrix(ref Vector4, ref Matrix)`](VRageMath.UnpackOrthoMatrix)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`Equals(Vector4)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|[`Distance(Vector4, Vector4)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|[`Distance(ref Vector4, ref Vector4, ref float)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|[`DistanceSquared(Vector4, Vector4)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|[`DistanceSquared(ref Vector4, ref Vector4, ref float)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|[`Dot(Vector4, Vector4)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`Dot(ref Vector4, ref Vector4, ref float)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector.|
|[`Normalize(Vector4)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|[`Normalize(ref Vector4, ref Vector4)`](VRageMath.Normalize)|Returns a normalized version of the specified vector.|
|[`Min(Vector4, Vector4)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[`Min(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[`Max(Vector4, Vector4)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[`Max(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[`Clamp(Vector4, Vector4, Vector4)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|[`Clamp(ref Vector4, ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|[`Lerp(Vector4, Vector4, float)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|[`Lerp(ref Vector4, ref Vector4, float, ref Vector4)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|[`Barycentric(Vector4, Vector4, Vector4, float, float)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|[`Barycentric(ref Vector4, ref Vector4, ref Vector4, float, float, ref Vector4)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|[`SmoothStep(Vector4, Vector4, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|[`SmoothStep(ref Vector4, ref Vector4, float, ref Vector4)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|[`CatmullRom(Vector4, Vector4, Vector4, Vector4, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[`CatmullRom(ref Vector4, ref Vector4, ref Vector4, ref Vector4, float, ref Vector4)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[`Hermite(Vector4, Vector4, Vector4, Vector4, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|[`Hermite(ref Vector4, ref Vector4, ref Vector4, ref Vector4, float, ref Vector4)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|[`Transform(Vector2, Matrix)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|[`Transform(ref Vector2, ref Matrix, ref Vector4)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|[`Transform(Vector3, Matrix)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|[`Transform(ref Vector3, ref Matrix, ref Vector4)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|[`Transform(Vector4, Matrix)`](VRageMath.Transform)|Transforms a Vector4 by the specified Matrix.|
|[`Transform(ref Vector4, ref Matrix, ref Vector4)`](VRageMath.Transform)|Transforms a Vector4 by the given Matrix.|
|[`Transform(Vector2, Quaternion)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|[`Transform(ref Vector2, ref Quaternion, ref Vector4)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|[`Transform(Vector3, Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|[`Transform(ref Vector3, ref Quaternion, ref Vector4)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|[`Transform(Vector4, Quaternion)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|[`Transform(ref Vector4, ref Quaternion, ref Vector4)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|[`Transform(Vector4[], ref Matrix, Vector4[])`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|[`Transform(Vector4[], int, ref Matrix, Vector4[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|[`Transform(Vector4[], ref Quaternion, Vector4[])`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|[`Transform(Vector4[], int, ref Quaternion, Vector4[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|[`Negate(Vector4)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`Negate(ref Vector4, ref Vector4)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`Add(Vector4, Vector4)`](VRageMath.Add)|Adds two vectors.|
|[`Add(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Add)|Adds two vectors.|
|[`Subtract(Vector4, Vector4)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|[`Subtract(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|[`Multiply(Vector4, Vector4)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|[`Multiply(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|[`Multiply(Vector4, float)`](VRageMath.Multiply)|Multiplies a vector by a scalar.|
|[`Multiply(ref Vector4, float, ref Vector4)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|[`Divide(Vector4, Vector4)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|[`Divide(ref Vector4, ref Vector4, ref Vector4)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|[`Divide(Vector4, float)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`Divide(ref Vector4, float, ref Vector4)`](VRageMath.Divide)|Divides a vector by a scalar value.|
