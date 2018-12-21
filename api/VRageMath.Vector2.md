← [Index](index)
# Vector2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`float&nbsp;X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`float&nbsp;Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|static&nbsp;[`Vector2&nbsp;Zero`](VRageMath.Zero)||
|static&nbsp;[`Vector2&nbsp;One`](VRageMath.One)||
|static&nbsp;[`Vector2&nbsp;UnitX`](VRageMath.UnitX)||
|static&nbsp;[`Vector2&nbsp;UnitY`](VRageMath.UnitY)||
|static&nbsp;[`Vector2&nbsp;PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`float&nbsp;Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool&nbsp;Equals(Vector2&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of the vector object.|
|[`bool&nbsp;IsValid()`](VRageMath.IsValid)||
|[`void&nbsp;AssertIsValid()`](VRageMath.AssertIsValid)||
|[`float&nbsp;Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float&nbsp;LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static&nbsp;[`float&nbsp;Distance(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`void&nbsp;Distance(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`float&nbsp;DistanceSquared(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`void&nbsp;DistanceSquared(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`float&nbsp;Dot(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`void&nbsp;Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector2&nbsp;Normalize(Vector2&nbsp;value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;Vector2&nbsp;value,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector2&nbsp;Reflect(Vector2&nbsp;vector,&nbsp;Vector2&nbsp;normal)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static&nbsp;[`void&nbsp;Reflect(ref&nbsp;Vector2&nbsp;vector,&nbsp;ref&nbsp;Vector2&nbsp;normal,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static&nbsp;[`Vector2&nbsp;Min(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Min(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`Vector2&nbsp;Max(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Max(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`Vector2&nbsp;Clamp(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;min,&nbsp;Vector2&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`void&nbsp;Clamp(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;min,&nbsp;ref&nbsp;Vector2&nbsp;max,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`Vector2&nbsp;ClampToSphere(Vector2&nbsp;vector,&nbsp;float&nbsp;radius)`](VRageMath.ClampToSphere)||
|static&nbsp;[`void&nbsp;ClampToSphere(ref&nbsp;Vector2&nbsp;vector,&nbsp;float&nbsp;radius)`](VRageMath.ClampToSphere)||
|static&nbsp;[`Vector2&nbsp;Lerp(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2,&nbsp;float&nbsp;amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`Vector2&nbsp;Barycentric(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2,&nbsp;Vector2&nbsp;value3,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2)`](VRageMath.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static&nbsp;[`void&nbsp;Barycentric(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;value3,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static&nbsp;[`Vector2&nbsp;SmoothStep(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2,&nbsp;float&nbsp;amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`void&nbsp;SmoothStep(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`Vector2&nbsp;CatmullRom(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2,&nbsp;Vector2&nbsp;value3,&nbsp;Vector2&nbsp;value4,&nbsp;float&nbsp;amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`void&nbsp;CatmullRom(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;value3,&nbsp;ref&nbsp;Vector2&nbsp;value4,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`Vector2&nbsp;Hermite(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;tangent1,&nbsp;Vector2&nbsp;value2,&nbsp;Vector2&nbsp;tangent2,&nbsp;float&nbsp;amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`void&nbsp;Hermite(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;tangent1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;tangent2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`Vector2&nbsp;Transform(Vector2&nbsp;position,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector2&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static&nbsp;[`Vector2&nbsp;TransformNormal(Vector2&nbsp;normal,&nbsp;Matrix&nbsp;matrix)`](VRageMath.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector2&nbsp;normal,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static&nbsp;[`Vector2&nbsp;Transform(Vector2&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector2&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Transform)|Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(Vector2[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector2[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|static&nbsp;[`void&nbsp;Transform(Vector2[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector2[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|static&nbsp;[`void&nbsp;TransformNormal(Vector2[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector2[]&nbsp;destinationArray)`](VRageMath.TransformNormal)|Transforms an array of Vector2 vector normals by a specified Matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(Vector2[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector2[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.TransformNormal)|Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector2[]&nbsp;sourceArray,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector2[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|static&nbsp;[`void&nbsp;Transform(Vector2[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector2[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|static&nbsp;[`Vector2&nbsp;Negate(Vector2&nbsp;value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Vector2&nbsp;value,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`Vector2&nbsp;Add(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`Vector2&nbsp;Subtract(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`Vector2&nbsp;Multiply(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`Vector2&nbsp;Multiply(Vector2&nbsp;value1,&nbsp;float&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector2&nbsp;value1,&nbsp;float&nbsp;scaleFactor,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`Vector2&nbsp;Divide(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector2&nbsp;value1,&nbsp;ref&nbsp;Vector2&nbsp;value2,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`Vector2&nbsp;Divide(Vector2&nbsp;value1,&nbsp;float&nbsp;divider)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector2&nbsp;value1,&nbsp;float&nbsp;divider,&nbsp;ref&nbsp;Vector2&nbsp;result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`bool&nbsp;Between(ref&nbsp;Vector2&nbsp;start,&nbsp;ref&nbsp;Vector2&nbsp;end)`](VRageMath.Between)||
|static&nbsp;[`Vector2&nbsp;Floor(Vector2&nbsp;position)`](VRageMath.Floor)||
|[`void&nbsp;Rotate(double&nbsp;angle)`](VRageMath.Rotate)||
|static&nbsp;[`bool&nbsp;IsZero(ref&nbsp;Vector2&nbsp;value)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(ref&nbsp;Vector2&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(Vector2&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`Vector2&nbsp;SignNonZero(Vector2&nbsp;value)`](VRageMath.SignNonZero)||
