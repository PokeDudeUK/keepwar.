# Keepwar

Tower-conquest strategy game. Single-file HTML + PWA wrapper, no build step.

## Deploy
1. Push this folder to a GitHub repo.
2. Import it in Vercel (framework preset: Other). Deploy.
3. Open the URL in Safari on iPhone -> Share -> Add to Home Screen.
4. Launch from the home screen. Works fully offline after the first load; progress saves on-device.

To ship an update, bump `CACHE` in `sw.js` so phones fetch the new version.
