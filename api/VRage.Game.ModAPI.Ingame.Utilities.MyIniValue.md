← [Index](Api-Index)

### MyIniValue Struct

```csharp
private public sealed MyIniValue
```csharp

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

### Example

### Remarks

###### Fields

|Member|Description|
|---|---|
|[Key](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.Key)|Gets the [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) this value was retrieved from|
|[EMPTY](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.EMPTY)|Represents an empty [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) |

###### Properties

|Member|Description|
|---|---|
|[IsEmpty](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.IsEmpty)|Determines whether this value is empty. Be aware that an empty string is not considered to be an empty value.|

###### Methods

|Member|Description|
|---|---|
|[ToBoolean(bool)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToBoolean)|Attempts to get this value as a [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetBoolean(ref bool)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetBoolean)|Attempts to get this value as a [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) . Fills the`value`on success.|
|[ToChar(char)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToChar)|Attempts to get this value as a [System.Char](https://docs.microsoft.com/en-us/dotnet/api/system.char?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetChar(ref char)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetChar)|Attempts to get this value as a [System.Char](https://docs.microsoft.com/en-us/dotnet/api/system.char?view=netframework-4.6) . Fills the`value`on success.|
|[ToSByte(sbyte)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToSByte)|Attempts to get this value as a [System.SByte](https://docs.microsoft.com/en-us/dotnet/api/system.sbyte?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetSByte(ref sbyte)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetSByte)|Attempts to get this value as a [System.SByte](https://docs.microsoft.com/en-us/dotnet/api/system.sbyte?view=netframework-4.6) . Fills the`value`on success.|
|[ToByte(byte)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToByte)|Attempts to get this value as a [System.Byte](https://docs.microsoft.com/en-us/dotnet/api/system.byte?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetByte(ref byte)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetByte)|Attempts to get this value as a [System.Byte](https://docs.microsoft.com/en-us/dotnet/api/system.byte?view=netframework-4.6) . Fills the`value`on success.|
|[ToUInt16(ushort)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToUInt16)|Attempts to get this value as a [System.UInt16](https://docs.microsoft.com/en-us/dotnet/api/system.uint16?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetUInt16(ref ushort)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetUInt16)|Attempts to get this value as a [System.UInt16](https://docs.microsoft.com/en-us/dotnet/api/system.uint16?view=netframework-4.6) . Fills the`value`on success.|
|[ToInt16(short)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToInt16)|Attempts to get this value as a [System.Int16](https://docs.microsoft.com/en-us/dotnet/api/system.int16?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetInt16(ref short)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetInt16)|Attempts to get this value as a [System.Int16](https://docs.microsoft.com/en-us/dotnet/api/system.int16?view=netframework-4.6) . Fills the`value`on success.|
|[ToUInt32(uint)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToUInt32)|Attempts to get this value as a [System.UInt32](https://docs.microsoft.com/en-us/dotnet/api/system.uint32?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetUInt32(ref uint)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetUInt32)|Attempts to get this value as a [System.UInt32](https://docs.microsoft.com/en-us/dotnet/api/system.uint32?view=netframework-4.6) . Fills the`value`on success.|
|[ToInt32(int)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToInt32)|Attempts to get this value as a [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetInt32(ref int)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetInt32)|Attempts to get this value as a [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32?view=netframework-4.6) . Fills the`value`on success.|
|[ToUInt64(ulong)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToUInt64)|Attempts to get this value as a [System.UInt64](https://docs.microsoft.com/en-us/dotnet/api/system.uint64?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetUInt64(ref ulong)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetUInt64)|Attempts to get this value as a [System.UInt64](https://docs.microsoft.com/en-us/dotnet/api/system.uint64?view=netframework-4.6) . Fills the`value`on success.|
|[ToInt64(long)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToInt64)|Attempts to get this value as a [System.Int64](https://docs.microsoft.com/en-us/dotnet/api/system.int64?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetInt64(ref long)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetInt64)|Attempts to get this value as a [System.Int64](https://docs.microsoft.com/en-us/dotnet/api/system.int64?view=netframework-4.6) . Fills the`value`on success.|
|[ToSingle(float)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToSingle)|Attempts to get this value as a [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetSingle(ref float)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetSingle)|Attempts to get this value as a [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) . Fills the`value`on success.|
|[ToDouble(double)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToDouble)|Attempts to get this value as a [System.Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetDouble(ref double)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetDouble)|Attempts to get this value as a [System.Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) . Fills the`value`on success.|
|[ToDecimal(decimal)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToDecimal)|Attempts to get this value as a [System.Decimal](https://docs.microsoft.com/en-us/dotnet/api/system.decimal?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetDecimal(ref decimal)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetDecimal)|Attempts to get this value as a [System.Decimal](https://docs.microsoft.com/en-us/dotnet/api/system.decimal?view=netframework-4.6) . Fills the`value`on success.|
|[GetLines(List)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.GetLines)||
|[ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, an empty string will be returned instead.|
|[ToString(string)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.ToString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the defaultValue will be returned instead.|
|[TryGetString(ref string)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.TryGetString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . Fills the`value`on success.|
|[Write(StringBuilder)](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue.Write)|Writes this value as a string to the given string builder.|

