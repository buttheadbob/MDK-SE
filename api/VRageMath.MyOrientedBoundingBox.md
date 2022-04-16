← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyOrientedBoundingBox Struct

```csharp
public struct MyOrientedBoundingBox: IEquatable<MyOrientedBoundingBox>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<MyOrientedBoundingBox>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1static int CornerCount](VRageMath.MyOrientedBoundingBox.CornerCount)||
|\\%1static Int32\\%1] EndVertices](VRageMath.MyOrientedBoundingBox.EndVertices)||
|\\%1static Int32\\%1] EndXVertices](VRageMath.MyOrientedBoundingBox.EndXVertices)||
|\\%1static Int32\\%1] EndYVertices](VRageMath.MyOrientedBoundingBox.EndYVertices)||
|\\%1static Int32\\%1] EndZVertices](VRageMath.MyOrientedBoundingBox.EndZVertices)||
|\\%1static Int32\\%1] StartVertices](VRageMath.MyOrientedBoundingBox.StartVertices)||
|\\%1static Int32\\%1] StartXVertices](VRageMath.MyOrientedBoundingBox.StartXVertices)||
|\\%1static Int32\\%1] StartYVertices](VRageMath.MyOrientedBoundingBox.StartYVertices)||
|\\%1static Int32\\%1] StartZVertices](VRageMath.MyOrientedBoundingBox.StartZVertices)||
|\\%1static Vector3\\%1] XNeighbourVectorsBack](VRageMath.MyOrientedBoundingBox.XNeighbourVectorsBack)||
|\\%1static Vector3\\%1] XNeighbourVectorsForw](VRageMath.MyOrientedBoundingBox.XNeighbourVectorsForw)||
|\\%1static Vector3\\%1] YNeighbourVectorsBack](VRageMath.MyOrientedBoundingBox.YNeighbourVectorsBack)||
|\\%1static Vector3\\%1] YNeighbourVectorsForw](VRageMath.MyOrientedBoundingBox.YNeighbourVectorsForw)||
|\\%1static Vector3\\%1] ZNeighbourVectorsBack](VRageMath.MyOrientedBoundingBox.ZNeighbourVectorsBack)||
|\\%1static Vector3\\%1] ZNeighbourVectorsForw](VRageMath.MyOrientedBoundingBox.ZNeighbourVectorsForw)||
|\\%1Vector3 Center](VRageMath.MyOrientedBoundingBox.Center)||
|\\%1Vector3 HalfExtent](VRageMath.MyOrientedBoundingBox.HalfExtent)||
|\\%1Quaternion Orientation](VRageMath.MyOrientedBoundingBox.Orientation)||

#### Constructors

|Member|Description|
|---|---|
|\\%1MyOrientedBoundingBox(ref Matrix)](VRageMath.MyOrientedBoundingBox..ctor)||
|\\%1MyOrientedBoundingBox(Vector3, Vector3, Quaternion)](VRageMath.MyOrientedBoundingBox..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static ContainmentType Contains(ref BoundingBox, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\\%1static ContainmentType Contains(BoundingFrustum, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\\%1static ContainmentType Contains(ref BoundingSphere, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\\%1static ContainmentType ContainsRelativeBox(ref Vector3, ref Vector3, ref Matrix)](VRageMath.MyOrientedBoundingBox.ContainsRelativeBox)||
|\\%1static MyOrientedBoundingBox Create(BoundingBox, Matrix)](VRageMath.MyOrientedBoundingBox.Create)||
|\\%1static MyOrientedBoundingBox CreateFromBoundingBox(BoundingBox)](VRageMath.MyOrientedBoundingBox.CreateFromBoundingBox)||
|\\%1static bool GetNormalBetweenEdges(int, int, int, out Vector3)](VRageMath.MyOrientedBoundingBox.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|\\%1ContainmentType Contains(ref BoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\\%1ContainmentType Contains(ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\\%1ContainmentType Contains(BoundingFrustum)](VRageMath.MyOrientedBoundingBox.Contains)||
|\\%1ContainmentType Contains(ref BoundingSphere)](VRageMath.MyOrientedBoundingBox.Contains)||
|\\%1bool Contains(ref Vector3)](VRageMath.MyOrientedBoundingBox.Contains)||
|\\%1BoundingFrustum ConvertToFrustum()](VRageMath.MyOrientedBoundingBox.ConvertToFrustum)||
|\\%1bool Equals(MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Equals)||
|\\%1bool Equals(object)](VRageMath.MyOrientedBoundingBox.Equals)||
|\\%1BoundingBox GetAABB()](VRageMath.MyOrientedBoundingBox.GetAABB)||
|\\%1void GetCorners(Vector3\\%1], int)](VRageMath.MyOrientedBoundingBox.GetCorners)||
|\\%1int GetHashCode()](VRageMath.MyOrientedBoundingBox.GetHashCode)||
|\\%1bool Intersects(ref BoundingBox)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\\%1bool Intersects(ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\\%1bool Intersects(BoundingFrustum)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\\%1bool Intersects(ref BoundingSphere)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\\%1float? Intersects(ref Ray)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\\%1float? Intersects(ref Line)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\\%1PlaneIntersectionType Intersects(ref Plane)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\\%1string ToString()](VRageMath.MyOrientedBoundingBox.ToString)||
|\\%1MyOrientedBoundingBox Transform(Quaternion, Vector3)](VRageMath.MyOrientedBoundingBox.Transform)||
|\\%1MyOrientedBoundingBox Transform(float, Quaternion, Vector3)](VRageMath.MyOrientedBoundingBox.Transform)||
|\\%1void Transform(Matrix)](VRageMath.MyOrientedBoundingBox.Transform)||

