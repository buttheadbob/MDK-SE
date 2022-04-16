← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Ray Struct

```csharp
public struct Ray: IEquatable<Ray>
```

Defines a ray.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Ray>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\[Vector3 Direction](VRageMath.Ray.Direction)|Unit vector specifying the direction the Ray is pointing.|
|\\[Vector3 Position](VRageMath.Ray.Position)|Specifies the starting point of the Ray.|

#### Constructors

|Member|Description|
|---|---|
|\\[Ray(Vector3, Vector3)](VRageMath.Ray..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\[bool Equals(Ray)](VRageMath.Ray.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|\\[bool Equals(object)](VRageMath.Ray.Equals)|Determines whether two instances of Ray are equal.|
|\\[int GetHashCode()](VRageMath.Ray.GetHashCode)|Gets the hash code for this instance.|
|\\[float? Intersects(BoundingBox)](VRageMath.Ray.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|\\[void Intersects(ref BoundingBox, out float?)](VRageMath.Ray.Intersects)|Checks whether the current Ray intersects a BoundingBox.|
|\\[float? Intersects(BoundingFrustum)](VRageMath.Ray.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|\\[float? Intersects(Plane)](VRageMath.Ray.Intersects)|Determines whether this Ray intersects a specified Plane.|
|\\[void Intersects(ref Plane, out float?)](VRageMath.Ray.Intersects)|Determines whether this Ray intersects a specified Plane.|
|\\[float? Intersects(BoundingSphere)](VRageMath.Ray.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|\\[void Intersects(ref BoundingSphere, out float?)](VRageMath.Ray.Intersects)|Checks whether the current Ray intersects a BoundingSphere.|
|\\[string ToString()](VRageMath.Ray.ToString)|Returns a String that represents the current Ray.|

