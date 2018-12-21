← [Index](index)
# MyIniValue Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the value of a single configuration item.
### Fields
|Member|Description|
|---|---|
|[`MyIniKey Key`](VRage.Game.ModAPI.Ingame.Utilities.Key)|Gets the [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) this value was retrieved from|
|static [`MyIniValue EMPTY`](VRage.Game.ModAPI.Ingame.Utilities.EMPTY)|Represents an empty [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue)|
### Properties
|Member|Description|
|---|---|
|[`bool IsEmpty`](VRage.Game.ModAPI.Ingame.Utilities.IsEmpty)|Determines whether this value is empty. Be aware that an empty string is not considered to be an empty value.|
### Methods
|Member|Description|
|---|---|
|[`bool ToBoolean(bool defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToBoolean)|Attempts to get this value as a [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetBoolean(ref bool value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetBoolean)|Attempts to get this value as a [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) . Fills the`value`on success.|
|[`char ToChar(char defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToChar)|Attempts to get this value as a [System.Char](https://docs.microsoft.com/en-us/dotnet/api/system.char?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetChar(ref char value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetChar)|Attempts to get this value as a [System.Char](https://docs.microsoft.com/en-us/dotnet/api/system.char?view=netframework-4.6) . Fills the`value`on success.|
|[`sbyte ToSByte(sbyte defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToSByte)|Attempts to get this value as a [System.SByte](https://docs.microsoft.com/en-us/dotnet/api/system.sbyte?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetSByte(ref sbyte value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetSByte)|Attempts to get this value as a [System.SByte](https://docs.microsoft.com/en-us/dotnet/api/system.sbyte?view=netframework-4.6) . Fills the`value`on success.|
|[`byte ToByte(byte defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToByte)|Attempts to get this value as a [System.Byte](https://docs.microsoft.com/en-us/dotnet/api/system.byte?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetByte(ref byte value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetByte)|Attempts to get this value as a [System.Byte](https://docs.microsoft.com/en-us/dotnet/api/system.byte?view=netframework-4.6) . Fills the`value`on success.|
|[`ushort ToUInt16(ushort defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToUInt16)|Attempts to get this value as a [System.UInt16](https://docs.microsoft.com/en-us/dotnet/api/system.uint16?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetUInt16(ref ushort value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetUInt16)|Attempts to get this value as a [System.UInt16](https://docs.microsoft.com/en-us/dotnet/api/system.uint16?view=netframework-4.6) . Fills the`value`on success.|
|[`short ToInt16(short defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToInt16)|Attempts to get this value as a [System.Int16](https://docs.microsoft.com/en-us/dotnet/api/system.int16?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetInt16(ref short value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetInt16)|Attempts to get this value as a [System.Int16](https://docs.microsoft.com/en-us/dotnet/api/system.int16?view=netframework-4.6) . Fills the`value`on success.|
|[`uint ToUInt32(uint defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToUInt32)|Attempts to get this value as a [System.UInt32](https://docs.microsoft.com/en-us/dotnet/api/system.uint32?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetUInt32(ref uint value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetUInt32)|Attempts to get this value as a [System.UInt32](https://docs.microsoft.com/en-us/dotnet/api/system.uint32?view=netframework-4.6) . Fills the`value`on success.|
|[`int ToInt32(int defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToInt32)|Attempts to get this value as a [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetInt32(ref int value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetInt32)|Attempts to get this value as a [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32?view=netframework-4.6) . Fills the`value`on success.|
|[`ulong ToUInt64(ulong defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToUInt64)|Attempts to get this value as a [System.UInt64](https://docs.microsoft.com/en-us/dotnet/api/system.uint64?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetUInt64(ref ulong value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetUInt64)|Attempts to get this value as a [System.UInt64](https://docs.microsoft.com/en-us/dotnet/api/system.uint64?view=netframework-4.6) . Fills the`value`on success.|
|[`long ToInt64(long defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToInt64)|Attempts to get this value as a [System.Int64](https://docs.microsoft.com/en-us/dotnet/api/system.int64?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetInt64(ref long value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetInt64)|Attempts to get this value as a [System.Int64](https://docs.microsoft.com/en-us/dotnet/api/system.int64?view=netframework-4.6) . Fills the`value`on success.|
|[`float ToSingle(float defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToSingle)|Attempts to get this value as a [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetSingle(ref float value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetSingle)|Attempts to get this value as a [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) . Fills the`value`on success.|
|[`double ToDouble(double defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToDouble)|Attempts to get this value as a [System.Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetDouble(ref double value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetDouble)|Attempts to get this value as a [System.Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) . Fills the`value`on success.|
|[`decimal ToDecimal(decimal defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToDecimal)|Attempts to get this value as a [System.Decimal](https://docs.microsoft.com/en-us/dotnet/api/system.decimal?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetDecimal(ref decimal value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetDecimal)|Attempts to get this value as a [System.Decimal](https://docs.microsoft.com/en-us/dotnet/api/system.decimal?view=netframework-4.6) . Fills the`value`on success.|
|[`void GetLines(List<string> lines)`](VRage.Game.ModAPI.Ingame.Utilities.GetLines)|Retrieves each individual line of this value into the provided list.|
|[`string ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, an empty string will be returned instead.|
|[`string ToString(string defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . If the value is empty or cannot be understood as this data type, the `defaultValue` will be returned instead.|
|[`bool TryGetString(ref string value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetString)|Attempts to get this value as a [System.String](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) . Fills the`value`on success.|
|[`void Write(StringBuilder stringBuilder)`](VRage.Game.ModAPI.Ingame.Utilities.Write)|Writes this value as a string to the given string builder.|
