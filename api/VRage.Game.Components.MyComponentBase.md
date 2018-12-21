← [Index](index)
# MyComponentBase Class
**Namespace:** [`VRage.Game.Components`](VRage.Game.Components)  
**Assembly:** VRage.Game.dll  
### Properties
<table style="width: 100%">
<tr><td>[`MyComponentContainer ContainerBase`](VRage.Game.Components.ContainerBase)</td><td>This cannot be named Container to not conflict with the definition of Container in MyEntityComponentBase.</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`void SetContainer(MyComponentContainer container)`](VRage.Game.Components.SetContainer)</td><td>Sets the container of this component. Note that the component is not added to the container here! Therefore, use MyComponentContainer.Add(...) method and it will in turn call this method. Actually, you should seldom have the need to call this method yourself.</td></tr>
<tr><td>[`T GetAs<T>()`](VRage.Game.Components.GetAs)</td><td></td></tr>
<tr><td>[`void OnAddedToContainer()`](VRage.Game.Components.OnAddedToContainer)</td><td>Gets called after the container of this component changes</td></tr>
<tr><td>[`void OnBeforeRemovedFromContainer()`](VRage.Game.Components.OnBeforeRemovedFromContainer)</td><td>Gets called before the removal of this component from a container</td></tr>
<tr><td>[`void OnAddedToScene()`](VRage.Game.Components.OnAddedToScene)</td><td>CH: TOOD: Be careful! This does not get called if the component is added to a container that is in the scene already!</td></tr>
<tr><td>[`void OnRemovedFromScene()`](VRage.Game.Components.OnRemovedFromScene)</td><td>CH: TOOD: Be careful! This does not get called if the component is removed from a container that is still in the scene!</td></tr>
<tr><td>[`MyObjectBuilder_ComponentBase Serialize(bool copy)`](VRage.Game.Components.Serialize)</td><td></td></tr>
<tr><td>[`void Deserialize(MyObjectBuilder_ComponentBase builder)`](VRage.Game.Components.Deserialize)</td><td></td></tr>
<tr><td>[`void Init(MyComponentDefinitionBase definition)`](VRage.Game.Components.Init)</td><td></td></tr>
<tr><td>[`bool IsSerialized()`](VRage.Game.Components.IsSerialized)</td><td>Tells the component container serializer whether this component should be saved</td></tr>
</table>
