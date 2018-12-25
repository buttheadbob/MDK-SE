← [Index](Api-Index) ← [Vector3D](VRageMath.Vector3D)

```csharp[double](System.Double) Dot([Vector3D](VRageMath.Vector3D) vector1, [Vector3D](VRageMath.Vector3D) vector2)```##### Summary

Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.

```csharp[double](System.Double) Dot([Vector3D](VRageMath.Vector3D) vector1, [Vector3](VRageMath.Vector3) vector2)``````csharpvoid Dot(ref [Vector3D](VRageMath.Vector3D) vector1, ref [Vector3D](VRageMath.Vector3D) vector2, ref [double](System.Double) result)```##### Summary

Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.

```csharpvoid Dot(ref [Vector3D](VRageMath.Vector3D) vector1, ref [Vector3](VRageMath.Vector3) vector2, ref [double](System.Double) result)``````csharpvoid Dot(ref [Vector3](VRageMath.Vector3) vector1, ref [Vector3D](VRageMath.Vector3D) vector2, ref [double](System.Double) result)``````csharp[double](System.Double) Dot([Vector3D](VRageMath.Vector3D) v)``````csharp[double](System.Double) Dot([Vector3](VRageMath.Vector3) v)``````csharp[double](System.Double) Dot(ref [Vector3D](VRageMath.Vector3D) v)```