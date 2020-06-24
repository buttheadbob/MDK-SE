← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyIntergridCommunicationSystem Interface

```csharp
public interface IMyIntergridCommunicationSystem
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Properties

|Member|Description|
|---|---|
|[Me { get; }](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.Me)||
|[UnicastListener { get; }](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.UnicastListener)||

#### Methods

|Member|Description|
|---|---|
|[IsEndpointReachable(long, TransmissionDistance)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.IsEndpointReachable)||
|[RegisterBroadcastListener(string)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.RegisterBroadcastListener)||
|[DisableBroadcastListener(IMyBroadcastListener)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.DisableBroadcastListener)||
|[GetBroadcastListeners(List, Func)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.GetBroadcastListeners)||
|[SendBroadcastMessage(string, TData, TransmissionDistance)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.SendBroadcastMessage)||
|[SendUnicastMessage(long, string, TData)](Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem.SendUnicastMessage)||

