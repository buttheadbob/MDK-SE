← [Index](index)
# IMySlimBlock Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
basic block interface
### Properties
|Member|Description|
|---|---|
|[`SerializableDefinitionId&nbsp;BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|Block definition ID|
|[`float&nbsp;AccumulatedDamage`](VRage.Game.ModAPI.Ingame.AccumulatedDamage)|Current accumlated damage, pending application|
|[`float&nbsp;BuildIntegrity`](VRage.Game.ModAPI.Ingame.BuildIntegrity)|Build integrity (of components)|
|[`float&nbsp;BuildLevelRatio`](VRage.Game.ModAPI.Ingame.BuildLevelRatio)|Ratio of BuildIntegrity and MaxIntegrity|
|[`float&nbsp;CurrentDamage`](VRage.Game.ModAPI.Ingame.CurrentDamage)|BuildIntegrity - Integrity|
|[`float&nbsp;DamageRatio`](VRage.Game.ModAPI.Ingame.DamageRatio)||
|[`IMyCubeBlock&nbsp;FatBlock`](VRage.Game.ModAPI.Ingame.FatBlock)|Gets the fatblock if there is one|
|[`bool&nbsp;HasDeformation`](VRage.Game.ModAPI.Ingame.HasDeformation)|If this block is deformed (bones deformed)|
|[`bool&nbsp;IsDestroyed`](VRage.Game.ModAPI.Ingame.IsDestroyed)|Gets if component stack is empty|
|[`bool&nbsp;IsFullIntegrity`](VRage.Game.ModAPI.Ingame.IsFullIntegrity)|Integrity is at maximum|
|[`bool&nbsp;IsFullyDismounted`](VRage.Game.ModAPI.Ingame.IsFullyDismounted)|Gets if component stack is empty|
|[`float&nbsp;MaxDeformation`](VRage.Game.ModAPI.Ingame.MaxDeformation)|Maximum deformation of block|
|[`float&nbsp;MaxIntegrity`](VRage.Game.ModAPI.Ingame.MaxIntegrity)|The maximum integrity of block|
|[`float&nbsp;Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass|
|[`long&nbsp;OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Fatblock owner, if present; otherwise grid owner|
|[`bool&nbsp;ShowParts`](VRage.Game.ModAPI.Ingame.ShowParts)|Gets if sub parts are shown|
|[`bool&nbsp;StockpileAllocated`](VRage.Game.ModAPI.Ingame.StockpileAllocated)|A component stockpile has been allocated|
|[`bool&nbsp;StockpileEmpty`](VRage.Game.ModAPI.Ingame.StockpileEmpty)|The component stockpile is empty (no build components)|
|[`Vector3I&nbsp;Position`](VRage.Game.ModAPI.Ingame.Position)|Grid relative position of block|
|[`IMyCubeGrid&nbsp;CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Gets the grid the slimblock is on|
|[`Vector3&nbsp;ColorMaskHSV`](VRage.Game.ModAPI.Ingame.ColorMaskHSV)|Gets the color of the block|
### Methods
|Member|Description|
|---|---|
|[`void&nbsp;GetMissingComponents(Dictionary<string,&nbsp;int>&nbsp;addToDictionary)`](VRage.Game.ModAPI.Ingame.GetMissingComponents)|Gets the list of missing components for this block|
