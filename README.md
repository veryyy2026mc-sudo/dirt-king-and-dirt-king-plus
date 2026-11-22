# Dirt King \& Dirt King Plus

* **Dirt King** turns dirt into valuable resources through crafting and smelting.
* **Dirt King Plus** expands the idea with additional recipes, including recipes involving coarse dirt, and villager trades.

The two datapacks can be used independently. For the expanded experience, install both.

## Projects

|Datapack|Modrinth page|What it adds|
|-|-|-|
|Dirt King|https://modrinth.com/datapack/dirt-king|Dirt-based crafting and smelting recipes|
|Dirt King Plus|https://modrinth.com/datapack/dirt-king-plus|Additional dirt/coarse-dirt recipes and villager trades|

## Compatibility

* **Minecraft:** Java Edition 26.3,26.2,26.1.x
* **Type:** Datapack and mod
* **Environment:** Singleplayer and server-side
* **Pack format:** 121

Check the Modrinth pages for the latest supported versions.

## Installation

### Singleplayer

1. Download the datapack ZIP file(s) from the Modrinth pages above.
2. Open your Minecraft world's folder.
3. Open the `datapacks` folder.
4. Put the downloaded ZIP file(s) directly into that folder. Do not unzip them.
5. Load or reload the world.
6. Run `/datapack list enabled` to check that the datapacks are enabled.

### Multiplayer server

1. Stop the server.
2. Open the folder for the world used by the server (usually `world`).
3. Open that world's `datapacks` folder.
4. Put the downloaded ZIP file(s) directly into the folder.
5. Start the server again.
6. Run `/datapack list enabled` in the server console or in-game.

If you add a datapack while the world is running, you can try `/reload`, but making a backup and restarting the server is recommended.

## Recipe customization

These datapacks do not include a separate in-game configuration menu or a standalone config file. Their recipes are defined by JSON files inside each ZIP archive.

To customize a recipe:

1. Make a backup of the original ZIP.
2. Open the ZIP with an archive tool.
3. Find the recipe JSON file under the relevant `data/<namespace>/recipe/` directory.
4. Edit the recipe's `ingredients` and/or `result` fields, keeping the JSON syntax valid.
5. Save the file and make sure the archive still has `pack.mcmeta` and the `data` folder at its root.
6. Put the edited ZIP back in the world's `datapacks` folder and reload or restart the world.

### Recipe locations

* **Dirt King:** `data/minecraft/recipe/`
* **Dirt King Plus:** `data/dirt\_king\_plus/recipe/`

For example, a Dirt King Plus recipe that produces one cake is stored in a file under `data/dirt\_king\_plus/recipe/`. The `result` field controls the output item and amount; `ingredients` controls the required ingredients.

If you change a recipe, keep the recipe's `type` and other required fields intact. Invalid JSON or an invalid item ID can prevent that recipe from loading. Check the game log if a changed recipe does not appear.

## Notes

* Dirt King Plus can run by itself, but its Modrinth description recommends using it alongside Dirt King for the fuller experience.
* The datapack version is the recommended/stable format according to the project descriptions.
* Back up your world before installing, updating, or editing datapacks.
* These projects are licensed under MIT, as listed on their Modrinth pages.

## Additional Extensions

### Dirt Land

[**Dirt Land on Modrinth**](https://modrinth.com/mod/dirt-land)

An optional expansion mod that adds a new dirt-themed dimension to Minecraft.

**Features:**
- 1 new biome
- 1 new dimension
- 1 new block
- 1 new item
- Structures in the new dimension, including villages, strongholds, igloos, and fossils

**Compatibility:**
- Minecraft: Java Edition 26.3
- Mod loader: NeoForge
- Supported environment: Singleplayer and server-side

Dirt Land is a separate mod, not a required dependency for Dirt King or Dirt King Plus. It can be added as an optional extension. The project page states that its mod version supports NeoForge; other mod loaders are not supported.

The Dirt Land project also notes that combining it with Dirt King can make progression much easier.

## Links

* [Dirt King on Modrinth](https://modrinth.com/datapack/dirt-king)
* [Dirt King Plus on Modrinth](https://modrinth.com/datapack/dirt-king-plus)

