← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [MyWaypointInfo](Sandbox.ModAPI.Ingame.MyWaypointInfo)

### Summary

```csharp
public bool TryParse(string text, ref MyWaypointInfo gps)
```

Attempts to parse a GPS coordinate from the given text. The text cannot contain anything but the GPS coordinate.  
  
A GPS coordinate has the format GPS:Name:X:Y:Z:

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)



### Parameters

* [string](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) text
* [MyWaypointInfo](Sandbox.ModAPI.Ingame.MyWaypointInfo) gps
