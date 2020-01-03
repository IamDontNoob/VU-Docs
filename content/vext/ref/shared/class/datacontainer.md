---
title: DataContainer
---
## Description

A base Frostbite DataContainer. The lowest class in the Frostbite container instance hierarchy. All instances present in game data partitions (ebx) are derived from this type.

## Constructors

| Constructor                                                                                                      | Description                                              |
| ---------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [DataContainer](/vext/ref/shared/class/datacontainer)([DataContainer](/vext/ref/shared/class/datacontainer) **ref**) | Create a reference copy of an instance of the same type. |

## Static Members

| Type                                                    | Name                   | Description |
| ------------------------------------------------------- | ---------------------- | ----------- |
| [TypeInformation](/vext/ref/shared/class/typeinformation) | DataContainer.typeInfo |             |

## Properties

| Name         | Type                                                    | Writable | Description                                                                                    |
| ------------ | ------------------------------------------------------- | -------- | ---------------------------------------------------------------------------------------------- |
| typeInfo     | [TypeInformation](/vext/ref/shared/class/typeinformation) | N        | Type information for this instance.                                                            |
| isLazyLoaded | bool                                                    | N        | Whether this container is lazy-loaded.                                                         |
| isReadOnly   | bool                                                    | N        | Whether this container is read-only. Changes to read-only container properties have no effect. |
| instanceGuid | [Guid](/vext/ref/shared/class/guid)                       | N        | The GUID of the instance. If the instance has no assigned GUID this gives `nil`.               |

## Methods

| Type                                                | Name                                    | Parameters                                                          |
| --------------------------------------------------- | --------------------------------------- | ------------------------------------------------------------------- |
| bool                                                | [Eq](#eq)                               | [DataContainer](/vext/ref/shared/class/datacontainer) **other**       |
| [DataContainer](/vext/ref/shared/class/datacontainer) | [AsDC](#asdc)                           |                                                                     |
| [DataContainer](/vext/ref/shared/class/datacontainer) | [Clone](#clone)                         | [Guid](/vext/ref/shared/class/guid) **guid** = nil                    |
| void                                                | [ReplaceReferences](#replacereferences) | [DataContainer](/vext/ref/shared/class/datacontainer) **replacement** |
| void                                                | [MakeWritable](#makewritable)           |                                                                     |

### Eq

> bool **Eq**([DataContainer](/vext/ref/shared/class/datacontainer) **other**)

#### Parameters

| Name  | Type                                                | Description |
| ----- | --------------------------------------------------- | ----------- |
| other | [DataContainer](/vext/ref/shared/class/datacontainer) |             |

### AsDC

> [DataContainer](/vext/ref/shared/class/datacontainer) **AsDC**()

Returns a reference to the same instance as a [DataContainer](/vext/ref/shared/class/datacontainer) type. This is usually helpful when you have to downcast a more specific type to make it match the type definition of another field or a generic array.

### Clone

> [DataContainer](/vext/ref/shared/class/datacontainer) **Clone**([Guid](/vext/ref/shared/class/guid) **guid** = nil)

Creates a shallow-copy clone of the instance, which is essentially the equivalent of creating a new instance of the same type and assigning the values of the original instance to all of its members. A [Guid](/vext/ref/shared/class/guid) can optionally be passed in, which causes VeniceEXT to register the instance to the engine with that specific GUID. That is especially useful for modifying data-bound containers.

#### Parameters

| Name | Type                              | Description                                 |
| ---- | --------------------------------- | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid) | An optional GUID to assign to the instance. |

### ReplaceReferences

> void **ReplaceReferences**([DataContainer](/vext/ref/shared/class/datacontainer) **replacement**)

Replaces all registered references of the current instance with the provided instance. Passing `nil` is also allowed here.

#### Parameters

| Name        | Type                                                | Description                                                                        |
| ----------- | --------------------------------------------------- | ---------------------------------------------------------------------------------- |
| replacement | [DataContainer](/vext/ref/shared/class/datacontainer) | The instance to replace the references to the current instance with. Can be `nil`. |

### MakeWritable

> void **MakeWritable**()