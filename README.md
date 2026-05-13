# 📱 कॅल्क्युलेटर PWA — संपूर्ण गाइड

## 📁 Files List
```
calculator-pwa/
├── index.html      ← मुख्य App
├── manifest.json   ← PWA settings
├── sw.js           ← Service Worker (offline + update)
└── README.md       ← हे file
```

---

## 🚀 STEP 1 — GitHub वर Upload करा (मोफत Hosting)

1. **github.com** वर जा → Account नाही तर Sign Up करा
2. **New Repository** बनवा → नाव द्या: `calculator-app`
3. **Public** ठेवा
4. तिन्ही files upload करा: `index.html`, `manifest.json`, `sw.js`
5. **Settings → Pages → Branch: main → Save**
6. तुझा App live होईल:
   👉 `https://तुझं-username.github.io/calculator-app/`

---

## 📲 STEP 2 — Mobile वर Install करा

### Android (Chrome):
1. वरील link Chrome मध्ये उघड
2. **⋮ → Add to Home Screen** वर click कर
3. ✅ App install होईल!

### iPhone (Safari):
1. Link Safari मध्ये उघड
2. **Share (□↑) → Add to Home Screen**
3. ✅ Done!

---

## 🔐 STEP 3 — Master Admin Password

- Default Password: **`admin123`**
- App मध्ये **⚙️ बटण** दाब → Password टाक → Login
- **Admin Panel मधून password बदला** (पहिल्यांदाच बदलणे recommended!)

---

## 🔄 STEP 4 — App Update कसं द्यायचं

### Method A — GitHub वरून Update (Recommended):
1. `index.html` मध्ये बदल कर
2. GitHub वर file replace कर (Upload करताना "Commit changes")
3. Users ला automatic banner दिसेल: "नवीन Update आलं आहे!"
4. Click केल्यावर नवीन version install होईल

### Method B — Admin Panel मधून:
1. ⚙️ → Admin Login
2. **Version** टाक (उदा. 1.0.1)
3. **Update Message** टाक (users ला दिसेल)
4. **"Update Push करा"** click कर
5. Users ला banner दिसेल

---

## 🏪 Play Store वर कसं टाकायचं?

### Option A — TWA (Trusted Web Activity) — FREE
PWA असल्यामुळे तुझा app **TWA** म्हणून Play Store वर टाकता येतो.

**Tools:**
- **Bubblewrap** (Google चं tool): https://github.com/GoogleChromeLabs/bubblewrap
- **PWABuilder** (सर्वात सोपं): https://www.pwabuilder.com

**Steps:**
1. pwabuilder.com वर जा
2. तुझा GitHub Pages URL टाक
3. **"Build My PWA"** → Android → Download APK/AAB
4. Google Play Console: **play.google.com/console**
5. Account fee: **$25 (एकदाच)**
6. APK upload करा → Review → Publish!

### Option B — React Native / Flutter (Advanced)
मोठं app बनवायचं असेल तर developer लागेल.

---

## 💡 Tips
- GitHub Pages = **मोफत hosting**
- PWA = **offline** पण काम करतो
- Admin password **नक्की बदला** default पासून
- Version number बदलल्यावर `sw.js` मध्ये `CACHE_NAME` पण बदला

---
**बनवलं: Claude AI सोबत 🤖**
