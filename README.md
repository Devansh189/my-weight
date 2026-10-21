# My Weight

A simple daily weight tracker (calendar + graphs) that installs on an iPhone home screen.
All data is stored only on the phone (localStorage) — nothing is uploaded anywhere.

## Put it online (GitHub Pages)

1. Create a new public repo on GitHub, e.g. `my-weight`.
2. Upload all files from this folder to the repo root (`index.html`, `manifest.json`, `sw.js`, the 3 PNG icons).
3. Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
4. After a minute it's live at `https://<your-username>.github.io/my-weight/`.

## Install on iPhone

1. Open the link in **Safari** (not Chrome/WhatsApp's in-app browser).
2. Tap **Share → Add to Home Screen → Add**.
3. Open it from the new home-screen icon and use it **only from there**.
   (The home-screen app and Safari keep separate data, so entries made in Safari won't show in the app.)

## Notes

- Backups: Settings (gear icon) → *Save a backup file*. Do it once a month; restore with *Restore from backup*.
- Updating the app: just push new files to the repo. The data on the phone is not affected.
- The repo/site being public is fine — it only contains the code, not her weight data.
