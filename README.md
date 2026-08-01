# AntiDupe

An anti-duplication addon for Minecraft Bedrock that detects and blocks item-dupe exploits through hoppers, droppers, dispensers, and crafters, with a configurable strike system, player/area whitelist, and a teleportable log.

## 📥 Download

Grab the latest `.mcaddon` from the [Releases](../../releases) page.

## 🔍 Detection

- Monitors dupe-prone blocks by default: **Hopper, Dropper, Dispenser, Crafter**, and **Hopper Minecart**
- Add your own custom blocks/items to watch through the **Monitor Block/Item** menu
- Detects neighboring containers (chest/trapped chest/barrel) attached to a dupe machine, with an adjustable redstone-detection radius
- Heuristic check for duplicate bundles in a player's inventory

## ⚠️ Strike System & Punishment

- Configurable strike threshold (number of violations and time window)
- **Normal** mode (only destroys the machine block) or **Strict** mode (destroys the block + clears the surrounding area)
- Choose the punishment: **Freeze** (spectator, manual unfreeze), **Kick**, or **None**

## ✅ Whitelist

- Per-player whitelist (trusted players are exempt from detection)
- Per-area whitelist (set 2 positions to define a safe zone)

## 📜 Log & Monitoring

- Full dupe history log with time, location, offender, and container contents — click an entry to teleport straight to the scene
- Frozen Players menu to view and unfreeze frozen players
- Periodic rescan to catch blocks placed via commands (`/setblock`, `/fill`, etc.)

## 🌐 Language

Supports English & Indonesian, toggleable from the menu.

## 🎮 How to Use

1. Enable the **AntiDupe [RP]** resource pack and **AntiDupe [BP]** behavior pack in your world
2. Enable **Beta APIs** (Script API) in the experimental settings when creating/editing the world
3. Grab the AntiDupe menu item from your inventory (creative) to open the config panel

## 📋 Requirements

- Minecraft Bedrock **1.21.100+**
- **Beta APIs** experimental toggle must be enabled

## 📄 License

All rights reserved. See [LICENSE.md](RP/LICENSE.md) for full terms — in short: you may use and modify this addon for your own worlds/servers, but may not redistribute, resell, or reupload it elsewhere without permission.

## 🙏 Credits

- **Author:** Zeonn ([itzzeonn](https://github.com/itzzeonn))
- Menu item icon adapted from a vanilla Minecraft texture, © Mojang Studios
- Built with the `@minecraft/server` and `@minecraft/server-ui` script APIs

## 🐛 Found a bug?

Open an [issue](../../issues) or reach out via [itzzeonn](https://github.com/itzzeonn).
