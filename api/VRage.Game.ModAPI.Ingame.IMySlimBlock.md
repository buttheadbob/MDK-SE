← [Index](index)
# IMySlimBlock Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
basic block interface
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.BlockDefinition"><code>SerializableDefinitionId BlockDefinition</code></a>_</td><td>Block definition ID</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.AccumulatedDamage"><code>float AccumulatedDamage</code></a>_</td><td>Current accumlated damage, pending application</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.BuildIntegrity"><code>float BuildIntegrity</code></a>_</td><td>Build integrity (of components)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.BuildLevelRatio"><code>float BuildLevelRatio</code></a>_</td><td>Ratio of BuildIntegrity and MaxIntegrity</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CurrentDamage"><code>float CurrentDamage</code></a>_</td><td>BuildIntegrity - Integrity</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DamageRatio"><code>float DamageRatio</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.FatBlock"><code>IMyCubeBlock FatBlock</code></a>_</td><td>Gets the fatblock if there is one</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.HasDeformation"><code>bool HasDeformation</code></a>_</td><td>If this block is deformed (bones deformed)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsDestroyed"><code>bool IsDestroyed</code></a>_</td><td>Gets if component stack is empty</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsFullIntegrity"><code>bool IsFullIntegrity</code></a>_</td><td>Integrity is at maximum</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsFullyDismounted"><code>bool IsFullyDismounted</code></a>_</td><td>Gets if component stack is empty</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.MaxDeformation"><code>float MaxDeformation</code></a>_</td><td>Maximum deformation of block</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.MaxIntegrity"><code>float MaxIntegrity</code></a>_</td><td>The maximum integrity of block</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Mass"><code>float Mass</code></a>_</td><td>Block mass</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.OwnerId"><code>long OwnerId</code></a>_</td><td>Fatblock owner, if present; otherwise grid owner</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.ShowParts"><code>bool ShowParts</code></a>_</td><td>Gets if sub parts are shown</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.StockpileAllocated"><code>bool StockpileAllocated</code></a>_</td><td>A component stockpile has been allocated</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.StockpileEmpty"><code>bool StockpileEmpty</code></a>_</td><td>The component stockpile is empty (no build components)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Position"><code>Vector3I Position</code></a>_</td><td>Grid relative position of block</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CubeGrid"><code>IMyCubeGrid CubeGrid</code></a>_</td><td>Gets the grid the slimblock is on</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.ColorMaskHSV"><code>Vector3 ColorMaskHSV</code></a>_</td><td>Gets the color of the block</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetMissingComponents"><code>void GetMissingComponents(Dictionary<string, int> addToDictionary)</code></a>_</td><td>Gets the list of missing components for this block</td></tr>
</table>
