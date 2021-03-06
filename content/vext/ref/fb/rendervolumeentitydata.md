---
title: RenderVolumeEntityData
---

Inherits from [SpatialEntityData](/vext/ref/fb/spatialentitydata)

## Summary

### Constructors

|  |
| --- |
| **[RenderVolumeEntityData](#constructor-0)**() |
| **[RenderVolumeEntityData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[RenderVolumeEntityData](#constructor-2)**(other: [SpatialEntityData](/vext/ref/fb/spatialentitydata)) |
| **[RenderVolumeEntityData](#constructor-3)**(other: [EntityData](/vext/ref/fb/entitydata)) |
| **[RenderVolumeEntityData](#constructor-4)**(other: [GameObjectData](/vext/ref/fb/gameobjectdata)) |
| **[RenderVolumeEntityData](#constructor-5)**(other: [GameDataContainer](/vext/ref/fb/gamedatacontainer)) |
| **[RenderVolumeEntityData](#constructor-6)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "userMasks" >}} | [Vec4](/vext/ref/shared/type/vec4) |
| {{< prop "shader" >}} | [SurfaceShaderInstanceDataStruct](/vext/ref/fb/surfaceshaderinstancedatastruct) |
| {{< prop "transformType" >}} | [RenderVolumeTransformType](/vext/ref/fb/rendervolumetransformtype) |
| {{< prop "enabled" >}} | bool |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "RenderVolumeEntityData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### RenderVolumeEntityData {#constructor-0}

> **RenderVolumeEntityData**()

Creates a new [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata) frostbite instance.

### RenderVolumeEntityData {#constructor-1}

> **RenderVolumeEntityData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### RenderVolumeEntityData {#constructor-2}

> **RenderVolumeEntityData**(other: [SpatialEntityData](/vext/ref/fb/spatialentitydata))

Casts an instance of type [SpatialEntityData](/vext/ref/fb/spatialentitydata) to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [SpatialEntityData](/vext/ref/fb/spatialentitydata) | The instance to cast to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). |

### RenderVolumeEntityData {#constructor-3}

> **RenderVolumeEntityData**(other: [EntityData](/vext/ref/fb/entitydata))

Casts an instance of type [EntityData](/vext/ref/fb/entitydata) to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [EntityData](/vext/ref/fb/entitydata) | The instance to cast to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). |

### RenderVolumeEntityData {#constructor-4}

> **RenderVolumeEntityData**(other: [GameObjectData](/vext/ref/fb/gameobjectdata))

Casts an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata) to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [GameObjectData](/vext/ref/fb/gameobjectdata) | The instance to cast to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). |

### RenderVolumeEntityData {#constructor-5}

> **RenderVolumeEntityData**(other: [GameDataContainer](/vext/ref/fb/gamedatacontainer))

Casts an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer) to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [GameDataContainer](/vext/ref/fb/gamedatacontainer) | The instance to cast to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). |

### RenderVolumeEntityData {#constructor-6}

> **RenderVolumeEntityData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata). |

## Properties

### {{% prop-heading "userMasks" %}}

> **[Vec4](/vext/ref/shared/type/vec4)**

### {{% prop-heading "shader" %}}

> **[SurfaceShaderInstanceDataStruct](/vext/ref/fb/surfaceshaderinstancedatastruct)**

### {{% prop-heading "transformType" %}}

> **[RenderVolumeTransformType](/vext/ref/fb/rendervolumetransformtype)**

### {{% prop-heading "enabled" %}}

> **bool**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [RenderVolumeEntityData](/vext/ref/fb/rendervolumeentitydata) type.

