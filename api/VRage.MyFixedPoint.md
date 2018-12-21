← [Index](index)
# MyFixedPoint Struct
**Namespace:** [`VRage`](VRage)  
**Assembly:** VRage.Library.dll  
## Summary
Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)
### Fields
<table style="width:100%;display:table">
<tr><td>[`long RawValue`](VRage.RawValue)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MinValue`](VRage.MinValue)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MaxValue`](VRage.MaxValue)</td><td></td></tr>
<tr><td>static [`MyFixedPoint Zero`](VRage.Zero)</td><td></td></tr>
<tr><td>static [`MyFixedPoint SmallestPossibleValue`](VRage.SmallestPossibleValue)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MaxIntValue`](VRage.MaxIntValue)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MinIntValue`](VRage.MinIntValue)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`string SerializeString()`](VRage.SerializeString)</td><td>For XmlSerialization, format is 123.456789</td></tr>
<tr><td>static [`MyFixedPoint DeserializeStringSafe(string text)`](VRage.DeserializeStringSafe)</td><td>For XmlSerialization, format is 123.456789 Handles double and decimal formats too.</td></tr>
<tr><td>static [`MyFixedPoint DeserializeString(string text)`](VRage.DeserializeString)</td><td></td></tr>
<tr><td>static [`bool IsIntegral(MyFixedPoint fp)`](VRage.IsIntegral)</td><td></td></tr>
<tr><td>static [`MyFixedPoint Ceiling(MyFixedPoint a)`](VRage.Ceiling)</td><td></td></tr>
<tr><td>static [`MyFixedPoint Floor(MyFixedPoint a)`](VRage.Floor)</td><td></td></tr>
<tr><td>static [`MyFixedPoint Min(MyFixedPoint a, MyFixedPoint b)`](VRage.Min)</td><td></td></tr>
<tr><td>static [`MyFixedPoint Max(MyFixedPoint a, MyFixedPoint b)`](VRage.Max)</td><td></td></tr>
<tr><td>static [`MyFixedPoint Round(MyFixedPoint a)`](VRage.Round)</td><td></td></tr>
<tr><td>static [`MyFixedPoint AddSafe(MyFixedPoint a, MyFixedPoint b)`](VRage.AddSafe)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MultiplySafe(MyFixedPoint a, float b)`](VRage.MultiplySafe)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MultiplySafe(MyFixedPoint a, int b)`](VRage.MultiplySafe)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MultiplySafe(float a, MyFixedPoint b)`](VRage.MultiplySafe)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MultiplySafe(int a, MyFixedPoint b)`](VRage.MultiplySafe)</td><td></td></tr>
<tr><td>static [`MyFixedPoint MultiplySafe(MyFixedPoint a, MyFixedPoint b)`](VRage.MultiplySafe)</td><td></td></tr>
<tr><td>[`int ToIntSafe()`](VRage.ToIntSafe)</td><td></td></tr>
<tr><td>[`string ToString()`](VRage.ToString)</td><td></td></tr>
<tr><td>[`int GetHashCode()`](VRage.GetHashCode)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRage.Equals)</td><td></td></tr>
</table>
