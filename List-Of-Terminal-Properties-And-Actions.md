## Overview
**Note: Terminal actions and properties are for all intents and purposes obsolete since all vanilla block interfaces now contain proper API access to all this information. It is highly recommended you use those for less overhead.**

[IMyAdvancedDoor](#imyadvanceddoor)  
[IMyAirtightHangarDoor](#imyairtighthangardoor)  
[IMyAirtightSlideDoor](#imyairtightslidedoor)  
[IMyAirVent](#imyairvent)  
[IMyArtificialMassBlock](#imyartificialmassblock)  
[IMyAssembler](#imyassembler)  
[IMyBatteryBlock](#imybatteryblock)  
[IMyBeacon](#imybeacon)  
[IMyButtonPanel](#imybuttonpanel)  
[IMyCameraBlock](#imycamerablock)  
[IMyCargoContainer](#imycargocontainer)  
[IMyCockpit](#imycockpit)  
[IMyCollector](#imycollector)  
[IMyControlPanel](#imycontrolpanel)  
[IMyConveyorSorter](#imyconveyorsorter)  
[IMyCryoChamber](#imycryochamber)  
[IMyDecoy](#imydecoy)  
[IMyDoor](#imydoor)  
[IMyExtendedPistonBase](#imyextendedpistonbase)  
[IMyFunctionalBlock](#imyfunctionalblock)  
[IMyGasGenerator](#imygasgenerator)  
[IMyGasTank](#imygastank)  
[IMyGravityGenerator](#imygravitygenerator)  
[IMyGravityGeneratorSphere](#imygravitygeneratorsphere)  
[IMyGyro](#imygyro)  
[IMyInteriorLight](#imyinteriorlight)  
[IMyJumpDrive](#imyjumpdrive)  
[IMyLandingGear](#imylandinggear)  
[IMyLargeGatlingTurret](#imylargegatlingturret)  
[IMyLargeInteriorTurret](#imylargeinteriorturret)  
[IMyLaserAntenna](#imylaserantenna)  
[IMyMedicalRoom](#imymedicalroom)  
[IMyMotorAdvancedStator](#imymotoradvancedstator)  
[IMyMotorSuspension](#imymotorsuspension)  
[IMyOreDetector](#imyoredetector)  
[IMyOxygenFarm](#imyoxygenfarm)  
[IMyParachute](#imyparachute)  
[IMyPistonBase](#imypistonbase)  
[IMyProgrammableBlock](#imyprogrammableblock)  
[IMyProjector](#imyprojector)  
[IMyRadioAntenna](#imyradioantenna)  
[IMyReactor](#imyreactor)  
[IMyRefinery](#imyrefinery)  
[IMyReflectorLight](#imyreflectorlight)  
[IMyRemoteControl](#imyremotecontrol)  
[IMySafeZoneBlock](#imysafezoneblock)  
[IMySensorBlock](#imysensorblock)  
[IMyShipConnector](#imyshipconnector)  
[IMyShipController](#imyshipcontroller)  
[IMyShipDrill](#imyshipdrill)  
[IMyShipGrinder](#imyshipgrinder)  
[IMyShipMergeBlock](#imyshipmergeblock)  
[IMyShipWelder](#imyshipwelder)  
[IMySmallGatlingGun](#imysmallgatlinggun)  
[IMySmallMissileLauncher](#imysmallmissilelauncher)  
[IMySmallMissileLauncherReload](#imysmallmissilelauncherreload)  
[IMySolarPanel](#imysolarpanel)  
[IMySoundBlock](#imysoundblock)  
[IMySpaceBall](#imyspaceball)  
[IMyStoreBlock](#imystoreblock)  
[IMyTerminalBlock](#imyterminalblock)  
[IMyTextPanel](#imytextpanel)  
[IMyThrust](#imythrust)  
[IMyTimerBlock](#imytimerblock)  
[IMyUpgradeModule](#imyupgrademodule)  
[IMyWarhead](#imywarhead)  

## IMyAdvancedDoor

### Actions

|Name|Description|
|-|-|
|AnyoneCanUse|Anyone Can Use On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Open| Open/Closed|
|Open_Off| Closed|
|Open_On| Open|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|AnyoneCanUse|bool|
|Name|StringBuilder|
|OnOff|bool|
|Open|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyAirtightHangarDoor

### Actions

|Name|Description|
|-|-|
|AnyoneCanUse|Anyone Can Use On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Open| Open/Closed|
|Open_Off| Closed|
|Open_On| Open|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|AnyoneCanUse|bool|
|Name|StringBuilder|
|OnOff|bool|
|Open|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyAirtightSlideDoor

### Actions

|Name|Description|
|-|-|
|AnyoneCanUse|Anyone Can Use On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Open| Open/Closed|
|Open_Off| Closed|
|Open_On| Open|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|AnyoneCanUse|bool|
|Name|StringBuilder|
|OnOff|bool|
|Open|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyAirVent

### Actions

|Name|Description|
|-|-|
|Depressurize|Depressurize On/Off|
|Depressurize_Off|Depressurize Off|
|Depressurize_On|Depressurize On|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Depressurize|bool|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyArtificialMassBlock

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyAssembler

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|slaveMode|Cooperative Mode On/Off|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|slaveMode|bool|
|UseConveyor|bool|

## IMyBatteryBlock

### Actions

|Name|Description|
|-|-|
|Auto|Enable Auto|
|Discharge|Discharge On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Recharge|Recharge On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|ChargeMode|long|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyBeacon

### Actions

|Name|Description|
|-|-|
|DecreaseRadius|Decrease Broadcast radius|
|IncreaseRadius|Increase Broadcast radius|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|CustomName|StringBuilder|
|HudText|StringBuilder|
|OnOff|bool|
|Radius|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyButtonPanel

### Actions

|Name|Description|
|-|-|
|AnyoneCanUse|Anyone Can Use On/Off|
|DecreaseChangeIntervalSlider|Decrease Image change interval|
|DecreaseFontSize|Decrease Font Size|
|DecreaseTextPaddingSlider|Decrease Text Padding|
|IncreaseChangeIntervalSlider|Increase Image change interval|
|IncreaseFontSize|Increase Font Size|
|IncreaseTextPaddingSlider|Increase Text Padding|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|PreserveAspectRatio|Preserve aspect ratio On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|alignment|long|
|AnyoneCanUse|bool|
|BackgroundColor|Color|
|ButtonName|StringBuilder|
|ChangeIntervalSlider|float|
|Content|long|
|Font|long|
|FontColor|Color|
|FontSize|float|
|Name|StringBuilder|
|OnOff|bool|
|PreserveAspectRatio|bool|
|ScriptBackgroundColor|Color|
|ScriptForegroundColor|Color|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TextPaddingSlider|float|

## IMyCameraBlock

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyCargoContainer

### Actions

|Name|Description|
|-|-|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyCockpit

### Actions

|Name|Description|
|-|-|
|ControlGyros|Control Gyros On/Off|
|ControlThrusters|Control thrusters On/Off|
|ControlWheels|Control wheels On/Off|
|DampenersOverride|Inertia dampeners On/Off|
|DecreaseChangeIntervalSlider|Decrease Image change interval|
|DecreaseFontSize|Decrease Font Size|
|DecreaseTextPaddingSlider|Decrease Text Padding|
|HandBrake|Handbrake On/Off|
|HorizonIndicator|Show horizon and altitude On/Off|
|IncreaseChangeIntervalSlider|Increase Image change interval|
|IncreaseFontSize|Increase Font Size|
|IncreaseTextPaddingSlider|Increase Text Padding|
|MainCockpit|Main cockpit On/Off|
|PreserveAspectRatio|Preserve aspect ratio On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|alignment|long|
|BackgroundColor|Color|
|ChangeIntervalSlider|float|
|Content|long|
|ControlGyros|bool|
|ControlThrusters|bool|
|ControlWheels|bool|
|DampenersOverride|bool|
|Font|long|
|FontColor|Color|
|FontSize|float|
|HandBrake|bool|
|HorizonIndicator|bool|
|MainCockpit|bool|
|Name|StringBuilder|
|PreserveAspectRatio|bool|
|ScriptBackgroundColor|Color|
|ScriptForegroundColor|Color|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TextPaddingSlider|float|

## IMyCollector

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMyControlPanel

### Actions

|Name|Description|
|-|-|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyConveyorSorter

### Actions

|Name|Description|
|-|-|
|DrainAll|Drain All On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|blacklistWhitelist|long|
|DrainAll|bool|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyCryoChamber

### Actions

|Name|Description|
|-|-|
|ControlGyros|Control Gyros On/Off|
|ControlThrusters|Control thrusters On/Off|
|ControlWheels|Control wheels On/Off|
|DampenersOverride|Inertia dampeners On/Off|
|DecreaseChangeIntervalSlider|Decrease Image change interval|
|DecreaseFontSize|Decrease Font Size|
|DecreaseTextPaddingSlider|Decrease Text Padding|
|HandBrake|Handbrake On/Off|
|HorizonIndicator|Show horizon and altitude On/Off|
|IncreaseChangeIntervalSlider|Increase Image change interval|
|IncreaseFontSize|Increase Font Size|
|IncreaseTextPaddingSlider|Increase Text Padding|
|MainCockpit|Main cockpit On/Off|
|PreserveAspectRatio|Preserve aspect ratio On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|alignment|long|
|BackgroundColor|Color|
|ChangeIntervalSlider|float|
|Content|long|
|ControlGyros|bool|
|ControlThrusters|bool|
|ControlWheels|bool|
|DampenersOverride|bool|
|Font|long|
|FontColor|Color|
|FontSize|float|
|HandBrake|bool|
|HorizonIndicator|bool|
|MainCockpit|bool|
|Name|StringBuilder|
|PreserveAspectRatio|bool|
|ScriptBackgroundColor|Color|
|ScriptForegroundColor|Color|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TextPaddingSlider|float|

## IMyDecoy

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyDoor

### Actions

|Name|Description|
|-|-|
|AnyoneCanUse|Anyone Can Use On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Open| Open/Closed|
|Open_Off| Closed|
|Open_On| Open|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|AnyoneCanUse|bool|
|Name|StringBuilder|
|OnOff|bool|
|Open|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyExtendedPistonBase

### Actions

|Name|Description|
|-|-|
|Add Top Part|Add Piston Head|
|DecreaseLowerLimit|Decrease Minimum distance|
|DecreaseMaxImpulseAxis|Decrease Max Impulse Axis|
|DecreaseMaxImpulseNonAxis|Decrease Max Impulse NonAxis|
|DecreaseSafetyDetach|Decrease Safety detach|
|DecreaseUpperLimit|Decrease Maximum distance|
|DecreaseVelocity|Decrease Velocity|
|DecreaseWeld speed|Decrease Safety lock speed|
|Extend|Extend|
|Force weld|Safety lock override On/Off|
|IncreaseLowerLimit|Increase Minimum distance|
|IncreaseMaxImpulseAxis|Increase Max Impulse Axis|
|IncreaseMaxImpulseNonAxis|Increase Max Impulse NonAxis|
|IncreaseSafetyDetach|Increase Safety detach|
|IncreaseUpperLimit|Increase Maximum distance|
|IncreaseVelocity|Increase Velocity|
|IncreaseWeld speed|Increase Safety lock speed|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ResetVelocity|Reset Velocity|
|Retract|Retract|
|Reverse|Reverse|
|ShareInertiaTensor|Share inertia tensor On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Force weld|bool|
|LowerLimit|float|
|MaxImpulseAxis|float|
|MaxImpulseNonAxis|float|
|Name|StringBuilder|
|OnOff|bool|
|SafetyDetach|float|
|ShareInertiaTensor|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UpperLimit|float|
|Velocity|float|
|Weld speed|float|

## IMyFunctionalBlock

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyGasGenerator

### Actions

|Name|Description|
|-|-|
|Auto-Refill|Auto-Refill On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Refill|Refill Bottles|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Auto-Refill|bool|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMyGasTank

### Actions

|Name|Description|
|-|-|
|Auto-Refill|Auto-Refill On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Refill|Refill Bottles|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|Stockpile|Stockpile On/Off|
|Stockpile_Off|Stockpile Off|
|Stockpile_On|Stockpile On|

### Properties

|Name|Type|
|-|-|
|Auto-Refill|bool|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|Stockpile|bool|

## IMyGravityGenerator

### Actions

|Name|Description|
|-|-|
|DecreaseDepth|Decrease Field depth|
|DecreaseGravity|Decrease Acceleration|
|DecreaseHeight|Decrease Field height|
|DecreaseWidth|Decrease Field width|
|IncreaseDepth|Increase Field depth|
|IncreaseGravity|Increase Acceleration|
|IncreaseHeight|Increase Field height|
|IncreaseWidth|Increase Field width|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Depth|float|
|Gravity|float|
|Height|float|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|Width|float|

## IMyGravityGeneratorSphere

### Actions

|Name|Description|
|-|-|
|DecreaseGravity|Decrease Acceleration|
|DecreaseRadius|Decrease Radius|
|IncreaseGravity|Increase Acceleration|
|IncreaseRadius|Increase Radius|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Gravity|float|
|Name|StringBuilder|
|OnOff|bool|
|Radius|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyGyro

### Actions

|Name|Description|
|-|-|
|DecreasePitch|Decrease Pitch override|
|DecreasePower|Decrease Power|
|DecreaseRoll|Decrease Roll override|
|DecreaseYaw|Decrease Yaw override|
|IncreasePitch|Increase Pitch override|
|IncreasePower|Increase Power|
|IncreaseRoll|Increase Roll override|
|IncreaseYaw|Increase Yaw override|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Override|Override controls On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|Override|bool|
|Pitch|float|
|Power|float|
|Roll|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|Yaw|float|

## IMyInteriorLight

### Actions

|Name|Description|
|-|-|
|DecreaseBlink Interval|Decrease Blink Interval|
|DecreaseBlink Lenght|Decrease Blink Length|
|DecreaseBlink Offset|Decrease Blink Offset|
|DecreaseFalloff|Decrease Falloff|
|DecreaseIntensity|Decrease Intensity|
|DecreaseOffset|Decrease Offset|
|DecreaseRadius|Decrease Radius|
|IncreaseBlink Interval|Increase Blink Interval|
|IncreaseBlink Lenght|Increase Blink Length|
|IncreaseBlink Offset|Increase Blink Offset|
|IncreaseFalloff|Increase Falloff|
|IncreaseIntensity|Increase Intensity|
|IncreaseOffset|Increase Offset|
|IncreaseRadius|Increase Radius|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Blink Interval|float|
|Blink Lenght|float|
|Blink Offset|float|
|Color|Color|
|Falloff|float|
|Intensity|float|
|Name|StringBuilder|
|Offset|float|
|OnOff|bool|
|Radius|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyJumpDrive

### Actions

|Name|Description|
|-|-|
|DecreaseJumpDistance|Decrease Distance|
|IncreaseJumpDistance|Increase Distance|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Recharge|Recharge On/Off|
|Recharge_Off|Recharge Off|
|Recharge_On|Recharge On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|JumpDistance|float|
|Name|StringBuilder|
|OnOff|bool|
|Recharge|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyLandingGear

### Actions

|Name|Description|
|-|-|
|Autolock|Autolock On/Off|
|Lock|Lock|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|SwitchLock|Switch lock|
|Unlock|Unlock|

### Properties

|Name|Type|
|-|-|
|Autolock|bool|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyLargeGatlingTurret

### Actions

|Name|Description|
|-|-|
|DecreaseRange|Decrease Aiming radius|
|EnableIdleMovement|Enable idle movement On/Off|
|EnableIdleMovement_Off|Enable idle movement Off|
|EnableIdleMovement_On|Enable idle movement On|
|IncreaseRange|Increase Aiming radius|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Shoot|Shoot On/Off|
|Shoot_Off|Shoot Off|
|Shoot_On|Shoot On|
|ShootOnce|Shoot once|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|TargetCharacters|Target characters On/Off|
|TargetCharacters_Off|Target characters Off|
|TargetCharacters_On|Target characters On|
|TargetLargeShips|Target large ships On/Off|
|TargetLargeShips_Off|Target large ships Off|
|TargetLargeShips_On|Target large ships On|
|TargetMeteors|Target meteors On/Off|
|TargetMeteors_Off|Target meteors Off|
|TargetMeteors_On|Target meteors On|
|TargetMissiles|Target missiles On/Off|
|TargetMissiles_Off|Target missiles Off|
|TargetMissiles_On|Target missiles On|
|TargetNeutrals|Target neutrals On/Off|
|TargetNeutrals_Off|Target neutrals Off|
|TargetNeutrals_On|Target neutrals On|
|TargetSmallShips|Target small ships On/Off|
|TargetSmallShips_Off|Target small ships Off|
|TargetSmallShips_On|Target small ships On|
|TargetStations|Target stations On/Off|
|TargetStations_Off|Target stations Off|
|TargetStations_On|Target stations On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|EnableIdleMovement|bool|
|Name|StringBuilder|
|OnOff|bool|
|Range|float|
|Shoot|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TargetCharacters|bool|
|TargetLargeShips|bool|
|TargetMeteors|bool|
|TargetMissiles|bool|
|TargetNeutrals|bool|
|TargetSmallShips|bool|
|TargetStations|bool|
|UseConveyor|bool|

## IMyLargeInteriorTurret

### Actions

|Name|Description|
|-|-|
|DecreaseRange|Decrease Aiming radius|
|EnableIdleMovement|Enable idle movement On/Off|
|EnableIdleMovement_Off|Enable idle movement Off|
|EnableIdleMovement_On|Enable idle movement On|
|IncreaseRange|Increase Aiming radius|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Shoot|Shoot On/Off|
|Shoot_Off|Shoot Off|
|Shoot_On|Shoot On|
|ShootOnce|Shoot once|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|TargetCharacters|Target characters On/Off|
|TargetCharacters_Off|Target characters Off|
|TargetCharacters_On|Target characters On|
|TargetLargeShips|Target large ships On/Off|
|TargetLargeShips_Off|Target large ships Off|
|TargetLargeShips_On|Target large ships On|
|TargetMeteors|Target meteors On/Off|
|TargetMeteors_Off|Target meteors Off|
|TargetMeteors_On|Target meteors On|
|TargetMissiles|Target missiles On/Off|
|TargetMissiles_Off|Target missiles Off|
|TargetMissiles_On|Target missiles On|
|TargetNeutrals|Target neutrals On/Off|
|TargetNeutrals_Off|Target neutrals Off|
|TargetNeutrals_On|Target neutrals On|
|TargetSmallShips|Target small ships On/Off|
|TargetSmallShips_Off|Target small ships Off|
|TargetSmallShips_On|Target small ships On|
|TargetStations|Target stations On/Off|
|TargetStations_Off|Target stations Off|
|TargetStations_On|Target stations On|

### Properties

|Name|Type|
|-|-|
|EnableIdleMovement|bool|
|Name|StringBuilder|
|OnOff|bool|
|Range|float|
|Shoot|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TargetCharacters|bool|
|TargetLargeShips|bool|
|TargetMeteors|bool|
|TargetMissiles|bool|
|TargetNeutrals|bool|
|TargetSmallShips|bool|
|TargetStations|bool|

## IMyLaserAntenna

### Actions

|Name|Description|
|-|-|
|ConnectGPS|Connect to coords|
|DecreaseRange|Decrease Range|
|Idle|Idle|
|IncreaseRange|Increase Range|
|isPerm|Permanent connection On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|PasteGpsCoords|Paste coords|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|gpsCoords|StringBuilder|
|isPerm|bool|
|Name|StringBuilder|
|OnOff|bool|
|Range|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyMedicalRoom

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|SetFaction|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|SpawnName|StringBuilder|
|TakeOwnership|bool|

## IMyMotorAdvancedStator

### Actions

|Name|Description|
|-|-|
|AddHingeTopPart|Add Hinge Head|
|AddRotorTopPart|Add Rotor Head|
|AddSmallHingeTopPart|Add Small Head|
|AddSmallRotorTopPart|Add Small Head|
|Attach|Attach|
|DecreaseBrakingTorque|Decrease Braking torque|
|DecreaseDisplacement|Decrease Rotor displacement|
|DecreaseLowerLimit|Decrease Lower limit|
|DecreaseSafetyDetach|Decrease Safety detach|
|DecreaseTorque|Decrease Torque|
|DecreaseUpperLimit|Decrease Upper limit|
|DecreaseVelocity|Decrease Velocity|
|DecreaseWeld speed|Decrease Safety lock speed|
|Detach|Detach|
|Force weld|Safety lock override On/Off|
|HingeLock|Hinge lock On/Off|
|IncreaseBrakingTorque|Increase Braking torque|
|IncreaseDisplacement|Increase Rotor displacement|
|IncreaseLowerLimit|Increase Lower limit|
|IncreaseSafetyDetach|Increase Safety detach|
|IncreaseTorque|Increase Torque|
|IncreaseUpperLimit|Increase Upper limit|
|IncreaseVelocity|Increase Velocity|
|IncreaseWeld speed|Increase Safety lock speed|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ResetVelocity|Reset Velocity|
|Reverse|Reverse|
|RotorLock|Rotor lock On/Off|
|ShareInertiaTensor|Share inertia tensor On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|BrakingTorque|float|
|Displacement|float|
|Force weld|bool|
|HingeLock|bool|
|LowerLimit|float|
|Name|StringBuilder|
|OnOff|bool|
|RotorLock|bool|
|SafetyDetach|float|
|ShareInertiaTensor|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|Torque|float|
|UpperLimit|float|
|Velocity|float|
|Weld speed|float|

## IMyMotorSuspension

### Actions

|Name|Description|
|-|-|
|Add Top Part|Add Wheel|
|AirShock|AirShock On/Off|
|Braking|Brake On/Off|
|DecreaseFriction|Decrease Friction|
|DecreaseHeight|Decrease Height Offset|
|DecreaseMaxSteerAngle|Decrease Steering Angle|
|DecreasePower|Decrease Power|
|DecreasePropulsion override|Decrease Propulsion override|
|DecreaseSafetyDetach|Decrease Safety detach|
|DecreaseSpeed Limit|Decrease Speed limit|
|DecreaseSteer override|Decrease Steer override|
|DecreaseStrength|Decrease Strength|
|DecreaseWeld speed|Decrease Safety lock speed|
|Force weld|Safety lock override On/Off|
|IncreaseFriction|Increase Friction|
|IncreaseHeight|Increase Height Offset|
|IncreaseMaxSteerAngle|Increase Steering Angle|
|IncreasePower|Increase Power|
|IncreasePropulsion override|Increase Propulsion override|
|IncreaseSafetyDetach|Increase Safety detach|
|IncreaseSpeed Limit|Increase Speed limit|
|IncreaseSteer override|Increase Steer override|
|IncreaseStrength|Increase Strength|
|IncreaseWeld speed|Increase Safety lock speed|
|InvertPropulsion|Invert Propulsion On/Off|
|InvertSteering|Invert Steering On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Propulsion|Propulsion On/Off|
|ResetHeight|Reset Height Offset|
|ResetMaxSteerAngle|Reset Steering Angle|
|ResetPropulsion override|Reset Propulsion override|
|ResetSpeed Limit|Reset Speed limit|
|ResetSteer override|Reset Steer override|
|ShareInertiaTensor|Share inertia tensor On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|Steering|Steering On/Off|

### Properties

|Name|Type|
|-|-|
|AirShock|bool|
|Braking|bool|
|Force weld|bool|
|Friction|float|
|Height|float|
|InvertPropulsion|bool|
|InvertSteering|bool|
|MaxSteerAngle|float|
|Name|StringBuilder|
|OnOff|bool|
|Power|float|
|Propulsion|bool|
|Propulsion override|float|
|SafetyDetach|float|
|ShareInertiaTensor|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|Speed Limit|float|
|Steer override|float|
|Steering|bool|
|Strength|float|
|Weld speed|float|

## IMyOreDetector

### Actions

|Name|Description|
|-|-|
|BroadcastUsingAntennas|Broadcast using antennas On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|BroadcastUsingAntennas|bool|
|Name|StringBuilder|
|OnOff|bool|
|Range|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyOxygenFarm

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyParachute

### Actions

|Name|Description|
|-|-|
|AnyoneCanUse|Anyone Can Use On/Off|
|AutoDeploy|Auto deploy On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Open| Open/Closed|
|Open_Off| Closed|
|Open_On| Open|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|AnyoneCanUse|bool|
|AutoDeploy|bool|
|AutoDeployHeight|float|
|Name|StringBuilder|
|OnOff|bool|
|Open|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyPistonBase

### Actions

|Name|Description|
|-|-|
|Add Top Part|Add Piston Head|
|DecreaseLowerLimit|Decrease Minimum distance|
|DecreaseMaxImpulseAxis|Decrease Max Impulse Axis|
|DecreaseMaxImpulseNonAxis|Decrease Max Impulse NonAxis|
|DecreaseSafetyDetach|Decrease Safety detach|
|DecreaseUpperLimit|Decrease Maximum distance|
|DecreaseVelocity|Decrease Velocity|
|DecreaseWeld speed|Decrease Safety lock speed|
|Extend|Extend|
|Force weld|Safety lock override On/Off|
|IncreaseLowerLimit|Increase Minimum distance|
|IncreaseMaxImpulseAxis|Increase Max Impulse Axis|
|IncreaseMaxImpulseNonAxis|Increase Max Impulse NonAxis|
|IncreaseSafetyDetach|Increase Safety detach|
|IncreaseUpperLimit|Increase Maximum distance|
|IncreaseVelocity|Increase Velocity|
|IncreaseWeld speed|Increase Safety lock speed|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ResetVelocity|Reset Velocity|
|Retract|Retract|
|Reverse|Reverse|
|ShareInertiaTensor|Share inertia tensor On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Force weld|bool|
|LowerLimit|float|
|MaxImpulseAxis|float|
|MaxImpulseNonAxis|float|
|Name|StringBuilder|
|OnOff|bool|
|SafetyDetach|float|
|ShareInertiaTensor|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UpperLimit|float|
|Velocity|float|
|Weld speed|float|

## IMyProgrammableBlock

### Actions

|Name|Description|
|-|-|
|DecreaseChangeIntervalSlider|Decrease Image change interval|
|DecreaseFontSize|Decrease Font Size|
|DecreaseTextPaddingSlider|Decrease Text Padding|
|IncreaseChangeIntervalSlider|Increase Image change interval|
|IncreaseFontSize|Increase Font Size|
|IncreaseTextPaddingSlider|Increase Text Padding|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|PreserveAspectRatio|Preserve aspect ratio On/Off|
|Run|Run|
|RunWithDefaultArgument|Run with default argument|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|alignment|long|
|BackgroundColor|Color|
|ChangeIntervalSlider|float|
|ConsoleCommand|StringBuilder|
|Content|long|
|Font|long|
|FontColor|Color|
|FontSize|float|
|Name|StringBuilder|
|OnOff|bool|
|PreserveAspectRatio|bool|
|ScriptBackgroundColor|Color|
|ScriptForegroundColor|Color|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TextPaddingSlider|float|

## IMyProjector

### Actions

|Name|Description|
|-|-|
|DecreaseChangeIntervalSlider|Decrease Image change interval|
|DecreaseFontSize|Decrease Font Size|
|DecreaseRotX|Decrease Pitch|
|DecreaseRotY|Decrease Yaw|
|DecreaseRotZ|Decrease Roll|
|DecreaseScale|Decrease Scale|
|DecreaseTextPaddingSlider|Decrease Text Padding|
|DecreaseX|Decrease Horizontal offset|
|DecreaseY|Decrease Vertical offset|
|DecreaseZ|Decrease Forward offset|
|IncreaseChangeIntervalSlider|Increase Image change interval|
|IncreaseFontSize|Increase Font Size|
|IncreaseRotX|Increase Pitch|
|IncreaseRotY|Increase Yaw|
|IncreaseRotZ|Increase Roll|
|IncreaseScale|Increase Scale|
|IncreaseTextPaddingSlider|Increase Text Padding|
|IncreaseX|Increase Horizontal offset|
|IncreaseY|Increase Vertical offset|
|IncreaseZ|Increase Forward offset|
|KeepProjection|Keep Projection On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|PreserveAspectRatio|Preserve aspect ratio On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|SpawnProjection|Spawn projection|

### Properties

|Name|Type|
|-|-|
|alignment|long|
|BackgroundColor|Color|
|ChangeIntervalSlider|float|
|Content|long|
|Font|long|
|FontColor|Color|
|FontSize|float|
|GetOwnership|bool|
|InstantBuilding|bool|
|KeepProjection|bool|
|Name|StringBuilder|
|NumberOfBlocks|float|
|NumberOfProjections|float|
|OnOff|bool|
|PreserveAspectRatio|bool|
|RotX|float|
|RotY|float|
|RotZ|float|
|Scale|float|
|ScriptBackgroundColor|Color|
|ScriptForegroundColor|Color|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|ShowOnlyBuildable|bool|
|TextPaddingSlider|float|
|X|float|
|Y|float|
|Z|float|

## IMyRadioAntenna

### Actions

|Name|Description|
|-|-|
|DecreaseRadius|Decrease Broadcast radius|
|EnableBroadCast|Enable broadcasting On/Off|
|IncreaseRadius|Increase Broadcast radius|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowShipName|Show ship name On/Off|

### Properties

|Name|Type|
|-|-|
|CustomName|StringBuilder|
|EnableBroadCast|bool|
|HudText|StringBuilder|
|OnOff|bool|
|Radius|float|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowShipName|bool|

## IMyReactor

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMyRefinery

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMyReflectorLight

### Actions

|Name|Description|
|-|-|
|DecreaseBlink Interval|Decrease Blink Interval|
|DecreaseBlink Lenght|Decrease Blink Length|
|DecreaseBlink Offset|Decrease Blink Offset|
|DecreaseFalloff|Decrease Falloff|
|DecreaseIntensity|Decrease Intensity|
|DecreaseOffset|Decrease Offset|
|DecreaseRadius|Decrease Radius|
|DecreaseRotationSpeed|Decrease Rotation speed|
|IncreaseBlink Interval|Increase Blink Interval|
|IncreaseBlink Lenght|Increase Blink Length|
|IncreaseBlink Offset|Increase Blink Offset|
|IncreaseFalloff|Increase Falloff|
|IncreaseIntensity|Increase Intensity|
|IncreaseOffset|Increase Offset|
|IncreaseRadius|Increase Radius|
|IncreaseRotationSpeed|Increase Rotation speed|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Blink Interval|float|
|Blink Lenght|float|
|Blink Offset|float|
|Color|Color|
|Falloff|float|
|Intensity|float|
|Name|StringBuilder|
|Offset|float|
|OnOff|bool|
|Radius|float|
|RotationSpeed|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyRemoteControl

### Actions

|Name|Description|
|-|-|
|AutoPilot|Autopilot On/Off|
|AutoPilot_Off|Autopilot Off|
|AutoPilot_On|Autopilot On|
|Backward|Backward|
|CollisionAvoidance|Collision avoidance On/Off|
|CollisionAvoidance_Off|Collision avoidance Off|
|CollisionAvoidance_On|Collision avoidance On|
|ControlGyros|Control Gyros On/Off|
|ControlThrusters|Control thrusters On/Off|
|ControlWheels|Control wheels On/Off|
|DampenersOverride|Inertia dampeners On/Off|
|DecreaseSpeedLimit|Decrease Speed limit|
|DockingMode|Precision Mode On/Off|
|DockingMode_Off|Precision Mode Off|
|DockingMode_On|Precision Mode On|
|Down|Down|
|Forward|Forward|
|HandBrake|Handbrake On/Off|
|HorizonIndicator|Show horizon and altitude On/Off|
|IncreaseSpeedLimit|Increase Speed limit|
|Left|Left|
|MainCockpit|Main cockpit On/Off|
|MainRemoteControl|Main Remote Control On/Off|
|Right|Right|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|Up|Up|

### Properties

|Name|Type|
|-|-|
|AutoPilot|bool|
|CameraList|long|
|CollisionAvoidance|bool|
|ControlGyros|bool|
|ControlThrusters|bool|
|ControlWheels|bool|
|DampenersOverride|bool|
|Direction|long|
|DockingMode|bool|
|FlightMode|long|
|HandBrake|bool|
|HorizonIndicator|bool|
|MainCockpit|bool|
|MainRemoteControl|bool|
|Name|StringBuilder|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|SpeedLimit|float|

## IMySafeZoneBlock

### Actions

|Name|Description|
|-|-|
|DecreaseChangeIntervalSlider|Decrease Image change interval|
|DecreaseFontSize|Decrease Font Size|
|DecreaseSafeZoneXSlider|Decrease Set Width|
|DecreaseTextPaddingSlider|Decrease Text Padding|
|IncreaseChangeIntervalSlider|Increase Image change interval|
|IncreaseFontSize|Increase Font Size|
|IncreaseSafeZoneXSlider|Increase Set Width|
|IncreaseTextPaddingSlider|Increase Text Padding|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|PreserveAspectRatio|Preserve aspect ratio On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|alignment|long|
|BackgroundColor|Color|
|ChangeIntervalSlider|float|
|Content|long|
|Font|long|
|FontColor|Color|
|FontSize|float|
|Name|StringBuilder|
|OnOff|bool|
|PreserveAspectRatio|bool|
|SafeZoneBuildingCb|bool|
|SafeZoneColor|Color|
|SafeZoneConvertToStationCb|bool|
|SafeZoneCreate|bool|
|SafeZoneDamageCb|bool|
|SafeZoneDrillingCb|bool|
|SafeZoneGrindingCb|bool|
|SafeZoneLandingGearCb|bool|
|SafeZoneShapeCombo|long|
|SafeZoneShootingCb|bool|
|SafeZoneSlider|float|
|SafeZoneTextureCombo|long|
|SafeZoneVoxelHandCb|bool|
|SafeZoneWeldingCb|bool|
|SafeZoneXSlider|float|
|SafeZoneYSlider|float|
|SafeZoneZSlider|float|
|ScriptBackgroundColor|Color|
|ScriptForegroundColor|Color|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TextPaddingSlider|float|

## IMySensorBlock

### Actions

|Name|Description|
|-|-|
|DecreaseBack|Decrease Back extent|
|DecreaseBottom|Decrease Bottom extent|
|DecreaseFront|Decrease Front extent|
|DecreaseLeft|Decrease Left extent|
|DecreaseRight|Decrease Right extent|
|DecreaseTop|Decrease Top extent|
|Detect Asteroids|Detect asteroids On/Off|
|Detect Asteroids_Off|Detect asteroids Off|
|Detect Asteroids_On|Detect asteroids On|
|Detect Enemy|Detect enemy On/Off|
|Detect Enemy_Off|Detect enemy Off|
|Detect Enemy_On|Detect enemy On|
|Detect Floating Objects|Detect floating objects On/Off|
|Detect Floating Objects_Off|Detect floating objects Off|
|Detect Floating Objects_On|Detect floating objects On|
|Detect Friendly|Detect friendly On/Off|
|Detect Friendly_Off|Detect friendly Off|
|Detect Friendly_On|Detect friendly On|
|Detect Large Ships|Detect large ships On/Off|
|Detect Large Ships_Off|Detect large ships Off|
|Detect Large Ships_On|Detect large ships On|
|Detect Neutral|Detect neutral On/Off|
|Detect Neutral_Off|Detect neutral Off|
|Detect Neutral_On|Detect neutral On|
|Detect Owner|Detect owner On/Off|
|Detect Owner_Off|Detect owner Off|
|Detect Owner_On|Detect owner On|
|Detect Players|Detect players On/Off|
|Detect Players_Off|Detect players Off|
|Detect Players_On|Detect players On|
|Detect Small Ships|Detect small ships On/Off|
|Detect Small Ships_Off|Detect small ships Off|
|Detect Small Ships_On|Detect small ships On|
|Detect Stations|Detect stations On/Off|
|Detect Stations_Off|Detect stations Off|
|Detect Stations_On|Detect stations On|
|Detect Subgrids|Detect subgrids On/Off|
|Detect Subgrids_Off|Detect subgrids Off|
|Detect Subgrids_On|Detect subgrids On|
|IncreaseBack|Increase Back extent|
|IncreaseBottom|Increase Bottom extent|
|IncreaseFront|Increase Front extent|
|IncreaseLeft|Increase Left extent|
|IncreaseRight|Increase Right extent|
|IncreaseTop|Increase Top extent|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Audible Proximity Alert|bool|
|Back|float|
|Bottom|float|
|Detect Asteroids|bool|
|Detect Enemy|bool|
|Detect Floating Objects|bool|
|Detect Friendly|bool|
|Detect Large Ships|bool|
|Detect Neutral|bool|
|Detect Owner|bool|
|Detect Players|bool|
|Detect Small Ships|bool|
|Detect Stations|bool|
|Detect Subgrids|bool|
|Front|float|
|Left|float|
|Name|StringBuilder|
|OnOff|bool|
|Right|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|Top|float|

## IMyShipConnector

### Actions

|Name|Description|
|-|-|
|CollectAll|Collect All On/Off|
|DecreaseAutoUnlockTime|Decrease Autounlock Time|
|DecreaseStrength|Decrease Strength|
|IncreaseAutoUnlockTime|Increase Autounlock Time|
|IncreaseStrength|Increase Strength|
|Lock|Lock|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|SwitchLock|Switch lock|
|ThrowOut|Throw Out On/Off|
|Trading|Trading Mode On/Off|
|Unlock|Unlock|

### Properties

|Name|Type|
|-|-|
|AutoUnlockTime|float|
|CollectAll|bool|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|Strength|float|
|ThrowOut|bool|
|Trading|bool|

## IMyShipController

### Actions

|Name|Description|
|-|-|
|ControlGyros|Control Gyros On/Off|
|ControlThrusters|Control thrusters On/Off|
|ControlWheels|Control wheels On/Off|
|DampenersOverride|Inertia dampeners On/Off|
|HandBrake|Handbrake On/Off|
|HorizonIndicator|Show horizon and altitude On/Off|
|MainCockpit|Main cockpit On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|ControlGyros|bool|
|ControlThrusters|bool|
|ControlWheels|bool|
|DampenersOverride|bool|
|HandBrake|bool|
|HorizonIndicator|bool|
|MainCockpit|bool|
|Name|StringBuilder|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyShipDrill

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMyShipGrinder

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMyShipMergeBlock

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyShipWelder

### Actions

|Name|Description|
|-|-|
|helpOthers|Help Others On/Off|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|helpOthers|bool|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMySmallGatlingGun

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Shoot|Shoot On/Off|
|Shoot_Off|Shoot Off|
|Shoot_On|Shoot On|
|ShootOnce|Shoot once|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|Shoot|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMySmallMissileLauncher

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Shoot|Shoot On/Off|
|Shoot_Off|Shoot Off|
|Shoot_On|Shoot On|
|ShootOnce|Shoot once|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|Shoot|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|

## IMySmallMissileLauncherReload

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|Shoot|Shoot On/Off|
|Shoot_Off|Shoot Off|
|Shoot_On|Shoot On|
|ShootOnce|Shoot once|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|Shoot|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|UseConveyor|bool|
|UseConveyor|bool|

## IMySolarPanel

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMySoundBlock

### Actions

|Name|Description|
|-|-|
|DecreaseLoopableSlider|Decrease Loop time|
|DecreaseRangeSlider|Decrease Range|
|DecreaseVolumeSlider|Decrease Volume|
|IncreaseLoopableSlider|Increase Loop time|
|IncreaseRangeSlider|Increase Range|
|IncreaseVolumeSlider|Increase Volume|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|PlaySound|Play|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|StopSound|Stop|

### Properties

|Name|Type|
|-|-|
|LoopableSlider|float|
|Name|StringBuilder|
|OnOff|bool|
|RangeSlider|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|VolumeSlider|float|

## IMySpaceBall

### Actions

|Name|Description|
|-|-|
|DecreaseVirtualMass|Decrease Virtual mass|
|EnableBroadCast|Enable broadcasting On/Off|
|IncreaseVirtualMass|Increase Virtual mass|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|EnableBroadCast|bool|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|VirtualMass|float|

## IMyStoreBlock

### Actions

|Name|Description|
|-|-|
|AnyoneCanUse|Anyone Can Use On/Off|
|DecreaseChangeIntervalSlider|Decrease Image change interval|
|DecreaseFontSize|Decrease Font Size|
|DecreaseTextPaddingSlider|Decrease Text Padding|
|IncreaseChangeIntervalSlider|Increase Image change interval|
|IncreaseFontSize|Increase Font Size|
|IncreaseTextPaddingSlider|Increase Text Padding|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|PreserveAspectRatio|Preserve aspect ratio On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|UseConveyor|Use Conveyor System On/Off|

### Properties

|Name|Type|
|-|-|
|alignment|long|
|AnyoneCanUse|bool|
|BackgroundColor|Color|
|ChangeIntervalSlider|float|
|Content|long|
|Font|long|
|FontColor|Color|
|FontSize|float|
|Name|StringBuilder|
|OnOff|bool|
|PreserveAspectRatio|bool|
|ScriptBackgroundColor|Color|
|ScriptForegroundColor|Color|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TextPaddingSlider|float|
|UseConveyor|bool|

## IMyTerminalBlock

### Actions

|Name|Description|
|-|-|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyTextPanel

### Actions

|Name|Description|
|-|-|
|DecreaseChangeIntervalSlider|Decrease Image change interval|
|DecreaseFontSize|Decrease Font Size|
|DecreaseRotate|Decrease Rotation|
|DecreaseTextPaddingSlider|Decrease Text Padding|
|IncreaseChangeIntervalSlider|Increase Image change interval|
|IncreaseFontSize|Increase Font Size|
|IncreaseRotate|Increase Rotation|
|IncreaseTextPaddingSlider|Increase Text Padding|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|PreserveAspectRatio|Preserve aspect ratio On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|alignment|long|
|BackgroundColor|Color|
|ChangeIntervalSlider|float|
|Content|long|
|Font|long|
|FontColor|Color|
|FontSize|float|
|Name|StringBuilder|
|OnOff|bool|
|PreserveAspectRatio|bool|
|Rotate|float|
|ScriptBackgroundColor|Color|
|ScriptForegroundColor|Color|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|TextPaddingSlider|float|
|Title|StringBuilder|

## IMyThrust

### Actions

|Name|Description|
|-|-|
|DecreaseOverride|Decrease Thrust override|
|IncreaseOverride|Increase Thrust override|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|Override|float|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyTimerBlock

### Actions

|Name|Description|
|-|-|
|DecreaseTriggerDelay|Decrease Delay|
|IncreaseTriggerDelay|Increase Delay|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|Silent|Silent On/Off|
|Start|Start|
|Stop|Stop|
|TriggerNow|Trigger now|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|
|Silent|bool|
|TriggerDelay|float|

## IMyUpgradeModule

### Actions

|Name|Description|
|-|-|
|OnOff|Toggle block On/Off|
|OnOff_Off|Toggle block Off|
|OnOff_On|Toggle block On|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|

### Properties

|Name|Type|
|-|-|
|Name|StringBuilder|
|OnOff|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

## IMyWarhead

### Actions

|Name|Description|
|-|-|
|DecreaseDetonationTime|Decrease Detonation time|
|Detonate|Detonate|
|IncreaseDetonationTime|Increase Detonation time|
|Safety|Arm warhead On/Off|
|ShowOnHUD|Show on HUD On/Off|
|ShowOnHUD_Off|Show on HUD Off|
|ShowOnHUD_On|Show on HUD On|
|StartCountdown|Start countdown|
|StopCountdown|Stop countdown|

### Properties

|Name|Type|
|-|-|
|DetonationTime|float|
|Name|StringBuilder|
|Safety|bool|
|ShowInInventory|bool|
|ShowInTerminal|bool|
|ShowInToolbarConfig|bool|
|ShowOnHUD|bool|

