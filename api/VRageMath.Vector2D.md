← [Index](index)
# Vector2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`Zero`](VRageMath.Zero)||
|[`One`](VRageMath.One)||
|[`UnitX`](VRageMath.UnitX)||
|[`UnitY`](VRageMath.UnitY)||
|[`PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`Equals(Vector2D)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2D.|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of the vector object.|
|[`IsValid()`](VRageMath.IsValid)||
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|[`Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|[`Distance(Vector2D, Vector2D)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|[`Distance(ref Vector2D, ref Vector2D, ref double)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|[`DistanceSquared(Vector2D, Vector2D)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|[`DistanceSquared(ref Vector2D, ref Vector2D, ref double)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|[`Dot(Vector2D, Vector2D)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`Dot(ref Vector2D, ref Vector2D, ref double)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`Normalize(Vector2D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`Normalize(ref Vector2D, ref Vector2D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`Reflect(Vector2D, Vector2D)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|[`Reflect(ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|[`Min(Vector2D, Vector2D)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[`Min(ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[`Max(Vector2D, Vector2D)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[`Max(ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[`Clamp(Vector2D, Vector2D, Vector2D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|[`Clamp(ref Vector2D, ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|[`ClampToSphere(Vector2D, double)`](VRageMath.ClampToSphere)||
|[`ClampToSphere(ref Vector2D, double)`](VRageMath.ClampToSphere)||
|[`Lerp(Vector2D, Vector2D, double)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|[`Lerp(ref Vector2D, ref Vector2D, double, ref Vector2D)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|[`Barycentric(Vector2D, Vector2D, Vector2D, double, double)`](VRageMath.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|[`Barycentric(ref Vector2D, ref Vector2D, ref Vector2D, double, double, ref Vector2D)`](VRageMath.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|[`SmoothStep(Vector2D, Vector2D, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|[`SmoothStep(ref Vector2D, ref Vector2D, double, ref Vector2D)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|[`CatmullRom(Vector2D, Vector2D, Vector2D, Vector2D, double)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[`CatmullRom(ref Vector2D, ref Vector2D, ref Vector2D, ref Vector2D, double, ref Vector2D)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[`Hermite(Vector2D, Vector2D, Vector2D, Vector2D, double)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|[`Hermite(ref Vector2D, ref Vector2D, ref Vector2D, ref Vector2D, double, ref Vector2D)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|[`Transform(Vector2D, Matrix)`](VRageMath.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|[`Transform(ref Vector2D, ref Matrix, ref Vector2D)`](VRageMath.Transform)|Transforms a Vector2D by the given Matrix.|
|[`TransformNormal(Vector2D, Matrix)`](VRageMath.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|[`TransformNormal(ref Vector2D, ref Matrix, ref Vector2D)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|[`Transform(Vector2D, Quaternion)`](VRageMath.Transform)|Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|[`Transform(ref Vector2D, ref Quaternion, ref Vector2D)`](VRageMath.Transform)|Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|[`Transform(Vector2D[], ref Matrix, Vector2D[])`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|[`Transform(Vector2D[], int, ref Matrix, Vector2D[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|[`TransformNormal(Vector2D[], ref Matrix, Vector2D[])`](VRageMath.TransformNormal)|Transforms an array of Vector2D vector normals by a specified Matrix.|
|[`TransformNormal(Vector2D[], int, ref Matrix, Vector2D[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of Vector2D vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|[`Transform(Vector2D[], ref Quaternion, Vector2D[])`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|[`Transform(Vector2D[], int, ref Quaternion, Vector2D[], int, int)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|[`Negate(Vector2D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`Negate(ref Vector2D, ref Vector2D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`Add(Vector2D, Vector2D)`](VRageMath.Add)|Adds two vectors.|
|[`Add(ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Add)|Adds two vectors.|
|[`Subtract(Vector2D, Vector2D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|[`Subtract(ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|[`Multiply(Vector2D, Vector2D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|[`Multiply(ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|[`Multiply(Vector2D, double)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|[`Multiply(ref Vector2D, double, ref Vector2D)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|[`Divide(Vector2D, Vector2D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|[`Divide(ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|[`Divide(Vector2D, double)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`Divide(ref Vector2D, double, ref Vector2D)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`Between(ref Vector2D, ref Vector2D)`](VRageMath.Between)||
|[`Floor(Vector2D)`](VRageMath.Floor)||
|[`Rotate(double)`](VRageMath.Rotate)||
