← [Index](index)
# Vector2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|static [`Zero`](VRageMath.Zero)||
|static [`One`](VRageMath.One)||
|static [`UnitX`](VRageMath.UnitX)||
|static [`UnitY`](VRageMath.UnitY)||
|static [`PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`Equals(Vector2)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2.|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of the vector object.|
|[`IsValid()`](VRageMath.IsValid)||
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|[`Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`Distance(Vector2, Vector2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`Distance(ref Vector2, ref Vector2, ref float)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`DistanceSquared(Vector2, Vector2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`DistanceSquared(ref Vector2, ref Vector2, ref float)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`Dot(Vector2, Vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`Dot(ref Vector2, ref Vector2, ref float)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Normalize(Vector2)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Normalize(ref Vector2, ref Vector2)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Reflect(Vector2, Vector2)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`Reflect(ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`Min(Vector2, Vector2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Min(ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Max(Vector2, Vector2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Max(ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Clamp(Vector2, Vector2, Vector2)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Clamp(ref Vector2, ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`ClampToSphere(Vector2, float)`](VRageMath.ClampToSphere)||
|static [`ClampToSphere(ref Vector2, float)`](VRageMath.ClampToSphere)||
|static [`Lerp(Vector2, Vector2, float)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Lerp(ref Vector2, ref Vector2, float, ref Vector2)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Barycentric(Vector2, Vector2, Vector2, float, float)`](VRageMath.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`Barycentric(ref Vector2, ref Vector2, ref Vector2, float, float, ref Vector2)`](VRageMath.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`SmoothStep(Vector2, Vector2, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`SmoothStep(ref Vector2, ref Vector2, float, ref Vector2)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`CatmullRom(Vector2, Vector2, Vector2, Vector2, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`CatmullRom(ref Vector2, ref Vector2, ref Vector2, ref Vector2, float, ref Vector2)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Hermite(Vector2, Vector2, Vector2, Vector2, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Hermite(ref Vector2, ref Vector2, ref Vector2, ref Vector2, float, ref Vector2)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Transform(Vector2, Matrix)`](VRageMath.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|static [`Transform(ref Vector2, ref Matrix, ref Vector2)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static [`TransformNormal(Vector2, Matrix)`](VRageMath.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|static [`TransformNormal(ref Vector2, ref Matrix, ref Vector2)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`Transform(Vector2, Quaternion)`](VRageMath.Transform)|Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`Transform(ref Vector2, ref Quaternion, ref Vector2)`](VRageMath.Transform)|Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`Transform(Vector2[], ref Matrix, Vector2[])`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|static [`Transform(Vector2[], int, ref Matrix, Vector2[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|static [`TransformNormal(Vector2[], ref Matrix, Vector2[])`](VRageMath.TransformNormal)|Transforms an array of Vector2 vector normals by a specified Matrix.|
|static [`TransformNormal(Vector2[], int, ref Matrix, Vector2[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|static [`Transform(Vector2[], ref Quaternion, Vector2[])`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|static [`Transform(Vector2[], int, ref Quaternion, Vector2[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|static [`Negate(Vector2)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Negate(ref Vector2, ref Vector2)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Add(Vector2, Vector2)`](VRageMath.Add)|Adds two vectors.|
|static [`Add(ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Add)|Adds two vectors.|
|static [`Subtract(Vector2, Vector2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Subtract(ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Multiply(Vector2, Vector2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Multiply(ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Multiply(Vector2, float)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Multiply(ref Vector2, float, ref Vector2)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Divide(Vector2, Vector2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Divide(ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Divide(Vector2, float)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`Divide(ref Vector2, float, ref Vector2)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`Between(ref Vector2, ref Vector2)`](VRageMath.Between)||
|static [`Floor(Vector2)`](VRageMath.Floor)||
|[`Rotate(double)`](VRageMath.Rotate)||
|static [`IsZero(ref Vector2)`](VRageMath.IsZero)||
|static [`IsZero(ref Vector2, float)`](VRageMath.IsZero)||
|static [`IsZero(Vector2, float)`](VRageMath.IsZero)||
|static [`SignNonZero(Vector2)`](VRageMath.SignNonZero)||
