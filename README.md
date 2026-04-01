# ⚔️ Quest Planner — 31 Day Adventure

A gamified pixel-RPG daily planner that works as a Progressive Web App (PWA).

## 📁 What's Inside

```
quest-planner-pwa/
├── index.html          ← The full app
├── manifest.json       ← PWA config (app name, icons, theme)
├── sw.js               ← Service worker (offline support)
├── README.md           ← This file
└── icons/
    ├── icon.svg         ← Source icon
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```

## 🚀 Deploy to GitHub Pages (Free, ~2 minutes)

### Step 1: Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up (free).

### Step 2: Create a New Repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `quest-planner`
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 3: Upload the Files
1. In your new repo, click **"Add file"** → **"Upload files"**
2. Drag the **entire contents** of this folder into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` folder (with all PNG files)
3. Click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under "Source", select **"Deploy from a branch"**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**
6. Wait 1-2 minutes, then your app is live at:
   **`https://YOUR-USERNAME.github.io/quest-planner/`**

## 📱 Install on Your Phone

### Android
1. Open the URL in Chrome
2. You'll see an "Install" banner — tap **Install**
3. Or tap the three-dot menu → **"Add to Home Screen"**

### iPhone/iPad
1. Open the URL in Safari
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add**

The app will now appear on your home screen with its own icon and open full-screen like a native app!

## 🔒 Privacy
- All data is stored locally on your device (localStorage)
- No servers, no accounts, no tracking, no analytics
- Works completely offline after first visit
- Your data never leaves your device
