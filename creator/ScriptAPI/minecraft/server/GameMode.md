---
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: .GameMode Enumeration
description: Contents of the .GameMode enumeration.
---
# GameMode Enumeration
>[!IMPORTANT]
>These APIs are experimental as part of the Beta APIs experiment. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to Beta APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

> [!CAUTION]
> This enum is still in pre-release.  Its signature may change or it may be removed in future releases.

Represents a game mode for the current world experience.

## Constants
### **adventure**
`adventure = "adventure"`

World is in a more locked-down experience, where blocks may not be manipulated.
### **creative**
`creative = "creative"`

World is in a full creative mode. In creative mode, the player has all the resources available in the item selection tabs and the survival selection tab. They can also destroy blocks instantly including those which would normally be indestructible. Command and structure blocks can also be used in creative mode. Items also do not lose durability or disappear.
### **spectator**
`spectator = "spectator"`
### **survival**
`survival = "survival"`

World is in a survival mode, where players can take damage and entities may not be peaceful. Survival mode is where the player must collect resources, build structures while surviving in their generated world. Activities can, over time, chip away at player health and hunger bar.