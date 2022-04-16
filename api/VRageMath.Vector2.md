← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector2 Struct

```csharp
public struct Vector2: IEquatable<Vector2>
```

Defines a vector with two components.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable\<Vector2>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[static Vector2 One](VRageMath.Vector2.One)||
|[static Vector2 PositiveInfinity](VRageMath.Vector2.PositiveInfinity)||
|[static Vector2 UnitX](VRageMath.Vector2.UnitX)||
|[static Vector2 UnitY](VRageMath.Vector2.UnitY)||
|[static Vector2 Zero](VRageMath.Vector2.Zero)||
|[float X](VRageMath.Vector2.X)|Gets or sets the x-component of the vector.|
|[float Y](VRageMath.Vector2.Y)|Gets or sets the y-component of the vector.|

#### Properties

|Member|Description|
|---|---|
|[float Item { get; set; }](VRageMath.Vector2.Item)||

#### Constructors

|Member|Description|
|---|---|
|[Vector2(float, float)](VRageMath.Vector2..ctor)||
|[Vector2(float)](VRageMath.Vector2..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static Vector2 Add(Vector2, Vector2)](VRageMath.Vector2.Add)|Adds two vectors.|
|[static void Add(ref Vector2, ref Vector2, out Vector2)](VRageMath.Vector2.Add)|Adds two vectors.|
|[static Vector2 Barycentric(Vector2, Vector2, Vector2, float, float)](VRageMath.Vector2.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|[static void Barycentric(ref Vector2, ref Vector2, ref Vector2, float, float, out Vector2)](VRageMath.Vector2.Barycentric)|Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.|
|[static Vector2 CatmullRom(Vector2, Vector2, Vector2, Vector2, float)](VRageMath.Vector2.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[static void CatmullRom(ref Vector2, ref Vector2, ref Vector2, ref Vector2, float, out Vector2)](VRageMath.Vector2.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[static Vector2 Clamp(Vector2, Vector2, Vector2)](VRageMath.Vector2.Clamp)|Restricts a value to be within a specified range.|
|[static void Clamp(ref Vector2, ref Vector2, ref Vector2, out Vector2)](VRageMath.Vector2.Clamp)|Restricts a value to be within a specified range.|
|[static Vector2 ClampToSphere(Vector2, float)](VRageMath.Vector2.ClampToSphere)||
|[static void ClampToSphere(ref Vector2, float)](VRageMath.Vector2.ClampToSphere)||
|[static float Distance(Vector2, Vector2)](VRageMath.Vector2.Distance)|Calculates the distance between two vectors.|
|[static void Distance(ref Vector2, ref Vector2, out float)](VRageMath.Vector2.Distance)|Calculates the distance between two vectors.|
|[static float DistanceSquared(Vector2, Vector2)](VRageMath.Vector2.DistanceSquared)|Calculates the distance between two vectors squared.|
|[static void DistanceSquared(ref Vector2, ref Vector2, out float)](VRageMath.Vector2.DistanceSquared)|Calculates the distance between two vectors squared.|
|[static Vector2 Divide(Vector2, Vector2)](VRageMath.Vector2.Divide)|Divides the components of a vector by the components of another vector.|
|[static void Divide(ref Vector2, ref Vector2, out Vector2)](VRageMath.Vector2.Divide)|Divides the components of a vector by the components of another vector.|
|[static Vector2 Divide(Vector2, float)](VRageMath.Vector2.Divide)|Divides a vector by a scalar value.|
|[static void Divide(ref Vector2, float, out Vector2)](VRageMath.Vector2.Divide)|Divides a vector by a scalar value.|
|[static float Dot(Vector2, Vector2)](VRageMath.Vector2.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[static void Dot(ref Vector2, ref Vector2, out float)](VRageMath.Vector2.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[static Vector2 Floor(Vector2)](VRageMath.Vector2.Floor)||
|[static Vector2 Hermite(Vector2, Vector2, Vector2, Vector2, float)](VRageMath.Vector2.Hermite)|Performs a Hermite spline interpolation.|
|[static void Hermite(ref Vector2, ref Vector2, ref Vector2, ref Vector2, float, out Vector2)](VRageMath.Vector2.Hermite)|Performs a Hermite spline interpolation.|
|[static bool IsZero(ref Vector2)](VRageMath.Vector2.IsZero)||
|[static bool IsZero(ref Vector2, float)](VRageMath.Vector2.IsZero)||
|[static bool IsZero(Vector2, float)](VRageMath.Vector2.IsZero)||
|[static Vector2 Lerp(Vector2, Vector2, float)](VRageMath.Vector2.Lerp)|Performs a linear interpolation between two vectors.|
|[static void Lerp(ref Vector2, ref Vector2, float, out Vector2)](VRageMath.Vector2.Lerp)|Performs a linear interpolation between two vectors.|
|[static Vector2 Max(Vector2, Vector2)](VRageMath.Vector2.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[static void Max(ref Vector2, ref Vector2, out Vector2)](VRageMath.Vector2.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[static Vector2 Min(Vector2, Vector2)](VRageMath.Vector2.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[static void Min(ref Vector2, ref Vector2, out Vector2)](VRageMath.Vector2.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[static Vector2 Multiply(Vector2, Vector2)](VRageMath.Vector2.Multiply)|Multiplies the components of two vectors by each other.|
|[static void Multiply(ref Vector2, ref Vector2, out Vector2)](VRageMath.Vector2.Multiply)|Multiplies the components of two vectors by each other.|
|[static Vector2 Multiply(Vector2, float)](VRageMath.Vector2.Multiply)|Multiplies a vector by a scalar value.|
|[static void Multiply(ref Vector2, float, out Vector2)](VRageMath.Vector2.Multiply)|Multiplies a vector by a scalar value.|
|[static Vector2 Negate(Vector2)](VRageMath.Vector2.Negate)|Returns a vector pointing in the opposite direction.|
|[static void Negate(ref Vector2, out Vector2)](VRageMath.Vector2.Negate)|Returns a vector pointing in the opposite direction.|
|[static Vector2 Normalize(Vector2)](VRageMath.Vector2.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[static void Normalize(ref Vector2, out Vector2)](VRageMath.Vector2.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[static Vector2 Reflect(Vector2, Vector2)](VRageMath.Vector2.Reflect)|Determines the reflect vector of the given vector and normal.|
|[static void Reflect(ref Vector2, ref Vector2, out Vector2)](VRageMath.Vector2.Reflect)|Determines the reflect vector of the given vector and normal.|
|[static Vector2 SignNonZero(Vector2)](VRageMath.Vector2.SignNonZero)||
|[static Vector2 SmoothStep(Vector2, Vector2, float)](VRageMath.Vector2.SmoothStep)|Interpolates between two values using a cubic equation.|
|[static void SmoothStep(ref Vector2, ref Vector2, float, out Vector2)](VRageMath.Vector2.SmoothStep)|Interpolates between two values using a cubic equation.|
|[static Vector2 Subtract(Vector2, Vector2)](VRageMath.Vector2.Subtract)|Subtracts a vector from a vector.|
|[static void Subtract(ref Vector2, ref Vector2, out Vector2)](VRageMath.Vector2.Subtract)|Subtracts a vector from a vector.|
|[static Vector2 Transform(Vector2, Matrix)](VRageMath.Vector2.Transform)|Transforms the vector (x, y, 0, 1) by the specified matrix.|
|[static void Transform(ref Vector2, ref Matrix, out Vector2)](VRageMath.Vector2.Transform)|Transforms a Vector2 by the given Matrix.|
|[static Vector2 Transform(Vector2, Quaternion)](VRageMath.Vector2.Transform)|Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|[static void Transform(ref Vector2, ref Quaternion, out Vector2)](VRageMath.Vector2.Transform)|Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.|
|[static void Transform(Vector2\[], ref Matrix, Vector2\[])](VRageMath.Vector2.Transform)|Transforms an array of Vector2s by a specified Matrix.|
|[static void Transform(Vector2\[], int, ref Matrix, Vector2\[], int, int)](VRageMath.Vector2.Transform)|Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.|
|[static void Transform(Vector2\[], ref Quaternion, Vector2\[])](VRageMath.Vector2.Transform)|Transforms an array of Vector2s by a specified Quaternion.|
|[static void Transform(Vector2\[], int, ref Quaternion, Vector2\[], int, int)](VRageMath.Vector2.Transform)|Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.|
|[static Vector2 TransformNormal(Vector2, Matrix)](VRageMath.Vector2.TransformNormal)|Transforms a 2D vector normal by a matrix.|
|[static void TransformNormal(ref Vector2, ref Matrix, out Vector2)](VRageMath.Vector2.TransformNormal)|Transforms a vector normal by a matrix.|
|[static void TransformNormal(Vector2\[], ref Matrix, Vector2\[])](VRageMath.Vector2.TransformNormal)|Transforms an array of Vector2 vector normals by a specified Matrix.|
|[static void TransformNormal(Vector2\[], int, ref Matrix, Vector2\[], int, int)](VRageMath.Vector2.TransformNormal)|Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.|
|[void AssertIsValid()](VRageMath.Vector2.AssertIsValid)||
|[bool Between(ref Vector2, ref Vector2)](VRageMath.Vector2.Between)||
|[bool Equals(Vector2)](VRageMath.Vector2.Equals)|Determines whether the specified Object is equal to the Vector2.|
|[bool Equals(object)](VRageMath.Vector2.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[int GetHashCode()](VRageMath.Vector2.GetHashCode)|Gets the hash code of the vector object.|
|[bool IsValid()](VRageMath.Vector2.IsValid)||
|[float Length()](VRageMath.Vector2.Length)|Calculates the length of the vector.|
|[float LengthSquared()](VRageMath.Vector2.LengthSquared)|Calculates the length of the vector squared.|
|[void Normalize()](VRageMath.Vector2.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[void Rotate(double)](VRageMath.Vector2.Rotate)||
|[string ToString()](VRageMath.Vector2.ToString)|Retrieves a string representation of the current object.|

