# Gunship Duel

Turn-based tactical fleet battle in orbit, in the spirit of classic 4X space-combat games. Single HTML file, Three.js (WebGL), no build step.

**Play:** https://aleksandrenko.github.io/gunship-duel/

- Fleet design screen: pick up to 6 hulls (frigate, destroyer, cruiser, battleship) and fit components into each hull's space within a 170 BC budget; the enemy gets a random fleet of the same cost
- Lasers, pulse cannons, fusion beams, missiles that travel across rounds, point defense
- Four shield arcs per ship, armor, structure; asteroids block movement and beams
- Ships act one at a time in initiative order
- Weapon reach is shaded on the map; picking or hovering a weapon shows its exact range and arc

**Controls:** click a hex to move · Q/E turn · click an enemy to fire (1–5 picks one weapon) · Enter ends the ship's turn · WASD pan, right-drag rotate, wheel zoom.

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
