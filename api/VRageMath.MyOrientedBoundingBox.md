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
|\[static int CornerCount](VRageMath.MyOrientedBoundingBox.CornerCount)||
|\[static Int32\[] EndVertices](VRageMath.MyOrientedBoundingBox.EndVertices)||
|\[static Int32\[] EndXVertices](VRageMath.MyOrientedBoundingBox.EndXVertices)||
|\[static Int32\[] EndYVertices](VRageMath.MyOrientedBoundingBox.EndYVertices)||
|\[static Int32\[] EndZVertices](VRageMath.MyOrientedBoundingBox.EndZVertices)||
|\[static Int32\[] StartVertices](VRageMath.MyOrientedBoundingBox.StartVertices)||
|\[static Int32\[] StartXVertices](VRageMath.MyOrientedBoundingBox.StartXVertices)||
|\[static Int32\[] StartYVertices](VRageMath.MyOrientedBoundingBox.StartYVertices)||
|\[static Int32\[] StartZVertices](VRageMath.MyOrientedBoundingBox.StartZVertices)||
|\[static Vector3\[] XNeighbourVectorsBack](VRageMath.MyOrientedBoundingBox.XNeighbourVectorsBack)||
|\[static Vector3\[] XNeighbourVectorsForw](VRageMath.MyOrientedBoundingBox.XNeighbourVectorsForw)||
|\[static Vector3\[] YNeighbourVectorsBack](VRageMath.MyOrientedBoundingBox.YNeighbourVectorsBack)||
|\[static Vector3\[] YNeighbourVectorsForw](VRageMath.MyOrientedBoundingBox.YNeighbourVectorsForw)||
|\[static Vector3\[] ZNeighbourVectorsBack](VRageMath.MyOrientedBoundingBox.ZNeighbourVectorsBack)||
|\[static Vector3\[] ZNeighbourVectorsForw](VRageMath.MyOrientedBoundingBox.ZNeighbourVectorsForw)||
|\[Vector3 Center](VRageMath.MyOrientedBoundingBox.Center)||
|\[Vector3 HalfExtent](VRageMath.MyOrientedBoundingBox.HalfExtent)||
|\[Quaternion Orientation](VRageMath.MyOrientedBoundingBox.Orientation)||

#### Constructors

|Member|Description|
|---|---|
|\[MyOrientedBoundingBox(ref Matrix)](VRageMath.MyOrientedBoundingBox..ctor)||
|\[MyOrientedBoundingBox(Vector3, Vector3, Quaternion)](VRageMath.MyOrientedBoundingBox..ctor)||

#### Methods

|Member|Description|
|---|---|
|\[static ContainmentType Contains(ref BoundingBox, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\[static ContainmentType Contains(BoundingFrustum, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\[static ContainmentType Contains(ref BoundingSphere, ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\[static ContainmentType ContainsRelativeBox(ref Vector3, ref Vector3, ref Matrix)](VRageMath.MyOrientedBoundingBox.ContainsRelativeBox)||
|\[static MyOrientedBoundingBox Create(BoundingBox, Matrix)](VRageMath.MyOrientedBoundingBox.Create)||
|\[static MyOrientedBoundingBox CreateFromBoundingBox(BoundingBox)](VRageMath.MyOrientedBoundingBox.CreateFromBoundingBox)||
|\[static bool GetNormalBetweenEdges(int, int, int, out Vector3)](VRageMath.MyOrientedBoundingBox.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|\[ContainmentType Contains(ref BoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\[ContainmentType Contains(ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Contains)||
|\[ContainmentType Contains(BoundingFrustum)](VRageMath.MyOrientedBoundingBox.Contains)||
|\[ContainmentType Contains(ref BoundingSphere)](VRageMath.MyOrientedBoundingBox.Contains)||
|\[bool Contains(ref Vector3)](VRageMath.MyOrientedBoundingBox.Contains)||
|\[BoundingFrustum ConvertToFrustum()](VRageMath.MyOrientedBoundingBox.ConvertToFrustum)||
|\[bool Equals(MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Equals)||
|\[bool Equals(object)](VRageMath.MyOrientedBoundingBox.Equals)||
|\[BoundingBox GetAABB()](VRageMath.MyOrientedBoundingBox.GetAABB)||
|\[void GetCorners(Vector3\[], int)](VRageMath.MyOrientedBoundingBox.GetCorners)||
|\[int GetHashCode()](VRageMath.MyOrientedBoundingBox.GetHashCode)||
|\[bool Intersects(ref BoundingBox)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\[bool Intersects(ref MyOrientedBoundingBox)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\[bool Intersects(BoundingFrustum)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\[bool Intersects(ref BoundingSphere)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\[float? Intersects(ref Ray)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\[float? Intersects(ref Line)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\[PlaneIntersectionType Intersects(ref Plane)](VRageMath.MyOrientedBoundingBox.Intersects)||
|\[string ToString()](VRageMath.MyOrientedBoundingBox.ToString)||
|\[MyOrientedBoundingBox Transform(Quaternion, Vector3)](VRageMath.MyOrientedBoundingBox.Transform)||
|\[MyOrientedBoundingBox Transform(float, Quaternion, Vector3)](VRageMath.MyOrientedBoundingBox.Transform)||
|\[void Transform(Matrix)](VRageMath.MyOrientedBoundingBox.Transform)||

