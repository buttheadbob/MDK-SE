← [Index](Api-Index)

#### MyComponentBase Class

```csharp
public abstract class MyComponentBase: object
```

**Namespace:** [VRage.Game.Components](VRage.Game.Components)  
**Assembly:** VRage.Game.dll

**Inheritance:** [object](https://docs.microsoft.com/en-us/dotnet/api/system.object?view=netframework-4.6)

#### Example

#### Remarks

#### Properties

|Member|Description|
|---|---|
|[ContainerBase](VRage.Game.Components.MyComponentBase.ContainerBase)|This cannot be named Container to not conflict with the definition of Container in MyEntityComponentBase.|

#### Methods

|Member|Description|
|---|---|
|[SetContainer(MyComponentContainer)](VRage.Game.Components.MyComponentBase.SetContainer)|Sets the container of this component. Note that the component is not added to the container here! Therefore, use MyComponentContainer.Add(...) method and it will in turn call this method. Actually, you should seldom have the need to call this method yourself.|
|[GetAs()](VRage.Game.Components.MyComponentBase.GetAs)||
|[OnAddedToContainer()](VRage.Game.Components.MyComponentBase.OnAddedToContainer)|Gets called after the container of this component changes|
|[OnBeforeRemovedFromContainer()](VRage.Game.Components.MyComponentBase.OnBeforeRemovedFromContainer)|Gets called before the removal of this component from a container|
|[OnAddedToScene()](VRage.Game.Components.MyComponentBase.OnAddedToScene)|CH: TOOD: Be careful! This does not get called if the component is added to a container that is in the scene already!|
|[OnRemovedFromScene()](VRage.Game.Components.MyComponentBase.OnRemovedFromScene)|CH: TOOD: Be careful! This does not get called if the component is removed from a container that is still in the scene!|
|[Serialize(bool)](VRage.Game.Components.MyComponentBase.Serialize)||
|[Deserialize(MyObjectBuilder_ComponentBase)](VRage.Game.Components.MyComponentBase.Deserialize)||
|[Init(MyComponentDefinitionBase)](VRage.Game.Components.MyComponentBase.Init)||
|[IsSerialized()](VRage.Game.Components.MyComponentBase.IsSerialized)|Tells the component container serializer whether this component should be saved|

