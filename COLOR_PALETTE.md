# 🎨 Chipped-Driven — Stonepunk 16-Bit Color Palette

This document defines the canonical pixel art color constraints for *Chipped-Driven*. All environment tiles, character sprites, and UI elements should draw from these five dominant colors to maintain a cohesive "Stonepunk" visual identity.

---

## Palette Overview

| Role | Name | Hex | Preview |
|------|------|-----|---------|
| 🌿 Earthy — Flora | **Mossy Jungle Green** | `#4A7C59` | ![#4A7C59](https://via.placeholder.com/16/4A7C59/000000?text=+) |
| 🪨 Earthy — Stone | **Deep Slate Grey** | `#3D3D3D` | ![#3D3D3D](https://via.placeholder.com/16/3D3D3D/000000?text=+) |
| 💨 Steam — Cloud | **Ashen Bone White** | `#E8E0D0` | ![#E8E0D0](https://via.placeholder.com/16/E8E0D0/000000?text=+) |
| ⚙️ Steam — Metal | **Iron Fog Grey** | `#9AA5A8` | ![#9AA5A8](https://via.placeholder.com/16/9AA5A8/000000?text=+) |
| 🌋 Volcanic Pop | **Lava Neon Orange** | `#FF6B1A` | ![#FF6B1A](https://via.placeholder.com/16/FF6B1A/000000?text=+) |

---

## Color Details

### 🌿 Mossy Jungle Green — `#4A7C59`
- **Role:** Earthy tone — vegetation, overgrown ruins, vine-wrapped structures, swamp biome ground tiles.
- **Feel:** Ancient, alive, and untamed. Suggests a world where nature has reclaimed stone.

### 🪨 Deep Slate Grey — `#3D3D3D`
- **Role:** Earthy tone — raw stone, boulders, cave walls, the chassis of stone-machined vehicles.
- **Feel:** Heavy, immovable, prehistoric. The bones of every structure the player builds or encounters.

### 💨 Ashen Bone White — `#E8E0D0`
- **Role:** Industrial/Steam tone — steam cloud puffs, exhaust plumes, sun-bleached bone materials, UI highlights.
- **Feel:** Ephemeral and light; contrasts the heavy stone palette to sell the steam-power fantasy.

### ⚙️ Iron Fog Grey — `#9AA5A8`
- **Role:** Industrial/Steam tone — riveted metal panels, pipe fixtures, gear teeth, pressurized tank surfaces.
- **Feel:** Cold and mechanical. Signals crafted, processed material versus raw natural stone.

### 🌋 Lava Neon Orange — `#FF6B1A`
- **Role:** Volcanic "Pop" — lava flows, glowing furnace cores, high-heat engine vents, danger indicators, UI health/fuel bars.
- **Feel:** Immediate visual danger and energy. The single warm accent that draws the player's eye to heat sources and critical systems.

---

## Usage Guidelines

- **Limit per-sprite palettes to 3 of these 5 colors** to preserve the 16-bit constrained aesthetic.
- Use **Lava Neon Orange** sparingly — it should feel special. Reserve it for interactive or hazardous elements only.
- **Deep Slate Grey** and **Mossy Jungle Green** form the base layer of every biome tile.
- **Ashen Bone White** and **Iron Fog Grey** distinguish player-built/crafted objects from the natural world.
- Shading should be done by darkening/lightening these base colors by no more than **20% luminosity** to stay within the palette spirit.
