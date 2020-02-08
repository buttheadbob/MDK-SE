#IGC for MDK

## Prerequisites
* https://github.com/malware-dev/MDK-SE/wiki/The-Anatomy-of-a-Script
* https://github.com/malware-dev/MDK-SE/wiki/Your-First-Script
* https://github.com/malware-dev/mdk-se/wiki/Continuous-Running-No-Timers-Needed (for UpdateType)

# Inter Grid Communication

Allows messages to be sent between Programmable Blocks.

There are two types of messages; broadcast and unicast.

Broadcast is available to all Programmable Blocks (that register for it)

Unicast messages are sent to a specific Programmable Block (only).

Tag should be chosen to be unique, or to match a known tag.

# Messages
Messages contain

* Tag.  The tag is the identification used to determine the expected contents of the message
* Data.  The actual data of the message. The message data sent can be any immutable type.  That means it’s not changeable.The simplest message is just a string
* Source. the source of the message (who sent it)

## Receiving Messages
Check for messages existing on a channel with .HasPendingMessages.
Get the next message in the channel with .AcceptMessage
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
Unicast messages are sent to a specified Programming Block.



# Example code

* [Simple Echo](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Example-1-Simple-Echo-Example)
* [Light Toggle](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Example-2-Toggle-Lights)
* [Echo with wicoIGC](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Example-3-Simple-Echo-using-wicoIGC-Class)
* [Echo and Unicast send/receive with wicoIGC](https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Example-4-Simple-Echo-wicoIGC-with-Unicast-Reply-receive)

https://github.com/malware-dev/MDK-SE/wiki/Advanced:-IGC:-Allowed-Message-Types


https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem


# Debugging messages
* Ensure that the grid is within antenna range.  An antenna can RECEIVE messages even if it’s  transmit range is lower, but any messages it sends will not make it to the destination.

* Make sure “Enable Broadcast’ is on or messages will not be RECEIVED

