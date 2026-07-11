# MC-Server-Side-Resource-Pack

This repository contains the resource packs used by the MCS Server.

> [!NOTE]
> All technical documentation and overviews in this repository are AI-generated to save development time.

---

## Default 3D Resource Pack

**Default 3D** is a lightweight Minecraft resource pack that enhances the vanilla experience by replacing selected flat textures with custom-modeled 3D geometry, while preserving the original 16×16 pixel art style.

Unlike realism-focused resource packs, Default 3D does not aim to redesign Minecraft's visual identity. Instead, it extends the vanilla asset set using Minecraft's native model system to introduce depth and volume to select blocks and items, without compromising performance or deviating from the game's iconic aesthetic.

The pack is built entirely on Minecraft's standard resource pack format and requires no client-side mods, making it fully compatible with vanilla clients and with multiplayer servers that distribute resource packs automatically.

---

## Features

* Faithful, vanilla-consistent visual style
* Native 3D block and item models (no mods required)
* Lightweight, performance-optimized geometry
* 16×16 texture resolution maintained throughout
* Built entirely on Minecraft's native resource pack system

---

## Technical Specifications

| Property | Value |
|---|---|
| Minecraft Version | 1.21.x |
| Texture Resolution | 16×16 |
| Pack Format | Compatible with Minecraft 1.21 |
| Resource Type | Resource Pack |
| Model Format | Native JSON Models |
| Dependencies | None |
| Mod Requirement | None |
| Performance Impact | Low |

---

## How It Works

Default 3D uses Minecraft's native JSON model format to replace selected 2D textures with optimized 3D geometry. Rather than relying on shaders, mods, or external rendering pipelines, the pack works entirely within the game's built-in rendering engine — ensuring full compatibility with vanilla gameplay and server-side resource pack delivery.

All models are optimized to minimize polygon count while delivering a noticeable visual improvement across the game world, keeping the performance overhead low even on modest hardware.

---

## Installation

1. Download the latest release.
2. Move the `.zip` file into your Minecraft `resourcepacks` folder.
3. Launch Minecraft.
4. Navigate to **Options → Resource Packs**.
5. Enable **Default 3D**.
6. Enjoy an enhanced vanilla experience.

---

## License

This repository contains the source assets and configuration files for the Default 3D Resource Pack. Please review and respect the project's license before redistributing or modifying any assets.

—Akkshath
