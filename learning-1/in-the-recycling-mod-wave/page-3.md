# Page 3

## 3 - Modifying

This Part Of the Wiki Show How To Modify The Recyling Mod/Datapack

_How Do I Modify Recycling Recipes?_

_**Simple! Just Edit The .json File.**_

### 3.1 - Editing Recipes

For Start There Are Two Types of Recipes:

* minecraft:crafting\_shaped
* minecraft:crafting\_shapeless

_What Is The Recipe Type: `minecraft:crafting_shaped`?_

_**The**** ****`minecraft:crafting_shaped`**** ****Say The Recipe Have A Pattern**_

**Example:**

```json
{
    "type": "minecraft:crafting_shaped",
    "pattern": [
        "/GR",
        "P/P",
        "RG/"
    ],
    "key": {
        "/": {
            "item": "minecraft:stick"
        },
        "G": {
            "item": "minecraft:glowstone_dust"
        },
        "R": {
            "item": "minecraft:redstone_lamp"
        },
        "P": {
            "item": "minecraft:redstone_block"
        }
    },
    "result": {
        "item": "minecraft:glowstone",
        "count": 4
    }
}

```

The Result Will be that:

![glowstone](https://github.com/DEMnetwork/Recycling/assets/105674889/25808446-4124-454e-a216-f01ec6419e37)

But If We Change Something It Won't Craft The Item:

![glowstone2](https://github.com/DEMnetwork/Recycling/assets/105674889/d4860839-90c3-4baf-b6c1-74d3d28faa0d)

![glowstone3](https://github.com/DEMnetwork/Recycling/assets/105674889/4ae813d8-cded-48e5-82f7-b21eb4204754)

_What Is The Recipe Type: `minecraft:crafting_shapeless`?_

_**`minecraft:crafting_shapeless`**** ****Says The The Recipe Doesn't Have A Pattern**_

For An Example I'll Use [chest.json](https://github.com/DEMnetwork/Recycling/blob/main/recycling%20mod/data/crafting/recipes/chest.json)

```json
{
    "type": "minecraft:crafting_shapeless",
    "ingredients": [
        {
            "item": "minecraft:chest"
        }
    ],
    "result": {
        "item": "minecraft:oak_planks",
        "count": 8
    }
}

```

This Will Result This Is Recipe:

![chest\_recipe](https://github.com/DEMnetwork/Recycling/assets/105674889/d0f871dd-79de-4582-a4d3-cdae65fc55f9)

> **Observation: The Ingredient Don't Need to Be Placed Exactly As the Image Above(The Result Will be The Same)**
