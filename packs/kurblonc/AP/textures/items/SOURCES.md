# Item texture sources

`dirt.png` is derived art: a full 16×16 isometric cube built from `../blocks/dirt_base.png` (top) and `../blocks/dirt_front.png` (sides) with the same construction, side shading and one-pixel silhouette as the wall icons.

`cave_rock.png` is derived art: `stone_brick_wall.png` with its body colors remapped onto the natural stone palette from `../blocks/natural_stone_wall_front.png` by `scripts/build_cave_rock_icon.py` — the same rule `scripts/build_natural_stone_wall_top.py` applies to the cap sheet. Pixels, alpha and silhouette are unchanged.

`log.png` is the owner-supplied log icon added on 2026-10-28 and kept at its authored 15×15 size.

`wheat_seeds.png` is copied unchanged from the owner-provided Forager Minecraft resource pack at `forager/Forager/assets/minecraft/textures/item/wheat_seeds.png`. Forager is by CanineGray (as credited in its `pack.mcmeta`) and is licensed CC BY-NC 4.0. The original terms are included in `LICENSE.txt`, copied from `forager/Forager/License.txt`.

`sandstone.png` is derived art: the pack's own `sand.png` inventory icon with the hue, saturation and brightness shift that turns the sand palette into the sandstone palette used by `../blocks/sandstone.png` and `../blocks/sandstone_wall_front.png`. The pixel structure and alpha are unchanged.
