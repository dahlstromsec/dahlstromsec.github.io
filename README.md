# FORM Gym — iPhone-ready PWA

## Publish using GitHub Pages
1. Create a **public** GitHub repository (for example `form-gym`).
2. Upload **all files in this folder to the repository root**, including `index.html`, `manifest.webmanifest`, `sw.js`, and the PNG icons.
3. In GitHub, open **Settings → Pages → Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
4. Open `https://YOUR-USERNAME.github.io/form-gym/` in **Safari on iPhone**.
5. Tap **Share → Add to Home Screen → Add**.

## Data and updates
Workouts are stored locally on the device/browser, not in GitHub. Back up with **Export JSON** regularly. The installed app may have separate storage from Safari or desktop; import a JSON backup to transfer records. Avoid private browsing. The app caches its interface for offline use after its first successful load, but the first installation requires internet access.

To publish an update, replace the site files and increment the `CACHE` version in `sw.js` if needed.
