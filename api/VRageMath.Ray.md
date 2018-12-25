← [Index](Api-Index)

#### Ray Struct

```csharp
public struct Ray: IEquatable<T>
```

Defines a ray.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.iequatable?view=netframework-4.6)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[Position](VRageMath.Ray.Position)|Specifies the starting point of the Ray.|
|[Direction](VRageMath.Ray.Direction)|Unit vector specifying the direction the Ray is pointing.|

#### Methods

|Member|Description|
|---|---|
|[Equals(Ray)](VRageMath.Ray.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|[Equals(object)](VRageMath.Ray.Equals)|Determines whether two instances of Ray are equal.|
|[GetHashCode()](VRageMath.Ray.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.Ray.ToString)|Returns a String that represents the current Ray.|
|[Intersects(BoundingBox)](VRageMath.Ray.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|[Intersects(ref BoundingBox, ref Nullable)](VRageMath.Ray.Intersects)||
|[Intersects(BoundingFrustum)](VRageMath.Ray.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[Intersects(Plane)](VRageMath.Ray.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[Intersects(ref Plane, ref Nullable)](VRageMath.Ray.Intersects)||
|[Intersects(BoundingSphere)](VRageMath.Ray.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|[Intersects(ref BoundingSphere, ref Nullable)](VRageMath.Ray.Intersects)||

