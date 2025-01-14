---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.ItemUseAfterEvent Class
description: Contents of the @minecraft/server.ItemUseAfterEvent class.
---
# ItemUseAfterEvent Class

## Classes that extend ItemUseAfterEvent
- [*ItemUseBeforeEvent*](ItemUseBeforeEvent.md)

Contains information related to an item being used. This event fires when an item is successfully used by a player.

## Properties

### **itemStack**
`itemStack: ItemStack;`

The impacted item stack that is being used.

Type: [*ItemStack*](ItemStack.md)

### **source**
`read-only source: Player;`

Returns the source entity that triggered this item event.

Type: [*Player*](Player.md)
