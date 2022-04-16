← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyWaypointInfo Struct

```csharp
public struct MyWaypointInfo: IEquatable<MyWaypointInfo>
```

Represents a GPS coordinate

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IEquatable<MyWaypointInfo>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\[static MyWaypointInfo Empty](Sandbox.ModAPI.Ingame.MyWaypointInfo.Empty)|Returns an empty (undefined) GPS coordinate|
|\[Vector3D Coords](Sandbox.ModAPI.Ingame.MyWaypointInfo.Coords)|Gets the target coordinate as a [Vector3D](VRageMath.Vector3D) |
|\[string Name](Sandbox.ModAPI.Ingame.MyWaypointInfo.Name)|The name of this GPS coordinate|

#### Constructors

|Member|Description|
|---|---|
|\[MyWaypointInfo(string, double, double, double)](Sandbox.ModAPI.Ingame.MyWaypointInfo..ctor)||
|\[MyWaypointInfo(string, Vector3D)](Sandbox.ModAPI.Ingame.MyWaypointInfo..ctor)||

#### Methods

|Member|Description|
|---|---|
|\[static void FindAll(string, List\<MyWaypointInfo>)](Sandbox.ModAPI.Ingame.MyWaypointInfo.FindAll)|Searches for all GPS coordinates in the given text.|
|\[static bool TryParse(string, out MyWaypointInfo)](Sandbox.ModAPI.Ingame.MyWaypointInfo.TryParse)|Attempts to parse a GPS coordinate from the given text. The text cannot contain anything but the GPS coordinate.<br /><br />A GPS coordinate has the format GPS:Name:X:Y:Z:|
|\[bool Equals(MyWaypointInfo)](Sandbox.ModAPI.Ingame.MyWaypointInfo.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|\[bool Equals(MyWaypointInfo, double)](Sandbox.ModAPI.Ingame.MyWaypointInfo.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|\[bool Equals(object)](Sandbox.ModAPI.Ingame.MyWaypointInfo.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|\[int GetHashCode()](Sandbox.ModAPI.Ingame.MyWaypointInfo.GetHashCode)|Gets the hashcode of this coordinate|
|\[bool IsEmpty()](Sandbox.ModAPI.Ingame.MyWaypointInfo.IsEmpty)|Determines whether this coordinate is empty (undefined)|
|\[string ToString()](Sandbox.ModAPI.Ingame.MyWaypointInfo.ToString)|Converts this GPS coordinate to its string equivalent|

