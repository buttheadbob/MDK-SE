← [Index](index)
# MyFixedPoint Struct
**Namespace:** [`VRage`](VRage)  
**Assembly:** VRage.Library.dll  
## Summary
Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)
### Fields
|Member|Description|
|---|---|
|[`RawValue`](VRage.RawValue)||
|static [`MinValue`](VRage.MinValue)||
|static [`MaxValue`](VRage.MaxValue)||
|static [`Zero`](VRage.Zero)||
|static [`SmallestPossibleValue`](VRage.SmallestPossibleValue)||
|static [`MaxIntValue`](VRage.MaxIntValue)||
|static [`MinIntValue`](VRage.MinIntValue)||
### Methods
|Member|Description|
|---|---|
|[`SerializeString()`](VRage.SerializeString)|For XmlSerialization, format is 123.456789|
|static [`DeserializeStringSafe(string)`](VRage.DeserializeStringSafe)|For XmlSerialization, format is 123.456789 Handles double and decimal formats too.|
|static [`DeserializeString(string)`](VRage.DeserializeString)||
|static [`IsIntegral(MyFixedPoint)`](VRage.IsIntegral)||
|static [`Ceiling(MyFixedPoint)`](VRage.Ceiling)||
|static [`Floor(MyFixedPoint)`](VRage.Floor)||
|static [`Min(MyFixedPoint, MyFixedPoint)`](VRage.Min)||
|static [`Max(MyFixedPoint, MyFixedPoint)`](VRage.Max)||
|static [`Round(MyFixedPoint)`](VRage.Round)||
|static [`AddSafe(MyFixedPoint, MyFixedPoint)`](VRage.AddSafe)||
|static [`MultiplySafe(MyFixedPoint, float)`](VRage.MultiplySafe)||
|static [`MultiplySafe(MyFixedPoint, int)`](VRage.MultiplySafe)||
|static [`MultiplySafe(float, MyFixedPoint)`](VRage.MultiplySafe)||
|static [`MultiplySafe(int, MyFixedPoint)`](VRage.MultiplySafe)||
|static [`MultiplySafe(MyFixedPoint, MyFixedPoint)`](VRage.MultiplySafe)||
|[`ToIntSafe()`](VRage.ToIntSafe)||
|[`ToString()`](VRage.ToString)||
|[`GetHashCode()`](VRage.GetHashCode)||
|[`Equals(Object)`](VRage.Equals)||
