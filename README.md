# SKG PBD Adventure V8 — Premium 3D

A playable Babylon.js + Vite 3D side-scrolling platformer, upgraded from the working V7 project.

## NEW
- Choose between **Fox, Rabbit, Panda, Cat** on the start screen. All four use genuine Babylon.js 3D meshes, not static images.
- Enhanced soft shadows, warm sunlight, color processing, subtle glow, rocks, mushrooms, grass blades and animated forest fireflies.
- Character running/jumping idle animations and animated tails; impact particles for magic, hits and collectibles.
- Retains V7: left/right movement, jumping, projectile attacks, 3 slime enemies, 5 collectibles, 3 lives, checkpoints, portal, camera follow, mobile buttons, fullscreen.

## Beginner deployment (Vercel)
1. Extract this ZIP, upload the files to a GitHub repository.
2. In Vercel select **Add New → Project** and import the repository.
3. Framework **Vite**; build command `npm run build`; output directory `dist`.
4. Deploy. Open the deployed link in desktop and mobile browsers.

## Run locally
```bash
npm install
npm run dev
```

## Controls
- A/D or left/right arrows = move
- Space / W / Up = jump
- X / J = magic shot
- Touch: left/right, jump, magic buttons
- Choose character before pressing Start.

## Important notes
- This is **true 3D** using procedural geometry, not a professionally sculpted or rigged character model.
- V8 is intentionally a single-world graphics upgrade; it does not yet include TP quiz or Google Sheets.
- Verify browser gameplay after deployment; an automated full browser test may not be available.
