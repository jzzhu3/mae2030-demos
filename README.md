# MAE 2030 — Interactive Demos

In-class HTML/JS simulations for MAE 2030 (Introduction to Aerospace Engineering), UVA.

## Contents
- `index.html` — landing page listing the demos
- `kinetic-temperature/` — Temperature & Molecular Motion (kinetic theory, v_rms ∝ √T, live Maxwell–Boltzmann)

## Publish to GitHub Pages

1. Create an empty repo on github.com named `mae2030-demos` (Public). Don't add a README/license — this folder already has them.
2. From this folder:

   ```bash
   git init
   git add .
   git commit -m "Add kinetic temperature demo"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/mae2030-demos.git
   git push -u origin main
   ```

3. On github.com: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save.**
4. Wait ~1 minute. Your live URLs will be:
   - Landing: `https://YOUR_USERNAME.github.io/mae2030-demos/`
   - Demo:    `https://YOUR_USERNAME.github.io/mae2030-demos/kinetic-temperature/`

Open the demo URL in **Safari** on the iPad — the particles will animate (Safari runs JavaScript; the Files/Quick Look preview does not).

## Notes
- `.nojekyll` is included so GitHub Pages serves the files as-is.
- To add a new demo later: drop it in its own folder as `index.html`, add a card to the root `index.html`, commit, and push.
