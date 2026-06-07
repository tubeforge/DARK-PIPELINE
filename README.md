# ⬡ The Dark Pipeline — PWA

YouTube content automation app. Generates complete production packages powered by Claude AI.

## Files
- `index.html` — main app
- `manifest.json` — PWA config
- `sw.js` — service worker (offline support)
- `icon-192.png` — app icon
- `icon-512.png` — app icon large

---

## 🚀 Deploy to GitHub Pages (Step by Step)

### Step 1 — Create GitHub Account
Go to github.com → Sign up (free)

### Step 2 — Create New Repository
- Click the **+** button → New repository
- Name it: `darkpipeline`
- Set to **Public**
- Click **Create repository**

### Step 3 — Upload Files
- Click **uploading an existing file**
- Drag and drop ALL files from this folder:
  - index.html
  - manifest.json
  - sw.js
  - icon-192.png
  - icon-512.png
- Click **Commit changes**

### Step 4 — Enable GitHub Pages
- Go to **Settings** tab of your repo
- Scroll to **Pages** section
- Under Source → select **Deploy from a branch**
- Branch → select **main** → folder **/ (root)**
- Click **Save**

### Step 5 — Get Your URL
- Wait 2–3 minutes
- Your app will be live at:
  `https://YOUR-USERNAME.github.io/darkpipeline`

---

## 📱 Install as Android App (PWA)

1. Open your GitHub Pages URL in **Chrome on Android**
2. Tap the **three dots menu** (⋮) in Chrome
3. Tap **"Add to Home screen"**
4. Tap **"Add"**
5. App icon appears on your home screen ✅

---

## 🔑 API Key Setup

1. Go to **console.anthropic.com**
2. Sign up / Log in
3. Go to **API Keys** → Create new key
4. Copy the key (starts with `sk-ant-`)
5. Open the app → tap **API Key** → paste it → Save

Your key is stored only on your device (localStorage). Never shared.

---

## Workflow

1. Generate Pipeline → script + image prompts + metadata
2. Script → paste to ElevenLabs → download MP3 voiceover
3. Image Prompts → generate in Midjourney / Leonardo.ai
4. Import voice + visuals into CapCut → assemble
5. Metadata → paste when uploading to YouTube
