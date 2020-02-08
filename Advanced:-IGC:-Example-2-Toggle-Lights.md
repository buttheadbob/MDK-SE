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

