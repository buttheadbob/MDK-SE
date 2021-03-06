← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [IMyCubeGrid](VRage.Game.ModAPI.Ingame.IMyCubeGrid)

### Summary

```csharp
public bool IsSameConstructAs(IMyCubeGrid other)
```

Determines whether this grid is [VRage.Game.ModAPI.GridLinkTypeEnum.Mechanical](https://docs.microsoft.com/en-us/dotnet/api/vrage.game.modapi.gridlinktypeenum.mechanical?view=netframework-4.6) connected to the other. This is any grid connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.  
  
Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean?view=netframework-4.6)

True if grid connected with [VRage.Game.ModAPI.GridLinkTypeEnum.Mechanical](https://docs.microsoft.com/en-us/dotnet/api/vrage.game.modapi.gridlinktypeenum.mechanical?view=netframework-4.6) linking

### Parameters

* [IMyCubeGrid](VRage.Game.ModAPI.Ingame.IMyCubeGrid) other
