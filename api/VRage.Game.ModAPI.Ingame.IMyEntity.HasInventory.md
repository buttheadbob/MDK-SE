← [Index](Api-Index) ← [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)

### Summary

```csharp
public bool HasInventory { get; }
```

Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

