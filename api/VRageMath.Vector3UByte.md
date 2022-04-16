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
|\\$1static EqualityComparer Comparer](VRageMath.Vector3UByte.Comparer)||
|\\$1static Vector3UByte Zero](VRageMath.Vector3UByte.Zero)||
|\\$1byte X](VRageMath.Vector3UByte.X)||
|\\$1byte Y](VRageMath.Vector3UByte.Y)||
|\\$1byte Z](VRageMath.Vector3UByte.Z)||

#### Constructors

|Member|Description|
|---|---|
|\\$1Vector3UByte(byte, byte, byte)](VRageMath.Vector3UByte..ctor)||
|\\$1Vector3UByte(Vector3I)](VRageMath.Vector3UByte..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static Vector3 Denormalize(Vector3UByte, float)](VRageMath.Vector3UByte.Denormalize)|Unpacks Vector3 from Vector3UByte, scales vector from (0, 255) to (-range, range)|
|\\$1static Vector3UByte Floor(Vector3)](VRageMath.Vector3UByte.Floor)||
|\\$1static bool IsMiddle(Vector3UByte)](VRageMath.Vector3UByte.IsMiddle)|Returns true when all components are 127|
|\\$1static Vector3UByte Normalize(Vector3, float)](VRageMath.Vector3UByte.Normalize)|Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";|
|\\$1static Vector3UByte Round(Vector3)](VRageMath.Vector3UByte.Round)||
|\\$1bool Equals(object)](VRageMath.Vector3UByte.Equals)||
|\\$1int GetHashCode()](VRageMath.Vector3UByte.GetHashCode)||
|\\$1int LengthSquared()](VRageMath.Vector3UByte.LengthSquared)||
|\\$1string ToString()](VRageMath.Vector3UByte.ToString)||

