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
|static [`Vector2D Zero`](VRageMath.Zero)||
|static [`Vector2D One`](VRageMath.One)||
|static [`Vector2D UnitX`](VRageMath.UnitX)||
|static [`Vector2D UnitY`](VRageMath.UnitY)||
|static [`Vector2D PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`double Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(Vector2D other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2D.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of the vector object.|
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`double Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`double Distance(Vector2D value1, Vector2D value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`double DistanceSquared(Vector2D value1, Vector2D value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`double Dot(Vector2D value1, Vector2D value2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`void Dot(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`void Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector2D Normalize(Vector2D value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`void Normalize(ref Vector2D value, ref Vector2D result)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector2D Reflect(Vector2D vector, Vector2D normal)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`void Reflect(ref Vector2D vector, ref Vector2D normal, ref Vector2D result)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static [`Vector2D Min(Vector2D value1, Vector2D value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Vector2D Max(Vector2D value1, Vector2D value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Vector2D Clamp(Vector2D value1, Vector2D min, Vector2D max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref Vector2D value1, ref Vector2D min, ref Vector2D max, ref Vector2D result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Vector2D ClampToSphere(Vector2D vector, double radius)`](VRageMath.ClampToSphere)||
|static [`void ClampToSphere(ref Vector2D vector, double radius)`](VRageMath.ClampToSphere)||
|static [`Vector2D Lerp(Vector2D value1, Vector2D value2, double amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref Vector2D value1, ref Vector2D value2, double amount, ref Vector2D result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Vector2D Barycentric(Vector2D value1, Vector2D value2, Vector2D value3, double amount1, double amount2)`](VRageMath.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`void Barycentric(ref Vector2D value1, ref Vector2D value2, ref Vector2D value3, double amount1, double amount2, ref Vector2D result)`](VRageMath.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static [`Vector2D SmoothStep(Vector2D value1, Vector2D value2, double amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref Vector2D value1, ref Vector2D value2, double amount, ref Vector2D result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`Vector2D CatmullRom(Vector2D value1, Vector2D value2, Vector2D value3, Vector2D value4, double amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref Vector2D value1, ref Vector2D value2, ref Vector2D value3, ref Vector2D value4, double amount, ref Vector2D result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Vector2D Hermite(Vector2D value1, Vector2D tangent1, Vector2D value2, Vector2D tangent2, double amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref Vector2D value1, ref Vector2D tangent1, ref Vector2D value2, ref Vector2D tangent2, double amount, ref Vector2D result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Vector2D Transform(Vector2D position, Matrix matrix)`](VRageMath.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|static [`void Transform(ref Vector2D position, ref Matrix matrix, ref Vector2D result)`](VRageMath.Transform)|Transforms a Vector2D by the given Matrix.|
|static [`Vector2D TransformNormal(Vector2D normal, Matrix matrix)`](VRageMath.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|static [`void TransformNormal(ref Vector2D normal, ref Matrix matrix, ref Vector2D result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`Vector2D Transform(Vector2D value, Quaternion rotation)`](VRageMath.Transform)|Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`void Transform(ref Vector2D value, ref Quaternion rotation, ref Vector2D result)`](VRageMath.Transform)|Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static [`void Transform(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|static [`void Transform(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|static [`void TransformNormal(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)`](VRageMath.TransformNormal)|Transforms an array of Vector2D vector normals by a specified Matrix.|
|static [`void TransformNormal(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)|Transforms a specified range in an array of Vector2D vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|static [`void Transform(Vector2D[] sourceArray, ref Quaternion rotation, Vector2D[] destinationArray)`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|static [`void Transform(Vector2D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|static [`Vector2D Negate(Vector2D value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref Vector2D value, ref Vector2D result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Vector2D Add(Vector2D value1, Vector2D value2)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Add)|Adds two vectors.|
|static [`Vector2D Subtract(Vector2D value1, Vector2D value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Vector2D Multiply(Vector2D value1, Vector2D value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Vector2D Multiply(Vector2D value1, double scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`void Multiply(ref Vector2D value1, double scaleFactor, ref Vector2D result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Vector2D Divide(Vector2D value1, Vector2D value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Vector2D Divide(Vector2D value1, double divider)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref Vector2D value1, double divider, ref Vector2D result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`bool Between(ref Vector2D start, ref Vector2D end)`](VRageMath.Between)||
|static [`Vector2D Floor(Vector2D position)`](VRageMath.Floor)||
|[`void Rotate(double angle)`](VRageMath.Rotate)||
