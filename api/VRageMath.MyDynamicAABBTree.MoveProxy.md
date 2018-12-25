← [Index](Api-Index) ← [MyDynamicAABBTree](VRageMath.MyDynamicAABBTree)

### Summary

```csharp
public bool MoveProxy(int proxyId, ref BoundingBox aabb, Vector3 displacement)
```

Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.

### Returns

[bool](System.Boolean)

true if the proxy was re-inserted.

### Parameters

* [int](System.Int32) proxyId
* [BoundingBox](VRageMath.BoundingBox) aabb
* [Vector3](VRageMath.Vector3) displacement
