---
type: worker
worker: mechanic
layout: worker
---
{% capture content %}
The Mechanic is part of the supply production of your colony. The Mechanic will craft redstone items, rails, minecarts, clocks, compasses, sea lanterns, torches, lanterns, jack-o-lanterns, storage blocks (like blocks of iron, coal, quartz, etc), dried kelp blocks, blue ice, packed ice, enchantment tables, ender chests, tripwire hooks, sticky pistons, [gates](../../source/items/gates), [multi-pistons](../../source/items/multipiston), glowstone blocks, anything made with blaze rods, and many other items that no other crafter can make. They will only make these items when they have been taught the recipes, receive a request for an item, and have the needed materials.

**Note:** The Mechanic can only learn a set number of recipes based on their hut level. So:

| Hut Level | Recipes |
| --------- | ------- |
| 1         | 10      |
| 2         | 20      |
| 3         | 40      |
| 4         | 80      |
| 5         | 160     |

All crafters have a chance to decrease the amount of materials needed for a taught recipe. (If this happens, the new recipe is kept until deleted or improved again.) The higher a Mechanic's Knowledge level, the greater their chance to decrease the amount of materials needed.

Mechanics' crafting speed increases as their Agility skill increases.
{% endcapture %}
{% capture infobox %}
{% include infobox/worker.html %}
{% endcapture %}
{% include page-infobox-wrapper.html content=content infobox=infobox %}