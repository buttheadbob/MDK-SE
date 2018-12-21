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
|static [`VRage.MyFixedPoint MinValue`](VRage.MinValue)||
|static [`VRage.MyFixedPoint MaxValue`](VRage.MaxValue)||
|static [`VRage.MyFixedPoint Zero`](VRage.Zero)||
|static [`VRage.MyFixedPoint SmallestPossibleValue`](VRage.SmallestPossibleValue)||
|static [`VRage.MyFixedPoint MaxIntValue`](VRage.MaxIntValue)||
|static [`VRage.MyFixedPoint MinIntValue`](VRage.MinIntValue)||
### Methods
|Member|Description|
|---|---|
|[`string SerializeString()`](VRage.SerializeString)|For XmlSerialization, format is 123.456789|
|static [`VRage.MyFixedPoint DeserializeStringSafe(string)`](VRage.DeserializeStringSafe)|For XmlSerialization, format is 123.456789 Handles double and decimal formats too.|
|static [`VRage.MyFixedPoint DeserializeString(string)`](VRage.DeserializeString)||
|static [`bool IsIntegral(VRage.MyFixedPoint)`](VRage.IsIntegral)||
|static [`VRage.MyFixedPoint Ceiling(VRage.MyFixedPoint)`](VRage.Ceiling)||
|static [`VRage.MyFixedPoint Floor(VRage.MyFixedPoint)`](VRage.Floor)||
|static [`VRage.MyFixedPoint Min(VRage.MyFixedPoint, VRage.MyFixedPoint)`](VRage.Min)||
|static [`VRage.MyFixedPoint Max(VRage.MyFixedPoint, VRage.MyFixedPoint)`](VRage.Max)||
|static [`VRage.MyFixedPoint Round(VRage.MyFixedPoint)`](VRage.Round)||
|static [`VRage.MyFixedPoint AddSafe(VRage.MyFixedPoint, VRage.MyFixedPoint)`](VRage.AddSafe)||
|static [`VRage.MyFixedPoint MultiplySafe(VRage.MyFixedPoint, float)`](VRage.MultiplySafe)||
|static [`VRage.MyFixedPoint MultiplySafe(VRage.MyFixedPoint, int)`](VRage.MultiplySafe)||
|static [`VRage.MyFixedPoint MultiplySafe(float, VRage.MyFixedPoint)`](VRage.MultiplySafe)||
|static [`VRage.MyFixedPoint MultiplySafe(int, VRage.MyFixedPoint)`](VRage.MultiplySafe)||
|static [`VRage.MyFixedPoint MultiplySafe(VRage.MyFixedPoint, VRage.MyFixedPoint)`](VRage.MultiplySafe)||
|[`int ToIntSafe()`](VRage.ToIntSafe)||
|[`string ToString()`](VRage.ToString)||
|[`int GetHashCode()`](VRage.GetHashCode)||
|[`bool Equals(System.Object)`](VRage.Equals)||
