← [Index](index)
# IMySlimBlock Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
basic block interface
### Properties
|Member|Description|
|---|---|
|[`BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|Block definition ID|
|[`AccumulatedDamage`](VRage.Game.ModAPI.Ingame.AccumulatedDamage)|Current accumlated damage, pending application|
|[`BuildIntegrity`](VRage.Game.ModAPI.Ingame.BuildIntegrity)|Build integrity (of components)|
|[`BuildLevelRatio`](VRage.Game.ModAPI.Ingame.BuildLevelRatio)|Ratio of BuildIntegrity and MaxIntegrity|
|[`CurrentDamage`](VRage.Game.ModAPI.Ingame.CurrentDamage)|BuildIntegrity - Integrity|
|[`DamageRatio`](VRage.Game.ModAPI.Ingame.DamageRatio)||
|[`FatBlock`](VRage.Game.ModAPI.Ingame.FatBlock)|Gets the fatblock if there is one|
|[`HasDeformation`](VRage.Game.ModAPI.Ingame.HasDeformation)|If this block is deformed (bones deformed)|
|[`IsDestroyed`](VRage.Game.ModAPI.Ingame.IsDestroyed)|Gets if component stack is empty|
|[`IsFullIntegrity`](VRage.Game.ModAPI.Ingame.IsFullIntegrity)|Integrity is at maximum|
|[`IsFullyDismounted`](VRage.Game.ModAPI.Ingame.IsFullyDismounted)|Gets if component stack is empty|
|[`MaxDeformation`](VRage.Game.ModAPI.Ingame.MaxDeformation)|Maximum deformation of block|
|[`MaxIntegrity`](VRage.Game.ModAPI.Ingame.MaxIntegrity)|The maximum integrity of block|
|[`Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass|
|[`OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Fatblock owner, if present; otherwise grid owner|
|[`ShowParts`](VRage.Game.ModAPI.Ingame.ShowParts)|Gets if sub parts are shown|
|[`StockpileAllocated`](VRage.Game.ModAPI.Ingame.StockpileAllocated)|A component stockpile has been allocated|
|[`StockpileEmpty`](VRage.Game.ModAPI.Ingame.StockpileEmpty)|The component stockpile is empty (no build components)|
|[`Position`](VRage.Game.ModAPI.Ingame.Position)|Grid relative position of block|
|[`CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Gets the grid the slimblock is on|
|[`ColorMaskHSV`](VRage.Game.ModAPI.Ingame.ColorMaskHSV)|Gets the color of the block|
### Methods
|Member|Description|
|---|---|
|[`GetMissingComponents(Dictionary<string, int>)`](VRage.Game.ModAPI.Ingame.GetMissingComponents)|Gets the list of missing components for this block|
