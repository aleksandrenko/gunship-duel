# Gunship Duel

Turn-based tactical fleet battle in orbit, in the spirit of classic 4X space-combat games. Single HTML file, Three.js (WebGL), no build step.

**Play:** https://aleksandrenko.github.io/gunship-duel/

- Fleet design screen: up to 6 ships, each with a hull (frigate, destroyer, cruiser, battleship), a design (Vanguard gunship or Bulwark turbine hauler) and any number of components; every ship must be saved before launch; the enemy gets a random fleet of the same total cost
- Lasers, pulse cannons, fusion beams, missiles that travel across rounds, point defense
- Four shield arcs per ship, armor, structure; asteroids block movement and beams
- Ships act one at a time in initiative order
- Weapon reach is shaded on the map; picking or hovering a weapon shows its exact range and arc

**Controls:** click a hex to move · Q/E turn · click an enemy to fire (1–5 picks one weapon) · Enter ends the ship's turn · WASD pan, right-drag rotate, wheel zoom.

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
