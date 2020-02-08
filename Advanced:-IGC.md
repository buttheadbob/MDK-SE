#IGC for MDK

## Prerequisites
* https://github.com/malware-dev/MDK-SE/wiki/The-Anatomy-of-a-Script
* https://github.com/malware-dev/MDK-SE/wiki/Your-First-Script
* https://github.com/malware-dev/mdk-se/wiki/Continuous-Running-No-Timers-Needed (for UpdateType)

**# Inter Grid Communication**

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
<<<EXAMPLE OF MYTUPLE FOR WAYPOINT>>>

### Unicast
Unicast messages are sent to a specified Programming Block.


# Example 1 Echo
You should already be familiar with basic scripts in SE.  (https://github.com/malware-dev/MDK-SE/wiki/Your-First-Script) 

Let’s start with a simple IGC example.  This is a script to send a message and receive a message and Echo it.

(footnote?) Source for this example is here: https://github.com/Wicorel/WicoSpaceEngineers/tree/master/Modular/IGC%20Echo

Here’s the deployed script with comments removed to make it shorter.

```csharp
int _runcount = 0;
string _broadCastTag = "MDK IGC EXAMPLE 1";
IMyBroadcastListener _myBroadcastListener;

public Program()
{
    Echo("Creator");
    _myBroadcastListener=IGC.RegisterBroadcastListener(_broadCastTag);
    _myBroadcastListener.SetMessageCallback(_broadCastTag); 
}

public void Main(string argument, UpdateType updateSource)
{
    _runcount++;
    Echo(_runcount.ToString()+ ":"+updateSource.ToString());

    if (
        (updateSource & (UpdateType.Trigger | UpdateType.Terminal)) > 0
        || (updateSource & (UpdateType.Mod)) > 0 
        || (updateSource & (UpdateType.Script)) > 0
        )
    { 
        if (argument != "")
        {
            IGC.SendBroadcastMessage(_broadCastTag, argument);
            Echo("Sending message:\n" + argument);
        }
    }

    if( (updateSource& UpdateType.IGC) >0)
    { 
        if (_myBroadcastListener.HasPendingMessage)
        {
            MyIGCMessage myIGCMessage = _myBroadcastListener.AcceptMessage();
            if(myIGCMessage.Tag==_broadCastTag)
            { // This is our tag
                if(myIGCMessage.Data is string)
                {
                    string str = myIGCMessage.Data.ToString();
                    Echo("Received IGC Public Message");
                    Echo("Tag=" + myIGCMessage.Tag);
                    Echo("Data=" + myIGCMessage.Data.ToString());
                    Echo("Source=" + myIGCMessage.Source.ToString("X"));
                }
                else // if(msg.Data is XXX)
                {
                }
            }
            else
            {
            }
        }
    }
}
```

So let’s go through this section by section.

## Definitions
```csharp
int _runcount = 0;
string _broadCastTag = "MDK IGC EXAMPLE 1";
IMyBroadcastListener _myBroadcastListener;
```

This is creating three variables to hold information for the script. The first is used as a counter for runs so that when multiple executions of the script happen quickly, that can be noticed.

The second is the tag for the broadcast channel we will be using.  This tag should be chosen to be unique so that messages from unexpected sources are not received.

The third is the broadcast channel we will be using for receiving messages.  Note that this listener is only needed to RECEIVE messages; you can SEND messages without a registered listener.

## Constructor

```csharp
public Program()
{
    Echo("Creator");
    _myBroadcastListener=IGC.RegisterBroadcastListener(_broadCastTag);
    _myBroadcastListener.SetMessageCallback(_broadCastTag); 
}
```

This is the script constructor.  (if you don’t know what that means, read https://github.com/malware-dev/MDK-SE/wiki/The-Anatomy-of-a-Script)

We start by doing a simple Echo so that the player can tell that the script has compiled.

The next line creates a broadcast channel with the broadcast tag.  

The next line sets the channel to have a callback to the script when a message is received by the IGC system.


## Main start
```csharp
public void Main(string argument, UpdateType updateSource)
{
    _runcount++;
    Echo(_runcount.ToString()+ ":"+updateSource.ToString());
```
Note that we are using Main with the string and UpdateType because we need to check them.

In the beginning here we are just incrementing the runcount and then outputting the value and the current updateSource for informational purposes.

## Checking Update Triggers
```csharp
    if (
        (updateSource & (UpdateType.Trigger | UpdateType.Terminal)) > 0
        || (updateSource & (UpdateType.Mod)) > 0 
        || (updateSource & (UpdateType.Script)) > 0
        )
    { 
        if (argument != "")
        {
            IGC.SendBroadcastMessage(_broadCastTag, argument);
            Echo("Sending message:\n" + argument);
        }
    }
```
Here we are checking to see if the updatesource is one of the trigger types where we want to check the argument.

If it is one of those types and the argument is not empty, then we will broadcast the message on our channel.
```csharp
   IGC.SendBroadcastMessage(_broadCastTag, argument);
```

This sends the message to the channel specified.  In this case, the channel is our _broadCastTag and the message is a string in argument.

We also Echo what we are sending for informational purposes.

## Message Processing
This is where the work happens on processing a message that is received.

```csharp
    if( (updateSource& UpdateType.IGC) >0)
    { 
        if (_myBroadcastListener.HasPendingMessage)
        {
            MyIGCMessage myIGCMessage = _myBroadcastListener.AcceptMessage();
            if(myIGCMessage.Tag==_broadCastTag)
            { // This is our tag
                if(myIGCMessage.Data is string)
                {
                    string str = myIGCMessage.Data.ToString();
                    Echo("Received IGC Public Message");
                    Echo("Tag=" + myIGCMessage.Tag);
                    Echo("Data=" + myIGCMessage.Data.ToString());
                    Echo("Source=" + myIGCMessage.Source.ToString("X"));
                }
```                

First we check to see if we were run because of an incoming IGC message.
```csharp
if( (updateSource& UpdateType.IGC) >0)
```

Then it checks if our broadcast channel has any pending incoming messages. Although this example only has one channel that it is listening to, it is a good habit to not assume which channel has the messages.
```csharp
if (_myBroadcastListener.HasPendingMessage)
```

If there is, then we get the message that was sent using AcceptMessage().  This will remove the message from the incoming queue.
```csharp
	MyIGCMessage myIGCMessage = _myBroadcastListener.AcceptMessage();
```
We then check the message to verify that it has our broadcasttag. For broadcast channel, it should always be our tag because that is what the channel was set up to receive.  However, for unicast messages they can be for many different tags.  So it is a good idea to get in the habit of checking the tag in your code.
```csharp
	if(myIGCMessage.Tag==_broadCastTag)
```

We also check to verify that the data is a string like we expect.
```csharp
if(myIGCMessage.Data is string)
```

Then we Echo the data to show that we received the message.
```csharp
string str = myIGCMessage.Data.ToString();
Echo("Received IGC Public Message");
Echo("Tag=" + myIGCMessage.Tag);
Echo("Data=" + myIGCMessage.Data.ToString());
Echo("Source=" + myIGCMessage.Source.ToString("X"));
```

## Unexpected data processing

Here we are processing if the data is not in the format we expected or not the tag we expect.  We could check other expected formats for the data, or Echo a message about it being unexpected, or just ignore it.
```csharp
               else // if(msg.Data is XXX)
               {
               }
            }
            else
            {
            }
```


# Example 2: Toggling a light using IGC

This code will toggle a light; just like “[Your First Script](https://github.com/Wicorel/WicoSpaceEngineers/tree/master/MDK%20IGC%20Example%202)” example 

The difference is that the code will receive a message to toggle the light from a remote script.

To shorten the explanations, only the differences from Example 1 are explained.

## Entire code:
```csharp
/*
 * This is MDK IGC Example 2 by wicorel
 * 
 * Takes the first example script of toggling a light and makes it work via IGC.
 * 
 * Go to:
 *  https://github.com/malware-dev/MDK-SE/wiki/Quick-Introduction-to-Space-Engineers-Ingame-Scripts
 *  to learn more about ingame scripts.
 * 
 * This Example source: 
 *  https://github.com/Wicorel/WicoSpaceEngineers/tree/master/MDK%20IGC%20Example%202
 */

/// <summary>
        /// This is our unique ID for our message.  We've defined the format for the message data (it's just a string)
        /// </summary>
string _broadCastTag = "MDK IGC EXAMPLE 2";

/// <summary>
        /// The broadcast listener for the channel we are interested in.
        /// </summary>
IMyBroadcastListener _myBroadcastListener;

public Program()
{
    // let them know we are alive
    Echo("Creator");

    // register a broadcast channel for our tag
    _myBroadcastListener = IGC.RegisterBroadcastListener(_broadCastTag);

    // Ask to be called back --to Main()-- when a message is received
    _myBroadcastListener.SetMessageCallback(_broadCastTag); // the callback agrument does NOT need to be the same as the tag

}


public void Main(string argument, UpdateType updateSource)
{
    if (
        (updateSource & (UpdateType.Trigger | UpdateType.Terminal)) > 0 // run by a terminal action
        || (updateSource & (UpdateType.Mod)) > 0 // script run by a mod
        || (updateSource & (UpdateType.Script)) > 0 // this pb run by another script (PB)
        )
    { // script was run because of an action
        if (argument != "")
        {
            // if we are given an argument, send it out over our broadcast channel
            IGC.SendBroadcastMessage(_broadCastTag, argument);
            Echo("Sending message:\n" + argument);
        }
    }

    if ((updateSource & UpdateType.IGC) > 0)
    { // script was run because of incoming IGC message
        if (_myBroadcastListener.HasPendingMessage)
        {
            var myIGCMessage = _myBroadcastListener.AcceptMessage();
            if (myIGCMessage.Tag == _broadCastTag)
            { // This is our tag
                if (myIGCMessage.Data is string)
                {
                    string lightName = myIGCMessage.Data.ToString();

                    IMyInteriorLight light;

                    light = GridTerminalSystem.GetBlockWithName(lightName) as IMyInteriorLight;
                    if (light == null)
                    {
                        Echo("Oh my! I couldn't find that block...");
                        Echo(lightName);
                        return;
                    }

                    light.Enabled = !light.Enabled;
                    Echo("I have toggled the light!");
                }
                else // if(msg.Data is XXX)
                {
                    // handle other data types here...
                }
            }
            else
            {
                // handle other tags here
            }
        }
    }
}
```

Note that we choose a different channel tag for this example.
```csharp
string _broadCastTag = "MDK IGC EXAMPLE 2";
```

Most of the code is exactly the same as Example 1.  If we are given an argument, then we send that string out to the channel.

The difference is what we do when we receive a message.  The processing code is almost the same as the code from the “Your First Script” example, except the name of the light is taken from the string in the received message.
```csharp

               if (myIGCMessage.Data is string)
               {
                    string lightName = myIGCMessage.Data.ToString();

                    IMyInteriorLight light;

                    light = GridTerminalSystem.GetBlockWithName(lightName) as IMyInteriorLight;
                    if (light == null)
                    {
                        Echo("Oh my! I couldn't find that block...");
                        Echo(lightName);
                        return;
                    }

                    light.Enabled = !light.Enabled;
                    Echo("I have toggled the light!");
                }
```

Here we get the name of the light from the message data.
```csharp
	string lightName = myIGCMessage.Data.ToString();
```

## Example 3 Simple Echo using wicoIGC Class
Go through class line-by-line
Go through handler line-by-line
https://github.com/Wicorel/WicoSpaceEngineers/tree/master/Modular/IGC%20Modular%20Example

## Entire code
```csharp
/*
 * Wico Modular IGC Example
 * 
 * November 28, 2019
 * Updated Feb 4, 2020 to be MDK IGC example 3
 * 
 * Steam workshop link: 
 * https://steamcommunity.com/sharedfiles/itemedittext/?id=1923270132
 * 
 * 
 * Source available at:
 * https://github.com/Wicorel/WicoSpaceEngineers/tree/master/Modular/IGC%20Modular%20Example
 */

WicoIGC _wicoIGC;

/// <summary>
        /// The combined set of UpdateTypes that count as a 'trigger'
        /// </summary>
UpdateType _utTriggers = UpdateType.Terminal | UpdateType.Trigger | UpdateType.Mod | UpdateType.Script;
/// <summary>
        /// the combined set of UpdateTypes and count as an 'Update'
        /// </summary>
UpdateType _utUpdates = UpdateType.Update1 | UpdateType.Update10 | UpdateType.Update100 | UpdateType.Once;

public Program()
{
    _wicoIGC = new WicoIGC(this);

    // cause ourselves to run again so we can do the init
    Runtime.UpdateFrequency = UpdateFrequency.Once;
}

public void Save()
{
}

/// <summary>
        /// Has everything been initialized?
        /// </summary>
bool _areWeInited=false;

public void Main(string argument, UpdateType updateSource)
{
    // Echo some information about 'me' and why we were run
    Echo("Source=" + updateSource.ToString());
    Echo("Me=" + Me.EntityId.ToString("X"));
    Echo(Me.CubeGrid.CustomName);

    if (!_areWeInited)
    {
        InitMessageHandlers();
        _areWeInited = true;
    }

    // always check for IGC messages in case some aren't using callbacks
    _wicoIGC.ProcessIGCMessages();
    if ((updateSource & UpdateType.IGC) > 0)
    {
        // we got a callback for an IGC message.
        // but we already processed them.
    }
    else if((updateSource & _utTriggers) > 0)
    {
        // if we got a 'trigger' source, send out the received argument
        IGC.SendBroadcastMessage(_broadCastTag, argument);
        Echo("Sending Message:\n" + argument);
    }
    else if((updateSource & _utUpdates) > 0)
    {
        // it was an automatic update

        // this script doesn't have anything to do
    }
}

/// <summary>
        /// This is our unique ID for our message.  We've defined the format for the message data (it's just a string)
        /// </summary>
string _broadCastTag = "MDK IGC Example 3";

void InitMessageHandlers()
{
    // creates a broadcast channel with the specified tag and calls the handler when messages are processed
    _wicoIGC.AddPublicHandler(_broadCastTag, TestBroadcastHandler);
}

// Handler for the test broadcast messages.
void TestBroadcastHandler(MyIGCMessage msg)
{
    // NOTE: called on ALL received messages; not just 'our' tag

    if (msg.Tag!= _broadCastTag)
        return; // not our message

    if (msg.Data is string)
    {
        Echo("Received Test Message");
        Echo(" Source=" + msg.Source.ToString("X"));
        Echo(" Data=\"" + msg.Data + "\"");
        Echo(" Tag=" + msg.Tag);
    }
}

// Source is available from: https://github.com/Wicorel/WicoSpaceEngineers/tree/master/Modular/IGC
class WicoIGC
{
    // the one and only unicast listener.  Must be shared amoung all interested parties
    IMyUnicastListener _unicastListener;

    /// <summary>
            /// the list of unicast message handlers. All handlers will be called on pending messages
            /// </summary>
    List<Action<MyIGCMessage>> _unicastMessageHandlers = new List<Action<MyIGCMessage>>();

    /// <summary>
            /// List of 'registered' broadcst message handlers.  All handlers will be called on each message received
            /// </summary>
    List<Action<MyIGCMessage>> _broadcastMessageHandlers = new List<Action<MyIGCMessage>>();
    /// <summary>
            /// List of broadcast channels.  All channels will be checked for incoming messages
            /// </summary>
    List<IMyBroadcastListener> _broadcastChannels = new List<IMyBroadcastListener>();

    MyGridProgram _gridProgram;
    bool _debug = false;
    IMyTextPanel _debugTextPanel;

    /// <summary>
            /// Constructor.
            /// </summary>
            /// <param name="myProgram"></param>
            /// <param name="debug"></param>
    public WicoIGC(MyGridProgram myProgram, bool debug = false)
    {
        _gridProgram = myProgram;
        _debug = debug;
        _debugTextPanel = _gridProgram.GridTerminalSystem.GetBlockWithName("IGC Report") as IMyTextPanel;
        if (_debug) _debugTextPanel?.WriteText("");
    }

    /// <summary>
            /// Call to add a handler for public messages.  Also registers the tag with IGC for reception.
            /// </summary>
            /// <param name="channelTag">The tag for the channel.  This should be unique to the use of the channel.</param>
            /// <param name="handler">The handler for messages when received. Note that this handler will be called with ALL broadcast messages; not just the one from ChannelTag</param>
            /// <param name="setCallback">Should a callback be set on the channel. The system will call Main() when the IGC message is received.</param>
            /// <returns></returns>
    public bool AddPublicHandler(string channelTag, Action<MyIGCMessage> handler, bool setCallback = true)
    {
        IMyBroadcastListener publicChannel;
        // IGC Init
        publicChannel = _gridProgram.IGC.RegisterBroadcastListener(channelTag); // What it listens for
        if (setCallback) publicChannel.SetMessageCallback(channelTag); // What it will run the PB with once it has a message

        // add broadcast message handlers
        _broadcastMessageHandlers.Add(handler);

        // add to list of channels to check
        _broadcastChannels.Add(publicChannel);
        return true;
    }

    /// <summary>
            /// Add a unicast handler.
            /// </summary>
            /// <param name="handler">The handler for messages when received. Note that this handler will be called with ALL Unicast messages. Always sets a callback handler</param>
            /// <returns></returns>
    public bool AddUnicastHandler(Action<MyIGCMessage> handler)
    {
        _unicastListener = _gridProgram.IGC.UnicastListener;
        _unicastListener.SetMessageCallback("UNICAST");
        _unicastMessageHandlers.Add(handler);
        return true;

    }
    /// <summary>
            /// Process all pending IGC messages.
            /// </summary>
    public void ProcessIGCMessages()
    {
        bool bFoundMessages = false;
        if (_debug) _gridProgram.Echo(_broadcastChannels.Count.ToString() + " broadcast channels");
        if (_debug) _gridProgram.Echo(_broadcastMessageHandlers.Count.ToString() + " broadcast message handlers");
        if (_debug) _gridProgram.Echo(_unicastMessageHandlers.Count.ToString() + " unicast message handlers");
        // TODO: make this a yield return thing if processing takes too long
        do
        {
            bFoundMessages = false;
            foreach (var channel in _broadcastChannels)
            {
                if (channel.HasPendingMessage)
                {
                    bFoundMessages = true;
                    var msg = channel.AcceptMessage();
                    if (_debug)
                    {
                        _gridProgram.Echo("Broadcast received. TAG:" + msg.Tag);
                        _debugTextPanel?.WriteText("IGC:" +msg.Tag+" SRC:"+msg.Source.ToString("X")+"\n",true);
                    }
                    foreach (var handler in _broadcastMessageHandlers)
                    {
                        handler(msg);
                    }
                }
            }
        } while (bFoundMessages); // Process all pending messages

        if (_unicastListener != null)
        {
            // TODO: make this a yield return thing if processing takes too long
            do
            {
                // since there's only one channel, we could just use .HasPendingMessages directly.. but this keeps the code loops the same
                bFoundMessages = false;

                if (_unicastListener.HasPendingMessage)
                {
                    bFoundMessages = true;
                    var msg = _unicastListener.AcceptMessage();
                    if (_debug) _gridProgram.Echo("Unicast received. TAG:" + msg.Tag);
                    foreach (var handler in _unicastMessageHandlers)
                    {
                        // Call each handler
                        handler(msg);
                    }
                }
            } while (bFoundMessages); // Process all pending messages
        }

    }
}
```


##Example 4 Simple Echo wicoIGC but add Unicast Reply/receive

```csharp
/*
 * This is MDK IGC Example 4 by wicorel
 * 
 * This does a simple echo of a received BROADCAST message. 
 * It sends out any arguments received on the broadcast channel.
 * 
 * It then responds with a UNICAST message back to the sending script.
 * 
 * Go to:
 *  https://github.com/malware-dev/MDK-SE/wiki/Quick-Introduction-to-Space-Engineers-Ingame-Scripts
 *  to learn more about ingame scripts.
 * 
 * This Example source: 
 *  https://github.com/Wicorel/WicoSpaceEngineers/tree/master/Modular/MDK%20IGC%20Example%204
 */

WicoIGC _wicoIGC;

/// <summary>
        /// The combined set of UpdateTypes that count as a 'trigger'
        /// </summary>
UpdateType _utTriggers = UpdateType.Terminal | UpdateType.Trigger | UpdateType.Mod | UpdateType.Script;

/// <summary>
        /// the combined set of UpdateTypes and count as an 'Update'
        /// </summary>
UpdateType _utUpdates = UpdateType.Update1 | UpdateType.Update10 | UpdateType.Update100 | UpdateType.Once;

public Program()
{
    _wicoIGC = new WicoIGC(this);

    // cause ourselves to run again so we can do the init
    Runtime.UpdateFrequency = UpdateFrequency.Once;
}

public void Save()
{
}

/// <summary>
        /// Has everything been initialized?
        /// </summary>
bool _areWeInited = false;

public void Main(string argument, UpdateType updateSource)
{
    // Echo some information aboue 'me' and why we were run
    Echo("Source=" + updateSource.ToString());
    Echo("Me=" + Me.EntityId.ToString("X"));
    Echo(Me.CubeGrid.CustomName);

    if (!_areWeInited)
    {
        InitMessageHandlers();
        _areWeInited = true;
    }

    // use if not setting callbacks for any of the desired channels
    //            if (bInit) wicoIGC.ProcessIGCMessages();

    // always check for IGC messages in case some aren't using callbacks
    _wicoIGC.ProcessIGCMessages();
    if ((updateSource & UpdateType.IGC) > 0)
    {
        // we got a callback for an IGC message.
        // but we already processed them.
    }
    else if ((updateSource & _utTriggers) > 0)
    {
        // if we got a 'trigger' source, send out the received argument
        IGC.SendBroadcastMessage(_broadCastTag, argument);
        Echo("Sending Message:\n" + argument);
    }
    else if ((updateSource & _utUpdates) > 0)
    {
        // it was an automatic update

        // this script doens't have anything to do
    }
}

/// <summary>
        /// This is our unique ID for our message.  We've defined the format for the message data (it's just a string)
        /// </summary>
string _broadCastTag = "MDK IGC Example 4";
string _unicastTag   = "MDK IGC Example 4 Ack";

void InitMessageHandlers()
{
    // creates a BROADCAST channel with the specified tag and calls the handler when messages are processed
    _wicoIGC.AddPublicHandler(_broadCastTag, TestBroadcastHandler);

    // calls the handler when UNICAST messages are processed
    _wicoIGC.AddUnicastHandler(TestUnicastHandler);
}

// Handler for the test broadcast messages.
void TestBroadcastHandler(MyIGCMessage msg)
{
    // NOTE: called on ALL received messages; not just 'our' tag

    if (msg.Tag != _broadCastTag)
        return; // not our message

    if (msg.Data is string)
    {
        Echo("Received Test Message");
        Echo(" Source=" + msg.Source.ToString("X"));
        Echo(" Data=\"" + msg.Data + "\"");
        Echo(" Tag=" + msg.Tag);

        // Now reply to the sender and let them know we received the message
        // NOTE: We are re-using the broadcast
        IGC.SendUnicastMessage(msg.Source, _unicastTag, "Acknowledge by:"+Me.CustomName);
        Echo(" Reply Sent");
    }
}

void TestUnicastHandler(MyIGCMessage msg)
{
    // NOTE: Called for ALL received unicast messages
    if (msg.Tag != _unicastTag)
        return; // not our message

    if (msg.Data is string)
    {
        Echo("Received Acknowledge Message");
        Echo(" Source=" + msg.Source.ToString("X"));
        Echo(" Data=\"" + msg.Data + "\"");
        Echo(" Tag=" + msg.Tag);
    }

}

// Source is available from: https://github.com/Wicorel/WicoSpaceEngineers/tree/master/Modular/IGC
class WicoIGC
{
    // the one and only unicast listener.  Must be shared amoung all interested parties
    IMyUnicastListener _unicastListener;

    /// <summary>
            /// the list of unicast message handlers. All handlers will be called on pending messages
            /// </summary>
    List<Action<MyIGCMessage>> _unicastMessageHandlers = new List<Action<MyIGCMessage>>();

    /// <summary>
            /// List of 'registered' broadcst message handlers.  All handlers will be called on each message received
            /// </summary>
    List<Action<MyIGCMessage>> _broadcastMessageHandlers = new List<Action<MyIGCMessage>>();
    /// <summary>
            /// List of broadcast channels.  All channels will be checked for incoming messages
            /// </summary>
    List<IMyBroadcastListener> _broadcastChannels = new List<IMyBroadcastListener>();

    MyGridProgram _gridProgram;
    bool _debug = false;
    IMyTextPanel _debugTextPanel;

    /// <summary>
            /// Constructor.
            /// </summary>
            /// <param name="myProgram"></param>
            /// <param name="debug"></param>
    public WicoIGC(MyGridProgram myProgram, bool debug = false)
    {
        _gridProgram = myProgram;
        _debug = debug;
        _debugTextPanel = _gridProgram.GridTerminalSystem.GetBlockWithName("IGC Report") as IMyTextPanel;
        if (_debug) _debugTextPanel?.WriteText("");
    }

    /// <summary>
            /// Call to add a handler for public messages.  Also registers the tag with IGC for reception.
            /// </summary>
            /// <param name="channelTag">The tag for the channel.  This should be unique to the use of the channel.</param>
            /// <param name="handler">The handler for messages when received. Note that this handler will be called with ALL broadcast messages; not just the one from ChannelTag</param>
            /// <param name="setCallback">Should a callback be set on the channel. The system will call Main() when the IGC message is received.</param>
            /// <returns></returns>
    public bool AddPublicHandler(string channelTag, Action<MyIGCMessage> handler, bool setCallback = true)
    {
        IMyBroadcastListener publicChannel;
        // IGC Init
        publicChannel = _gridProgram.IGC.RegisterBroadcastListener(channelTag); // What it listens for
        if (setCallback) publicChannel.SetMessageCallback(channelTag); // What it will run the PB with once it has a message

        // add broadcast message handlers
        _broadcastMessageHandlers.Add(handler);

        // add to list of channels to check
        _broadcastChannels.Add(publicChannel);
        return true;
    }

    /// <summary>
            /// Add a unicast handler.
            /// </summary>
            /// <param name="handler">The handler for messages when received. Note that this handler will be called with ALL Unicast messages. Always sets a callback handler</param>
            /// <returns></returns>
    public bool AddUnicastHandler(Action<MyIGCMessage> handler)
    {
        _unicastListener = _gridProgram.IGC.UnicastListener;
        _unicastListener.SetMessageCallback("UNICAST");
        _unicastMessageHandlers.Add(handler);
        return true;

    }
    /// <summary>
            /// Process all pending IGC messages.
            /// </summary>
    public void ProcessIGCMessages()
    {
        bool bFoundMessages = false;
        if (_debug) _gridProgram.Echo(_broadcastChannels.Count.ToString() + " broadcast channels");
        if (_debug) _gridProgram.Echo(_broadcastMessageHandlers.Count.ToString() + " broadcast message handlers");
        if (_debug) _gridProgram.Echo(_unicastMessageHandlers.Count.ToString() + " unicast message handlers");
        // TODO: make this a yield return thing if processing takes too long
        do
        {
            bFoundMessages = false;
            foreach (var channel in _broadcastChannels)
            {
                if (channel.HasPendingMessage)
                {
                    bFoundMessages = true;
                    var msg = channel.AcceptMessage();
                    if (_debug)
                    {
                        _gridProgram.Echo("Broadcast received. TAG:" + msg.Tag);
                        _debugTextPanel?.WriteText("IGC:" +msg.Tag+" SRC:"+msg.Source.ToString("X")+"\n",true);
                    }
                    foreach (var handler in _broadcastMessageHandlers)
                    {
                        handler(msg);
                    }
                }
            }
        } while (bFoundMessages); // Process all pending messages

        if (_unicastListener != null)
        {
            // TODO: make this a yield return thing if processing takes too long
            do
            {
                // since there's only one channel, we could just use .HasPendingMessages directly.. but this keeps the code loops the same
                bFoundMessages = false;

                if (_unicastListener.HasPendingMessage)
                {
                    bFoundMessages = true;
                    var msg = _unicastListener.AcceptMessage();
                    if (_debug) _gridProgram.Echo("Unicast received. TAG:" + msg.Tag);
                    foreach (var handler in _unicastMessageHandlers)
                    {
                        // Call each handler
                        handler(msg);
                    }
                }
            } while (bFoundMessages); // Process all pending messages
        }

    }
}
```



https://github.com/malware-dev/MDK-SE/wiki/Sandbox.ModAPI.Ingame.IMyIntergridCommunicationSystem


Advance section or separate topic:
# Allowed IGC Types
Source: https://discordapp.com/channels/125011928711036928/216219467959500800/663282827676221440


Compiled by GeorgIk
========- Types allowedin IGC -=========
```csharp

// Max recursion = 25
ImmutableArray<>
ImmutableList<>
ImmutableQueue<>
ImmutableStack<>
ImmutableHashSet<>
ImmutableSortedSet<>
ImmutableDictionary<, >
ImmutableSortedDictionary<, >
MyTuple<>
MyTuple<, >
MyTuple<, , >
MyTuple<, , , >
MyTuple<, , , , >
MyTuple<, , , , , >
Boolean
Byte
SByte
Int16
UInt16
Int32
UInt32
Int64
UInt64
IntPtr
UIntPtr
Char
Double
Single
string
Ray
RayD
Line
LineD
Color
Plane
Point
PlaneD
MyQuad
Matrix
MatrixD
MatrixI
MyQuadD
Capsule
Vector2
Vector3
Vector4
CapsuleD
Vector2D
Vector2B
Vector3L
Vector4D
Vector3D
MyShort4
MyBounds
Vector3B
Vector3S
Vector2I
Vector4I
CubeFace
Vector3I
Matrix3x3
MyUShort4
Rectangle
Quaternion
RectangleF
BoundingBox
QuaternionD
MyTransform
BoundingBox2
BoundingBoxI
BoundingBoxD
MyTransformD
Vector3UByte
CurveTangent
Vector4UByte
BoundingBox2I
BoundingBox2D
Vector3Ushort
CurveLoopType
BoundingSphere
BoundingSphereD
ContainmentType
CurveContinuity
MyBlockOrientation
Base6Directions.Axis
MyOrientedBoundingBox
PlaneIntersectionType
MyOrientedBoundingBoxD
Vector3I_RangeIterator
Base6Directions.Direction
Base27Directions.Direction
CompressedPositionOrientation
Base6Directions.DirectionFlags
HalfVector3
HalfVector2
HalfVector4
```

# Debugging messages
* Ensure that the grid is within antenna range.  An antenna can RECEIVE messages even if it’s  transmit range is lower, but any messages it sends will not make it to the destination.

* Make sure “Enable Broadcast’ is on or messages will not be RECEIVED

