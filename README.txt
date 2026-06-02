# BuddyRun PWA — Deploy Instructions

## What's in this folder
- `index.html` — the full BuddyRun app
- `manifest.json` — makes it installable as a home screen app
- `sw.js` — service worker for offline support
- `icon-192.png` / `icon-512.png` — you need to add app icons (see below)

---

## Step 1 — Add your app icon (2 mins)
You need two square icon images named:
- `icon-192.png` (192×192 pixels)
- `icon-512.png` (512×512 pixels)

**Quick option:** Use any square logo or image of a dog/paw.
Free icon maker: https://realfavicongenerator.net

---

## Step 2 — Deploy to Netlify (FREE, 2 mins)

1. Go to https://netlify.com and sign up free (use your Google account)
2. Once logged in, click **"Add new site" → "Deploy manually"**
3. **Drag the entire buddyrun-pwa folder** onto the Netlify drop zone
4. Wait ~30 seconds — Netlify gives you a URL like `https://random-name-123.netlify.app`
5. You can rename it to something like `https://buddyrun.netlify.app`

That's it — you now have a live URL!

---

## Step 3 — Install on your iPhone (30 seconds)

1. Open Safari on your iPhone (must be Safari, not Chrome)
2. Go to your Netlify URL
3. Tap the **Share button** (box with arrow pointing up)
4. Scroll down and tap **"Add to Home Screen"**
5. Name it **BuddyRun** and tap **Add**

BuddyRun now appears on your home screen like a real app! 🎉

---

## Step 4 — Install on Android (30 seconds)

1. Open Chrome on your Android phone
2. Go to your Netlify URL
3. Tap the **three dots menu** (top right)
4. Tap **"Add to Home screen"** or **"Install app"**
5. Tap **Add**

---

## Your data is saved locally
All your clients, schedule and settings are saved in your phone's local storage — they persist between sessions. When you're ready for cloud sync across multiple devices, we can add a backend.

---

## Custom domain (optional)
If you have a domain like `theperfectbuddy.com.au`, you can connect it to Netlify for free in Settings → Domain Management.

---

## Need help?
Come back to Claude and say "help me deploy BuddyRun" — I'll walk you through it step by step.
