← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector4D Struct

```csharp
public struct Vector4D: IEquatable<Vector4\>
```

Defines a vector with four components.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Vector4\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1static Vector4D One](VRageMath.Vector4D.One)||
|\$1static Vector4D UnitW](VRageMath.Vector4D.UnitW)||
|\$1static Vector4D UnitX](VRageMath.Vector4D.UnitX)||
|\$1static Vector4D UnitY](VRageMath.Vector4D.UnitY)||
|\$1static Vector4D UnitZ](VRageMath.Vector4D.UnitZ)||
|\$1static Vector4D Zero](VRageMath.Vector4D.Zero)||
|\$1double W](VRageMath.Vector4D.W)|Gets or sets the w-component of the vector.|
|\$1double X](VRageMath.Vector4D.X)|Gets or sets the x-component of the vector.|
|\$1double Y](VRageMath.Vector4D.Y)|Gets or sets the y-component of the vector.|
|\$1double Z](VRageMath.Vector4D.Z)|Gets or sets the z-component of the vector.|

#### Constructors

|Member|Description|
|---|---|
|\$1Vector4D(double, double, double, double)](VRageMath.Vector4D..ctor)||
|\$1Vector4D(Vector2, double, double)](VRageMath.Vector4D..ctor)||
|\$1Vector4D(Vector3D, double)](VRageMath.Vector4D..ctor)||
|\$1Vector4D(double)](VRageMath.Vector4D..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static Vector4D Add(Vector4D, Vector4D)](VRageMath.Vector4D.Add)|Adds two vectors.|
|\$1static void Add(ref Vector4D, ref Vector4D, out Vector4D)](VRageMath.Vector4D.Add)|Adds two vectors.|
|\$1static Vector4D Barycentric(Vector4D, Vector4D, Vector4D, double, double)](VRageMath.Vector4D.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|\$1static void Barycentric(ref Vector4D, ref Vector4D, ref Vector4D, double, double, out Vector4D)](VRageMath.Vector4D.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|\$1static Vector4D CatmullRom(Vector4D, Vector4D, Vector4D, Vector4D, double)](VRageMath.Vector4D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\$1static void CatmullRom(ref Vector4D, ref Vector4D, ref Vector4D, ref Vector4D, double, out Vector4D)](VRageMath.Vector4D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\$1static Vector4D Clamp(Vector4D, Vector4D, Vector4D)](VRageMath.Vector4D.Clamp)|Restricts a value to be within a specified range.|
|\$1static void Clamp(ref Vector4D, ref Vector4D, ref Vector4D, out Vector4D)](VRageMath.Vector4D.Clamp)|Restricts a value to be within a specified range.|
|\$1static double Distance(Vector4, Vector4)](VRageMath.Vector4D.Distance)|Calculates the distance between two vectors.|
|\$1static void Distance(ref Vector4, ref Vector4, out double)](VRageMath.Vector4D.Distance)|Calculates the distance between two vectors.|
|\$1static double DistanceSquared(Vector4, Vector4)](VRageMath.Vector4D.DistanceSquared)|Calculates the distance between two vectors squared.|
|\$1static void DistanceSquared(ref Vector4, ref Vector4, out double)](VRageMath.Vector4D.DistanceSquared)|Calculates the distance between two vectors squared.|
|\$1static Vector4D Divide(Vector4D, Vector4D)](VRageMath.Vector4D.Divide)|Divides the components of a vector by the components of another vector.|
|\$1static void Divide(ref Vector4D, ref Vector4D, out Vector4D)](VRageMath.Vector4D.Divide)|Divides the components of a vector by the components of another vector.|
|\$1static Vector4D Divide(Vector4D, double)](VRageMath.Vector4D.Divide)|Divides a vector by a scalar value.|
|\$1static void Divide(ref Vector4D, double, out Vector4D)](VRageMath.Vector4D.Divide)|Divides a vector by a scalar value.|
|\$1static double Dot(Vector4, Vector4)](VRageMath.Vector4D.Dot)|Calculates the dot product of two vectors.|
|\$1static void Dot(ref Vector4, ref Vector4, out double)](VRageMath.Vector4D.Dot)|Calculates the dot product of two vectors.|
|\$1static Vector4D Hermite(Vector4D, Vector4D, Vector4D, Vector4D, double)](VRageMath.Vector4D.Hermite)|Performs a Hermite spline interpolation.|
|\$1static void Hermite(ref Vector4D, ref Vector4D, ref Vector4D, ref Vector4D, double, out Vector4D)](VRageMath.Vector4D.Hermite)|Performs a Hermite spline interpolation.|
|\$1static Vector4D Lerp(Vector4D, Vector4D, double)](VRageMath.Vector4D.Lerp)|Performs a linear interpolation between two vectors.|
|\$1static void Lerp(ref Vector4D, ref Vector4D, double, out Vector4D)](VRageMath.Vector4D.Lerp)|Performs a linear interpolation between two vectors.|
|\$1static Vector4 Max(Vector4, Vector4)](VRageMath.Vector4D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|\$1static void Max(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|\$1static Vector4 Min(Vector4, Vector4)](VRageMath.Vector4D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|\$1static void Min(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|\$1static Vector4D Multiply(Vector4D, Vector4D)](VRageMath.Vector4D.Multiply)|Multiplies the components of two vectors by each other.|
|\$1static void Multiply(ref Vector4, ref Vector4, out Vector4)](VRageMath.Vector4D.Multiply)|Multiplies the components of two vectors by each other.|
|\$1static Vector4D Multiply(Vector4D, double)](VRageMath.Vector4D.Multiply)|Multiplies a vector by a scalar.|
|\$1static void Multiply(ref Vector4D, double, out Vector4D)](VRageMath.Vector4D.Multiply)|Multiplies a vector by a scalar value.|
|\$1static Vector4D Negate(Vector4D)](VRageMath.Vector4D.Negate)|Returns a vector pointing in the opposite direction.|
|\$1static void Negate(ref Vector4D, out Vector4D)](VRageMath.Vector4D.Negate)|Returns a vector pointing in the opposite direction.|
|\$1static Vector4D Normalize(Vector4D)](VRageMath.Vector4D.Normalize)|Creates a unit vector from the specified vector.|
|\$1static void Normalize(ref Vector4D, out Vector4D)](VRageMath.Vector4D.Normalize)|Returns a normalized version of the specified vector.|
|\$1static Vector4D PackOrthoMatrix(Vector3D, Vector3, Vector3)](VRageMath.Vector4D.PackOrthoMatrix)||
|\$1static Vector4D PackOrthoMatrix(ref MatrixD)](VRageMath.Vector4D.PackOrthoMatrix)||
|\$1static Vector4D SmoothStep(Vector4D, Vector4D, double)](VRageMath.Vector4D.SmoothStep)|Interpolates between two values using a cubic equation.|
|\$1static void SmoothStep(ref Vector4D, ref Vector4D, double, out Vector4D)](VRageMath.Vector4D.SmoothStep)|Interpolates between two values using a cubic equation.|
|\$1static Vector4 Subtract(Vector4, Vector4)](VRageMath.Vector4D.Subtract)|Subtracts a vector from a vector.|
|\$1static void Subtract(ref Vector4D, ref Vector4D, out Vector4D)](VRageMath.Vector4D.Subtract)|Subtracts a vector from a vector.|
|\$1static Vector4D Transform(Vector2, MatrixD)](VRageMath.Vector4D.Transform)|Transforms a Vector2 by the given Matrix.|
|\$1static void Transform(ref Vector2, ref MatrixD, out Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector2 by the given Matrix.|
|\$1static Vector4D Transform(Vector3D, MatrixD)](VRageMath.Vector4D.Transform)|Transforms a Vector3 by the given Matrix.|
|\$1static void Transform(ref Vector3D, ref MatrixD, out Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector3 by the given Matrix.|
|\$1static Vector4D Transform(Vector4D, MatrixD)](VRageMath.Vector4D.Transform)|Transforms a Vector4 by the specified Matrix.|
|\$1static void Transform(ref Vector4D, ref MatrixD, out Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector4 by the given Matrix.|
|\$1static Vector4D Transform(Vector2, Quaternion)](VRageMath.Vector4D.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|\$1static void Transform(ref Vector2, ref Quaternion, out Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|\$1static Vector4D Transform(Vector3D, Quaternion)](VRageMath.Vector4D.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|\$1static void Transform(ref Vector3D, ref Quaternion, out Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|\$1static Vector4D Transform(Vector4D, Quaternion)](VRageMath.Vector4D.Transform)|Transforms a Vector4 by a specified Quaternion.|
|\$1static void Transform(ref Vector4D, ref Quaternion, out Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector4 by a specified Quaternion.|
|\$1static void Transform(Vector4D\$1], ref MatrixD, Vector4D\$1])](VRageMath.Vector4D.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|\$1static void Transform(Vector4D\$1], int, ref MatrixD, Vector4D\$1], int, int)](VRageMath.Vector4D.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|\$1static void Transform(Vector4D\$1], ref Quaternion, Vector4D\$1])](VRageMath.Vector4D.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|\$1static void Transform(Vector4D\$1], int, ref Quaternion, Vector4D\$1], int, int)](VRageMath.Vector4D.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|\$1static MatrixD UnpackOrthoMatrix(ref Vector4D)](VRageMath.Vector4D.UnpackOrthoMatrix)||
|\$1bool Equals(Vector4)](VRageMath.Vector4D.Equals)|Determines whether the specified Object is equal to the Vector4.|
|\$1bool Equals(object)](VRageMath.Vector4D.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\$1int GetHashCode()](VRageMath.Vector4D.GetHashCode)|Gets the hash code of this object.|
|\$1double Length()](VRageMath.Vector4D.Length)|Calculates the length of the vector.|
|\$1double LengthSquared()](VRageMath.Vector4D.LengthSquared)|Calculates the length of the vector squared.|
|\$1void Normalize()](VRageMath.Vector4D.Normalize)|Turns the current vector into a unit vector.|
|\$1string ToString()](VRageMath.Vector4D.ToString)|Retrieves a string representation of the current object.|

