← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyIniValue Struct

```csharp
public struct MyIniValue
```

Represents the value of a single configuration item.

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

#### Fields

|Member|Description|
|---|---|
|\\%1static MyIniValue EMPTY](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.EMPTY)|Represents an empty [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) |
|\\%1MyIniKey Key](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.Key)|Gets the [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) this value was retrieved from|

#### Properties

|Member|Description|
|---|---|
|\\%1bool IsEmpty { get; }](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.IsEmpty)|Determines whether this value is empty. Be aware that an empty string is not considered to be an empty value.|

#### Constructors

|Member|Description|
|---|---|
|\\%1MyIniValue(MyIniKey, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1void GetLines(List\\%1string>)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.GetLines)|Retrieves each individual line of this value into the provided list.|
|\\%1bool ToBoolean(\\%1bool])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToBoolean)|Attempts to get this value as a [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1byte ToByte(\\%1byte])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToByte)|Attempts to get this value as a [System.Byte](https://docs.microsoft.com/en-us/dotnet/api/system.byte?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1char ToChar(\\%1char])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToChar)|Attempts to get this value as a [System.Char](https://docs.microsoft.com/en-us/dotnet/api/system.char?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1decimal ToDecimal(\\%1decimal])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToDecimal)|Attempts to get this value as a [System.Decimal](https://docs.microsoft.com/en-us/dotnet/api/system.decimal?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1double ToDouble(\\%1double])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToDouble)|Attempts to get this value as a [System.Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1short ToInt16(\\%1short])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToInt16)|Attempts to get this value as a [System.Int16](https://docs.microsoft.com/en-us/dotnet/api/system.int16?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1int ToInt32(\\%1int])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToInt32)|Attempts to get this value as a [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1long ToInt64(\\%1long])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToInt64)|Attempts to get this value as a [System.Int64](https://docs.microsoft.com/en-us/dotnet/api/system.int64?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1sbyte ToSByte(\\%1sbyte])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToSByte)|Attempts to get this value as a [System.SByte](https://docs.microsoft.com/en-us/dotnet/api/system.sbyte?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1float ToSingle(\\%1float])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToSingle)|Attempts to get this value as a [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1string ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, an empty string will be returned instead.|
|\\%1string ToString(string)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1ushort ToUInt16(\\%1ushort])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToUInt16)|Attempts to get this value as a [System.UInt16](https://docs.microsoft.com/en-us/dotnet/api/system.uint16?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1uint ToUInt32(\\%1uint])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToUInt32)|Attempts to get this value as a [System.UInt32](https://docs.microsoft.com/en-us/dotnet/api/system.uint32?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1ulong ToUInt64(\\%1ulong])](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToUInt64)|Attempts to get this value as a [System.UInt64](https://docs.microsoft.com/en-us/dotnet/api/system.uint64?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|\\%1bool TryGetBoolean(out bool)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetBoolean)|Attempts to get this value as a [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetByte(out byte)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetByte)|Attempts to get this value as a [System.Byte](https://docs.microsoft.com/en-us/dotnet/api/system.byte?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetChar(out char)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetChar)|Attempts to get this value as a [System.Char](https://docs.microsoft.com/en-us/dotnet/api/system.char?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetDecimal(out decimal)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetDecimal)|Attempts to get this value as a [System.Decimal](https://docs.microsoft.com/en-us/dotnet/api/system.decimal?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetDouble(out double)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetDouble)|Attempts to get this value as a [System.Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetInt16(out short)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetInt16)|Attempts to get this value as a [System.Int16](https://docs.microsoft.com/en-us/dotnet/api/system.int16?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetInt32(out int)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetInt32)|Attempts to get this value as a [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetInt64(out long)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetInt64)|Attempts to get this value as a [System.Int64](https://docs.microsoft.com/en-us/dotnet/api/system.int64?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetSByte(out sbyte)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetSByte)|Attempts to get this value as a [System.SByte](https://docs.microsoft.com/en-us/dotnet/api/system.sbyte?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetSingle(out float)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetSingle)|Attempts to get this value as a [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetString(out string)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetUInt16(out ushort)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetUInt16)|Attempts to get this value as a [System.UInt16](https://docs.microsoft.com/en-us/dotnet/api/system.uint16?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetUInt32(out uint)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetUInt32)|Attempts to get this value as a [System.UInt32](https://docs.microsoft.com/en-us/dotnet/api/system.uint32?view=netframework-4.6) . Fills the`value`on success.|
|\\%1bool TryGetUInt64(out ulong)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetUInt64)|Attempts to get this value as a [System.UInt64](https://docs.microsoft.com/en-us/dotnet/api/system.uint64?view=netframework-4.6) . Fills the`value`on success.|
|\\%1void Write(StringBuilder)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.Write)|Writes this value as a string to the given string builder.|

