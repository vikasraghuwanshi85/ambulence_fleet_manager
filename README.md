# Ambulance Fleet Manager - Android App

## GitHub Pages Deployment (2 minutes)

### Step 1: Create GitHub Repo
1. Go to github.com/new
2. Repo name: ambulance-fleet-app
3. Make it Public
4. Don't add README (we have files)
5. Create

### Step 2: Upload files
Option A - Web upload (easiest):
1. In your new repo, click "Add file" > "Upload files"
2. Drag these 3 files: index.html, manifest.json, sw.js
3. Commit

Option B - Git:
```
git clone https://github.com/YOUR_USERNAME/ambulance-fleet-app.git
cd ambulance-fleet-app
cp /path/to/index.html .
cp /path/to/manifest.json .
cp /path/to/sw.js .
git add .
git commit -m "Ambulance app"
git push
```

### Step 3: Enable GitHub Pages
1. In repo, go to Settings > Pages
2. Source: Deploy from a branch
3. Branch: main, Folder: / (root)
4. Save
5. Wait 1-2 minutes, your link will appear: https://YOUR_USERNAME.github.io/ambulance-fleet-app/

### Step 4: Install on Android
1. Open that link on Android Chrome
2. Chrome will show popup "Install Ambulance Fleet Manager" or 3 dots > Install App / Add to Home Screen
3. Tap Install
4. App appears on home screen with ambulance icon 🚑
5. Opens like native app, works offline, camera for bill scanning works

Your app includes:
- 12-month Jan-Dec sheets logic
- WhatsApp text parser (Date- format)
- Bill photo scanner (Bharat Petroleum + handwritten Hindi)
- Full vehicle number support: CG04NS7412, MP09AB6072
- Local storage + Export to Excel

No Play Store needed!
