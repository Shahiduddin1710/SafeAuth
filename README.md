# 🛡️ SafeAuth - Your Personal 2FA Authenticator

**100% your code. Free to deploy. Works on Android as a native-like app.**

---

## 📱 How to Install on Android (Free - No App Store needed)

### Option 1: Deploy on GitHub Pages (FREE)
1. Create a free account at [github.com](https://github.com)
2. Create a new repository (e.g. `safeauth`)
3. Upload `index.html` and `manifest.json` to the repo
4. Go to **Settings → Pages → Source → main branch**
5. Your app will be live at: `https://YOUR-USERNAME.github.io/safeauth`
6. Open that URL in Chrome on Android
7. Tap the **"Add to Home Screen"** prompt (or Menu → Add to Home Screen)
8. SafeAuth is now installed like a native app! ✅

### Option 2: Deploy on Netlify (FREE)
1. Go to [netlify.com](https://netlify.com) → Sign up free
2. Drag & drop the `safeauth` folder onto the Netlify dashboard
3. Get your live URL instantly
4. Open in Android Chrome → Add to Home Screen

### Option 3: Run Locally (Offline)
- Just open `index.html` directly in Chrome on Android
- Or use VS Code Live Server on PC

---

## ✅ Features
- 🔐 TOTP (RFC 6238) — same standard as Google Authenticator
- 📷 QR Code scanner (uses camera)
- ⌨️ Manual secret key entry
- 🔄 Auto-refreshing OTP every 30 seconds
- ⏱️ Countdown ring timer
- 📋 Tap to copy OTP
- 🗂️ Categories (Work, Social, Finance, Uncategorized)
- 🔍 Search accounts
- 💾 Export/Import backup (JSON)
- 📱 PWA — installable on Android like a native app
- 🔒 All data stored locally on YOUR device (no server)

---

## 🔒 Privacy
- **No data ever leaves your device**
- All secrets stored in browser localStorage
- No backend, no accounts, no tracking

---

## 🛠️ Tech Stack
- Vanilla HTML/CSS/JavaScript
- Web Crypto API (for HMAC-SHA1)
- jsQR library (for QR scanning)
- localStorage (for data persistence)

---

## 👑 Ownership
This code is entirely yours. No license restrictions.
Do whatever you want with it — modify, redistribute, sell.

---

Made with ❤️ — Your personal SafeAuth clone
