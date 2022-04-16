← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyFixedPoint Struct

```csharp
public struct MyFixedPoint: IXmlSerializable
```

Fixed point number represented as 64-bit integer with 6 decimal places (one millionts)

**Namespace:** [VRage](VRage)  
**Assembly:** VRage.Library.dll

**Implements:**  
* [IXmlSerializable](https://docs.microsoft.com/en-us/dotnet/api/System.Xml.Serialization.IXmlSerializable?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1static MyFixedPoint MaxIntValue](VRage.MyFixedPoint.MaxIntValue)||
|\\%1static MyFixedPoint MaxValue](VRage.MyFixedPoint.MaxValue)||
|\\%1static MyFixedPoint MinIntValue](VRage.MyFixedPoint.MinIntValue)||
|\\%1static MyFixedPoint MinValue](VRage.MyFixedPoint.MinValue)||
|\\%1static MyFixedPoint SmallestPossibleValue](VRage.MyFixedPoint.SmallestPossibleValue)||
|\\%1static MyFixedPoint Zero](VRage.MyFixedPoint.Zero)||
|\\%1long RawValue](VRage.MyFixedPoint.RawValue)||

#### Methods

|Member|Description|
|---|---|
|\\%1static MyFixedPoint AddSafe(MyFixedPoint, MyFixedPoint)](VRage.MyFixedPoint.AddSafe)||
|\\%1static MyFixedPoint Ceiling(MyFixedPoint)](VRage.MyFixedPoint.Ceiling)||
|\\%1static MyFixedPoint DeserializeString(string)](VRage.MyFixedPoint.DeserializeString)||
|\\%1static MyFixedPoint DeserializeStringSafe(string)](VRage.MyFixedPoint.DeserializeStringSafe)|For XmlSerialization, format is 123.456789 Handles double and decimal formats too.|
|\\%1static MyFixedPoint Floor(MyFixedPoint)](VRage.MyFixedPoint.Floor)||
|\\%1static bool IsIntegral(MyFixedPoint)](VRage.MyFixedPoint.IsIntegral)||
|\\%1static MyFixedPoint Max(MyFixedPoint, MyFixedPoint)](VRage.MyFixedPoint.Max)||
|\\%1static MyFixedPoint Min(MyFixedPoint, MyFixedPoint)](VRage.MyFixedPoint.Min)||
|\\%1static MyFixedPoint MultiplySafe(MyFixedPoint, float)](VRage.MyFixedPoint.MultiplySafe)||
|\\%1static MyFixedPoint MultiplySafe(MyFixedPoint, int)](VRage.MyFixedPoint.MultiplySafe)||
|\\%1static MyFixedPoint MultiplySafe(float, MyFixedPoint)](VRage.MyFixedPoint.MultiplySafe)||
|\\%1static MyFixedPoint MultiplySafe(int, MyFixedPoint)](VRage.MyFixedPoint.MultiplySafe)||
|\\%1static MyFixedPoint MultiplySafe(MyFixedPoint, MyFixedPoint)](VRage.MyFixedPoint.MultiplySafe)||
|\\%1static MyFixedPoint Round(MyFixedPoint)](VRage.MyFixedPoint.Round)||
|\\%1bool Equals(object)](VRage.MyFixedPoint.Equals)||
|\\%1int GetHashCode()](VRage.MyFixedPoint.GetHashCode)||
|\\%1string SerializeString()](VRage.MyFixedPoint.SerializeString)|For XmlSerialization, format is 123.456789|
|\\%1int ToIntSafe()](VRage.MyFixedPoint.ToIntSafe)||
|\\%1string ToString()](VRage.MyFixedPoint.ToString)||

