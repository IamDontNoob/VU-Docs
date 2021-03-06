---
title: ProfileOptionDataEnumItem
---

## Summary

### Constructors

|  |
| --- |
| **[ProfileOptionDataEnumItem](#constructor-0)**() |
| **[ProfileOptionDataEnumItem](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "displayName" >}} | string |
| {{< prop "default" >}} | bool |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [ProfileOptionDataEnumItem](/vext/ref/fb/profileoptiondataenumitem) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "ProfileOptionDataEnumItem" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### ProfileOptionDataEnumItem {#constructor-0}

> **ProfileOptionDataEnumItem**()

Creates a new [ProfileOptionDataEnumItem](/vext/ref/fb/profileoptiondataenumitem) frostbite instance.

### ProfileOptionDataEnumItem {#constructor-1}

> **ProfileOptionDataEnumItem**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [ProfileOptionDataEnumItem](/vext/ref/fb/profileoptiondataenumitem) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "displayName" %}}

> **string**

### {{% prop-heading "default" %}}

> **bool**

## Methods

### Clone {#clone}

> **Clone**(): [ProfileOptionDataEnumItem](/vext/ref/fb/profileoptiondataenumitem)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[ProfileOptionDataEnumItem](/vext/ref/fb/profileoptiondataenumitem)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [ProfileOptionDataEnumItem](/vext/ref/fb/profileoptiondataenumitem) type.

