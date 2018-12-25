← [Index](Api-Index) ← [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)

### Summary

```csharp
public bool HasInventory { get; }
```

Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.

### Returns

[bool](System.Boolean)

