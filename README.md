 <p align="center">⏱️ TTW - Time to Work 🌌</p>

<p align="center">
  <strong>A Futuristic, Cyberpunk-themed Work & Productivity Timer Web Application</strong><br>
  <em>Track focused work sessions, downtime, and overtime seamlessly with high precision.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-00f0ff?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/Platform-Web%20Browser-ff007f?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/Storage-Local%20Storage-7000ff?style=for-the-badge" alt="Local Storage">
  <img src="https://img.shields.io/badge/UI-Cyberpunk%20Space-00ffcc?style=for-the-badge" alt="Theme">
</p>

<p align="center">
  <a href="#-about-the-project">About</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-technologies-used">Technologies</a> •
  <a href="#-how-it-works">How It Works</a> •
  <a href="#-local-storage-keys">Storage Keys</a> •
  <a href="#-getting-started">Getting Started</a>
</p>

---

## 🌟 About the Project

**TTW (Time to Work)** යනු කාර්යක්ෂමව වැඩ කරන කාලය (Focus Time), නවතා තබන කාලය (Break/Stop Time) සහ අමතරව වැඩ කරන කාලය (Overtime) නිරීක්ෂණය කිරීම සඳහා නිර්මාණය කරන ලද නවීන Web App එකකි.

එදිනෙදා වැඩ කටයුතු හෝ Study sessions වලදී ලබාගන්නා Breaks පිළිබඳව නිවැරදි සටහනක් පවත්වා ගැනීමටත්, නියමිත ඉලක්කය අවසන් වූ පසු අමතරව වැඩ කරන කාලය (+Overtime) Neon Pink පැහැයෙන් පැහැදිලිව වෙනස් වී පෙන්වීමටත් මෙහි හැකියාව ඇත.

---

## ✨ Key Features

- 🌌 **Cyberpunk & Deep Space Theme:** HTML5 Canvas මගින් dynamic interactive starfield animation එකක් සහ Glowing RGB gradients අඩංගු කර ඇත.
- 🎯 **Target Time Countdown:** පැය, මිනිත්තු, තත්පර අනුව තමන්ගේ වැඩ කිරීමේ ඉලක්කය සකස් කිරීමේ පහසුකම.
- 🛑 **Total Stop Tracker:** "Stop" බටන් එක එබූ විට, තමන් කොපමණ වේලාවක් Break එකක් ලබාගෙන ඇත්දැයි වෙනමම සටහන් වන "Total Stopped" ටයිමරය.
- ➕ **Automatic Overtime Switch:** Target කාලය අවසන් වූ පසු ටයිමරය නතර නොවී, සජීවීව **Overtime Phase** එකකට මාරු වී අමතර කාලය ගණනය කිරීම.
- 💾 **State Persistence (LocalStorage):** Page එක Refresh කළද හෝ Browser එක close කළද ටයිමරයේ දත්ත අහිමි නොවන Persistent State පද්ධතිය.
- 📱 **Fully Responsive Layout:** Mobile, Tablet, සහ Desktop වැනි ඕනෑම Screen Size එකකට සහ Digital Font Display එකකට ගැලපෙන ලෙස සකසා තිබීම.

---

## 🛠️ Technologies Used

- **HTML5:** Semantic structural setup.
- **CSS3:** Custom Animations, Glassmorphism Backdrop Filters, Cyberpunk Neon Glow Effects, Flexbox.
- **Vanilla JavaScript (ES6+):** Timer State Logic, LocalStorage Sync, HTML5 Canvas Rendering.
- **Google / CDN Fonts:** Digital Numbers Font for Retro Display look.

---

## 📊 Status Panel Logic

| Metric | Description |
| :--- | :--- |
| **Target Time** | ඔබ ආරම්භයේදී සකස් කළ මුළු ඉලක්කගත කාලය. |
| **Total Elapsed** | මෙතෙක් ගතවූ සමස්ත කාලය (Initial Countdown + Overtime). |
| **Total Stopped** | වැඩ කටයුතු නවතා (Stopped) තැබූ සමස්ත කාලය. |
| **Overtime (අමතර කාලය)** | Target එක ඉක්මවා වැඩ කළ අමතර කාලය (Pink Glow Theme එකෙන් පෙන්නුම් කරයි). |

---

## 💾 Local Storage Keys

ටයිමරයේ දත්ත නොමැකී පවත්වා ගැනීමට පහත Storage Keys භාවිත වේ:

- `ttw_initial`: ආරම්භක target කාලය (තත්පර වලින්).
- `ttw_current`: දැනට ඉතිරිව ඇති target කාලය.
- `ttw_stop_seconds`: Stop කර තැබූ සමස්ත කාලය.
- `ttw_is_stopped`: Stop state එකේ පවතින්නේද යන්න (`true`/`false`).
- `ttw_is_overtime`: Overtime state එකේ පවතින්නේද යන්න (`true`/`false`).
- `ttw_overtime_seconds`: Overtime ලෙස ගතවූ කාලය.

---

## 🚀 Getting Started

1. මෙම Repository එක Clone කරගන්න හෝ `index.html` ෆයිල් එක Download කරගන්න.
2. `index.html` ෆයිල් එක ඕනෑම Web Browser එකකින් (Chrome, Firefox, Edge, Safari) Open කරගන්න.
3. ඉලක්කගත කාලය (HH : MM : SS) සටහන් කර **Start Timer** ලබා දී ඔබේ වැඩ කටයුතු ආරම්භ කරන්න!

---

<p align="center">
  Crafted with ❤️ for Productivity Enthusiasts!
</p>
