# Natural cave stone

`blocks/natural_stone.png` is copied unchanged from the owner-supplied
`forager/Forager/assets/minecraft/textures/block/stone.png` (16×16).
`blocks/natural_stone_front.png` repeats that tile four times horizontally
to supply the existing wall-front connection slots, without resampling or recoloring.
Both render at the existing terrain scale of two world pixels per source pixel.

`blocks/cave_rock_top.png` repeats the same unchanged tile in a 192×64 wall
autotile sheet. `blocks/cave_rock_front.png` repeats it in four 16px columns,
with two source rows repeated below the first 16 rows to match the existing
18px wall lift. No source pixels are stretched or recolored.
