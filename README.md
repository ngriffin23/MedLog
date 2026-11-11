# MedLog

Put these files online for free so you and your friends can open MedLog from a link and add it to your iPhone Home Screen.

## What's in this folder

- `index.html` is the home page people see first, with an **Open MedLog** button and Home Screen steps
- `app.html` is the app itself
- `manifest.webmanifest` gives it a name, colors and Home Screen settings
- `sw.js` lets it open without internet
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` are the app icons

## Put it online (about 5 minutes)

1. Make a free account at github.com if you don't have one.
2. Tap **+** (top right), then **New repository**. Name it `medlog`, choose **Public**, then **Create repository**. On a free account, GitHub Pages needs a public repository. That's fine here, because the repository holds only the app itself and never anyone's entries.
3. On the new repository page, choose **uploading an existing file**. Drag in all seven files from this folder (not the folder itself, and unzip first if you have the .zip), then choose **Commit changes**.
4. Open **Settings**, then **Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick the **main** branch and the **/ (root)** folder, then **Save**.
5. Wait a minute or two and refresh. The page shows your link, which opens the home page and looks like `https://YOUR-USERNAME.github.io/medlog/`.

## Install it on an iPhone

1. Open your link in **Safari** (it has to be Safari).
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. From now on, open MedLog from its Home Screen icon only. The icon goes straight to the app and skips the home page.

Send friends the same link and the same steps.

## Good to know

- **Everyone's data stays on their own phone.** Nobody can see anyone else's entries, and the repository never receives them.
- **Use the Home Screen icon, not Safari.** The icon and Safari keep separate saved data, so entries made in one won't appear in the other.
- **Nothing syncs between devices.** Someone who gets a new phone starts empty.
- **Reminders only fire while MedLog is open.** They need iOS 16.4 or newer and the Home Screen version of the app. Set a phone alarm for any dose you can't afford to miss.
- **Don't clear website data** in Safari settings, or the saved entries are erased.

## Updating the app later

1. Replace `app.html` in the repository (open the file, tap the pencil icon, or upload the new one). The home page, `index.html`, rarely needs changing.
2. Open `sw.js` and change `medlog-v2` to `medlog-v3`, then `medlog-v4` next time, and so on.
3. Commit. Phones pick up the new version after the app has been opened twice.
