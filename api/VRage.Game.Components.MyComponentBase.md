← [Index](index.md)
# MyComponentBase Class
**Namespace:** VRage.Game.Components  
**Assembly:** VRage.Game.dll  
### Properties
|Member|Description|
|---|---|
|[`MyComponentContainer ContainerBase`](VRage.Game.Components.ContainerBase.md)||
### Methods
|Member|Description|
|---|---|
|[`void SetContainer(MyComponentContainer container)`](VRage.Game.Components.SetContainer.md)|Sets the container of this component. Note that the component is not added to the container here! Therefore, use MyComponentContainer.Add(...) method and it will in turn call this method. Actually, you should seldom have the need to call this method yourself.|
|[`T GetAs<T>()`](VRage.Game.Components.GetAs.md)||
|[`void OnAddedToContainer()`](VRage.Game.Components.OnAddedToContainer.md)||
|[`void OnBeforeRemovedFromContainer()`](VRage.Game.Components.OnBeforeRemovedFromContainer.md)||
|[`void OnAddedToScene()`](VRage.Game.Components.OnAddedToScene.md)||
|[`void OnRemovedFromScene()`](VRage.Game.Components.OnRemovedFromScene.md)||
|[`MyObjectBuilder_ComponentBase Serialize(bool copy)`](VRage.Game.Components.Serialize.md)||
|[`void Deserialize(MyObjectBuilder_ComponentBase builder)`](VRage.Game.Components.Deserialize.md)||
|[`void Init(MyComponentDefinitionBase definition)`](VRage.Game.Components.Init.md)||
|[`bool IsSerialized()`](VRage.Game.Components.IsSerialized.md)||
