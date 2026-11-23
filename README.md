# Gunship Duel

Turn-based tactical fleet battle in orbit, in the spirit of classic 4X space-combat games. Single HTML file, Three.js (WebGL), no build step.

**Play:** https://aleksandrenko.github.io/gunship-duel/

- 4 ships a side: frigate, destroyer, cruiser, battleship
- Lasers, pulse cannons, fusion beams, missiles that travel across rounds, point defense
- Four shield arcs per ship, armor, structure; asteroids block movement and beams
- Ships act one at a time in initiative order

**Controls:** click a hex to move · Q/E turn · click an enemy to fire (1–5 picks one weapon) · Enter ends the ship's turn · WASD pan, right-drag rotate, wheel zoom.

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
