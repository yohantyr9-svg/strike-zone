# Strike Zone

A mobile-first shooter built with Three.js. Single file, no build step.

## Real 3D models
The game loads a rigged soldier model automatically (from the three.js repo via jsDelivr).
To use your own character, put a rigged .glb (Mixamo-style skeleton with Idle and Run animations)
at `models/soldier.glb` in this repo. It takes priority.
If no model loads, the built-in procedural soldier is used.

Host with GitHub Pages: repo Settings > Pages > Deploy from branch > main / (root).
