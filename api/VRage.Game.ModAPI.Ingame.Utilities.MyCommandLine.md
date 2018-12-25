← [Index](Api-Index)

#### MyCommandLine Class

```csharp
public class MyCommandLine: object
```

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

**Inheritance:** [object](https://docs.microsoft.com/en-us/dotnet/api/system.object?view=netframework-4.6)

#### Example

#### Remarks

#### Properties

|Member|Description|
|---|---|
|[Items](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine.Items)|Contains all items, both arguments and switches|
|[Switches](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine.Switches)|Contains a list of all detected switches|
|[ArgumentCount](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine.ArgumentCount)|Returns the number of non-switch arguments|

#### Methods

|Member|Description|
|---|---|
|[TryParse(string)](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine.TryParse)|Attempts to parse the given string as a command line|
|[Argument(int)](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine.Argument)|Returns the argument at the given index. Switches are not counted.|
|[Switch(string)](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine.Switch)|Determines whether the given switch is set. Switches are specified without their prefixed hyphen.|
|[Switch(string, int)](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine.Switch)|Gets an argument of a switch. For example, using`Switch("key", 0)`on the command line`someOtherArgument -key value`will return`value`.|
|[Clear()](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine.Clear)|Clears all arguments|

