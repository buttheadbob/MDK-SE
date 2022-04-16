← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyOrientedBoundingBoxD Struct

```csharp
public struct MyOrientedBoundingBoxD: IEquatable<MyOrientedBoundingBox>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable&lt;MyOrientedBoundingBox&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

[static int CornerCount](VRageMath.MyOrientedBoundingBoxD.CornerCount)

> 

[static Int32&#91&#93; EndVertices](VRageMath.MyOrientedBoundingBoxD.EndVertices)

> 

[static Int32&#91&#93; EndXVertices](VRageMath.MyOrientedBoundingBoxD.EndXVertices)

> 

[static Int32&#91&#93; EndYVertices](VRageMath.MyOrientedBoundingBoxD.EndYVertices)

> 

[static Int32&#91&#93; EndZVertices](VRageMath.MyOrientedBoundingBoxD.EndZVertices)

> 

[static Int32&#91&#93; StartVertices](VRageMath.MyOrientedBoundingBoxD.StartVertices)

> 

[static Int32&#91&#93; StartXVertices](VRageMath.MyOrientedBoundingBoxD.StartXVertices)

> 

[static Int32&#91&#93; StartYVertices](VRageMath.MyOrientedBoundingBoxD.StartYVertices)

> 

[static Int32&#91&#93; StartZVertices](VRageMath.MyOrientedBoundingBoxD.StartZVertices)

> 

[static Vector3&#91&#93; XNeighbourVectorsBack](VRageMath.MyOrientedBoundingBoxD.XNeighbourVectorsBack)

> 

[static Vector3&#91&#93; XNeighbourVectorsForw](VRageMath.MyOrientedBoundingBoxD.XNeighbourVectorsForw)

> 

[static Vector3&#91&#93; YNeighbourVectorsBack](VRageMath.MyOrientedBoundingBoxD.YNeighbourVectorsBack)

> 

[static Vector3&#91&#93; YNeighbourVectorsForw](VRageMath.MyOrientedBoundingBoxD.YNeighbourVectorsForw)

> 

[static Vector3&#91&#93; ZNeighbourVectorsBack](VRageMath.MyOrientedBoundingBoxD.ZNeighbourVectorsBack)

> 

[static Vector3&#91&#93; ZNeighbourVectorsForw](VRageMath.MyOrientedBoundingBoxD.ZNeighbourVectorsForw)

> 

[Vector3D Center](VRageMath.MyOrientedBoundingBoxD.Center)

> 

[Vector3D HalfExtent](VRageMath.MyOrientedBoundingBoxD.HalfExtent)

> 

[Quaternion Orientation](VRageMath.MyOrientedBoundingBoxD.Orientation)

> 

#### Constructors

[MyOrientedBoundingBoxD(MatrixD)](VRageMath.MyOrientedBoundingBoxD..ctor)

> 

[MyOrientedBoundingBoxD(Vector3D, Vector3D, Quaternion)](VRageMath.MyOrientedBoundingBoxD..ctor)

> 

[MyOrientedBoundingBoxD(BoundingBoxD, MatrixD)](VRageMath.MyOrientedBoundingBoxD..ctor)

> 

#### Methods

[static ContainmentType Contains(ref BoundingBox, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[static ContainmentType Contains(BoundingFrustumD, ref MyOrientedBoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[static ContainmentType Contains(ref BoundingSphere, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[static ContainmentType ContainsRelativeBox(ref Vector3D, ref Vector3D, ref MatrixD)](VRageMath.MyOrientedBoundingBoxD.ContainsRelativeBox)

> 

[static MyOrientedBoundingBoxD Create(BoundingBoxD, MatrixD)](VRageMath.MyOrientedBoundingBoxD.Create)

> 

[static MyOrientedBoundingBoxD CreateFromBoundingBox(BoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.CreateFromBoundingBox)

> 

[static bool GetNormalBetweenEdges(int, int, int, out Vector3)](VRageMath.MyOrientedBoundingBoxD.GetNormalBetweenEdges)

> Returns normal between two cube edge of same direction

[ContainmentType Contains(ref BoundingBox)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[ContainmentType Contains(ref BoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[ContainmentType Contains(ref MyOrientedBoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[ContainmentType Contains(BoundingFrustumD)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[ContainmentType Contains(ref BoundingSphereD)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[bool Contains(ref Vector3)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[bool Contains(ref Vector3D)](VRageMath.MyOrientedBoundingBoxD.Contains)

> 

[BoundingFrustumD ConvertToFrustum()](VRageMath.MyOrientedBoundingBoxD.ConvertToFrustum)

> 

[float Distance(RayD)](VRageMath.MyOrientedBoundingBoxD.Distance)

> 

[bool Equals(MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBoxD.Equals)

> 

[bool Equals(object)](VRageMath.MyOrientedBoundingBoxD.Equals)

> 

[BoundingBoxD GetAABB()](VRageMath.MyOrientedBoundingBoxD.GetAABB)

> 

[void GetCorners(Vector3D&#91&#93;, int)](VRageMath.MyOrientedBoundingBoxD.GetCorners)

> 

[int GetHashCode()](VRageMath.MyOrientedBoundingBoxD.GetHashCode)

> 

[bool Intersects(ref BoundingBox)](VRageMath.MyOrientedBoundingBoxD.Intersects)

> 

[bool Intersects(ref BoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Intersects)

> 

[bool Intersects(ref MyOrientedBoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Intersects)

> 

[bool Intersects(BoundingFrustumD)](VRageMath.MyOrientedBoundingBoxD.Intersects)

> 

[bool Intersects(ref BoundingSphereD)](VRageMath.MyOrientedBoundingBoxD.Intersects)

> 

[double? Intersects(ref RayD)](VRageMath.MyOrientedBoundingBoxD.Intersects)

> 

[double? Intersects(ref LineD)](VRageMath.MyOrientedBoundingBoxD.Intersects)

> 

[PlaneIntersectionType Intersects(ref PlaneD)](VRageMath.MyOrientedBoundingBoxD.Intersects)

> 

[double? IntersectsOrContains(ref LineD)](VRageMath.MyOrientedBoundingBoxD.IntersectsOrContains)

> 

[string ToString()](VRageMath.MyOrientedBoundingBoxD.ToString)

> 

[MyOrientedBoundingBoxD Transform(Quaternion, Vector3D)](VRageMath.MyOrientedBoundingBoxD.Transform)

> 

[MyOrientedBoundingBoxD Transform(float, Quaternion, Vector3D)](VRageMath.MyOrientedBoundingBoxD.Transform)

> 

[void Transform(MatrixD)](VRageMath.MyOrientedBoundingBoxD.Transform)

> 

[void Transform(ref MatrixD)](VRageMath.MyOrientedBoundingBoxD.Transform)

> 

