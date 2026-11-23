IRON FRONT: WORLD WAR is a complete top-down WWII vehicle combat game in one index.html file - tanks, aircraft, and transport runs, all rendered on HTML5 Canvas with procedurally generated battlefields. No build tools, no libraries, no external assets. Open it and deploy.

The premise: 1944, a fictional European theatre. Every vehicle has a role. Every mission has a cost.

Features

Three vehicle classes, seven machines - medium/infantry/cruiser tanks (Sherman, Churchill, Cromwell), fighters (Spitfire, Hurricane, Mustang), and an unarmed cargo truck - each with distinct handling, armour, and armament

12-mission campaign across 3 chapters and 3 biomes (summer, winter, industrial), plus a free-play Training Ground

Component damage model - hull, engine, tracks, and turret degrade independently, each affecting speed, steering, or aim

Tank gunnery - independently traversing turret, shell ballistics, reload timing, and a mouse-aimed reticle

Flight model - throttle, banking turns, pitch/altitude control, fuel burn, and a ground-crash consequence

Objective variety - destroy armour, reach/deliver to a zone, hold position against waves, fly a recon waypoint route, or train

Seeded procedural maps - roads, buildings, tree cover, rough terrain, and craters generated deterministically per mission

Enemy AI state machines - idle -> pursue -> attack with aim error and re-targeting; enemy fighters match altitude and lead their turns

Period military HUD - live minimap, compass heading, speed, per-component bars, ammo/reload, mission timer, and an objectives readout

Full game feel - screen shake, muzzle flashes, dust trails, contrails, explosion smoke, and a synthesized WebAudio engine/gun/explosion soundtrack

Persistent progression via localStorage - mission unlocks, S/A/B/C ratings, and a sound toggle

Responsive & accessible - safe-area-aware layout, scaled HUD on small screens, and a toggleable mute

Tech: vanilla JavaScript, HTML5 Canvas 2D, WebAudio API. Zero dependencies, one file, ~1,800 lines. Fixed 60 Hz simulation decoupled from render rate.

Controls: WASD drive - Mouse aim/fire - Space fire - R reload-adjacent - W/S throttle (air) - A/D bank - ↑/↓ or Shift/Ctrl pitch - Esc pause

Note: All nations, vehicles, and theatres are fictionalised for gameplay; this is not a historical simulation.