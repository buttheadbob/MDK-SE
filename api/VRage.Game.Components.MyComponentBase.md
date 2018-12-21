← [Index](index)
# MyComponentBase Class
**Namespace:** [`VRage.Game.Components`](VRage.Game.Components)  
**Assembly:** VRage.Game.dll  
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.Components.ContainerBase"><code>MyComponentContainer ContainerBase</code></a>_</td><td>This cannot be named Container to not conflict with the definition of Container in MyEntityComponentBase.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.Components.SetContainer"><code>void SetContainer(MyComponentContainer container)</code></a>_</td><td>Sets the container of this component. Note that the component is not added to the container here! Therefore, use MyComponentContainer.Add(...) method and it will in turn call this method. Actually, you should seldom have the need to call this method yourself.</td></tr>
<tr><td>_<a href="VRage.Game.Components.GetAs"><code>T GetAs<T>()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.Components.OnAddedToContainer"><code>void OnAddedToContainer()</code></a>_</td><td>Gets called after the container of this component changes</td></tr>
<tr><td>_<a href="VRage.Game.Components.OnBeforeRemovedFromContainer"><code>void OnBeforeRemovedFromContainer()</code></a>_</td><td>Gets called before the removal of this component from a container</td></tr>
<tr><td>_<a href="VRage.Game.Components.OnAddedToScene"><code>void OnAddedToScene()</code></a>_</td><td>CH: TOOD: Be careful! This does not get called if the component is added to a container that is in the scene already!</td></tr>
<tr><td>_<a href="VRage.Game.Components.OnRemovedFromScene"><code>void OnRemovedFromScene()</code></a>_</td><td>CH: TOOD: Be careful! This does not get called if the component is removed from a container that is still in the scene!</td></tr>
<tr><td>_<a href="VRage.Game.Components.Serialize"><code>MyObjectBuilder_ComponentBase Serialize(bool copy)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.Components.Deserialize"><code>void Deserialize(MyObjectBuilder_ComponentBase builder)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.Components.Init"><code>void Init(MyComponentDefinitionBase definition)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.Components.IsSerialized"><code>bool IsSerialized()</code></a>_</td><td>Tells the component container serializer whether this component should be saved</td></tr>
</table>
