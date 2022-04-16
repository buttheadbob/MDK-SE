← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)

### Summary

```csharp
public bool HasLocalPlayerAccess()
```

Returns if local player can use block. Executes [HasPlayerAccess(long, MyRelationsBetweenPlayerAndBlock = MyRelationsBetweenPlayerAndBlock.NoOwnership)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasPlayerAccess) with local player identityId. On Dedicated Server as identityId it is using 0 as playerId

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean?view=netframework-4.6)

Can player access this block or not. (Result of [HasPlayerAccess(long, MyRelationsBetweenPlayerAndBlock = MyRelationsBetweenPlayerAndBlock.NoOwnership)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasPlayerAccess) function call)

