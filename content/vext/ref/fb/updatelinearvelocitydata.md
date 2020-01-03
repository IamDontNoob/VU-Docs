---
title: UpdateLinearVelocityData
---
### Base Classes

[ProcessorData](ProcessorData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                         | Description                                                                                                                             |
| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| UpdateLinearVelocityData()                                                          | Create a new instance of this container type.                                                                                           |
| UpdateLinearVelocityData(UpdateLinearVelocityData other)                            | Create a reference copy of an instance of the same type.                                                                                |
| UpdateLinearVelocityData([ProcessorData](ProcessorData) other)                      | Upcast an instance of type [ProcessorData](ProcessorData) to [UpdateLinearVelocityData](UpdateLinearVelocityData).                      |
| UpdateLinearVelocityData([EmitterComponentData](EmitterComponentData) other)        | Upcast an instance of type [EmitterComponentData](EmitterComponentData) to [UpdateLinearVelocityData](UpdateLinearVelocityData).        |
| UpdateLinearVelocityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UpdateLinearVelocityData](UpdateLinearVelocityData). |

## Methods

| Type                                                 | Name            | Parameters                                     |
| ---------------------------------------------------- | --------------- | ---------------------------------------------- |
| [UpdateLinearVelocityData](UpdateLinearVelocityData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UpdateLinearVelocityData](UpdateLinearVelocityData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |