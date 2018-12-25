← [Index](Api-Index)

#### Vector2 Struct

```csharp
public struct Vector2: ValueType, IEquatable<T>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Inheritance: **[ValueType](System.ValueType)

**Implements:**  
* [IEquatable<T>](System.IEquatable`1)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector2.X)|Gets or sets the x-component of the vector.|
|[Y](VRageMath.Vector2.Y)|Gets or sets the y-component of the vector.|
|[Zero](VRageMath.Vector2.Zero)||
|[One](VRageMath.Vector2.One)||
|[UnitX](VRageMath.Vector2.UnitX)||
|[UnitY](VRageMath.Vector2.UnitY)||
|[PositiveInfinity](VRageMath.Vector2.PositiveInfinity)||

#### Properties

|Member|Description|
|---|---|
|[Item](VRageMath.Vector2.Item)||

#### Methods

|Member|Description|
|---|---|
|[ToString()](VRageMath.Vector2.ToString)|Retrieves a string representation of the current object.|
|[Equals(Vector2)](VRageMath.Vector2.Equals)|Determines whether the specified Object is equal to the Vector2.|
|[Equals(object)](VRageMath.Vector2.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Vector2.GetHashCode)|Gets the hash code of the vector object.|
|[IsValid()](VRageMath.Vector2.IsValid)||
|[AssertIsValid()](VRageMath.Vector2.AssertIsValid)||
|[Length()](VRageMath.Vector2.Length)|Calculates the length of the vector.|
|[LengthSquared()](VRageMath.Vector2.LengthSquared)|Calculates the length of the vector squared.|
|[Distance(Vector2, Vector2)](VRageMath.Vector2.Distance)|Calculates the distance between two vectors.|
|[Distance(ref Vector2, ref Vector2, ref float)](VRageMath.Vector2.Distance)|Calculates the distance between two vectors.|
|[DistanceSquared(Vector2, Vector2)](VRageMath.Vector2.DistanceSquared)|Calculates the distance between two vectors squared.|
|[DistanceSquared(ref Vector2, ref Vector2, ref float)](VRageMath.Vector2.DistanceSquared)|Calculates the distance between two vectors squared.|
|[Dot(Vector2, Vector2)](VRageMath.Vector2.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[Dot(ref Vector2, ref Vector2, ref float)](VRageMath.Vector2.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[Normalize()](VRageMath.Vector2.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Normalize(Vector2)](VRageMath.Vector2.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Normalize(ref Vector2, ref Vector2)](VRageMath.Vector2.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Reflect(Vector2, Vector2)](VRageMath.Vector2.Reflect)|Determines the reflect vector of the given vector and normal.|
|[Reflect(ref Vector2, ref Vector2, ref Vector2)](VRageMath.Vector2.Reflect)|Determines the reflect vector of the given vector and normal.|
|[Min(Vector2, Vector2)](VRageMath.Vector2.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Min(ref Vector2, ref Vector2, ref Vector2)](VRageMath.Vector2.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Max(Vector2, Vector2)](VRageMath.Vector2.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Max(ref Vector2, ref Vector2, ref Vector2)](VRageMath.Vector2.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Clamp(Vector2, Vector2, Vector2)](VRageMath.Vector2.Clamp)|Restricts a value to be within a specified range.|
|[Clamp(ref Vector2, ref Vector2, ref Vector2, ref Vector2)](VRageMath.Vector2.Clamp)|Restricts a value to be within a specified range.|
|[ClampToSphere(Vector2, float)](VRageMath.Vector2.ClampToSphere)||
|[ClampToSphere(ref Vector2, float)](VRageMath.Vector2.ClampToSphere)||
|[Lerp(Vector2, Vector2, float)](VRageMath.Vector2.Lerp)|Performs a linear interpolation between two vectors.|
|[Lerp(ref Vector2, ref Vector2, float, ref Vector2)](VRageMath.Vector2.Lerp)|Performs a linear interpolation between two vectors.|
|[Barycentric(Vector2, Vector2, Vector2, float, float)](VRageMath.Vector2.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|[Barycentric(ref Vector2, ref Vector2, ref Vector2, float, float, ref Vector2)](VRageMath.Vector2.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|[SmoothStep(Vector2, Vector2, float)](VRageMath.Vector2.SmoothStep)|Interpolates between two values using a cubic equation.|
|[SmoothStep(ref Vector2, ref Vector2, float, ref Vector2)](VRageMath.Vector2.SmoothStep)|Interpolates between two values using a cubic equation.|
|[CatmullRom(Vector2, Vector2, Vector2, Vector2, float)](VRageMath.Vector2.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[CatmullRom(ref Vector2, ref Vector2, ref Vector2, ref Vector2, float, ref Vector2)](VRageMath.Vector2.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[Hermite(Vector2, Vector2, Vector2, Vector2, float)](VRageMath.Vector2.Hermite)|Performs a Hermite spline interpolation.|
|[Hermite(ref Vector2, ref Vector2, ref Vector2, ref Vector2, float, ref Vector2)](VRageMath.Vector2.Hermite)|Performs a Hermite spline interpolation.|
|[Transform(Vector2, Matrix)](VRageMath.Vector2.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|[Transform(ref Vector2, ref Matrix, ref Vector2)](VRageMath.Vector2.Transform)|Transforms a Vector2 by the given Matrix.|
|[TransformNormal(Vector2, Matrix)](VRageMath.Vector2.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|[TransformNormal(ref Vector2, ref Matrix, ref Vector2)](VRageMath.Vector2.TransformNormal)|Transforms a vector normal by a matrix.|
|[Transform(Vector2, Quaternion)](VRageMath.Vector2.Transform)|Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|[Transform(ref Vector2, ref Quaternion, ref Vector2)](VRageMath.Vector2.Transform)|Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|[Transform(Vector2[], ref Matrix, Vector2[])](VRageMath.Vector2.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|[Transform(Vector2[], int, ref Matrix, Vector2[], int, int)](VRageMath.Vector2.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|[TransformNormal(Vector2[], ref Matrix, Vector2[])](VRageMath.Vector2.TransformNormal)|Transforms an array of Vector2 vector normals by a specified Matrix.|
|[TransformNormal(Vector2[], int, ref Matrix, Vector2[], int, int)](VRageMath.Vector2.TransformNormal)|Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|[Transform(Vector2[], ref Quaternion, Vector2[])](VRageMath.Vector2.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|[Transform(Vector2[], int, ref Quaternion, Vector2[], int, int)](VRageMath.Vector2.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|[Negate(Vector2)](VRageMath.Vector2.Negate)|Returns a vector pointing in the opposite direction.|
|[Negate(ref Vector2, ref Vector2)](VRageMath.Vector2.Negate)|Returns a vector pointing in the opposite direction.|
|[Add(Vector2, Vector2)](VRageMath.Vector2.Add)|Adds two vectors.|
|[Add(ref Vector2, ref Vector2, ref Vector2)](VRageMath.Vector2.Add)|Adds two vectors.|
|[Subtract(Vector2, Vector2)](VRageMath.Vector2.Subtract)|Subtracts a vector from a vector.|
|[Subtract(ref Vector2, ref Vector2, ref Vector2)](VRageMath.Vector2.Subtract)|Subtracts a vector from a vector.|
|[Multiply(Vector2, Vector2)](VRageMath.Vector2.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(ref Vector2, ref Vector2, ref Vector2)](VRageMath.Vector2.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(Vector2, float)](VRageMath.Vector2.Multiply)|Multiplies a vector by a scalar value.|
|[Multiply(ref Vector2, float, ref Vector2)](VRageMath.Vector2.Multiply)|Multiplies a vector by a scalar value.|
|[Divide(Vector2, Vector2)](VRageMath.Vector2.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(ref Vector2, ref Vector2, ref Vector2)](VRageMath.Vector2.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(Vector2, float)](VRageMath.Vector2.Divide)|Divides a vector by a scalar value.|
|[Divide(ref Vector2, float, ref Vector2)](VRageMath.Vector2.Divide)|Divides a vector by a scalar value.|
|[Between(ref Vector2, ref Vector2)](VRageMath.Vector2.Between)||
|[Floor(Vector2)](VRageMath.Vector2.Floor)||
|[Rotate(double)](VRageMath.Vector2.Rotate)||
|[IsZero(ref Vector2)](VRageMath.Vector2.IsZero)||
|[IsZero(ref Vector2, float)](VRageMath.Vector2.IsZero)||
|[IsZero(Vector2, float)](VRageMath.Vector2.IsZero)||
|[SignNonZero(Vector2)](VRageMath.Vector2.SignNonZero)||

