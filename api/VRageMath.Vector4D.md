← [Index](Api-Index)

#### Vector4D Struct

```csharp
private public sealed struct.Vector4D
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector4D.X)|Gets or sets the x-component of the vector.|
|[Y](VRageMath.Vector4D.Y)|Gets or sets the y-component of the vector.|
|[Z](VRageMath.Vector4D.Z)|Gets or sets the z-component of the vector.|
|[W](VRageMath.Vector4D.W)|Gets or sets the w-component of the vector.|
|[Zero](VRageMath.Vector4D.Zero)||
|[One](VRageMath.Vector4D.One)||
|[UnitX](VRageMath.Vector4D.UnitX)||
|[UnitY](VRageMath.Vector4D.UnitY)||
|[UnitZ](VRageMath.Vector4D.UnitZ)||
|[UnitW](VRageMath.Vector4D.UnitW)||

#### Methods

|Member|Description|
|---|---|
|[PackOrthoMatrix(Vector3D, Vector3D, Vector3D)](VRageMath.Vector4D.PackOrthoMatrix)||
|[PackOrthoMatrix(ref MatrixD)](VRageMath.Vector4D.PackOrthoMatrix)||
|[UnpackOrthoMatrix(ref Vector4D)](VRageMath.Vector4D.UnpackOrthoMatrix)||
|[ToString()](VRageMath.Vector4D.ToString)|Retrieves a string representation of the current object.|
|[Equals(Vector4)](VRageMath.Vector4D.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[Equals(object)](VRageMath.Vector4D.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Vector4D.GetHashCode)|Gets the hash code of this object.|
|[Length()](VRageMath.Vector4D.Length)|Calculates the length of the vector.|
|[LengthSquared()](VRageMath.Vector4D.LengthSquared)|Calculates the length of the vector squared.|
|[Distance(Vector4, Vector4)](VRageMath.Vector4D.Distance)|Calculates the distance between two vectors.|
|[Distance(ref Vector4, ref Vector4, ref double)](VRageMath.Vector4D.Distance)|Calculates the distance between two vectors.|
|[DistanceSquared(Vector4, Vector4)](VRageMath.Vector4D.DistanceSquared)|Calculates the distance between two vectors squared.|
|[DistanceSquared(ref Vector4, ref Vector4, ref double)](VRageMath.Vector4D.DistanceSquared)|Calculates the distance between two vectors squared.|
|[Dot(Vector4, Vector4)](VRageMath.Vector4D.Dot)|Calculates the dot product of two vectors.|
|[Dot(ref Vector4, ref Vector4, ref double)](VRageMath.Vector4D.Dot)|Calculates the dot product of two vectors.|
|[Normalize()](VRageMath.Vector4D.Normalize)|Turns the current vector into a unit vector.|
|[Normalize(Vector4D)](VRageMath.Vector4D.Normalize)|Creates a unit vector from the specified vector.|
|[Normalize(ref Vector4D, ref Vector4D)](VRageMath.Vector4D.Normalize)|Returns a normalized version of the specified vector.|
|[Min(Vector4, Vector4)](VRageMath.Vector4D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Min(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Max(Vector4, Vector4)](VRageMath.Vector4D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Max(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Clamp(Vector4D, Vector4D, Vector4D)](VRageMath.Vector4D.Clamp)|Restricts a value to be within a specified range.|
|[Clamp(ref Vector4D, ref Vector4D, ref Vector4D, ref Vector4D)](VRageMath.Vector4D.Clamp)|Restricts a value to be within a specified range.|
|[Lerp(Vector4D, Vector4D, double)](VRageMath.Vector4D.Lerp)|Performs a linear interpolation between two vectors.|
|[Lerp(ref Vector4D, ref Vector4D, double, ref Vector4D)](VRageMath.Vector4D.Lerp)|Performs a linear interpolation between two vectors.|
|[Barycentric(Vector4D, Vector4D, Vector4D, double, double)](VRageMath.Vector4D.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|[Barycentric(ref Vector4D, ref Vector4D, ref Vector4D, double, double, ref Vector4D)](VRageMath.Vector4D.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|[SmoothStep(Vector4D, Vector4D, double)](VRageMath.Vector4D.SmoothStep)|Interpolates between two values using a cubic equation.|
|[SmoothStep(ref Vector4D, ref Vector4D, double, ref Vector4D)](VRageMath.Vector4D.SmoothStep)|Interpolates between two values using a cubic equation.|
|[CatmullRom(Vector4D, Vector4D, Vector4D, Vector4D, double)](VRageMath.Vector4D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[CatmullRom(ref Vector4D, ref Vector4D, ref Vector4D, ref Vector4D, double, ref Vector4D)](VRageMath.Vector4D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[Hermite(Vector4D, Vector4D, Vector4D, Vector4D, double)](VRageMath.Vector4D.Hermite)|Performs a Hermite spline interpolation.|
|[Hermite(ref Vector4D, ref Vector4D, ref Vector4D, ref Vector4D, double, ref Vector4D)](VRageMath.Vector4D.Hermite)|Performs a Hermite spline interpolation.|
|[Transform(Vector2, MatrixD)](VRageMath.Vector4D.Transform)|Transforms a Vector2 by the given Matrix.|
|[Transform(ref Vector2, ref MatrixD, ref Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector2 by the given Matrix.|
|[Transform(Vector3D, MatrixD)](VRageMath.Vector4D.Transform)|Transforms a Vector3 by the given Matrix.|
|[Transform(ref Vector3D, ref MatrixD, ref Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector3 by the given Matrix.|
|[Transform(Vector4D, MatrixD)](VRageMath.Vector4D.Transform)|Transforms a Vector4 by the specified Matrix.|
|[Transform(ref Vector4D, ref MatrixD, ref Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector4 by the given Matrix.|
|[Transform(Vector2, Quaternion)](VRageMath.Vector4D.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|[Transform(ref Vector2, ref Quaternion, ref Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|[Transform(Vector3D, Quaternion)](VRageMath.Vector4D.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|[Transform(ref Vector3D, ref Quaternion, ref Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|[Transform(Vector4D, Quaternion)](VRageMath.Vector4D.Transform)|Transforms a Vector4 by a specified Quaternion.|
|[Transform(ref Vector4D, ref Quaternion, ref Vector4D)](VRageMath.Vector4D.Transform)|Transforms a Vector4 by a specified Quaternion.|
|[Transform(Vector4D[], ref MatrixD, Vector4D[])](VRageMath.Vector4D.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|[Transform(Vector4D[], int, ref MatrixD, Vector4D[], int, int)](VRageMath.Vector4D.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|[Transform(Vector4D[], ref Quaternion, Vector4D[])](VRageMath.Vector4D.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|[Transform(Vector4D[], int, ref Quaternion, Vector4D[], int, int)](VRageMath.Vector4D.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|[Negate(Vector4D)](VRageMath.Vector4D.Negate)|Returns a vector pointing in the opposite direction.|
|[Negate(ref Vector4D, ref Vector4D)](VRageMath.Vector4D.Negate)|Returns a vector pointing in the opposite direction.|
|[Add(Vector4D, Vector4D)](VRageMath.Vector4D.Add)|Adds two vectors.|
|[Add(ref Vector4D, ref Vector4D, ref Vector4D)](VRageMath.Vector4D.Add)|Adds two vectors.|
|[Subtract(Vector4, Vector4)](VRageMath.Vector4D.Subtract)|Subtracts a vector from a vector.|
|[Subtract(ref Vector4D, ref Vector4D, ref Vector4D)](VRageMath.Vector4D.Subtract)|Subtracts a vector from a vector.|
|[Multiply(Vector4D, Vector4D)](VRageMath.Vector4D.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4D.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(Vector4D, double)](VRageMath.Vector4D.Multiply)|Multiplies a vector by a scalar.|
|[Multiply(ref Vector4D, double, ref Vector4D)](VRageMath.Vector4D.Multiply)|Multiplies a vector by a scalar value.|
|[Divide(Vector4D, Vector4D)](VRageMath.Vector4D.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(ref Vector4D, ref Vector4D, ref Vector4D)](VRageMath.Vector4D.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(Vector4D, double)](VRageMath.Vector4D.Divide)|Divides a vector by a scalar value.|
|[Divide(ref Vector4D, double, ref Vector4D)](VRageMath.Vector4D.Divide)|Divides a vector by a scalar value.|

