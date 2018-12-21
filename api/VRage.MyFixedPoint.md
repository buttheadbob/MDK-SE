← [Index](index.md)
# MyFixedPoint Struct
**Namespace:** VRage  
**Assembly:** VRage.Library.dll  
## Summary
Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)
### Fields
|Member|Description|
|---|---|
|[`long RawValue`](VRage.RawValue.md)||
|[`MyFixedPoint MinValue`](VRage.MinValue.md)||
|[`MyFixedPoint MaxValue`](VRage.MaxValue.md)||
|[`MyFixedPoint Zero`](VRage.Zero.md)||
|[`MyFixedPoint SmallestPossibleValue`](VRage.SmallestPossibleValue.md)||
|[`MyFixedPoint MaxIntValue`](VRage.MaxIntValue.md)||
|[`MyFixedPoint MinIntValue`](VRage.MinIntValue.md)||
### Methods
|Member|Description|
|---|---|
|[`string SerializeString()`](VRage.SerializeString.md)||
|[`MyFixedPoint DeserializeStringSafe(string text)`](VRage.DeserializeStringSafe.md)|For XmlSerialization, format is 123.456789 Handles double and decimal formats too.|
|[`MyFixedPoint DeserializeString(string text)`](VRage.DeserializeString.md)||
|[`bool IsIntegral(MyFixedPoint fp)`](VRage.IsIntegral.md)||
|[`MyFixedPoint Ceiling(MyFixedPoint a)`](VRage.Ceiling.md)||
|[`MyFixedPoint Floor(MyFixedPoint a)`](VRage.Floor.md)||
|[`MyFixedPoint Min(MyFixedPoint a, MyFixedPoint b)`](VRage.Min.md)||
|[`MyFixedPoint Max(MyFixedPoint a, MyFixedPoint b)`](VRage.Max.md)||
|[`MyFixedPoint Round(MyFixedPoint a)`](VRage.Round.md)||
|[`MyFixedPoint AddSafe(MyFixedPoint a, MyFixedPoint b)`](VRage.AddSafe.md)||
|[`MyFixedPoint MultiplySafe(MyFixedPoint a, float b)`](VRage.MultiplySafe.md)||
|[`MyFixedPoint MultiplySafe(MyFixedPoint a, int b)`](VRage.MultiplySafe.md)||
|[`MyFixedPoint MultiplySafe(float a, MyFixedPoint b)`](VRage.MultiplySafe.md)||
|[`MyFixedPoint MultiplySafe(int a, MyFixedPoint b)`](VRage.MultiplySafe.md)||
|[`MyFixedPoint MultiplySafe(MyFixedPoint a, MyFixedPoint b)`](VRage.MultiplySafe.md)||
|[`int ToIntSafe()`](VRage.ToIntSafe.md)||
|[`string ToString()`](VRage.ToString.md)||
|[`int GetHashCode()`](VRage.GetHashCode.md)||
|[`bool Equals(Object obj)`](VRage.Equals.md)||
