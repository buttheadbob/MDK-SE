← [Index](index)
# Vector4D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`double&nbsp;X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`double&nbsp;Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`double&nbsp;Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|[`double&nbsp;W`](VRageMath.W)|Gets or sets the w-component of the vector.|
|static&nbsp;[`Vector4D&nbsp;Zero`](VRageMath.Zero)||
|static&nbsp;[`Vector4D&nbsp;One`](VRageMath.One)||
|static&nbsp;[`Vector4D&nbsp;UnitX`](VRageMath.UnitX)||
|static&nbsp;[`Vector4D&nbsp;UnitY`](VRageMath.UnitY)||
|static&nbsp;[`Vector4D&nbsp;UnitZ`](VRageMath.UnitZ)||
|static&nbsp;[`Vector4D&nbsp;UnitW`](VRageMath.UnitW)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`Vector4D&nbsp;PackOrthoMatrix(Vector3D&nbsp;position,&nbsp;Vector3D&nbsp;forward,&nbsp;Vector3D&nbsp;up)`](VRageMath.PackOrthoMatrix)||
|static&nbsp;[`Vector4D&nbsp;PackOrthoMatrix(ref&nbsp;MatrixD&nbsp;matrix)`](VRageMath.PackOrthoMatrix)||
|static&nbsp;[`MatrixD&nbsp;UnpackOrthoMatrix(ref&nbsp;Vector4D&nbsp;packed)`](VRageMath.UnpackOrthoMatrix)||
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool&nbsp;Equals(Vector4&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`double&nbsp;Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double&nbsp;LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static&nbsp;[`double&nbsp;Distance(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`void&nbsp;Distance(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`double&nbsp;DistanceSquared(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`void&nbsp;DistanceSquared(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`double&nbsp;Dot(Vector4&nbsp;vector1,&nbsp;Vector4&nbsp;vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector4&nbsp;vector1,&nbsp;ref&nbsp;Vector4&nbsp;vector2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of two vectors.|
|[`void&nbsp;Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector.|
|static&nbsp;[`Vector4D&nbsp;Normalize(Vector4D&nbsp;vector)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;Vector4D&nbsp;vector,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Normalize)|Returns a normalized version of the specified vector.|
|static&nbsp;[`Vector4&nbsp;Min(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Min(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`Vector4&nbsp;Max(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Max(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`Vector4D&nbsp;Clamp(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;min,&nbsp;Vector4D&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`void&nbsp;Clamp(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;min,&nbsp;ref&nbsp;Vector4D&nbsp;max,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`Vector4D&nbsp;Lerp(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;value2,&nbsp;double&nbsp;amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;value2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`Vector4D&nbsp;Barycentric(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;value2,&nbsp;Vector4D&nbsp;value3,&nbsp;double&nbsp;amount1,&nbsp;double&nbsp;amount2)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|static&nbsp;[`void&nbsp;Barycentric(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;value2,&nbsp;ref&nbsp;Vector4D&nbsp;value3,&nbsp;double&nbsp;amount1,&nbsp;double&nbsp;amount2,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|static&nbsp;[`Vector4D&nbsp;SmoothStep(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;value2,&nbsp;double&nbsp;amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`void&nbsp;SmoothStep(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;value2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`Vector4D&nbsp;CatmullRom(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;value2,&nbsp;Vector4D&nbsp;value3,&nbsp;Vector4D&nbsp;value4,&nbsp;double&nbsp;amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`void&nbsp;CatmullRom(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;value2,&nbsp;ref&nbsp;Vector4D&nbsp;value3,&nbsp;ref&nbsp;Vector4D&nbsp;value4,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`Vector4D&nbsp;Hermite(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;tangent1,&nbsp;Vector4D&nbsp;value2,&nbsp;Vector4D&nbsp;tangent2,&nbsp;double&nbsp;amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`void&nbsp;Hermite(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;tangent1,&nbsp;ref&nbsp;Vector4D&nbsp;value2,&nbsp;ref&nbsp;Vector4D&nbsp;tangent2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`Vector4D&nbsp;Transform(Vector2&nbsp;position,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector2&nbsp;position,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector2 by the given Matrix.|
|static&nbsp;[`Vector4D&nbsp;Transform(Vector3D&nbsp;position,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3D&nbsp;position,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static&nbsp;[`Vector4D&nbsp;Transform(Vector4D&nbsp;vector,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Transform)|Transforms a Vector4 by the specified Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector4D&nbsp;vector,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector4 by the given Matrix.|
|static&nbsp;[`Vector4D&nbsp;Transform(Vector2&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector2&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|static&nbsp;[`Vector4D&nbsp;Transform(Vector3D&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3D&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|static&nbsp;[`Vector4D&nbsp;Transform(Vector4D&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector4D&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector4 by a specified Quaternion.|
|static&nbsp;[`void&nbsp;Transform(Vector4D[]&nbsp;sourceArray,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;Vector4D[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|static&nbsp;[`void&nbsp;Transform(Vector4D[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;Vector4D[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector4D[]&nbsp;sourceArray,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector4D[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|static&nbsp;[`void&nbsp;Transform(Vector4D[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector4D[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|static&nbsp;[`Vector4D&nbsp;Negate(Vector4D&nbsp;value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Vector4D&nbsp;value,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`Vector4D&nbsp;Add(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;value2)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;value2,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`Vector4&nbsp;Subtract(Vector4&nbsp;value1,&nbsp;Vector4&nbsp;value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;value2,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`Vector4D&nbsp;Multiply(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector4&nbsp;value1,&nbsp;ref&nbsp;Vector4&nbsp;value2,&nbsp;ref&nbsp;Vector4&nbsp;result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`Vector4D&nbsp;Multiply(Vector4D&nbsp;value1,&nbsp;double&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector4D&nbsp;value1,&nbsp;double&nbsp;scaleFactor,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`Vector4D&nbsp;Divide(Vector4D&nbsp;value1,&nbsp;Vector4D&nbsp;value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector4D&nbsp;value1,&nbsp;ref&nbsp;Vector4D&nbsp;value2,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`Vector4D&nbsp;Divide(Vector4D&nbsp;value1,&nbsp;double&nbsp;divider)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector4D&nbsp;value1,&nbsp;double&nbsp;divider,&nbsp;ref&nbsp;Vector4D&nbsp;result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
