← [Index](index)
# MyFixedPoint Struct
**Namespace:** [`VRage`](VRage)  
**Assembly:** VRage.Library.dll  
## Summary
Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.RawValue"><code>long RawValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MinValue"><code>MyFixedPoint MinValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MaxValue"><code>MyFixedPoint MaxValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.Zero"><code>MyFixedPoint Zero</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.SmallestPossibleValue"><code>MyFixedPoint SmallestPossibleValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MaxIntValue"><code>MyFixedPoint MaxIntValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MinIntValue"><code>MyFixedPoint MinIntValue</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.SerializeString"><code>string SerializeString()</code></a>_</td><td>For XmlSerialization, format is 123.456789</td></tr>
<tr><td>static _<a href="VRage.DeserializeStringSafe"><code>MyFixedPoint DeserializeStringSafe(string text)</code></a>_</td><td>For XmlSerialization, format is 123.456789 Handles double and decimal formats too.</td></tr>
<tr><td>static _<a href="VRage.DeserializeString"><code>MyFixedPoint DeserializeString(string text)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.IsIntegral"><code>bool IsIntegral(MyFixedPoint fp)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.Ceiling"><code>MyFixedPoint Ceiling(MyFixedPoint a)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.Floor"><code>MyFixedPoint Floor(MyFixedPoint a)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.Min"><code>MyFixedPoint Min(MyFixedPoint a, MyFixedPoint b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.Max"><code>MyFixedPoint Max(MyFixedPoint a, MyFixedPoint b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.Round"><code>MyFixedPoint Round(MyFixedPoint a)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.AddSafe"><code>MyFixedPoint AddSafe(MyFixedPoint a, MyFixedPoint b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MultiplySafe"><code>MyFixedPoint MultiplySafe(MyFixedPoint a, float b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MultiplySafe"><code>MyFixedPoint MultiplySafe(MyFixedPoint a, int b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MultiplySafe"><code>MyFixedPoint MultiplySafe(float a, MyFixedPoint b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MultiplySafe"><code>MyFixedPoint MultiplySafe(int a, MyFixedPoint b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRage.MultiplySafe"><code>MyFixedPoint MultiplySafe(MyFixedPoint a, MyFixedPoint b)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.ToIntSafe"><code>int ToIntSafe()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.ToString"><code>string ToString()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.GetHashCode"><code>int GetHashCode()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Equals"><code>bool Equals(Object obj)</code></a>_</td><td></td></tr>
</table>
