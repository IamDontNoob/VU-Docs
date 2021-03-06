---
title: UIMinimapIconTextureAtlasAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[UIMinimapIconTextureAtlasAsset](#constructor-0)**() |
| **[UIMinimapIconTextureAtlasAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[UIMinimapIconTextureAtlasAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[UIMinimapIconTextureAtlasAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "icons" >}} | [UIMinimapIconTexture](/vext/ref/fb/uiminimapicontexture)[] |
| {{< prop "textureAtlas" >}} | [TextureAsset](/vext/ref/fb/textureasset) \| nil |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "UIMinimapIconTextureAtlasAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### UIMinimapIconTextureAtlasAsset {#constructor-0}

> **UIMinimapIconTextureAtlasAsset**()

Creates a new [UIMinimapIconTextureAtlasAsset](/vext/ref/fb/uiminimapicontextureatlasasset) frostbite instance.

### UIMinimapIconTextureAtlasAsset {#constructor-1}

> **UIMinimapIconTextureAtlasAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [UIMinimapIconTextureAtlasAsset](/vext/ref/fb/uiminimapicontextureatlasasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### UIMinimapIconTextureAtlasAsset {#constructor-2}

> **UIMinimapIconTextureAtlasAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [UIMinimapIconTextureAtlasAsset](/vext/ref/fb/uiminimapicontextureatlasasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [UIMinimapIconTextureAtlasAsset](/vext/ref/fb/uiminimapicontextureatlasasset). |

### UIMinimapIconTextureAtlasAsset {#constructor-3}

> **UIMinimapIconTextureAtlasAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [UIMinimapIconTextureAtlasAsset](/vext/ref/fb/uiminimapicontextureatlasasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [UIMinimapIconTextureAtlasAsset](/vext/ref/fb/uiminimapicontextureatlasasset). |

## Properties

### {{% prop-heading "icons" %}}

> **[UIMinimapIconTexture](/vext/ref/fb/uiminimapicontexture)**[]

### {{% prop-heading "textureAtlas" %}}

> **[TextureAsset](/vext/ref/fb/textureasset)** \| **nil**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [UIMinimapIconTextureAtlasAsset](/vext/ref/fb/uiminimapicontextureatlasasset) type.

