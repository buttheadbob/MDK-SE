← [Index](Api-Index) ← [MyDynamicAABBTreeD](VRageMath.MyDynamicAABBTreeD)

[int](System.Int32) NullNode

## Summary

A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.

