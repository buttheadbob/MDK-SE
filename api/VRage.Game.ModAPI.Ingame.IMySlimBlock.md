← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMySlimBlock Interface

```csharp
public interface IMySlimBlock
```

basic block interface

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

#### Properties

|Member|Description|
|---|---|
|[BlockDefinition](VRage.Game.ModAPI.Ingame.IMySlimBlock.BlockDefinition)|Block definition ID|
|[AccumulatedDamage](VRage.Game.ModAPI.Ingame.IMySlimBlock.AccumulatedDamage)|Current accumlated damage, pending application|
|[BuildIntegrity](VRage.Game.ModAPI.Ingame.IMySlimBlock.BuildIntegrity)|Build integrity (of components)|
|[BuildLevelRatio](VRage.Game.ModAPI.Ingame.IMySlimBlock.BuildLevelRatio)|Ratio of BuildIntegrity and MaxIntegrity|
|[CurrentDamage](VRage.Game.ModAPI.Ingame.IMySlimBlock.CurrentDamage)|BuildIntegrity - Integrity|
|[DamageRatio](VRage.Game.ModAPI.Ingame.IMySlimBlock.DamageRatio)||
|[FatBlock](VRage.Game.ModAPI.Ingame.IMySlimBlock.FatBlock)|Gets the fatblock if there is one|
|[HasDeformation](VRage.Game.ModAPI.Ingame.IMySlimBlock.HasDeformation)|If this block is deformed (bones deformed)|
|[IsDestroyed](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsDestroyed)|Gets if component stack is empty|
|[IsFullIntegrity](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsFullIntegrity)|Integrity is at maximum|
|[IsFullyDismounted](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsFullyDismounted)|Gets if component stack is empty|
|[MaxDeformation](VRage.Game.ModAPI.Ingame.IMySlimBlock.MaxDeformation)|Maximum deformation of block|
|[MaxIntegrity](VRage.Game.ModAPI.Ingame.IMySlimBlock.MaxIntegrity)|The maximum integrity of block|
|[Mass](VRage.Game.ModAPI.Ingame.IMySlimBlock.Mass)|Block mass|
|[OwnerId](VRage.Game.ModAPI.Ingame.IMySlimBlock.OwnerId)|Fatblock owner, if present; otherwise grid owner|
|[ShowParts](VRage.Game.ModAPI.Ingame.IMySlimBlock.ShowParts)|Gets if sub parts are shown|
|[StockpileAllocated](VRage.Game.ModAPI.Ingame.IMySlimBlock.StockpileAllocated)|A component stockpile has been allocated|
|[StockpileEmpty](VRage.Game.ModAPI.Ingame.IMySlimBlock.StockpileEmpty)|The component stockpile is empty (no build components)|
|[Position](VRage.Game.ModAPI.Ingame.IMySlimBlock.Position)|Grid relative position of block|
|[CubeGrid](VRage.Game.ModAPI.Ingame.IMySlimBlock.CubeGrid)|Gets the grid the slimblock is on|
|[ColorMaskHSV](VRage.Game.ModAPI.Ingame.IMySlimBlock.ColorMaskHSV)|Gets the color of the block|
|[SkinSubtypeId](VRage.Game.ModAPI.Ingame.IMySlimBlock.SkinSubtypeId)|Gets the skin of the block|

#### Methods

|Member|Description|
|---|---|
|[GetMissingComponents(Dictionary)](VRage.Game.ModAPI.Ingame.IMySlimBlock.GetMissingComponents)|Gets the list of missing components for this block|

