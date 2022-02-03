← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMySlimBlock Interface

```csharp
public interface IMySlimBlock
```

Basic block interface (PB scripting interface)

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

#### Properties

|Member|Description|
|---|---|
|[BlockDefinition { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.BlockDefinition)|Block definition ID|
|[AccumulatedDamage { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.AccumulatedDamage)|Current accumlated damage, pending application|
|[BuildIntegrity { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.BuildIntegrity)|Build integrity (of components)|
|[BuildLevelRatio { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.BuildLevelRatio)|Ratio of BuildIntegrity and MaxIntegrity|
|[CurrentDamage { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.CurrentDamage)|BuildIntegrity - Integrity|
|[DamageRatio { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.DamageRatio)||
|[FatBlock { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.FatBlock)|Gets the fatblock if there is one|
|[HasDeformation { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.HasDeformation)|If this block is deformed (bones deformed)|
|[IsDestroyed { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsDestroyed)|Gets if component stack is empty|
|[IsFullIntegrity { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsFullIntegrity)|Integrity is at maximum|
|[IsFullyDismounted { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsFullyDismounted)|Gets if component stack is empty|
|[MaxDeformation { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.MaxDeformation)|Maximum deformation of block|
|[MaxIntegrity { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.MaxIntegrity)|The maximum integrity of block|
|[Mass { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.Mass)|Block mass|
|[OwnerId { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.OwnerId)|Fatblock owner, if present; otherwise grid owner|
|[ShowParts { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.ShowParts)|Gets if sub parts are shown|
|[StockpileAllocated { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.StockpileAllocated)|A component stockpile has been allocated|
|[StockpileEmpty { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.StockpileEmpty)|The component stockpile is empty (no build components)|
|[Position { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.Position)|Grid relative position of block|
|[CubeGrid { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.CubeGrid)|Gets the grid the slimblock is on|
|[ColorMaskHSV { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.ColorMaskHSV)|Gets the color of the block|
|[SkinSubtypeId { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.SkinSubtypeId)|Gets the skin of the block|

#### Methods

|Member|Description|
|---|---|
|[GetMissingComponents(Dictionary)](VRage.Game.ModAPI.Ingame.IMySlimBlock.GetMissingComponents)|Gets the list of missing components for this block|

