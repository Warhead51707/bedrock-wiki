---
title: Block Categories
tags:
    - beta
mention:
	- warhead51707
---

<Label color="red">Beta</Label>

-   Block Categories were added in the Minecraft: Bedrock Edition, Beta 1.17.20.23.
-   Block Categories are used for adding Data Driven Blocks in the Creative Inventory, similar to adding [Item Categories](/items/item-categories) for a Data Driven Item.

## Block Categories Definition

Block Categories are defined via the `minecraft:creative_category` component, your custom block will not show up in the Creative Inventory if you don't have this component, here's an example:

```json
{
	"format_version": "1.17.20",
	"minecraft:block": {
		"description": {
			"identifier": "foo:bar_block"
		},
		"components": {
			"minecraft:creative_category": {
				"category": "nature",
				"group": "itemGroup.name.wood"
			}
		}
	}
}
```

As you can see, the `minecraft:creative_category` component accepts 2 optional children, the `category` child & the `group` child. A list of groups & categories can be found below.

## List of Creative Tabs

> _For use with `creative_category` parameter `category`_

| Category  
| --------------------------------
| Commands |  
| Construction |  
| Equipment |  
| Items |  
| Nature |  
| None |

## List of Categories

> _For use with the `creative_category` parameter 'group'_

| Category  
| --------------------------------
| itemGroup.name.anvil |  
| itemGroup.name.arrow |  
| itemGroup.name.axe |  
| itemGroup.name.banner |  
| itemGroup.name.banner_pattern |  
| itemGroup.name.bed |  
| itemGroup.name.boat |  
| itemGroup.name.boots |  
| itemGroup.name.buttons |  
| itemGroup.name.chalkboard |  
| itemGroup.name.chest |  
| itemGroup.name.chestplate |  
| itemGroup.name.concrete |  
| itemGroup.name.concretePowder |  
| itemGroup.name.cookedFood |  
| itemGroup.name.coral |  
| itemGroup.name.coral_decorations |  
| itemGroup.name.crop |  
| itemGroup.name.door |  
| itemGroup.name.dye |  
| itemGroup.name.enchantedBook |  
| itemGroup.name.fence |  
| itemGroup.name.fenceGate |  
| itemGroup.name.firework |  
| itemGroup.name.fireworkStars |  
| itemGroup.name.flower |  
| itemGroup.name.glass |  
| itemGroup.name.glassPane |  
| itemGroup.name.glazedTerracotta |  
| itemGroup.name.grass |  
| itemGroup.name.helmet |  
| itemGroup.name.hoe |  
| itemGroup.name.horseArmor |  
| itemGroup.name.leaves |  
| itemGroup.name.leggings |  
| itemGroup.name.lingeringPotion |  
| itemGroup.name.log |  
| itemGroup.name.minecart |  
| itemGroup.name.miscFood |  
| itemGroup.name.mobEgg |  
| itemGroup.name.monsterStoneEgg |  
| itemGroup.name.mushroom |  
| itemGroup.name.netherWartBlock |  
| itemGroup.name.ore |  
| itemGroup.name.permission |  
| itemGroup.name.pickaxe |  
| itemGroup.name.planks |  
| itemGroup.name.potion |  
| itemGroup.name.pressurePlate |  
| itemGroup.name.rail |  
| itemGroup.name.rawFood |  
| itemGroup.name.record |  
| itemGroup.name.sandstone |  
| itemGroup.name.sapling |  
| itemGroup.name.seed |  
| itemGroup.name.shovel |  
| itemGroup.name.shulkerBox |  
| itemGroup.name.sign |  
| itemGroup.name.skull |  
| itemGroup.name.slab |  
| itemGroup.name.splashPotion |  
| itemGroup.name.stainedClay |  
| itemGroup.name.stairs |  
| itemGroup.name.stone |  
| itemGroup.name.stoneBrick |  
| itemGroup.name.sword |  
| itemGroup.name.trapdoor |  
| itemGroup.name.walls |  
| itemGroup.name.wood |  
| itemGroup.name.wool |  
| itemGroup.name.woolCarpet |
