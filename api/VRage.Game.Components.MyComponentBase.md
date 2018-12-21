← [Index](index)
# MyComponentBase Class
**Namespace:** [`VRage.Game.Components`](VRage.Game.Components)  
**Assembly:** VRage.Game.dll  
### Properties
|Member|Description|
|---|---|
|[`MyComponentContainer ContainerBase`](VRage.Game.Components.ContainerBase)|This cannot be named Container to not conflict with the definition of Container in MyEntityComponentBase.|
### Methods
|Member|Description|
|---|---|
|[`void SetContainer(MyComponentContainer container)`](VRage.Game.Components.SetContainer)|Sets the container of this component. Note that the component is not added to the container here! Therefore, use MyComponentContainer.Add(...) method and it will in turn call this method. Actually, you should seldom have the need to call this method yourself.|
|[`T GetAs<T>()`](VRage.Game.Components.GetAs)||
|[`void OnAddedToContainer()`](VRage.Game.Components.OnAddedToContainer)|Gets called after the container of this component changes|
|[`void OnBeforeRemovedFromContainer()`](VRage.Game.Components.OnBeforeRemovedFromContainer)|Gets called before the removal of this component from a container|
|[`void OnAddedToScene()`](VRage.Game.Components.OnAddedToScene)|CH: TOOD: Be careful! This does not get called if the component is added to a container that is in the scene already!|
|[`void OnRemovedFromScene()`](VRage.Game.Components.OnRemovedFromScene)|CH: TOOD: Be careful! This does not get called if the component is removed from a container that is still in the scene!|
|[`MyObjectBuilder_ComponentBase Serialize(bool copy)`](VRage.Game.Components.Serialize)||
|[`void Deserialize(MyObjectBuilder_ComponentBase builder)`](VRage.Game.Components.Deserialize)||
|[`void Init(MyComponentDefinitionBase definition)`](VRage.Game.Components.Init)||
|[`bool IsSerialized()`](VRage.Game.Components.IsSerialized)|Tells the component container serializer whether this component should be saved|
