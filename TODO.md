Things to add:

Pixel-art dragons (PAUSED: extra, and expensive). Not needed for the game to work; only do this if there is budget to spare.
- The dragons are drawn by code (`dragonArt` in grow-a-dragon.html): 13 levels from egg to Monarch, 8 species, hybrids, moods and motion, plus 8 background scenes.
- Cheap version: pixelate the existing art (render small, scale up with hard pixels, limited palette). Rough estimate 0.2-0.4M tokens. Looks like pixelated vector art, not hand-drawn sprites.
- Full version: redraw as true layered sprites, recoloured per species so hybrids still work. Rough estimate 2-4M tokens, plus 0.5-1M for the scenes. Models draw pixel art poorly, so expect many screenshot-and-fix rounds.
- If picked up, start with a pilot: one species (Volcano) at egg, hatchling and one Mega form, about 0.2-0.3M tokens, and judge the quality before doing the rest.
