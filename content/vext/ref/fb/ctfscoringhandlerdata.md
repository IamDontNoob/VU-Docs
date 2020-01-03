---
title: CTFScoringHandlerData
---
### Base Classes

[ScoringHandlerData](ScoringHandlerData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| CTFScoringHandlerData()                                                          | Create a new instance of this container type.                                                                                     |
| CTFScoringHandlerData(CTFScoringHandlerData other)                               | Create a reference copy of an instance of the same type.                                                                          |
| CTFScoringHandlerData([ScoringHandlerData](ScoringHandlerData) other)            | Upcast an instance of type [ScoringHandlerData](ScoringHandlerData) to [CTFScoringHandlerData](CTFScoringHandlerData).            |
| CTFScoringHandlerData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [CTFScoringHandlerData](CTFScoringHandlerData). |

## Properties

| Name                    | Type   | Description |
| ----------------------- | ------ | ----------- |
| maxTeams                | number |             |
| pickUpAssistRadius      | number |             |
| captureAssistRadius     | number |             |
| enemyThreatRadius       | number |             |
| enemySuppressionTimeout | number |             |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [CTFScoringHandlerData](CTFScoringHandlerData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [CTFScoringHandlerData](CTFScoringHandlerData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |