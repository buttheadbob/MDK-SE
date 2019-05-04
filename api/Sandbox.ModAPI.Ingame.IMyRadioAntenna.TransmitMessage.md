← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [IMyRadioAntenna](Sandbox.ModAPI.Ingame.IMyRadioAntenna)

### Summary

```csharp
public bool TransmitMessage(string message, MyTransmitTarget target)
```

Broadcasts a message to all PB attached to the antenna system. Broadcast is delayed until the start of the next tick, and only one transmission can be sent per tick. Returns false if broadcasting failed for any reason. Limited to 100,000 characters.

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean?view=netframework-4.6)

### Parameters

* [string](https://docs.microsoft.com/en-us/dotnet/api/System.String?view=netframework-4.6) message
* [MyTransmitTarget](Sandbox.ModAPI.Ingame.MyTransmitTarget) target
