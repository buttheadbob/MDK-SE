← [Index](Api-Index)

#MyWaypointInfo Struct

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

###Fields

|Member|Description|
|---|---|
|[Name](Sandbox.ModAPI.Ingame.MyWaypointInfo.Name)|The name of this GPS coordinate|
|[Coords](Sandbox.ModAPI.Ingame.MyWaypointInfo.Coords)|Gets the target coordinate as a [Vector3D](VRageMath.Vector3D) |
|[Empty](Sandbox.ModAPI.Ingame.MyWaypointInfo.Empty)|Returns an empty (undefined) GPS coordinate|

###Methods

|Member|Description|
|---|---|
|[FindAll(string, List)](Sandbox.ModAPI.Ingame.MyWaypointInfo.FindAll)||
|[TryParse(string, ref MyWaypointInfo)](Sandbox.ModAPI.Ingame.MyWaypointInfo.TryParse)|Attempts to parse a GPS coordinate from the given text. The text cannot contain anything but the GPS coordinate.<br /><br />A GPS coordinate has the format GPS:Name:X:Y:Z:|
|[IsEmpty()](Sandbox.ModAPI.Ingame.MyWaypointInfo.IsEmpty)|Determines whether this coordinate is empty (undefined)|
|[ToString()](Sandbox.ModAPI.Ingame.MyWaypointInfo.ToString)|Converts this GPS coordinate to its string equivalent|
|[Equals(MyWaypointInfo)](Sandbox.ModAPI.Ingame.MyWaypointInfo.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[Equals(MyWaypointInfo, double)](Sandbox.ModAPI.Ingame.MyWaypointInfo.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[Equals(object)](Sandbox.ModAPI.Ingame.MyWaypointInfo.Equals)|Determines whether this coordinate is the same as another. Uses 0.0001 as the epsilon to counter floating point inaccuracies.|
|[GetHashCode()](Sandbox.ModAPI.Ingame.MyWaypointInfo.GetHashCode)|Gets the hashcode of this coordinate|

