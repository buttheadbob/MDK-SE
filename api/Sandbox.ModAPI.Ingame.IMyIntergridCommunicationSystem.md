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
|[long Me { get; }](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.Me)|Gets communication address for current programmable block.|
|[IMyUnicastListener UnicastListener { get; }](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.UnicastListener)|Gets unicast listener for current programmable block.|

#### Methods

|Member|Description|
|---|---|
|[void DisableBroadcastListener(IMyBroadcastListener)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.DisableBroadcastListener)|Disables given broadcast listener. In case given broadcast listener is not active nothing happens. Instance of this broadcast listener remains valid and all pending messages may be accepted as normal. Disabling broadcast listener also disables it's message callback, if active. Consuming the last pending message will permanently disable the the provided listener and it's never going to be activated again. ==> Registering new broadcast lister with the same tag will will allocate new listener instance instead.|
|[void GetBroadcastListeners(List\<IMyBroadcastListener>, \[Func\<IMyBroadcastListener, bool>])](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.GetBroadcastListeners)|Retrieves list of all active broadcast listeners and listeners with pending messages, registered by current programmable block. Returned list is snapshot of current state and is not updated by future operations.|
|[bool IsEndpointReachable(long, \[TransmissionDistance])](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.IsEndpointReachable)|Determines if given endpoint is currently reachable. Similar to sending ICMP message.|
|[IMyBroadcastListener RegisterBroadcastListener(string)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.RegisterBroadcastListener)|Registers broadcast listener with given tag for current programmable block. In case there is already another active broadcast lister with given tag new listener is NOT registered and the already active one is returned instead.|
|[void SendBroadcastMessage\<TData>(string, TData, \[TransmissionDistance])](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.SendBroadcastMessage)||
|[bool SendUnicastMessage\<TData>(long, string, TData)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.SendUnicastMessage)||

