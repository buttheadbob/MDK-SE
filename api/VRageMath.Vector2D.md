← [Index](index)
# Vector2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`double&nbsp;X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`double&nbsp;Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|static&nbsp;[`Vector2D&nbsp;Zero`](VRageMath.Zero)||
|static&nbsp;[`Vector2D&nbsp;One`](VRageMath.One)||
|static&nbsp;[`Vector2D&nbsp;UnitX`](VRageMath.UnitX)||
|static&nbsp;[`Vector2D&nbsp;UnitY`](VRageMath.UnitY)||
|static&nbsp;[`Vector2D&nbsp;PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`double&nbsp;Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool&nbsp;Equals(Vector2D&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2D.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of the vector object.|
|[`bool&nbsp;IsValid()`](VRageMath.IsValid)||
|[`void&nbsp;AssertIsValid()`](VRageMath.AssertIsValid)||
|[`double&nbsp;Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double&nbsp;LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static&nbsp;[`double&nbsp;Distance(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`void&nbsp;Distance(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`double&nbsp;DistanceSquared(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`void&nbsp;DistanceSquared(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`double&nbsp;Dot(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`void&nbsp;Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector2D&nbsp;Normalize(Vector2D&nbsp;value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;Vector2D&nbsp;value,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector2D&nbsp;Reflect(Vector2D&nbsp;vector,&nbsp;Vector2D&nbsp;normal)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static&nbsp;[`void&nbsp;Reflect(ref&nbsp;Vector2D&nbsp;vector,&nbsp;ref&nbsp;Vector2D&nbsp;normal,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Reflect)|Determines the reflect vector of the given vector and normal.|
|static&nbsp;[`Vector2D&nbsp;Min(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Min(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`Vector2D&nbsp;Max(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Max(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`Vector2D&nbsp;Clamp(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;min,&nbsp;Vector2D&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`void&nbsp;Clamp(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;min,&nbsp;ref&nbsp;Vector2D&nbsp;max,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`Vector2D&nbsp;ClampToSphere(Vector2D&nbsp;vector,&nbsp;double&nbsp;radius)`](VRageMath.ClampToSphere)||
|static&nbsp;[`void&nbsp;ClampToSphere(ref&nbsp;Vector2D&nbsp;vector,&nbsp;double&nbsp;radius)`](VRageMath.ClampToSphere)||
|static&nbsp;[`Vector2D&nbsp;Lerp(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2,&nbsp;double&nbsp;amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`Vector2D&nbsp;Barycentric(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2,&nbsp;Vector2D&nbsp;value3,&nbsp;double&nbsp;amount1,&nbsp;double&nbsp;amount2)`](VRageMath.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static&nbsp;[`void&nbsp;Barycentric(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;value3,&nbsp;double&nbsp;amount1,&nbsp;double&nbsp;amount2,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|static&nbsp;[`Vector2D&nbsp;SmoothStep(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2,&nbsp;double&nbsp;amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`void&nbsp;SmoothStep(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`Vector2D&nbsp;CatmullRom(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2,&nbsp;Vector2D&nbsp;value3,&nbsp;Vector2D&nbsp;value4,&nbsp;double&nbsp;amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`void&nbsp;CatmullRom(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;value3,&nbsp;ref&nbsp;Vector2D&nbsp;value4,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`Vector2D&nbsp;Hermite(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;tangent1,&nbsp;Vector2D&nbsp;value2,&nbsp;Vector2D&nbsp;tangent2,&nbsp;double&nbsp;amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`void&nbsp;Hermite(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;tangent1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;tangent2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`Vector2D&nbsp;Transform(Vector2D&nbsp;position,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector2D&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector2D by the given Matrix.|
|static&nbsp;[`Vector2D&nbsp;TransformNormal(Vector2D&nbsp;normal,&nbsp;Matrix&nbsp;matrix)`](VRageMath.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector2D&nbsp;normal,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static&nbsp;[`Vector2D&nbsp;Transform(Vector2D&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector2D&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(Vector2D[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector2D[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|static&nbsp;[`void&nbsp;Transform(Vector2D[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector2D[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|static&nbsp;[`void&nbsp;TransformNormal(Vector2D[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector2D[]&nbsp;destinationArray)`](VRageMath.TransformNormal)|Transforms an array of Vector2D vector normals by a specified Matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(Vector2D[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector2D[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.TransformNormal)|Transforms a specified range in an array of Vector2D vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector2D[]&nbsp;sourceArray,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector2D[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|static&nbsp;[`void&nbsp;Transform(Vector2D[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector2D[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|static&nbsp;[`Vector2D&nbsp;Negate(Vector2D&nbsp;value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Vector2D&nbsp;value,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`Vector2D&nbsp;Add(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`Vector2D&nbsp;Subtract(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`Vector2D&nbsp;Multiply(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`Vector2D&nbsp;Multiply(Vector2D&nbsp;value1,&nbsp;double&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector2D&nbsp;value1,&nbsp;double&nbsp;scaleFactor,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`Vector2D&nbsp;Divide(Vector2D&nbsp;value1,&nbsp;Vector2D&nbsp;value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector2D&nbsp;value1,&nbsp;ref&nbsp;Vector2D&nbsp;value2,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`Vector2D&nbsp;Divide(Vector2D&nbsp;value1,&nbsp;double&nbsp;divider)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector2D&nbsp;value1,&nbsp;double&nbsp;divider,&nbsp;ref&nbsp;Vector2D&nbsp;result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`bool&nbsp;Between(ref&nbsp;Vector2D&nbsp;start,&nbsp;ref&nbsp;Vector2D&nbsp;end)`](VRageMath.Between)||
|static&nbsp;[`Vector2D&nbsp;Floor(Vector2D&nbsp;position)`](VRageMath.Floor)||
|[`void&nbsp;Rotate(double&nbsp;angle)`](VRageMath.Rotate)||
