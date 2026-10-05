# Glow Room

Full-screen visual sensory play for the classroom, made for iPads.

Ten modes: Sparkles, Bubbles, Draw, Numbers, Letters, Fireworks, Ripples, Shapes, Light tunnel and Swirl paint.

- Students pick a mode from big picture tiles (or the teacher sets one).
- Teacher settings: press and hold the lock in the top corner for 3 seconds.
- Session timer, calm mode, gentle sounds, and numbers/letters read aloud.
- Nothing flashes or strobes the whole screen.
- Settings are saved on each device. Works offline after the first visit.

## Put it on GitHub Pages

1. Create a new public repository (for example `GlowRoom`).
2. Upload every file in this folder to the top level of the repository.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute the app is live at `https://YOUR-USERNAME.github.io/GlowRoom/`.

## Add it to an iPad home screen

Open the link in Safari, tap **Share**, then **Add to Home Screen**. It opens full screen with no browser bars. Use Guided Access to keep students in it.

## Updating

Replace `index.html` with the new version and change `glowroom-v1` in `sw.js` to `glowroom-v2` (and so on), so iPads pick up the update.
