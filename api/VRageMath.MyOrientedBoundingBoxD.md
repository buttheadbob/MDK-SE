← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyOrientedBoundingBoxD Struct

```csharp
public struct MyOrientedBoundingBoxD: IEquatable<MyOrientedBoundingBox\>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<MyOrientedBoundingBox\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1static int CornerCount](VRageMath.MyOrientedBoundingBoxD.CornerCount)||
|\$1static Int32\$1] EndVertices](VRageMath.MyOrientedBoundingBoxD.EndVertices)||
|\$1static Int32\$1] EndXVertices](VRageMath.MyOrientedBoundingBoxD.EndXVertices)||
|\$1static Int32\$1] EndYVertices](VRageMath.MyOrientedBoundingBoxD.EndYVertices)||
|\$1static Int32\$1] EndZVertices](VRageMath.MyOrientedBoundingBoxD.EndZVertices)||
|\$1static Int32\$1] StartVertices](VRageMath.MyOrientedBoundingBoxD.StartVertices)||
|\$1static Int32\$1] StartXVertices](VRageMath.MyOrientedBoundingBoxD.StartXVertices)||
|\$1static Int32\$1] StartYVertices](VRageMath.MyOrientedBoundingBoxD.StartYVertices)||
|\$1static Int32\$1] StartZVertices](VRageMath.MyOrientedBoundingBoxD.StartZVertices)||
|\$1static Vector3\$1] XNeighbourVectorsBack](VRageMath.MyOrientedBoundingBoxD.XNeighbourVectorsBack)||
|\$1static Vector3\$1] XNeighbourVectorsForw](VRageMath.MyOrientedBoundingBoxD.XNeighbourVectorsForw)||
|\$1static Vector3\$1] YNeighbourVectorsBack](VRageMath.MyOrientedBoundingBoxD.YNeighbourVectorsBack)||
|\$1static Vector3\$1] YNeighbourVectorsForw](VRageMath.MyOrientedBoundingBoxD.YNeighbourVectorsForw)||
|\$1static Vector3\$1] ZNeighbourVectorsBack](VRageMath.MyOrientedBoundingBoxD.ZNeighbourVectorsBack)||
|\$1static Vector3\$1] ZNeighbourVectorsForw](VRageMath.MyOrientedBoundingBoxD.ZNeighbourVectorsForw)||
|\$1Vector3D Center](VRageMath.MyOrientedBoundingBoxD.Center)||
|\$1Vector3D HalfExtent](VRageMath.MyOrientedBoundingBoxD.HalfExtent)||
|\$1Quaternion Orientation](VRageMath.MyOrientedBoundingBoxD.Orientation)||

#### Constructors

|Member|Description|
|---|---|
|\$1MyOrientedBoundingBoxD(MatrixD)](VRageMath.MyOrientedBoundingBoxD..ctor)||
|\$1MyOrientedBoundingBoxD(Vector3D, Vector3D, Quaternion)](VRageMath.MyOrientedBoundingBoxD..ctor)||
|\$1MyOrientedBoundingBoxD(BoundingBoxD, MatrixD)](VRageMath.MyOrientedBoundingBoxD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static ContainmentType Contains(ref BoundingBox, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1static ContainmentType Contains(BoundingFrustumD, ref MyOrientedBoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1static ContainmentType Contains(ref BoundingSphere, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1static ContainmentType ContainsRelativeBox(ref Vector3D, ref Vector3D, ref MatrixD)](VRageMath.MyOrientedBoundingBoxD.ContainsRelativeBox)||
|\$1static MyOrientedBoundingBoxD Create(BoundingBoxD, MatrixD)](VRageMath.MyOrientedBoundingBoxD.Create)||
|\$1static MyOrientedBoundingBoxD CreateFromBoundingBox(BoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.CreateFromBoundingBox)||
|\$1static bool GetNormalBetweenEdges(int, int, int, out Vector3)](VRageMath.MyOrientedBoundingBoxD.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|\$1ContainmentType Contains(ref BoundingBox)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1ContainmentType Contains(ref BoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1ContainmentType Contains(ref MyOrientedBoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1ContainmentType Contains(BoundingFrustumD)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1ContainmentType Contains(ref BoundingSphereD)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1bool Contains(ref Vector3)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1bool Contains(ref Vector3D)](VRageMath.MyOrientedBoundingBoxD.Contains)||
|\$1BoundingFrustumD ConvertToFrustum()](VRageMath.MyOrientedBoundingBoxD.ConvertToFrustum)||
|\$1float Distance(RayD)](VRageMath.MyOrientedBoundingBoxD.Distance)||
|\$1bool Equals(MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBoxD.Equals)||
|\$1bool Equals(object)](VRageMath.MyOrientedBoundingBoxD.Equals)||
|\$1BoundingBoxD GetAABB()](VRageMath.MyOrientedBoundingBoxD.GetAABB)||
|\$1void GetCorners(Vector3D\$1], int)](VRageMath.MyOrientedBoundingBoxD.GetCorners)||
|\$1int GetHashCode()](VRageMath.MyOrientedBoundingBoxD.GetHashCode)||
|\$1bool Intersects(ref BoundingBox)](VRageMath.MyOrientedBoundingBoxD.Intersects)||
|\$1bool Intersects(ref BoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Intersects)||
|\$1bool Intersects(ref MyOrientedBoundingBoxD)](VRageMath.MyOrientedBoundingBoxD.Intersects)||
|\$1bool Intersects(BoundingFrustumD)](VRageMath.MyOrientedBoundingBoxD.Intersects)||
|\$1bool Intersects(ref BoundingSphereD)](VRageMath.MyOrientedBoundingBoxD.Intersects)||
|\$1double? Intersects(ref RayD)](VRageMath.MyOrientedBoundingBoxD.Intersects)||
|\$1double? Intersects(ref LineD)](VRageMath.MyOrientedBoundingBoxD.Intersects)||
|\$1PlaneIntersectionType Intersects(ref PlaneD)](VRageMath.MyOrientedBoundingBoxD.Intersects)||
|\$1double? IntersectsOrContains(ref LineD)](VRageMath.MyOrientedBoundingBoxD.IntersectsOrContains)||
|\$1string ToString()](VRageMath.MyOrientedBoundingBoxD.ToString)||
|\$1MyOrientedBoundingBoxD Transform(Quaternion, Vector3D)](VRageMath.MyOrientedBoundingBoxD.Transform)||
|\$1MyOrientedBoundingBoxD Transform(float, Quaternion, Vector3D)](VRageMath.MyOrientedBoundingBoxD.Transform)||
|\$1void Transform(MatrixD)](VRageMath.MyOrientedBoundingBoxD.Transform)||
|\$1void Transform(ref MatrixD)](VRageMath.MyOrientedBoundingBoxD.Transform)||

