← [Index](Api-Index)
# MyFixedPoint Struct
**Namespace:** [`VRage`](VRage)  
**Assembly:** VRage.Library.dll  
## Summary
Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)
### Fields
|Member|Description|
|---|---|
|[`RawValue`](VRage.RawValue)||
|[`MinValue`](VRage.MinValue)||
|[`MaxValue`](VRage.MaxValue)||
|[`Zero`](VRage.Zero)||
|[`SmallestPossibleValue`](VRage.SmallestPossibleValue)||
|[`MaxIntValue`](VRage.MaxIntValue)||
|[`MinIntValue`](VRage.MinIntValue)||
### Methods
|Member|Description|
|---|---|
|[`SerializeString()`](VRage.SerializeString)|For XmlSerialization, format is 123.456789|
|[`DeserializeStringSafe(string)`](VRage.DeserializeStringSafe)|For XmlSerialization, format is 123.456789 Handles double and decimal formats too.|
|[`DeserializeString(string)`](VRage.DeserializeString)||
|[`IsIntegral(MyFixedPoint)`](VRage.IsIntegral)||
|[`Ceiling(MyFixedPoint)`](VRage.Ceiling)||
|[`Floor(MyFixedPoint)`](VRage.Floor)||
|[`Min(MyFixedPoint, MyFixedPoint)`](VRage.Min)||
|[`Max(MyFixedPoint, MyFixedPoint)`](VRage.Max)||
|[`Round(MyFixedPoint)`](VRage.Round)||
|[`AddSafe(MyFixedPoint, MyFixedPoint)`](VRage.AddSafe)||
|[`MultiplySafe(MyFixedPoint, float)`](VRage.MultiplySafe)||
|[`MultiplySafe(MyFixedPoint, int)`](VRage.MultiplySafe)||
|[`MultiplySafe(float, MyFixedPoint)`](VRage.MultiplySafe)||
|[`MultiplySafe(int, MyFixedPoint)`](VRage.MultiplySafe)||
|[`MultiplySafe(MyFixedPoint, MyFixedPoint)`](VRage.MultiplySafe)||
|[`ToIntSafe()`](VRage.ToIntSafe)||
|[`ToString()`](VRage.ToString)||
|[`GetHashCode()`](VRage.GetHashCode)||
|[`Equals(Object)`](VRage.Equals)||
