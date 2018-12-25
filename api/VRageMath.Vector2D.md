← [Index](Api-Index)

# Vector2D Struct

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

###### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector2D.X)|Gets or sets the x-component of the vector.|
|[Y](VRageMath.Vector2D.Y)|Gets or sets the y-component of the vector.|
|[Zero](VRageMath.Vector2D.Zero)||
|[One](VRageMath.Vector2D.One)||
|[UnitX](VRageMath.Vector2D.UnitX)||
|[UnitY](VRageMath.Vector2D.UnitY)||
|[PositiveInfinity](VRageMath.Vector2D.PositiveInfinity)||

###### Properties

|Member|Description|
|---|---|
|[Item](VRageMath.Vector2D.Item)||

###### Methods

|Member|Description|
|---|---|
|[ToString()](VRageMath.Vector2D.ToString)|Retrieves a string representation of the current object.|
|[Equals(Vector2D)](VRageMath.Vector2D.Equals)|Determines whether the specified Object is equal to the Vector2D.|
|[Equals(object)](VRageMath.Vector2D.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Vector2D.GetHashCode)|Gets the hash code of the vector object.|
|[IsValid()](VRageMath.Vector2D.IsValid)||
|[AssertIsValid()](VRageMath.Vector2D.AssertIsValid)||
|[Length()](VRageMath.Vector2D.Length)|Calculates the length of the vector.|
|[LengthSquared()](VRageMath.Vector2D.LengthSquared)|Calculates the length of the vector squared.|
|[Distance(Vector2D, Vector2D)](VRageMath.Vector2D.Distance)|Calculates the distance between two vectors.|
|[Distance(ref Vector2D, ref Vector2D, ref double)](VRageMath.Vector2D.Distance)|Calculates the distance between two vectors.|
|[DistanceSquared(Vector2D, Vector2D)](VRageMath.Vector2D.DistanceSquared)|Calculates the distance between two vectors squared.|
|[DistanceSquared(ref Vector2D, ref Vector2D, ref double)](VRageMath.Vector2D.DistanceSquared)|Calculates the distance between two vectors squared.|
|[Dot(Vector2D, Vector2D)](VRageMath.Vector2D.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[Dot(ref Vector2D, ref Vector2D, ref double)](VRageMath.Vector2D.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[Normalize()](VRageMath.Vector2D.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Normalize(Vector2D)](VRageMath.Vector2D.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Normalize(ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Reflect(Vector2D, Vector2D)](VRageMath.Vector2D.Reflect)|Determines the reflect vector of the given vector and normal.|
|[Reflect(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Reflect)|Determines the reflect vector of the given vector and normal.|
|[Min(Vector2D, Vector2D)](VRageMath.Vector2D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Min(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Max(Vector2D, Vector2D)](VRageMath.Vector2D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Max(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Clamp(Vector2D, Vector2D, Vector2D)](VRageMath.Vector2D.Clamp)|Restricts a value to be within a specified range.|
|[Clamp(ref Vector2D, ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Clamp)|Restricts a value to be within a specified range.|
|[ClampToSphere(Vector2D, double)](VRageMath.Vector2D.ClampToSphere)||
|[ClampToSphere(ref Vector2D, double)](VRageMath.Vector2D.ClampToSphere)||
|[Lerp(Vector2D, Vector2D, double)](VRageMath.Vector2D.Lerp)|Performs a linear interpolation between two vectors.|
|[Lerp(ref Vector2D, ref Vector2D, double, ref Vector2D)](VRageMath.Vector2D.Lerp)|Performs a linear interpolation between two vectors.|
|[Barycentric(Vector2D, Vector2D, Vector2D, double, double)](VRageMath.Vector2D.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|[Barycentric(ref Vector2D, ref Vector2D, ref Vector2D, double, double, ref Vector2D)](VRageMath.Vector2D.Barycentric)|Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|[SmoothStep(Vector2D, Vector2D, double)](VRageMath.Vector2D.SmoothStep)|Interpolates between two values using a cubic equation.|
|[SmoothStep(ref Vector2D, ref Vector2D, double, ref Vector2D)](VRageMath.Vector2D.SmoothStep)|Interpolates between two values using a cubic equation.|
|[CatmullRom(Vector2D, Vector2D, Vector2D, Vector2D, double)](VRageMath.Vector2D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[CatmullRom(ref Vector2D, ref Vector2D, ref Vector2D, ref Vector2D, double, ref Vector2D)](VRageMath.Vector2D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[Hermite(Vector2D, Vector2D, Vector2D, Vector2D, double)](VRageMath.Vector2D.Hermite)|Performs a Hermite spline interpolation.|
|[Hermite(ref Vector2D, ref Vector2D, ref Vector2D, ref Vector2D, double, ref Vector2D)](VRageMath.Vector2D.Hermite)|Performs a Hermite spline interpolation.|
|[Transform(Vector2D, Matrix)](VRageMath.Vector2D.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|[Transform(ref Vector2D, ref Matrix, ref Vector2D)](VRageMath.Vector2D.Transform)|Transforms a Vector2D by the given Matrix.|
|[TransformNormal(Vector2D, Matrix)](VRageMath.Vector2D.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|[TransformNormal(ref Vector2D, ref Matrix, ref Vector2D)](VRageMath.Vector2D.TransformNormal)|Transforms a vector normal by a matrix.|
|[Transform(Vector2D, Quaternion)](VRageMath.Vector2D.Transform)|Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|[Transform(ref Vector2D, ref Quaternion, ref Vector2D)](VRageMath.Vector2D.Transform)|Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|[Transform(Vector2D[], ref Matrix, Vector2D[])](VRageMath.Vector2D.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|[Transform(Vector2D[], int, ref Matrix, Vector2D[], int, int)](VRageMath.Vector2D.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|[TransformNormal(Vector2D[], ref Matrix, Vector2D[])](VRageMath.Vector2D.TransformNormal)|Transforms an array of Vector2D vector normals by a specified Matrix.|
|[TransformNormal(Vector2D[], int, ref Matrix, Vector2D[], int, int)](VRageMath.Vector2D.TransformNormal)|Transforms a specified range in an array of Vector2D vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|[Transform(Vector2D[], ref Quaternion, Vector2D[])](VRageMath.Vector2D.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|[Transform(Vector2D[], int, ref Quaternion, Vector2D[], int, int)](VRageMath.Vector2D.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|[Negate(Vector2D)](VRageMath.Vector2D.Negate)|Returns a vector pointing in the opposite direction.|
|[Negate(ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Negate)|Returns a vector pointing in the opposite direction.|
|[Add(Vector2D, Vector2D)](VRageMath.Vector2D.Add)|Adds two vectors.|
|[Add(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Add)|Adds two vectors.|
|[Subtract(Vector2D, Vector2D)](VRageMath.Vector2D.Subtract)|Subtracts a vector from a vector.|
|[Subtract(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Subtract)|Subtracts a vector from a vector.|
|[Multiply(Vector2D, Vector2D)](VRageMath.Vector2D.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(Vector2D, double)](VRageMath.Vector2D.Multiply)|Multiplies a vector by a scalar value.|
|[Multiply(ref Vector2D, double, ref Vector2D)](VRageMath.Vector2D.Multiply)|Multiplies a vector by a scalar value.|
|[Divide(Vector2D, Vector2D)](VRageMath.Vector2D.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(Vector2D, double)](VRageMath.Vector2D.Divide)|Divides a vector by a scalar value.|
|[Divide(ref Vector2D, double, ref Vector2D)](VRageMath.Vector2D.Divide)|Divides a vector by a scalar value.|
|[Between(ref Vector2D, ref Vector2D)](VRageMath.Vector2D.Between)||
|[Floor(Vector2D)](VRageMath.Vector2D.Floor)||
|[Rotate(double)](VRageMath.Vector2D.Rotate)||

