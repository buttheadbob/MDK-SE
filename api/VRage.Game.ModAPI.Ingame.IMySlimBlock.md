← [Index](index)
# IMySlimBlock Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
basic block interface
### Properties
|Member|Description|
|---|---|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|Block definition ID|
|[`float AccumulatedDamage`](VRage.Game.ModAPI.Ingame.AccumulatedDamage)|Current accumlated damage, pending application|
|[`float BuildIntegrity`](VRage.Game.ModAPI.Ingame.BuildIntegrity)|Build integrity (of components)|
|[`float BuildLevelRatio`](VRage.Game.ModAPI.Ingame.BuildLevelRatio)|Ratio of BuildIntegrity and MaxIntegrity|
|[`float CurrentDamage`](VRage.Game.ModAPI.Ingame.CurrentDamage)|BuildIntegrity - Integrity|
|[`float DamageRatio`](VRage.Game.ModAPI.Ingame.DamageRatio)||
|[`IMyCubeBlock FatBlock`](VRage.Game.ModAPI.Ingame.FatBlock)|Gets the fatblock if there is one|
|[`bool HasDeformation`](VRage.Game.ModAPI.Ingame.HasDeformation)|If this block is deformed (bones deformed)|
|[`bool IsDestroyed`](VRage.Game.ModAPI.Ingame.IsDestroyed)|Gets if component stack is empty|
|[`bool IsFullIntegrity`](VRage.Game.ModAPI.Ingame.IsFullIntegrity)|Integrity is at maximum|
|[`bool IsFullyDismounted`](VRage.Game.ModAPI.Ingame.IsFullyDismounted)|Gets if component stack is empty|
|[`float MaxDeformation`](VRage.Game.ModAPI.Ingame.MaxDeformation)|Maximum deformation of block|
|[`float MaxIntegrity`](VRage.Game.ModAPI.Ingame.MaxIntegrity)|The maximum integrity of block|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Fatblock owner, if present; otherwise grid owner|
|[`bool ShowParts`](VRage.Game.ModAPI.Ingame.ShowParts)|Gets if sub parts are shown|
|[`bool StockpileAllocated`](VRage.Game.ModAPI.Ingame.StockpileAllocated)|A component stockpile has been allocated|
|[`bool StockpileEmpty`](VRage.Game.ModAPI.Ingame.StockpileEmpty)|The component stockpile is empty (no build components)|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)|Grid relative position of block|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Gets the grid the slimblock is on|
|[`Vector3 ColorMaskHSV`](VRage.Game.ModAPI.Ingame.ColorMaskHSV)|Gets the color of the block|
### Methods
|Member|Description|
|---|---|
|[`void GetMissingComponents(Dictionary<string, int> addToDictionary)`](VRage.Game.ModAPI.Ingame.GetMissingComponents)|Gets the list of missing components for this block|
