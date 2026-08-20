# NatureVerse

### Future Visionaries

"No Humans. No Machines. Just Nature."

---

## Concept
NatureVerse is an immersive 3D WebXR world exploration experience designed to provide a digital escape. In a world saturated with screens, noise, and automated systems, NatureVerse provides a sanctuary: an untouched natural landscape completely free of humans, buildings, vehicles, and machines. 

## Problem
Modern life is cluttered with constant digital notifications, screens, and virtual noise, leading to mental fatigue and stress. Existing virtual experiences often reinforce this clutter with complex menus, game mechanics, and simulated technologies.

## Solution
NatureVerse offers a pure, silent, and peaceful 3D natural sanctuary. Built with A-Frame and optimized for WebXR, it places the user directly inside a breathing ecosystem where they can watch butterflies, approach a grazing deer, sit by a flowing river, and explore a misty waterfall.

## Features
- **3D Forest Landscape**: Randomized procedural trees, bushes, flowers, and low-poly rocks.
- **Distant Mountain Ranges**: Giant background peaks creating a deep horizon.
- **Animated River & Waterfall**: Scrolling water textures and vertical cascade effects representing flowing water.
- **Interactive Deer**: A responsive procedural animal that wanders, grazes, and runs away to safety if the user approaches.
- **Birds & Butterflies**: Birds flying in loop sequences high above, and butterflies fluttering around flowers.
- **Spatial Audio**: Directional sounds for the river and waterfall, with randomized bird calls.
- **Web Audio Ambience Synth**: A synthesized soundscape generated directly in the browser using the Web Audio API as a robust offline fallback if external audio files fail.
- **Meta Quest 3S Locomotion**: Comfortable raycast teleportation controls to explore the environment without motion sickness.

## Technologies
- **A-Frame (v1.5.0)**: Core WebXR framework.
- **HTML5 & Vanilla CSS**: Minimal, glassmorphic landing screen.
- **Vanilla JavaScript**: Custom A-Frame components for locomotion, waterfall flow, river animation, and deer AI.
- **Web Audio API**: Browser-synthesized background nature ambience.

## Meta Quest 3S Support
- Fully tested and optimized for the **Meta Quest 3S** browser.
- **Right Controller**: Aim at the ground and press the trigger/thumbstick to project a teleportation reticle. Release to teleport to that location.
- **Left Controller**: Point and view interactive objects or wildlife.

## How to Run
Since this application runs entirely in a single HTML file without backends or build steps, you can run it using any static file server.

### Option 1: Using Python (Built-in)
Run the following command in the workspace directory:
```powershell
python -m http.server 8000
```
Then open `http://localhost:8000` in your web browser.

### Option 2: Using Node.js (npx)
```powershell
npx live-server
```

## How to Deploy
Since the project consists of only an `index.html` file, it is highly suitable for static web hosting.
- **GitHub Pages**: Push the repository to GitHub, go to Settings -> Pages, and enable deployment from your main branch.
- **Vercel / Netlify**: Connect the repository or upload `index.html` directly for instant global hosting.

## How to Enter VR on Meta Quest 3S
1. Host the project online (e.g., using GitHub Pages, Vercel, or a local server accessible via your local Wi-Fi network).
2. Open the **Meta Quest Browser** on your Meta Quest 3S headset.
3. Navigate to the URL where NatureVerse is hosted.
4. Click the **[ ENTER NATUREVERSE ]** button on the landing page.
5. Click the **VR** button in the bottom right corner of the screen to enter immersive mode.
6. Put on your headset and start exploring!
