---
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.EntityIsIgnitedComponent Class
description: Contents of the @minecraft/server.EntityIsIgnitedComponent class.
---
# EntityIsIgnitedComponent Class
>[!IMPORTANT]
>These APIs are experimental as part of the Beta APIs experiment. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to Beta APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Extends
- [*IEntityComponent*](IEntityComponent.md)

When added, this component signifies that this entity this currently on fire.

## Properties

### **typeId**
`read-only typeId: string;`

Identifier of this component. Should always be minecraft:is_ignited.

Type: *string*

## Constants

### **componentId**
`static read-only componentId = "minecraft:is_ignited";`

Identifier of this component. Should always be minecraft:is_ignited.

Type: *string*