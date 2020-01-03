---
title: UpdateAlphaLevelMaxData
---
### Base Classes

[ProcessorData](ProcessorData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                        | Description                                                                                                                           |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| UpdateAlphaLevelMaxData()                                                          | Create a new instance of this container type.                                                                                         |
| UpdateAlphaLevelMaxData(UpdateAlphaLevelMaxData other)                             | Create a reference copy of an instance of the same type.                                                                              |
| UpdateAlphaLevelMaxData([ProcessorData](ProcessorData) other)                      | Upcast an instance of type [ProcessorData](ProcessorData) to [UpdateAlphaLevelMaxData](UpdateAlphaLevelMaxData).                      |
| UpdateAlphaLevelMaxData([EmitterComponentData](EmitterComponentData) other)        | Upcast an instance of type [EmitterComponentData](EmitterComponentData) to [UpdateAlphaLevelMaxData](UpdateAlphaLevelMaxData).        |
| UpdateAlphaLevelMaxData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UpdateAlphaLevelMaxData](UpdateAlphaLevelMaxData). |

## Properties

| Name     | Type   | Description |
| -------- | ------ | ----------- |
| maxLevel | number |             |

## Methods

| Type                                               | Name            | Parameters                                     |
| -------------------------------------------------- | --------------- | ---------------------------------------------- |
| [UpdateAlphaLevelMaxData](UpdateAlphaLevelMaxData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UpdateAlphaLevelMaxData](UpdateAlphaLevelMaxData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |