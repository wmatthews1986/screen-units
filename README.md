# Screen Unit Calculator

An installable app with two tools:
- **Screen units**: (M1 + M2 + …) × H, every measurement and the height rounded up to whole feet
- **Inches → Feet**: turns inch measurements into feet and inches, with a running total

Once it's installed it works offline, and it doesn't need a sign-in.

## Put it on GitHub Pages (one time, about 10 minutes)

1. Go to github.com, click **+** (top right), then **New repository**.
   - Name it `screen-units`.
   - Set it to **Public**. Free GitHub Pages needs a public repo. Nothing private is stored in these files.
   - Click **Create repository**.
2. On the new repo's page, click **uploading an existing file**.
3. Drag in **everything inside this folder**: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the whole `icons` folder.
   Then click **Commit changes**.
4. Go to **Settings**, then **Pages** (left side).
   - Under *Build and deployment*, set **Source** to **Deploy from a branch**.
   - Set **Branch** to **main** and the folder to **/ (root)**, then click **Save**.
5. Wait 1 to 2 minutes, then refresh the Pages screen. Your app's address shows at the top:
   `https://YOUR-USERNAME.github.io/screen-units/`

## Install it

- **iPhone:** open the address in **Safari**, tap **Share**, then **Add to Home Screen**.
- **Android:** open it in **Chrome**, tap **⋮**, then **Install app** (or **Add to Home screen**).
- **Windows / Mac:** open it in **Chrome** or **Edge** and click the install icon at the right end of the address bar.

Open the app once while you're online. After that it works without signal.

## Changing it later

Edit or re-upload the files in the repo. Then, in `sw.js`, bump the version line
(`screen-units-v1` becomes `screen-units-v2`) so phones pick up the new version the next time they open it online.
