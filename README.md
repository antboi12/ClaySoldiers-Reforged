# Clay Soldiers Reforged

An Architectury-based Minecraft 1.21 mod that brings clay soldiers, teams,
upgrades, mounts, and disruptors to Fabric and NeoForge.

This project is based on
[matthewperiut/Clay-Soldiers](https://github.com/matthewperiut/Clay-Soldiers)
and retains its MIT license and original attribution.

## Requirements

- Java 21
- The included Gradle wrapper; no system Gradle installation is required

## Build

On Windows:

```powershell
.\gradlew.bat build
```

On Linux or macOS:

```bash
./gradlew build
```

The remapped loader jars are written to `fabric/build/libs` and
`neoforge/build/libs`.

## Project layout

- `common/` — shared gameplay code, models, textures, recipes, loot tables,
  tags, and mixins
- `fabric/` — Fabric entrypoints and loader metadata
- `neoforge/` — NeoForge entrypoint and loader metadata

## Implemented content

- Sixteen clay-soldier teams
- Clay-soldier combat and item-seeking AI
- Horse mounts
- Stick, flint, glowstone, leather, wool, and gold upgrade foundations
- Clay, terracotta, and obsidian disruptors
