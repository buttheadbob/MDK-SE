← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector4 Struct

```csharp
public struct Vector4: IEquatable<Vector4>
```

Defines a vector with four components.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Vector4>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\$1static Vector4 One](VRageMath.Vector4.One)||
|\\$1static Vector4 UnitW](VRageMath.Vector4.UnitW)||
|\\$1static Vector4 UnitX](VRageMath.Vector4.UnitX)||
|\\$1static Vector4 UnitY](VRageMath.Vector4.UnitY)||
|\\$1static Vector4 UnitZ](VRageMath.Vector4.UnitZ)||
|\\$1static Vector4 Zero](VRageMath.Vector4.Zero)||
|\\$1float W](VRageMath.Vector4.W)|Gets or sets the w-component of the vector.|
|\\$1float X](VRageMath.Vector4.X)|Gets or sets the x-component of the vector.|
|\\$1float Y](VRageMath.Vector4.Y)|Gets or sets the y-component of the vector.|
|\\$1float Z](VRageMath.Vector4.Z)|Gets or sets the z-component of the vector.|

#### Properties

|Member|Description|
|---|---|
|\\$1float Item { get; set; }](VRageMath.Vector4.Item)||

#### Constructors

|Member|Description|
|---|---|
|\\$1Vector4(float, float, float, float)](VRageMath.Vector4..ctor)||
|\\$1Vector4(Vector2, float, float)](VRageMath.Vector4..ctor)||
|\\$1Vector4(Vector3, float)](VRageMath.Vector4..ctor)||
|\\$1Vector4(float)](VRageMath.Vector4..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static Vector4 Add(Vector4, Vector4)](VRageMath.Vector4.Add)|Adds two vectors.|
|\\$1static void Add(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4.Add)|Adds two vectors.|
|\\$1static Vector4 Barycentric(Vector4, Vector4, Vector4, float, float)](VRageMath.Vector4.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|\\$1static void Barycentric(ref Vector4, ref Vector4, ref Vector4, float, float, out Vector4)](VRageMath.Vector4.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|\\$1static Vector4 CatmullRom(Vector4, Vector4, Vector4, Vector4, float)](VRageMath.Vector4.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\\$1static void CatmullRom(ref Vector4, ref Vector4, ref Vector4, ref Vector4, float, out Vector4)](VRageMath.Vector4.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\\$1static Vector4 Clamp(Vector4, Vector4, Vector4)](VRageMath.Vector4.Clamp)|Restricts a value to be within a specified range.|
|\\$1static void Clamp(ref Vector4, ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4.Clamp)|Restricts a value to be within a specified range.|
|\\$1static float Distance(Vector4, Vector4)](VRageMath.Vector4.Distance)|Calculates the distance between two vectors.|
|\\$1static void Distance(ref Vector4, ref Vector4, out float)](VRageMath.Vector4.Distance)|Calculates the distance between two vectors.|
|\\$1static float DistanceSquared(Vector4, Vector4)](VRageMath.Vector4.DistanceSquared)|Calculates the distance between two vectors squared.|
|\\$1static void DistanceSquared(ref Vector4, ref Vector4, out float)](VRageMath.Vector4.DistanceSquared)|Calculates the distance between two vectors squared.|
|\\$1static Vector4 Divide(Vector4, Vector4)](VRageMath.Vector4.Divide)|Divides the components of a vector by the components of another vector.|
|\\$1static void Divide(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4.Divide)|Divides the components of a vector by the components of another vector.|
|\\$1static Vector4 Divide(Vector4, float)](VRageMath.Vector4.Divide)|Divides a vector by a scalar value.|
|\\$1static void Divide(ref Vector4, float, out Vector4)](VRageMath.Vector4.Divide)|Divides a vector by a scalar value.|
|\\$1static float Dot(Vector4, Vector4)](VRageMath.Vector4.Dot)|Calculates the dot product of two vectors.|
|\\$1static void Dot(ref Vector4, ref Vector4, out float)](VRageMath.Vector4.Dot)|Calculates the dot product of two vectors.|
|\\$1static Vector4 Hermite(Vector4, Vector4, Vector4, Vector4, float)](VRageMath.Vector4.Hermite)|Performs a Hermite spline interpolation.|
|\\$1static void Hermite(ref Vector4, ref Vector4, ref Vector4, ref Vector4, float, out Vector4)](VRageMath.Vector4.Hermite)|Performs a Hermite spline interpolation.|
|\\$1static Vector4 Lerp(Vector4, Vector4, float)](VRageMath.Vector4.Lerp)|Performs a linear interpolation between two vectors.|
|\\$1static void Lerp(ref Vector4, ref Vector4, float, out Vector4)](VRageMath.Vector4.Lerp)|Performs a linear interpolation between two vectors.|
|\\$1static Vector4 Max(Vector4, Vector4)](VRageMath.Vector4.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|\\$1static void Max(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|\\$1static Vector4 Min(Vector4, Vector4)](VRageMath.Vector4.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|\\$1static void Min(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|\\$1static Vector4 Multiply(Vector4, Vector4)](VRageMath.Vector4.Multiply)|Multiplies the components of two vectors by each other.|
|\\$1static void Multiply(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4.Multiply)|Multiplies the components of two vectors by each other.|
|\\$1static Vector4 Multiply(Vector4, float)](VRageMath.Vector4.Multiply)|Multiplies a vector by a scalar.|
|\\$1static void Multiply(ref Vector4, float, out Vector4)](VRageMath.Vector4.Multiply)|Multiplies a vector by a scalar value.|
|\\$1static Vector4 Negate(Vector4)](VRageMath.Vector4.Negate)|Returns a vector pointing in the opposite direction.|
|\\$1static void Negate(ref Vector4, out Vector4)](VRageMath.Vector4.Negate)|Returns a vector pointing in the opposite direction.|
|\\$1static Vector4 Normalize(Vector4)](VRageMath.Vector4.Normalize)|Creates a unit vector from the specified vector.|
|\\$1static void Normalize(ref Vector4, out Vector4)](VRageMath.Vector4.Normalize)|Returns a normalized version of the specified vector.|
|\\$1static Vector4 PackOrthoMatrix(Vector3, Vector3, Vector3)](VRageMath.Vector4.PackOrthoMatrix)||
|\\$1static Vector4 PackOrthoMatrix(ref Matrix)](VRageMath.Vector4.PackOrthoMatrix)||
|\\$1static Vector4 SmoothStep(Vector4, Vector4, float)](VRageMath.Vector4.SmoothStep)|Interpolates between two values using a cubic equation.|
|\\$1static void SmoothStep(ref Vector4, ref Vector4, float, out Vector4)](VRageMath.Vector4.SmoothStep)|Interpolates between two values using a cubic equation.|
|\\$1static Vector4 Subtract(Vector4, Vector4)](VRageMath.Vector4.Subtract)|Subtracts a vector from a vector.|
|\\$1static void Subtract(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4.Subtract)|Subtracts a vector from a vector.|
|\\$1static Vector4 Transform(Vector2, Matrix)](VRageMath.Vector4.Transform)|Transforms a Vector2 by the given Matrix.|
|\\$1static void Transform(ref Vector2, ref Matrix, out Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector2 by the given Matrix.|
|\\$1static Vector4 Transform(Vector3, Matrix)](VRageMath.Vector4.Transform)|Transforms a Vector3 by the given Matrix.|
|\\$1static void Transform(ref Vector3, ref Matrix, out Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector3 by the given Matrix.|
|\\$1static Vector4 Transform(Vector4, Matrix)](VRageMath.Vector4.Transform)|Transforms a Vector4 by the specified Matrix.|
|\\$1static void Transform(ref Vector4, ref Matrix, out Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector4 by the given Matrix.|
|\\$1static Vector4 Transform(Vector2, Quaternion)](VRageMath.Vector4.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|\\$1static void Transform(ref Vector2, ref Quaternion, out Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|\\$1static Vector4 Transform(Vector3, Quaternion)](VRageMath.Vector4.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|\\$1static void Transform(ref Vector3, ref Quaternion, out Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|\\$1static Vector4 Transform(Vector4, Quaternion)](VRageMath.Vector4.Transform)|Transforms a Vector4 by a specified Quaternion.|
|\\$1static void Transform(ref Vector4, ref Quaternion, out Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector4 by a specified Quaternion.|
|\\$1static void Transform(Vector4\\$1], ref Matrix, Vector4\\$1])](VRageMath.Vector4.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|\\$1static void Transform(Vector4\\$1], int, ref Matrix, Vector4\\$1], int, int)](VRageMath.Vector4.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|\\$1static void Transform(Vector4\\$1], ref Quaternion, Vector4\\$1])](VRageMath.Vector4.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|\\$1static void Transform(Vector4\\$1], int, ref Quaternion, Vector4\\$1], int, int)](VRageMath.Vector4.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|\\$1static Matrix UnpackOrthoMatrix(ref Vector4)](VRageMath.Vector4.UnpackOrthoMatrix)||
|\\$1static void UnpackOrthoMatrix(ref Vector4, out Matrix)](VRageMath.Vector4.UnpackOrthoMatrix)||
|\\$1bool Equals(Vector4)](VRageMath.Vector4.Equals)|Determines whether the specified Object is equal to the Vector4.|
|\\$1bool Equals(object)](VRageMath.Vector4.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\\$1int GetHashCode()](VRageMath.Vector4.GetHashCode)|Gets the hash code of this object.|
|\\$1float Length()](VRageMath.Vector4.Length)|Calculates the length of the vector.|
|\\$1float LengthSquared()](VRageMath.Vector4.LengthSquared)|Calculates the length of the vector squared.|
|\\$1void Normalize()](VRageMath.Vector4.Normalize)|Turns the current vector into a unit vector.|
|\\$1string ToString()](VRageMath.Vector4.ToString)|Retrieves a string representation of the current object.|

