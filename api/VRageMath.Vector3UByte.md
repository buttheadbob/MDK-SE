← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector3UByte Struct

```csharp
public struct Vector3UByte
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector3UByte.X)||
|[Y](VRageMath.Vector3UByte.Y)||
|[Z](VRageMath.Vector3UByte.Z)||
|[Comparer](VRageMath.Vector3UByte.Comparer)||
|[Zero](VRageMath.Vector3UByte.Zero)||

#### Constructors

|Member|Description|
|---|---|
|[Vector3UByte(byte, byte, byte)](VRageMath.Vector3UByte..ctor)||
|[Vector3UByte(Vector3I)](VRageMath.Vector3UByte..ctor)||

#### Methods

|Member|Description|
|---|---|
|[ToString()](VRageMath.Vector3UByte.ToString)||
|[GetHashCode()](VRageMath.Vector3UByte.GetHashCode)||
|[Equals(object)](VRageMath.Vector3UByte.Equals)||
|[Round(Vector3)](VRageMath.Vector3UByte.Round)||
|[Floor(Vector3)](VRageMath.Vector3UByte.Floor)||
|[LengthSquared()](VRageMath.Vector3UByte.LengthSquared)||
|[IsMiddle(Vector3UByte)](VRageMath.Vector3UByte.IsMiddle)|Returns true when all components are 127|
|[Normalize(Vector3, float)](VRageMath.Vector3UByte.Normalize)|Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";|
|[Denormalize(Vector3UByte, float)](VRageMath.Vector3UByte.Denormalize)|Unpacks Vector3 from Vector3UByte, scales vector from (0, 255) to (-range, range)|

