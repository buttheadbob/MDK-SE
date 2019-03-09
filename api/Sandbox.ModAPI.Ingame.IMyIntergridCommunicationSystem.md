← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyIntergridCommunicationSystem Interface

```csharp
public interface IMyIntergridCommunicationSystem
```

This is the entry point for all communication operations.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Properties

|Member|Description|
|---|---|
|[Me](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.Me)|Gets communication address for current programmable block.|
|[UnicastListener](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.UnicastListener)|Gets unicast listener for current programmable block.|

#### Methods

|Member|Description|
|---|---|
|[IsEndpointReachable(long, TransmissionDistance)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.IsEndpointReachable)|Determines if given endpoint is currently reachable. Similar to sending ICMP message.|
|[RegisterBroadcastListener(string)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.RegisterBroadcastListener)|Registers broadcast listener with given tag for current programmable block. In case there is already another active broadcast lister with given tag new listener is NOT registered and the already active one is returned instead.|
|[DisableBroadcastListener(IMyBroadcastListener)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.DisableBroadcastListener)|Disables given broadcast listener. In case given broadcast listener is not active nothing happens. Instance of this broadcast listener remains valid and all pending messages may be accepted as normal. Disabling broadcast listener also disables it's message callback, if active. Consuming the last pending message will permanently disable the the provided listener and it's never going to be activated again. ==> Registering new broadcast lister with the same tag will will allocate new listener instance instead.|
|[GetBroadcastListeners(List, Func)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.GetBroadcastListeners)||
|[SendBroadcastMessage(string, TData, TransmissionDistance)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.SendBroadcastMessage)||
|[SendUnicastMessage(long, string, TData)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.SendUnicastMessage)||
