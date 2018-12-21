← [Index](index)
# Vector4 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`float&nbsp;X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`float&nbsp;Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`float&nbsp;Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|[`float&nbsp;W`](VRageMath.W)|Gets or sets the w-component of the vector.|
|static&nbsp;[`Vector4&nbsp;Zero`](VRageMath.Zero)||
|static&nbsp;[`Vector4&nbsp;One`](VRageMath.One)||
|static&nbsp;[`Vector4&nbsp;UnitX`](VRageMath.UnitX)||
|static&nbsp;[`Vector4&nbsp;UnitY`](VRageMath.UnitY)||
|static&nbsp;[`Vector4&nbsp;UnitZ`](VRageMath.UnitZ)||
|static&nbsp;[`Vector4&nbsp;UnitW`](VRageMath.UnitW)||
### Properties
|Member|Description|
|---|---|
|[`float&nbsp;Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`Vector4&nbsp;PackOrthoMatrix(Vector3&nbsp;position,&nbsp;Vector3&nbsp;forward,&nbsp;Vector3&nbsp;up)`](VRageMath.PackOrthoMatrix)||
|static&nbsp;[`Vector4&nbsp;PackOrthoMatrix(ref&nbsp;Matrix&nbsp;matrix)`](VRageMath.PackOrthoMatrix)||
|static&nbsp;[`Matrix&nbsp;UnpackOrthoMatrix(ref&nbsp;Vector4&nbsp;packed)`](VRageMath.UnpackOrthoMatrix)||
|static&nbsp;[`void&nbsp;UnpackOrthoMatrix(ref&nbsp;Vector4&nbsp;packed,&nbsp;ref&nbsp;Matrix&nbsp;matrix)`](VRageMath.UnpackOrthoMatrix)||
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool&nbsp;Equals(Vector4&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`float&nbsp;Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float&nbsp;LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static&nbsp;[`float&nbsp;Distance(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`void&nbsp;Distance(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`float&nbsp;DistanceSquared(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`void&nbsp;DistanceSquared(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`float&nbsp;Dot(Vector4&nbsp;vector1,&nbsp;Vector4&nbsp;vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector4&nbsp;vector1,&nbsp;ref&nbsp;Vector4&nbsp;vector2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`void&nbsp;Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector.|
|static&nbsp;[`Vector4&nbsp;Normalize(Vector4&nbsp;vector)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;Vector4&nbsp;vector,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Normalize)|Returns a normalized version of the specified vector.|
|static&nbsp;[`Vector4&nbsp;Min(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Min(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`Vector4&nbsp;Max(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Max(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`Vector4&nbsp;Clamp(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;min,&nbsp;Vector4&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`void&nbsp;Clamp(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;min,&nbsp;ref&nbsp;Vector4&nbsp;max,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`Vector4&nbsp;Lerp(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2,&nbsp;float&nbsp;amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`Vector4&nbsp;Barycentric(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2,&nbsp;Vector4&nbsp;value3,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|static&nbsp;[`void&nbsp;Barycentric(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;value3,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|static&nbsp;[`Vector4&nbsp;SmoothStep(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2,&nbsp;float&nbsp;amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`void&nbsp;SmoothStep(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`Vector4&nbsp;CatmullRom(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2,&nbsp;Vector4&nbsp;value3,&nbsp;Vector4&nbsp;value4,&nbsp;float&nbsp;amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`void&nbsp;CatmullRom(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;value3,&nbsp;ref&nbsp;Vector4&nbsp;value4,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`Vector4&nbsp;Hermite(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;tangent1,&nbsp;Vector4&nbsp;value2,&nbsp;Vector4&nbsp;tangent2,&nbsp;float&nbsp;amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`void&nbsp;Hermite(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;tangent1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;tangent2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`Vector4&nbsp;Transform(Vector2&nbsp;position,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector2&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static&nbsp;[`Vector4&nbsp;Transform(Vector3&nbsp;position,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static&nbsp;[`Vector4&nbsp;Transform(Vector4&nbsp;vector,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)|Transforms a Vector4 by the specified Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector4&nbsp;vector,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Transform)|Transforms a Vector4 by the given Matrix.|
|static&nbsp;[`Vector4&nbsp;Transform(Vector2&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector2&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static&nbsp;[`Vector4&nbsp;Transform(Vector3&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static&nbsp;[`Vector4&nbsp;Transform(Vector4&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector4&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static&nbsp;[`void&nbsp;Transform(Vector4[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector4[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|static&nbsp;[`void&nbsp;Transform(Vector4[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector4[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector4[]&nbsp;sourceArray,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector4[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|static&nbsp;[`void&nbsp;Transform(Vector4[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector4[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|static&nbsp;[`Vector4&nbsp;Negate(Vector4&nbsp;value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Vector4&nbsp;value,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`Vector4&nbsp;Add(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`Vector4&nbsp;Subtract(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`Vector4&nbsp;Multiply(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`Vector4&nbsp;Multiply(Vector4&nbsp;value1,&nbsp;float&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector4&nbsp;value1,&nbsp;float&nbsp;scaleFactor,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`Vector4&nbsp;Divide(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`Vector4&nbsp;Divide(Vector4&nbsp;value1,&nbsp;float&nbsp;divider)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector4&nbsp;value1,&nbsp;float&nbsp;divider,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
