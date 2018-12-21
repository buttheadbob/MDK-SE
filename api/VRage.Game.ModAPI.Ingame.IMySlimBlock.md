← [Index](index)
# IMySlimBlock Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
basic block interface
### Properties
<table style="width:100%;display:table">
<tr><td>[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)</td><td>Block definition ID</td></tr>
<tr><td>[`float AccumulatedDamage`](VRage.Game.ModAPI.Ingame.AccumulatedDamage)</td><td>Current accumlated damage, pending application</td></tr>
<tr><td>[`float BuildIntegrity`](VRage.Game.ModAPI.Ingame.BuildIntegrity)</td><td>Build integrity (of components)</td></tr>
<tr><td>[`float BuildLevelRatio`](VRage.Game.ModAPI.Ingame.BuildLevelRatio)</td><td>Ratio of BuildIntegrity and MaxIntegrity</td></tr>
<tr><td>[`float CurrentDamage`](VRage.Game.ModAPI.Ingame.CurrentDamage)</td><td>BuildIntegrity - Integrity</td></tr>
<tr><td>[`float DamageRatio`](VRage.Game.ModAPI.Ingame.DamageRatio)</td><td></td></tr>
<tr><td>[`IMyCubeBlock FatBlock`](VRage.Game.ModAPI.Ingame.FatBlock)</td><td>Gets the fatblock if there is one</td></tr>
<tr><td>[`bool HasDeformation`](VRage.Game.ModAPI.Ingame.HasDeformation)</td><td>If this block is deformed (bones deformed)</td></tr>
<tr><td>[`bool IsDestroyed`](VRage.Game.ModAPI.Ingame.IsDestroyed)</td><td>Gets if component stack is empty</td></tr>
<tr><td>[`bool IsFullIntegrity`](VRage.Game.ModAPI.Ingame.IsFullIntegrity)</td><td>Integrity is at maximum</td></tr>
<tr><td>[`bool IsFullyDismounted`](VRage.Game.ModAPI.Ingame.IsFullyDismounted)</td><td>Gets if component stack is empty</td></tr>
<tr><td>[`float MaxDeformation`](VRage.Game.ModAPI.Ingame.MaxDeformation)</td><td>Maximum deformation of block</td></tr>
<tr><td>[`float MaxIntegrity`](VRage.Game.ModAPI.Ingame.MaxIntegrity)</td><td>The maximum integrity of block</td></tr>
<tr><td>[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)</td><td>Block mass</td></tr>
<tr><td>[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)</td><td>Fatblock owner, if present; otherwise grid owner</td></tr>
<tr><td>[`bool ShowParts`](VRage.Game.ModAPI.Ingame.ShowParts)</td><td>Gets if sub parts are shown</td></tr>
<tr><td>[`bool StockpileAllocated`](VRage.Game.ModAPI.Ingame.StockpileAllocated)</td><td>A component stockpile has been allocated</td></tr>
<tr><td>[`bool StockpileEmpty`](VRage.Game.ModAPI.Ingame.StockpileEmpty)</td><td>The component stockpile is empty (no build components)</td></tr>
<tr><td>[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)</td><td>Grid relative position of block</td></tr>
<tr><td>[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)</td><td>Gets the grid the slimblock is on</td></tr>
<tr><td>[`Vector3 ColorMaskHSV`](VRage.Game.ModAPI.Ingame.ColorMaskHSV)</td><td>Gets the color of the block</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`void GetMissingComponents(Dictionary<string, int> addToDictionary)`](VRage.Game.ModAPI.Ingame.GetMissingComponents)</td><td>Gets the list of missing components for this block</td></tr>
</table>
