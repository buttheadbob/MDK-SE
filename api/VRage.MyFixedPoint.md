← [Index](index)
# MyFixedPoint Struct
**Namespace:** [`VRage`](VRage)  
**Assembly:** VRage.Library.dll  
## Summary
Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)
### Fields
|Member|Description|
|---|---|
|[`long&nbsp;RawValue`](VRage.RawValue)||
|static&nbsp;[`MyFixedPoint&nbsp;MinValue`](VRage.MinValue)||
|static&nbsp;[`MyFixedPoint&nbsp;MaxValue`](VRage.MaxValue)||
|static&nbsp;[`MyFixedPoint&nbsp;Zero`](VRage.Zero)||
|static&nbsp;[`MyFixedPoint&nbsp;SmallestPossibleValue`](VRage.SmallestPossibleValue)||
|static&nbsp;[`MyFixedPoint&nbsp;MaxIntValue`](VRage.MaxIntValue)||
|static&nbsp;[`MyFixedPoint&nbsp;MinIntValue`](VRage.MinIntValue)||
### Methods
|Member|Description|
|---|---|
|[`string&nbsp;SerializeString()`](VRage.SerializeString)|For XmlSerialization, format is 123.456789|
|static&nbsp;[`MyFixedPoint&nbsp;DeserializeStringSafe(string&nbsp;text)`](VRage.DeserializeStringSafe)|For XmlSerialization, format is 123.456789 Handles double and decimal formats too.|
|static&nbsp;[`MyFixedPoint&nbsp;DeserializeString(string&nbsp;text)`](VRage.DeserializeString)||
|static&nbsp;[`bool&nbsp;IsIntegral(MyFixedPoint&nbsp;fp)`](VRage.IsIntegral)||
|static&nbsp;[`MyFixedPoint&nbsp;Ceiling(MyFixedPoint&nbsp;a)`](VRage.Ceiling)||
|static&nbsp;[`MyFixedPoint&nbsp;Floor(MyFixedPoint&nbsp;a)`](VRage.Floor)||
|static&nbsp;[`MyFixedPoint&nbsp;Min(MyFixedPoint&nbsp;a,&nbsp;MyFixedPoint&nbsp;b)`](VRage.Min)||
|static&nbsp;[`MyFixedPoint&nbsp;Max(MyFixedPoint&nbsp;a,&nbsp;MyFixedPoint&nbsp;b)`](VRage.Max)||
|static&nbsp;[`MyFixedPoint&nbsp;Round(MyFixedPoint&nbsp;a)`](VRage.Round)||
|static&nbsp;[`MyFixedPoint&nbsp;AddSafe(MyFixedPoint&nbsp;a,&nbsp;MyFixedPoint&nbsp;b)`](VRage.AddSafe)||
|static&nbsp;[`MyFixedPoint&nbsp;MultiplySafe(MyFixedPoint&nbsp;a,&nbsp;float&nbsp;b)`](VRage.MultiplySafe)||
|static&nbsp;[`MyFixedPoint&nbsp;MultiplySafe(MyFixedPoint&nbsp;a,&nbsp;int&nbsp;b)`](VRage.MultiplySafe)||
|static&nbsp;[`MyFixedPoint&nbsp;MultiplySafe(float&nbsp;a,&nbsp;MyFixedPoint&nbsp;b)`](VRage.MultiplySafe)||
|static&nbsp;[`MyFixedPoint&nbsp;MultiplySafe(int&nbsp;a,&nbsp;MyFixedPoint&nbsp;b)`](VRage.MultiplySafe)||
|static&nbsp;[`MyFixedPoint&nbsp;MultiplySafe(MyFixedPoint&nbsp;a,&nbsp;MyFixedPoint&nbsp;b)`](VRage.MultiplySafe)||
|[`int&nbsp;ToIntSafe()`](VRage.ToIntSafe)||
|[`string&nbsp;ToString()`](VRage.ToString)||
|[`int&nbsp;GetHashCode()`](VRage.GetHashCode)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRage.Equals)||
