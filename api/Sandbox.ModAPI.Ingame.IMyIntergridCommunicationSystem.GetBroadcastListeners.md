← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [IMyIntergridCommunicationSystem](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem)

### Summary

```csharp
public void GetBroadcastListeners(List broadcastListeners, [Func collect])
```

Retrieves list of all active broadcast listeners and listeners with pending messages, registered by current programmable block. Returned list is snapshot of current state and is not updated by future operations.

### Parameters

* [List<Sandbox.ModAPI.Ingame.IMyBroadcastListener>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1?view=netframework-4.6) broadcastListeners
* [Func<Sandbox.ModAPI.Ingame.IMyBroadcastListener, System.Boolean>](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2?view=netframework-4.6) collect
