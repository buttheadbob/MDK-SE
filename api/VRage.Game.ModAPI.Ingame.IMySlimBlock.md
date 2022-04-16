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
|\$1float AccumulatedDamage { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.AccumulatedDamage)|Current accumlated damage, pending application|
|\$1SerializableDefinitionId BlockDefinition { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.BlockDefinition)|Block definition ID|
|\$1float BuildIntegrity { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.BuildIntegrity)|Build integrity (of components)|
|\$1float BuildLevelRatio { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.BuildLevelRatio)|Ratio of BuildIntegrity and MaxIntegrity|
|\$1Vector3 ColorMaskHSV { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.ColorMaskHSV)|Gets the color of the block|
|\$1IMyCubeGrid CubeGrid { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.CubeGrid)|Gets the grid the slimblock is on|
|\$1float CurrentDamage { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.CurrentDamage)|BuildIntegrity - Integrity|
|\$1float DamageRatio { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.DamageRatio)||
|\$1IMyCubeBlock FatBlock { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.FatBlock)|Gets the fatblock if there is one|
|\$1bool HasDeformation { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.HasDeformation)|If this block is deformed (bones deformed)|
|\$1bool IsDestroyed { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsDestroyed)|Gets if component stack is empty|
|\$1bool IsFullIntegrity { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsFullIntegrity)|Integrity is at maximum|
|\$1bool IsFullyDismounted { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.IsFullyDismounted)|Gets if component stack is empty|
|\$1float Mass { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.Mass)|Block mass|
|\$1float MaxDeformation { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.MaxDeformation)|Maximum deformation of block|
|\$1float MaxIntegrity { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.MaxIntegrity)|The maximum integrity of block|
|\$1long OwnerId { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.OwnerId)|Fatblock owner, if present; otherwise grid owner|
|\$1Vector3I Position { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.Position)|Grid relative position of block|
|\$1bool ShowParts { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.ShowParts)|Gets if sub parts are shown|
|\$1MyStringHash SkinSubtypeId { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.SkinSubtypeId)|Gets the skin of the block|
|\$1bool StockpileAllocated { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.StockpileAllocated)|A component stockpile has been allocated|
|\$1bool StockpileEmpty { get; }](VRage.Game.ModAPI.Ingame.IMySlimBlock.StockpileEmpty)|The component stockpile is empty (no build components)|

#### Methods

|Member|Description|
|---|---|
|\$1void GetMissingComponents(Dictionary\$1string, int\>)](VRage.Game.ModAPI.Ingame.IMySlimBlock.GetMissingComponents)|Gets the list of missing components for this block|

