← [Index](Api-Index) ← [MyDynamicAABBTree](VRageMath.MyDynamicAABBTree)

```csharp[bool](System.Boolean) MoveProxy([int](System.Int32) proxyId, ref [BoundingBox](VRageMath.BoundingBox) aabb, [Vector3](VRageMath.Vector3) displacement)```##### Summary

Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.

##### Returns

true if the proxy was re-inserted.

