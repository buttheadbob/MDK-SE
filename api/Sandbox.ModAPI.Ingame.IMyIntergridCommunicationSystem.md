← [Index](index.md)
#IMyIntergridCommunicationSystem Interface
**Namespace:** Sandbox.ModAPI.Ingame  
**Assembly:** Sandbox.Common.dll  
###Properties
|Member|Description|
|---|---|
|[`long Me`](Sandbox.ModAPI.Ingame.Me.md)||
|[`Sandbox.ModAPI.Ingame.IMyUnicastListener UnicastListener`](Sandbox.ModAPI.Ingame.UnicastListener.md)||
###Methods
|Member|Description|
|---|---|
|[`bool IsEndpointReachable(long address)`](Sandbox.ModAPI.Ingame.IsEndpointReachable.md)||
|[`Sandbox.ModAPI.Ingame.IMyBroadcastListener RegisterBroadcastListener(string tag)`](Sandbox.ModAPI.Ingame.RegisterBroadcastListener.md)||
|[`void DisableBroadcastListener(Sandbox.ModAPI.Ingame.IMyBroadcastListener broadcastListener)`](Sandbox.ModAPI.Ingame.DisableBroadcastListener.md)||
|[`void GetBroadcastListeners(List<Sandbox.ModAPI.Ingame.IMyBroadcastListener> broadcastListeners, Func<Sandbox.ModAPI.Ingame.IMyBroadcastListener, System.Boolean> collect)`](Sandbox.ModAPI.Ingame.GetBroadcastListeners.md)||
|[`void SendBroadcastMessage<TData>(string tag, Sandbox.ModAPI.Ingame.TData data)`](Sandbox.ModAPI.Ingame.SendBroadcastMessage.md)||
|[`bool SendUnicastMessage<TData>(long addressee, string tag, Sandbox.ModAPI.Ingame.TData data)`](Sandbox.ModAPI.Ingame.SendUnicastMessage.md)||
