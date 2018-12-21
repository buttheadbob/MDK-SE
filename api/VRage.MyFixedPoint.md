← [Index](index)
# MyFixedPoint Struct
**Namespace:** [`VRage`](VRage)  
**Assembly:** VRage.Library.dll  
## Summary
Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)
### Fields
|Member|Description|
|---|---|
|[`long RawValue`](VRage.RawValue)||
|[`MyFixedPoint MinValue`](VRage.MinValue)||
|[`MyFixedPoint MaxValue`](VRage.MaxValue)||
|[`MyFixedPoint Zero`](VRage.Zero)||
|[`MyFixedPoint SmallestPossibleValue`](VRage.SmallestPossibleValue)||
|[`MyFixedPoint MaxIntValue`](VRage.MaxIntValue)||
|[`MyFixedPoint MinIntValue`](VRage.MinIntValue)||
### Methods
|Member|Description|
|---|---|
|[`string SerializeString()`](VRage.SerializeString)||
|[`MyFixedPoint DeserializeStringSafe(string text)`](VRage.DeserializeStringSafe)|For XmlSerialization, format is 123.456789 Handles double and decimal formats too.|
|[`MyFixedPoint DeserializeString(string text)`](VRage.DeserializeString)||
|[`bool IsIntegral(MyFixedPoint fp)`](VRage.IsIntegral)||
|[`MyFixedPoint Ceiling(MyFixedPoint a)`](VRage.Ceiling)||
|[`MyFixedPoint Floor(MyFixedPoint a)`](VRage.Floor)||
|[`MyFixedPoint Min(MyFixedPoint a, MyFixedPoint b)`](VRage.Min)||
|[`MyFixedPoint Max(MyFixedPoint a, MyFixedPoint b)`](VRage.Max)||
|[`MyFixedPoint Round(MyFixedPoint a)`](VRage.Round)||
|[`MyFixedPoint AddSafe(MyFixedPoint a, MyFixedPoint b)`](VRage.AddSafe)||
|[`MyFixedPoint MultiplySafe(MyFixedPoint a, float b)`](VRage.MultiplySafe)||
|[`MyFixedPoint MultiplySafe(MyFixedPoint a, int b)`](VRage.MultiplySafe)||
|[`MyFixedPoint MultiplySafe(float a, MyFixedPoint b)`](VRage.MultiplySafe)||
|[`MyFixedPoint MultiplySafe(int a, MyFixedPoint b)`](VRage.MultiplySafe)||
|[`MyFixedPoint MultiplySafe(MyFixedPoint a, MyFixedPoint b)`](VRage.MultiplySafe)||
|[`int ToIntSafe()`](VRage.ToIntSafe)||
|[`string ToString()`](VRage.ToString)||
|[`int GetHashCode()`](VRage.GetHashCode)||
|[`bool Equals(Object obj)`](VRage.Equals)||
