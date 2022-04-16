← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyBroadcastListener Interface

```csharp
public interface IMyBroadcastListener: IMyMessageProvider
```

Broadcast listeners scan the network for broadcasted messages with specific tag.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IMyMessageProvider](Sandbox.ModAPI.Ingame.IMyMessageProvider)

#### Properties

|Member|Description|
|---|---|
|[bool HasPendingMessage { get; }](Sandbox.ModAPI.Ingame.IMyMessageProvider.HasPendingMessage)|Determines whether there is a message pending to be accepted in this message provider or not. There may be multiple messages pending in single message provider. In such case the flag will stay raised until the last message is consumed.<br /><br />_Inherited from [IMyMessageProvider](Sandbox.ModAPI.Ingame.IMyMessageProvider)_|
|[bool IsActive { get; }](Sandbox.ModAPI.Ingame.IMyBroadcastListener.IsActive)|Gets a value that indicates whether the broadcast listener is active.|
|[int MaxWaitingMessages { get; }](Sandbox.ModAPI.Ingame.IMyMessageProvider.MaxWaitingMessages)|Indicates number of max messages waiting in queue before the oldest one will be dropped to make space for new one.<br /><br />_Inherited from [IMyMessageProvider](Sandbox.ModAPI.Ingame.IMyMessageProvider)_|
|[string Tag { get; }](Sandbox.ModAPI.Ingame.IMyBroadcastListener.Tag)|Gets the tag this broadcast listener is listening for.|

#### Methods

|Member|Description|
|---|---|
|[MyIGCMessage AcceptMessage()](Sandbox.ModAPI.Ingame.IMyMessageProvider.AcceptMessage)|Accepts first message from pending message queue for this message provider. Messages are guaranteed to be dequeued and returned by this method in order they arrived.<br /><br />_Inherited from [IMyMessageProvider](Sandbox.ModAPI.Ingame.IMyMessageProvider)_|
|[void DisableMessageCallback()](Sandbox.ModAPI.Ingame.IMyMessageProvider.DisableMessageCallback)|Disables registered message callback.<br /><br />_Inherited from [IMyMessageProvider](Sandbox.ModAPI.Ingame.IMyMessageProvider)_|
|[void SetMessageCallback([string])](Sandbox.ModAPI.Ingame.IMyMessageProvider.SetMessageCallback)|Whenever given message provider obtains new message respective programmable block gets called with provided argument. Each raised callback argument will be called only once per simulation tick no matter how many messages are there pending to be accepted. At most a single callback will be invoked each tick ==> If there are messages pending in multiple message providers with registered callback, one will be randomly picked and invoked. Rest will be deferred to the next tick and follow the same process. In case you don't consume all messages pending in given message provider, the callback will not be raise again in following tick unless new message arrives.<br /><br />_Inherited from [IMyMessageProvider](Sandbox.ModAPI.Ingame.IMyMessageProvider)_|

