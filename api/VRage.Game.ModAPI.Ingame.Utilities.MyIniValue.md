← [Index](index)
# MyIniValue Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the value of a single configuration item.
### Fields
|Member|Description|
|---|---|
|[`MyIniKey Key`](VRage.Game.ModAPI.Ingame.Utilities.Key)||
|[`MyIniValue EMPTY`](VRage.Game.ModAPI.Ingame.Utilities.EMPTY)||
### Properties
|Member|Description|
|---|---|
|[`bool IsEmpty`](VRage.Game.ModAPI.Ingame.Utilities.IsEmpty)||
### Methods
|Member|Description|
|---|---|
|[`bool ToBoolean(bool defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToBoolean)|Attempts to get this value as aT:System.Boolean. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetBoolean(ref bool value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetBoolean)||
|[`char ToChar(char defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToChar)|Attempts to get this value as aT:System.Char. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetChar(ref char value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetChar)||
|[`sbyte ToSByte(sbyte defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToSByte)|Attempts to get this value as aT:System.SByte. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetSByte(ref sbyte value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetSByte)||
|[`byte ToByte(byte defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToByte)|Attempts to get this value as aT:System.Byte. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetByte(ref byte value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetByte)||
|[`ushort ToUInt16(ushort defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToUInt16)|Attempts to get this value as aT:System.UInt16. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetUInt16(ref ushort value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetUInt16)||
|[`short ToInt16(short defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToInt16)|Attempts to get this value as aT:System.Int16. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetInt16(ref short value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetInt16)||
|[`uint ToUInt32(uint defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToUInt32)|Attempts to get this value as aT:System.UInt32. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetUInt32(ref uint value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetUInt32)||
|[`int ToInt32(int defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToInt32)|Attempts to get this value as aT:System.Int32. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetInt32(ref int value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetInt32)||
|[`ulong ToUInt64(ulong defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToUInt64)|Attempts to get this value as aT:System.UInt64. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetUInt64(ref ulong value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetUInt64)||
|[`long ToInt64(long defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToInt64)|Attempts to get this value as aT:System.Int64. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetInt64(ref long value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetInt64)||
|[`float ToSingle(float defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToSingle)|Attempts to get this value as aT:System.Single. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetSingle(ref float value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetSingle)||
|[`double ToDouble(double defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToDouble)|Attempts to get this value as aT:System.Double. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetDouble(ref double value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetDouble)||
|[`decimal ToDecimal(decimal defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToDecimal)|Attempts to get this value as aT:System.Decimal. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetDecimal(ref decimal value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetDecimal)||
|[`void GetLines(List<string> lines)`](VRage.Game.ModAPI.Ingame.Utilities.GetLines)|Retrieves each individual line of this value into the provided list.|
|[`string ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)||
|[`string ToString(string defaultValue)`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Attempts to get this value as aT:System.String. If the value is empty or cannot be understood as this data type, the!:defaultValuewill be returned instead.|
|[`bool TryGetString(ref string value)`](VRage.Game.ModAPI.Ingame.Utilities.TryGetString)||
|[`void Write(StringBuilder stringBuilder)`](VRage.Game.ModAPI.Ingame.Utilities.Write)|Writes this value as a string to the given string builder.|
