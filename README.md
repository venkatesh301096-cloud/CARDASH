# CarDash — Custom Android Auto-Style Dashboard

## How to get the APK on your F27LC tablet

### STEP 1 — Create a free GitHub account
1. Go to https://github.com/signup
2. Enter your email, create a password, choose a username
3. Verify your email

### STEP 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it: `cardash`
3. Set to **Public**
4. Click **Create repository**

### STEP 3 — Upload the code
1. In the new repo page, click **uploading an existing file**
2. Open the folder: `C:\Users\pzvp\.aki\tmp\cardash` on your PC
3. Select ALL files and folders, drag them into the GitHub upload area
4. Scroll down, click **Commit changes**

### STEP 4 — Wait for the build (2-3 minutes)
1. Click the **Actions** tab in your repo
2. You'll see a workflow running called "Build CarDash APK"
3. Wait for the green ✅ checkmark

### STEP 5 — Download the APK
1. Click on the completed workflow run
2. Scroll down to **Artifacts**
3. Click **CarDash-APK** to download a zip file
4. Unzip it — you'll find `app-debug.apk` inside

### STEP 6 — Install on the F27LC tablet
1. Transfer `app-debug.apk` to the tablet (USB cable or WiFi file transfer)
2. On the tablet: Settings → Security → enable **Unknown Sources** (or Install unknown apps)
3. Open the APK file → Install
4. Done!

### STEP 7 — First-time setup on tablet
1. Open CarDash
2. Go to **Settings → Apps → Special app access → Notification access**
3. Enable **CarDash** — this allows music controls to work
4. Connect tablet to your **phone's hotspot** for weather + navigation
5. Pair phone via **Bluetooth** for hands-free call display

---

## What CarDash does

| Feature | How it works |
|---------|-------------|
| 🕐 Clock | Always visible, real-time |
| 🌤️ Weather | Live Chennai weather (Open-Meteo, no account needed) |
| 🗺️ Navigation | Opens Google Maps on tablet |
| 🎵 Music | Shows Spotify/YouTube Music playing — play/pause/skip controls |
| 📞 Calls | Shows incoming call on screen with caller number |
| 🔋 Battery/WiFi | Status bar shows tablet battery + WiFi |
| 🌙 Dark theme | Like Android Auto — easy on eyes while driving |
| 📺 Full screen | Landscape, no status bar clutter |

