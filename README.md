# ⚙️ Industrial Craft 3
IC3 is a remake of original ic2 mod for Forge 1.21.1.

## Features:
### ♨️ Machines:
- Iron Furnace (`ic3:iron_furnace`) — 25% faster smelting, 20% less fuel consumption (1 coal smelts 12 items)

### ⛏️ Ores:
- Tin Ore (`ic3:tin_ore`)
- Deepslate Tin Ore (`ic3:deepslate_tin_ore`)
- Uranium Ore (`ic3:uranium_ore`)
- Deepslate Uranium Ore (`ic3:deepslate_uranium_ore`)

### 🔩 Materials:
- Raw Tin (`ic3:raw_tin`)
- Raw Uranium (`ic3:raw_uranium`)
- Tin Ingot (`ic3:tin_ingot`)
- RE Battery (`ic3:re_battery`) — rechargeable, stores 10k EU

### ⛽ Fuel Values (EU per item):
| Item | EU |
|---|---|
| Coal/Charcoal | 4000 |
| Wooden planks/logs | 750 |
| Cactus | 120 |
| Sugar Cane | 120 |
| Any vanilla furnace fuel | vanilla_value × 2.5

Cactus and Sugar Cane also work as fuel in all furnaces (120 ticks each).

### 🔨 Plates & Casings:
- Iron Plate (`ic3:iron_plate`)
- Copper Plate (`ic3:copper_plate`)
- Tin Plate (`ic3:tin_plate`)
- Gold Plate (`ic3:gold_plate`)
- Copper Casing (`ic3:copper_casing`)
- Tin Casing (`ic3:tin_casing`)
- Gold Casing (`ic3:gold_casing`)
- Iron Casing (`ic3:iron_casing`)

### 🔌 Cables:
- Tin Cable (`ic3:tin_cable`) — LV, 32 EU/t, loss 0.025 EU/block
- Copper Cable (`ic3:copper_cable`) — MV, 128 EU/t, loss 0.20 EU/block
- Iron Cable (`ic3:iron_cable`) — EV, 2048 EU/t, loss 0.025 EU/block
- Gold Cable (`ic3:gold_cable`) — HV, 512 EU/t, loss 0.40 EU/block

### ⚡ Energy:
- Generator (`ic3:generator`) — burns fuel to produce 10 EU/t, 4000 EU buffer
- Creative EU Generator (`ic3:creative_eu_generator`)
- Energy Collector (`ic3:creative_eu_collector`)

### 🌳 Rubber Tree:
- Rubber Wood (`ic3:rubber_wood`) — generates resin holes on one side
- Rubber Leaves (`ic3:rubber_leaves`) — drop saplings when broken
- Rubber Sapling (`ic3:rubber_sapling`) — grows into rubber trees
- Sticky Resin (`ic3:sticky_resin`) — collected from resin holes
- Tree Tapper (`ic3:tree_tapper`) — used to collect resin, has durability

### 🛠️ Tools:
- Forge Hammer (`ic3:forge_hammer`) — used in plate crafting
- Cutter (`ic3:cutter`) — used in cable crafting
- Tree Tapper (`ic3:tree_tapper`) — collects sticky resin from rubber wood

### 🌍 World Generation:
- Tin Ore — generates between Y=0 and Y=72
- Deepslate Tin Ore — generates in deepslate
- Uranium Ore — generates deep underground
- Rubber Trees — spawn rarely in overworld; more common in swamps, mangrove swamps, and jungles

### 🔧 Recipes:
- Iron Furnace: 4 Iron Plates + Furnace (ring pattern: top/bot/mid sides)
- Generator: 3 Iron Plates + Iron Casing + Furnace
- RE Battery: 2 Tin Ingots + Redstone + 2 Copper Cables
- Cables: Cutter + 3 Ingots → 6 cables (shapeless)
- Forge Hammer: 2 Iron Ingots + Stick
- Cutter: 3 Iron Ingots + Stick

## :exclamation: If game crashes :exclamation:
- Try different Forge versions 52.0.16-52.1.0 when using OptiFine. I’ve been using Forge 52.0.23 and haven’t experienced any crashes so far.
- Forge 52.1.0+ works without OptiFine.

## License
All rights reserved. See [LICENSE.md](LICENSE.md) for details.
