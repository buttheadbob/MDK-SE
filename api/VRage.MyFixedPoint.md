← [Index](index)
# MyFixedPoint Struct
**Namespace:** [`VRage`](VRage)  
**Assembly:** VRage.Library.dll  
## Summary
Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)
### Fields
|Member|Description|
|---|---|
|[`long RawValue`](VRage.RawValue)||
|static [`MyFixedPoint MinValue`](VRage.MinValue)||
|static [`MyFixedPoint MaxValue`](VRage.MaxValue)||
|static [`MyFixedPoint Zero`](VRage.Zero)||
|static [`MyFixedPoint SmallestPossibleValue`](VRage.SmallestPossibleValue)||
|static [`MyFixedPoint MaxIntValue`](VRage.MaxIntValue)||
|static [`MyFixedPoint MinIntValue`](VRage.MinIntValue)||
### Methods
|Member|Description|
|---|---|
|[`string SerializeString()`](VRage.SerializeString)|For XmlSerialization, format is 123.456789|
|static [`MyFixedPoint DeserializeStringSafe(string text)`](VRage.DeserializeStringSafe)|For XmlSerialization, format is 123.456789 Handles double and decimal formats too.|
|static [`MyFixedPoint DeserializeString(string text)`](VRage.DeserializeString)||
|static [`bool IsIntegral(MyFixedPoint fp)`](VRage.IsIntegral)||
|static [`MyFixedPoint Ceiling(MyFixedPoint a)`](VRage.Ceiling)||
|static [`MyFixedPoint Floor(MyFixedPoint a)`](VRage.Floor)||
|static [`MyFixedPoint Min(MyFixedPoint a, MyFixedPoint b)`](VRage.Min)||
|static [`MyFixedPoint Max(MyFixedPoint a, MyFixedPoint b)`](VRage.Max)||
|static [`MyFixedPoint Round(MyFixedPoint a)`](VRage.Round)||
|static [`MyFixedPoint AddSafe(MyFixedPoint a, MyFixedPoint b)`](VRage.AddSafe)||
|static [`MyFixedPoint MultiplySafe(MyFixedPoint a, float b)`](VRage.MultiplySafe)||
|static [`MyFixedPoint MultiplySafe(MyFixedPoint a, int b)`](VRage.MultiplySafe)||
|static [`MyFixedPoint MultiplySafe(float a, MyFixedPoint b)`](VRage.MultiplySafe)||
|static [`MyFixedPoint MultiplySafe(int a, MyFixedPoint b)`](VRage.MultiplySafe)||
|static [`MyFixedPoint MultiplySafe(MyFixedPoint a, MyFixedPoint b)`](VRage.MultiplySafe)||
|[`int ToIntSafe()`](VRage.ToIntSafe)||
|[`string ToString()`](VRage.ToString)||
|[`int GetHashCode()`](VRage.GetHashCode)||
|[`bool Equals(Object obj)`](VRage.Equals)||
