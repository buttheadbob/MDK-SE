# Prerequisites
* https://github.com/malware-dev/MDK-SE/wiki/The-Anatomy-of-a-Script
* https://github.com/malware-dev/MDK-SE/wiki/Your-First-Script
* https://github.com/malware-dev/mdk-se/wiki/Continuous-Running-No-Timers-Needed (for UpdateType)

# [Inter Grid Communication](https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem)

Inter Grid Communication (IGC) allows messages to be sent between Programmable Blocks.

There are two types of messages; broadcast and unicast.

[Broadcast](https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.IMyBroadcastListener) is available to all Programmable Blocks (that register for it)

[Unicast](https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.IMyUnicastListener) messages are sent to a specific Programmable Block (only).

Tag should be chosen to be unique, or to match a known tag.

# Messages
Messages contain

* [Tag](https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.MyIGCMessage.Tag).  The tag is the identification used to determine the expected contents of the message
* [Data](https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.MyIGCMessage.Data).  The actual data of the message. The message data sent can be any immutable type.  That means it’s not changeable.The simplest message is just a string
* [Source](https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.MyIGCMessage.Source). the source of the message (who sent it).  The source can be used to send unicast messages back to the sender.

## Receiving Messages
Check for messages existing on a channel with [.HasPendingMessages](https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.IMyMessageProvider.HasPendingMessage).
Get the next message in the channel with [.AcceptMessage](https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.IMyMessageProvider.AcceptMessage)
```csharp
if (_myBroadcastListener.HasPendingMessage)
{
    MyIGCMessage myIGCMessage = _myBroadcastListener.AcceptMessage();
```

Each channel can have multiple messages pending.  When accepted, that message is removed from the queue so it must be processed or it will be lost.

### Broadcast
To receive broadcast messages, a channel must first be opened.  The name of the channel must be specified as a tag.  Only messages sent on this channel will be received.

### Unicast
There is a predefined unicast channel.  All messages sent to the Programmable Block are received on the one unicast channel.
Tags should be checked by the receiver to process the messages correctly.

## Sending Messages
### Broadcast
Broadcast messages are sent to a named channel.  
```csharp
IGC.SendBroadcastMessage(_broadCastTag, theString);
```

Data sent can be any of the specified types.  The easiest is string.  But other complex types can be created.

[Here is a list of types that can be sent/received in IGC messages.](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Allowed-Message-Types)


### Unicast
Unicast messages are sent to a specified Programming Block. This allows more efficient use of communications to only those scripts that are affected by the information.

# Example code

I've created a number of examples of using IGC.  I've also created a [world](https://steamcommunity.com/sharedfiles/filedetails/?id=1989825518) with all of the scripts loaded for easy demonstration.  
* [Simple Echo](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Example-1-Simple-Echo-Example)
* [Light Toggle](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Example-2-Toggle-Lights)
* [Echo with wicoIGC](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Example-3-Simple-Echo-using-wicoIGC-Class)
* [Echo and Unicast send/receive with wicoIGC](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Example-4-Simple-Echo-wicoIGC-with-Unicast-Reply-receive)

# Debugging messages
* Ensure that the grid is within antenna range.  An antenna can RECEIVE messages even if it’s  transmit range is lower, but any messages it sends will not make it to the destination.

* Make sure “Enable Broadcast’ is on or messages will not be RECEIVED

