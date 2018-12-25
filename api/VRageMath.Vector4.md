← [Index](Api-Index)

#### Vector4 Struct

```csharp
public sealed struct Vector4
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector4.X)|Gets or sets the x-component of the vector.|
|[Y](VRageMath.Vector4.Y)|Gets or sets the y-component of the vector.|
|[Z](VRageMath.Vector4.Z)|Gets or sets the z-component of the vector.|
|[W](VRageMath.Vector4.W)|Gets or sets the w-component of the vector.|
|[Zero](VRageMath.Vector4.Zero)||
|[One](VRageMath.Vector4.One)||
|[UnitX](VRageMath.Vector4.UnitX)||
|[UnitY](VRageMath.Vector4.UnitY)||
|[UnitZ](VRageMath.Vector4.UnitZ)||
|[UnitW](VRageMath.Vector4.UnitW)||

#### Properties

|Member|Description|
|---|---|
|[Item](VRageMath.Vector4.Item)||

#### Methods

|Member|Description|
|---|---|
|[PackOrthoMatrix(Vector3, Vector3, Vector3)](VRageMath.Vector4.PackOrthoMatrix)||
|[PackOrthoMatrix(ref Matrix)](VRageMath.Vector4.PackOrthoMatrix)||
|[UnpackOrthoMatrix(ref Vector4)](VRageMath.Vector4.UnpackOrthoMatrix)||
|[UnpackOrthoMatrix(ref Vector4, ref Matrix)](VRageMath.Vector4.UnpackOrthoMatrix)||
|[ToString()](VRageMath.Vector4.ToString)|Retrieves a string representation of the current object.|
|[Equals(Vector4)](VRageMath.Vector4.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[Equals(object)](VRageMath.Vector4.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Vector4.GetHashCode)|Gets the hash code of this object.|
|[Length()](VRageMath.Vector4.Length)|Calculates the length of the vector.|
|[LengthSquared()](VRageMath.Vector4.LengthSquared)|Calculates the length of the vector squared.|
|[Distance(Vector4, Vector4)](VRageMath.Vector4.Distance)|Calculates the distance between two vectors.|
|[Distance(ref Vector4, ref Vector4, ref float)](VRageMath.Vector4.Distance)|Calculates the distance between two vectors.|
|[DistanceSquared(Vector4, Vector4)](VRageMath.Vector4.DistanceSquared)|Calculates the distance between two vectors squared.|
|[DistanceSquared(ref Vector4, ref Vector4, ref float)](VRageMath.Vector4.DistanceSquared)|Calculates the distance between two vectors squared.|
|[Dot(Vector4, Vector4)](VRageMath.Vector4.Dot)|Calculates the dot product of two vectors.|
|[Dot(ref Vector4, ref Vector4, ref float)](VRageMath.Vector4.Dot)|Calculates the dot product of two vectors.|
|[Normalize()](VRageMath.Vector4.Normalize)|Turns the current vector into a unit vector.|
|[Normalize(Vector4)](VRageMath.Vector4.Normalize)|Creates a unit vector from the specified vector.|
|[Normalize(ref Vector4, ref Vector4)](VRageMath.Vector4.Normalize)|Returns a normalized version of the specified vector.|
|[Min(Vector4, Vector4)](VRageMath.Vector4.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Min(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Max(Vector4, Vector4)](VRageMath.Vector4.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Max(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Clamp(Vector4, Vector4, Vector4)](VRageMath.Vector4.Clamp)|Restricts a value to be within a specified range.|
|[Clamp(ref Vector4, ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4.Clamp)|Restricts a value to be within a specified range.|
|[Lerp(Vector4, Vector4, float)](VRageMath.Vector4.Lerp)|Performs a linear interpolation between two vectors.|
|[Lerp(ref Vector4, ref Vector4, float, ref Vector4)](VRageMath.Vector4.Lerp)|Performs a linear interpolation between two vectors.|
|[Barycentric(Vector4, Vector4, Vector4, float, float)](VRageMath.Vector4.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.|
|[Barycentric(ref Vector4, ref Vector4, ref Vector4, float, float, ref Vector4)](VRageMath.Vector4.Barycentric)|Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.|
|[SmoothStep(Vector4, Vector4, float)](VRageMath.Vector4.SmoothStep)|Interpolates between two values using a cubic equation.|
|[SmoothStep(ref Vector4, ref Vector4, float, ref Vector4)](VRageMath.Vector4.SmoothStep)|Interpolates between two values using a cubic equation.|
|[CatmullRom(Vector4, Vector4, Vector4, Vector4, float)](VRageMath.Vector4.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[CatmullRom(ref Vector4, ref Vector4, ref Vector4, ref Vector4, float, ref Vector4)](VRageMath.Vector4.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[Hermite(Vector4, Vector4, Vector4, Vector4, float)](VRageMath.Vector4.Hermite)|Performs a Hermite spline interpolation.|
|[Hermite(ref Vector4, ref Vector4, ref Vector4, ref Vector4, float, ref Vector4)](VRageMath.Vector4.Hermite)|Performs a Hermite spline interpolation.|
|[Transform(Vector2, Matrix)](VRageMath.Vector4.Transform)|Transforms a Vector2 by the given Matrix.|
|[Transform(ref Vector2, ref Matrix, ref Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector2 by the given Matrix.|
|[Transform(Vector3, Matrix)](VRageMath.Vector4.Transform)|Transforms a Vector3 by the given Matrix.|
|[Transform(ref Vector3, ref Matrix, ref Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector3 by the given Matrix.|
|[Transform(Vector4, Matrix)](VRageMath.Vector4.Transform)|Transforms a Vector4 by the specified Matrix.|
|[Transform(ref Vector4, ref Matrix, ref Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector4 by the given Matrix.|
|[Transform(Vector2, Quaternion)](VRageMath.Vector4.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|[Transform(ref Vector2, ref Quaternion, ref Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector2 by a specified Quaternion into a Vector4.|
|[Transform(Vector3, Quaternion)](VRageMath.Vector4.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|[Transform(ref Vector3, ref Quaternion, ref Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector3 by a specified Quaternion into a Vector4.|
|[Transform(Vector4, Quaternion)](VRageMath.Vector4.Transform)|Transforms a Vector4 by a specified Quaternion.|
|[Transform(ref Vector4, ref Quaternion, ref Vector4)](VRageMath.Vector4.Transform)|Transforms a Vector4 by a specified Quaternion.|
|[Transform(Vector4[], ref Matrix, Vector4[])](VRageMath.Vector4.Transform)|Transforms an array of Vector4s by a specified Matrix.|
|[Transform(Vector4[], int, ref Matrix, Vector4[], int, int)](VRageMath.Vector4.Transform)|Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.|
|[Transform(Vector4[], ref Quaternion, Vector4[])](VRageMath.Vector4.Transform)|Transforms an array of Vector4s by a specified Quaternion.|
|[Transform(Vector4[], int, ref Quaternion, Vector4[], int, int)](VRageMath.Vector4.Transform)|Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.|
|[Negate(Vector4)](VRageMath.Vector4.Negate)|Returns a vector pointing in the opposite direction.|
|[Negate(ref Vector4, ref Vector4)](VRageMath.Vector4.Negate)|Returns a vector pointing in the opposite direction.|
|[Add(Vector4, Vector4)](VRageMath.Vector4.Add)|Adds two vectors.|
|[Add(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4.Add)|Adds two vectors.|
|[Subtract(Vector4, Vector4)](VRageMath.Vector4.Subtract)|Subtracts a vector from a vector.|
|[Subtract(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4.Subtract)|Subtracts a vector from a vector.|
|[Multiply(Vector4, Vector4)](VRageMath.Vector4.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(Vector4, float)](VRageMath.Vector4.Multiply)|Multiplies a vector by a scalar.|
|[Multiply(ref Vector4, float, ref Vector4)](VRageMath.Vector4.Multiply)|Multiplies a vector by a scalar value.|
|[Divide(Vector4, Vector4)](VRageMath.Vector4.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(ref Vector4, ref Vector4, ref Vector4)](VRageMath.Vector4.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(Vector4, float)](VRageMath.Vector4.Divide)|Divides a vector by a scalar value.|
|[Divide(ref Vector4, float, ref Vector4)](VRageMath.Vector4.Divide)|Divides a vector by a scalar value.|

