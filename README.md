# Morphs-3D-Cube

High-performance 3D volumetric match-3 puzzle game inside a morphing holographic cube with WebGL/WebGPU-ready rendering, touch-optimized controls, and multiple game modes
<img width="1376" height="1712" alt="1793348783901-2228cf74-b4fd-498c-8ba4-2e0a93b03990-01a18be9-a510-7df8-ab1e-9762b1e228a2" src="https://github.com/user-attachments/assets/9e9d14d1-eae0-4ac1-aac4-7129f0f39d38" />
https://morphs-3d-cube.ai.studio/
https://youtube.com/shorts/R37mhc31ZWM

Morphs 3D Cube is a high-performance, volumetric match-3 puzzle game set inside a customizable, morphing holographic cyber-cube. Built with Three.js, WebGL, Web Audio API, and React, it transforms the classic 2D grid matching genre into a true three-dimensional spatial puzzle experience.
🎮 Core Game Mechanics & Volumetric 3D Engine
True 3D Grid ( Nodes):
Crystals are arranged throughout a 3D volumetric matrix. Matches can be formed across all 3 spatial dimensions: horizontally (
), vertically (), and through depth planes ().
Full Orbit & Spatial Controls:
Free-orbit 3D touch/drag rotation and pinch-to-zoom.
Instant camera angle presets: Iso 3D, Front, Top, and Side.
Precise 90° axial cube turn and tilt buttons with keyboard shortcuts (Arrow keys / WASD).
Directional Swap Dock & Reticle:
Tap any crystal to highlight it with a neon targeting reticle and bring up 6 directional swap buttons (Left, Up, Right, Down, Forward, Backward) or directly swipe neighboring blocks in 3D space.
Cascades, Gravitational Drops & Refills:
Matches trigger physics-based vaporizations, sound synthesis, cascading drops, and combo chain multipliers ().
Hyper & Nova Special Crystals:
Matching 4 crystals creates a Nova Bomb (detonates a sphere).
Matching 5 crystals creates a Hypercube (vaporizes every crystal of the targeted color in the entire cube).
🕹️ 4 Distinct Game Modes
Endless Mode:
Relaxed, unbounded spatial match-3 play with persistent local high-score tracking.
Blitz Mode:
A 60-second high-adrenaline sprint to build maximum combos and rack up points before the timer runs out.
Puzzle Mode (8 Handcrafted Mission Levels):
Fixed move budgets with specific objectives (e.g., harvest 15 Cyan crystals, trigger Nova Bombs, or reach target score thresholds).
Daily Challenge Mode:
A unique procedural puzzle level generated fresh each day at UTC midnight from a deterministic seed.
Compete on an identical 3D layout against the Global Daily Leaderboard with score, moves used, and max combo metrics.
🔬 Slicing & Layer Isolation (The "X-Ray" Tool)
Multi-Axis Slicing Bar:
Inspect the inner core of the cube by isolating individual 2D planar cross-sections:
-Axis (Depth Layers L1–L4)
-Axis (Height Layers L1–L4)
-Axis (Width Layers L1–L4)
Full 3D Mode (restores complete volumetric visibility)
🎨 Visual Theme Studio (Deep Customization)
Customize the visual identity of the entire app in real time with auto-saving to local storage:
8 Quick-Select Presets:
Cyberpunk 2099, Retro Synthwave, Matrix Digital, Celestial Astral, Magma Volcanic, Sweet Candy Orbs, Laser RGB Clarity, and Abyssal Bioluminescent.
5 Geometric Block Shapes:
Polyhedra Facets (dual dodecahedrons, octahedrons, tetrahedrons)
Cyber Beveled Cubes (classic high-tech arcade voxels)
Plasma Spheres (luminescent geodesic energy cores)
Brilliant Cut Gems (diamond facets, emerald cuts, and double cones)
Stellar Stars (stellated 3D star polyhedra)
9 High-Contrast Chromatic Palettes:
Strictly balanced 5-color spectrum (Ruby Red, Cyan/Azure Blue, Emerald/Mint Green, Amethyst Purple, and Amber Gold) with zero muddy overlapping oranges or yellows.
5 Atmospheric Backgrounds & Dynamic Lighting:
Cosmic Deep Space, Synthwave Neon Grid, Matrix Abyss, Celestial Nebula, and Dark Minimalist Void (with matching volumetric exponential fog and particle starfields).
5 Holographic Cube Frame Enclosures:
Hologram Wireframe, Quantum Corner Brackets, Laser Dual-Matrix, Solid Translucent Glass Shield, and Minimal Clean.
📴 100% Standalone Offline & Multi-Platform Support
Zero Online Hard Blocks:
All 4 game modes, daily puzzles, and procedural rivals function without an internet connection.
Autonomous Daily Challenge:
Even when offline, the daily challenge seed is computed client-side, populating competitive procedural rivals on the leaderboard and saving your scores locally.
Synthesized Audio Engine:
Sound effects (crystal selection, directional swaps, match chimes, explosion bass, and victory flourishes) are synthesized on the fly via the browser's Web Audio API—no audio files need to be fetched over the network.
PWA & Native APK Packaging Ready:
Registered Service Worker with Workbox caching.
Relative asset bundling (./) allowing direct compilation into Android APKs (via Capacitor, Cordova, or Website 2 APK Builder) without path errors or offline warnings.
In-app install prompt with device-specific guidance for Android, iOS Safari, and Windows desktop.
📱 Responsive & Ergonomic Layout
Mobile-Optimized Architecture:
Multi-tier header keeping brand on the left, game modes on the right, and utility controls centered.
Dedicated rows for the Axis Slice Bar and Score/Objective HUD to eliminate overlapping on compact screens.
Hint (with remaining count indicator) and Board Shuffle floating right above the collapsible bottom dock for comfortable single-handed thumb play.
