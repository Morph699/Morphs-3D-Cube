<img width="2168" height="1755" alt="image" src="https://github.com/user-attachments/assets/ae2bea66-555b-4cf4-8da6-a3b4c95b5282" />

### Morphs 3D Cube

"Match Beyond the Surface. A True 3D Spatial Puzzle Experience."
Morphs 3D Cube reimagines the classic match-3 puzzle genre as a living, holographic 4×4×4 volumetric matrix floating in cosmic deep space. Instead of matching tokens across a flat 2D board, players navigate an interactive 64-crystal lattice where every move cascades across Width (X), Height (Y), and Depth (Z) simultaneously.

### 1. Volumetric 3D Matching Engine
Full 4×4×4 Grid: 64 translucent crystal nodes floating in 3-dimensional space.
Tri-Axial Matches: Align 3 or more matching crystals along any axis:
Width (X-Axis): Left-to-right horizontal alignments.
Height (Y-Axis): Vertical column alignments affected by simulated gravity.
Depth (Z-Axis): Front-to-back cross-layer penetration through the cube core.
Cascades & Gravity Drops: Matched crystals shatter in sparkling particle bursts; crystals above drop with elastic bounce physics, triggering multi-tier chain reaction cascades.

### 2. Physical Gemstone Optics & Visuals
Crystalline Transmission Shading: Powered by Three.js MeshPhysicalMaterial with real physical transmission (transmission: 0.35, ior: 1.62), giving crystals the optical depth and translucency of cut jewels rather than opaque plastic.
Mirror-Polished Facets: Configured with clearcoat: 1.0, low roughness, and flatShading: true so every polygon facet catches specular highlights independently as light glances across them.
Laser-Etched Facet Outlines: High-opacity glowing edges trace every geometric facet for laser-sharp definition.
Studio Lighting Rig:
Key Light: High-intensity warm-white directional light for crisp specular glints.
Electric Cyan Rim Light: Backlights the cube to produce the signature holographic cyan halo along every crystal silhouette.
Deep Violet Bounce Fill: Provides rich cosmic contrast in the shadows.
Orbiting Sparkle Lights: Dynamic amber and cyan point lights gently orbit the cube, causing facets to sparkle continuously during gameplay.
Holographic Containment Cage: An electric cyan wireframe box with 8 quantum corner brackets and a luminous floor grid.

### 3. Special Crystals & Dimensional Detonations
Nova Bomb (Match 4 in a row):
Visual: A faceted geodesic icosahedron with ruby-fuchsia transmission, a spinning plasma energy ring, and a rotating internal fire core.
Power: Triggers a 3D cross-axis shockwave clearing surrounding crystals across all three dimensions.
Hypercube (Match 5 in a row / cross-match):
Visual: A 4D tesseract chromatic glass cube with iridescent rainbow edges encasing a floating, rotating white-diamond crystal.
Power: Swapping it vaporizes every crystal of the chosen color across the entire 64-crystal matrix.

### 4. Interactive 3D Camera & Controls
Free Orbit & Pinch-to-Zoom: Fluid 360° spherical rotation with touch-drag and mouse controls.
Floating Camera Presets: Dedicated capsule pill buttons on the right flank:
Iso 3D (Cyan neon) · Front (Ultra Violet neon) · Top (Golden Amber neon) · Side (Vibrant Magenta neon).
90° Axial Turns: Quick one-tap snaps to rotate left/right (⟲ / ⟳ 90°) or tilt up/down (▲ / ▼ 90°).
Holographic Directional Reticle: Selecting a crystal spawns glowing 3D arrowheads along all available directions:
Up/Down (Y): Cyan arrows
Left/Right (X): Amber arrows
Depth (Z): Fuchsia arrows
Selecting a crystal emits a golden-cyan spark particle burst, and the arrows breathe with an animated energy pulse.
Drag-to-Swap: Drag directly in screen space along any projected 3D direction vector to execute instant swaps.

### 5. X-Ray Slicing Tool (Slice Inside the Cube)
Direct Axis Isolation: One-tap toggles between Depth (Z), Height (Y), and Width (X).
Layer Stepper: Switch between Full 3D (all layers visible) and single cross-section layers (L1, L2, L3, L4) to isolate internal structures and reveal hidden matches deep inside the core.

### 6. Four Distinct Game Modes
Endless Mode: Zen-like spatial puzzle solving with no timer pressure. Includes tactical Hint and Shuffle assistance.
Blitz 60s: Adrenaline-fueled speed attack. Start with 60 seconds; every successful 3D match awards +1 bonus second to keep combos alive.
Puzzle Missions (8 Levels): 8 handcrafted missions with specific objectives and move constraints:
Level 1: Neon Awakening (Harvest 15 Cyan matrix crystals in 14 moves)
Level 2: Plasma Surge (Score 5,000 points in 12 moves)
Level 3: Nova Synthesis (Spawn 2 Nova Bomb specials in 10 moves)
Level 4: Solar Resonance (Harvest 18 Amber crystals + 6,500 pts in 15 moves)
Level 5: Singularity Breach (Score 10,000 points in 16 moves)
Level 6: Quantum Entanglement (Harvest 20 Ruby crystals in 14 moves)
Level 7: Chrono Fracture (Score 14,000 points in 15 moves)
Level 8: Tesseract Transcendence (Harvest 25 Emerald crystals + score 18,000 pts in 18 moves)
Daily Challenge: A deterministic 4×4×4 cube seeded from the UTC date via Mulberry32 PRNG. Compete against offline procedural rivals and record high scores on the persistent daily leaderboard.

### 7. Visual Theme Studio & Synthesizer
13 Thematic Presets: Cyberpunk 2099, Retro Synthwave, Matrix Digital, Celestial Astral, Magma Volcanic, Sweet Candy Orbs, Laser RGB Clarity, Abyssal Bioluminescent, Neon Surge, Sunset Heat, Toxic Cyber, Aurora Borealis, Retro Arcade.
   
5 Block Geometries: Prismatic Polyhedra, Cyber Cubes, Quantum Orbs, Brilliant Cut Gems, Cosmic Stellar.
5 Containment Frames: Holographic Wireframe, Quantum Floating Brackets, Laser Matrix, Prism Glass, Stealth Titanium.
5 Atmospheric Backgrounds: Cosmic Deep Space, Retro Synthwave Grid, Matrix Digital Void, Celestial Nebula, Pure Minimal Void.
Web Audio Procedural Synthesizer: Built-in sound engine generating dynamic chimes, bass drops, laser hums, and explosion resonant filters without external audio files.

### 8. Architecture & Offline PWA

Tech Stack: React 19, TypeScript, Three.js, Tailwind CSS v4, Web Audio API.
Zero-Dependency Offline Play: 100% of game logic, daily puzzles, and audio synthesis run locally in-browser.
PWA & Mobile Install Ready: Configured with Web App Manifest, Apple touch icons, full touch/pinch handlers, and in-app installation prompts.
