← [Index](index)
# Vector4 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`float Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`float Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|[`float W`](VRageMath.W)|Gets or sets the w-component of the vector.|
|static [`VRageMath.Vector4 Zero`](VRageMath.Zero)||
|static [`VRageMath.Vector4 One`](VRageMath.One)||
|static [`VRageMath.Vector4 UnitX`](VRageMath.UnitX)||
|static [`VRageMath.Vector4 UnitY`](VRageMath.UnitY)||
|static [`VRageMath.Vector4 UnitZ`](VRageMath.UnitZ)||
|static [`VRageMath.Vector4 UnitW`](VRageMath.UnitW)||
### Properties
|Member|Description|
|---|---|
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static [`VRageMath.Vector4 PackOrthoMatrix(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.PackOrthoMatrix)||
|static [`VRageMath.Vector4 PackOrthoMatrix(ref VRageMath.Matrix)`](VRageMath.PackOrthoMatrix)||
|static [`VRageMath.Matrix UnpackOrthoMatrix(ref VRageMath.Vector4)`](VRageMath.UnpackOrthoMatrix)||
|static [`void UnpackOrthoMatrix(ref VRageMath.Vector4, ref VRageMath.Matrix)`](VRageMath.UnpackOrthoMatrix)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(VRageMath.Vector4)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`float Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`float Distance(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref VRageMath.Vector4, ref VRageMath.Vector4, ref float)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`float DistanceSquared(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref VRageMath.Vector4, ref VRageMath.Vector4, ref float)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`float Dot(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|static [`void Dot(ref VRageMath.Vector4, ref VRageMath.Vector4, ref float)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`void Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector.|
|static [`VRageMath.Vector4 Normalize(VRageMath.Vector4)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|static [`void Normalize(ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Normalize)|Returns a normalized version of the specified vector.|
|static [`VRageMath.Vector4 Min(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`VRageMath.Vector4 Max(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`VRageMath.Vector4 Clamp(VRageMath.Vector4, VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`VRageMath.Vector4 Lerp(VRageMath.Vector4, VRageMath.Vector4, float)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref VRageMath.Vector4, ref VRageMath.Vector4, float, ref VRageMath.Vector4)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`VRageMath.Vector4 Barycentric(VRageMath.Vector4, VRageMath.Vector4, VRageMath.Vector4, float, float)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|static [`void Barycentric(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4, float, float, ref VRageMath.Vector4)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|static [`VRageMath.Vector4 SmoothStep(VRageMath.Vector4, VRageMath.Vector4, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref VRageMath.Vector4, ref VRageMath.Vector4, float, ref VRageMath.Vector4)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`VRageMath.Vector4 CatmullRom(VRageMath.Vector4, VRageMath.Vector4, VRageMath.Vector4, VRageMath.Vector4, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4, float, ref VRageMath.Vector4)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`VRageMath.Vector4 Hermite(VRageMath.Vector4, VRageMath.Vector4, VRageMath.Vector4, VRageMath.Vector4, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4, float, ref VRageMath.Vector4)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`VRageMath.Vector4 Transform(VRageMath.Vector2, VRageMath.Matrix)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`void Transform(ref VRageMath.Vector2, ref VRageMath.Matrix, ref VRageMath.Vector4)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`VRageMath.Vector4 Transform(VRageMath.Vector3, VRageMath.Matrix)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`void Transform(ref VRageMath.Vector3, ref VRageMath.Matrix, ref VRageMath.Vector4)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`VRageMath.Vector4 Transform(VRageMath.Vector4, VRageMath.Matrix)`](VRageMath.Transform)|Transforms a Vector4 by the specified Matrix.|
|static [`void Transform(ref VRageMath.Vector4, ref VRageMath.Matrix, ref VRageMath.Vector4)`](VRageMath.Transform)|Transforms a Vector4 by the given Matrix.|
|static [`VRageMath.Vector4 Transform(VRageMath.Vector2, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`void Transform(ref VRageMath.Vector2, ref VRageMath.Quaternion, ref VRageMath.Vector4)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static [`VRageMath.Vector4 Transform(VRageMath.Vector3, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`void Transform(ref VRageMath.Vector3, ref VRageMath.Quaternion, ref VRageMath.Vector4)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static [`VRageMath.Vector4 Transform(VRageMath.Vector4, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`void Transform(ref VRageMath.Vector4, ref VRageMath.Quaternion, ref VRageMath.Vector4)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static [`void Transform(VRageMath.Vector4[], ref VRageMath.Matrix, VRageMath.Vector4[])`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|static [`void Transform(VRageMath.Vector4[], int, ref VRageMath.Matrix, VRageMath.Vector4[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|static [`void Transform(VRageMath.Vector4[], ref VRageMath.Quaternion, VRageMath.Vector4[])`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|static [`void Transform(VRageMath.Vector4[], int, ref VRageMath.Quaternion, VRageMath.Vector4[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|static [`VRageMath.Vector4 Negate(VRageMath.Vector4)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`VRageMath.Vector4 Add(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Add)|Adds two vectors.|
|static [`VRageMath.Vector4 Subtract(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`VRageMath.Vector4 Multiply(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`VRageMath.Vector4 Multiply(VRageMath.Vector4, float)`](VRageMath.Multiply)|Multiplies a vector by a scalar.|
|static [`void Multiply(ref VRageMath.Vector4, float, ref VRageMath.Vector4)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`VRageMath.Vector4 Divide(VRageMath.Vector4, VRageMath.Vector4)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref VRageMath.Vector4, ref VRageMath.Vector4, ref VRageMath.Vector4)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`VRageMath.Vector4 Divide(VRageMath.Vector4, float)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref VRageMath.Vector4, float, ref VRageMath.Vector4)`](VRageMath.Divide)|Divides a vector by a scalar value.|
