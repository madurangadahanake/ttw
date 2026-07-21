# <p align="center">✨ <code>TTW</code> — Time to Work ✨</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=24&duration=3000&pause=1000&color=00F0FF&center=true&vCenter=true&width=500&lines=NEXT-GEN+PRODUCTIVITY+TIMER;CYBERPUNK+DEEP-SPACE+THEME;PRECISION+TIME+TRACKING" alt="Typing Banner" />
</p>

<p align="center">
  <em>Level up your focus, master your downtime, and dominate your overtime.</em>
</p>

<p align="center">
  <a href="#-about-the-project"><img src="https://img.shields.io/badge/VERSION-1.0.0-00f0ff?style=for-the-badge&logo=codeforces&logoColor=white" alt="Version"></a>
  <a href="#-key-features"><img src="https://img.shields.io/badge/THEME-CYBERPUNK%20SPACE-ff007f?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Theme"></a>
  <a href="#-tech-stack"><img src="https://img.shields.io/badge/ENGINE-VANILLA%20JS-7000ff?style=for-the-badge&logo=javascript&logoColor=white" alt="Engine"></a>
  <a href="#-local-storage-matrix"><img src="https://img.shields.io/badge/STORAGE-OFFLINE%20SYNC-00ffcc?style=for-the-badge&logo=databricks&logoColor=white" alt="Storage"></a>
</p>

<br>

<p align="center">
  <a href="#-about-the-project"><b>Overview</b></a> •
  <a href="#-key-features"><b>Features</b></a> •
  <a href="#-tech-stack"><b>Tech Stack</b></a> •
  <a href="#-status-panel-breakdown"><b>Metrics</b></a> •
  <a href="#-local-storage-matrix"><b>Storage Sync</b></a> •
  <a href="#-getting-started"><b>Quick Start</b></a>
</p>

---

## 🌌 Overview

**TTW (Time to Work)** කියන්නේ නිකම්ම නිකන් Countdown Timer එකක් නෙමෙයි. මේක **Deep Space & Cyberpunk Aesthetic** එකකින් නිර්මාණය වුණු Ultra-Modern Focus & Productivity Web Application එකක්.

ඔයා වැඩ කරන **Focus Time**, Breaks සඳහා ගන්නා **Stop Time** සහ Target එක අවසන් වූ පසු නොනැවතී සටහන් වන **Overtime** එක ඉතා නිවැරදිව (Precision Analytics) එකම Dashboard එකකින් Track කිරීමට මෙය උපකාරී වේ.

> 💡 **Why TTW?**  
> වැඩක් කරද්දී ගන්නා Breaks නිසා මුළු කාලය අපතේ යනවාද? TTW එකෙන් ඔයා Stop කරගෙන සිටින සෑම තත්පරයක්ම සටහන් කරන නිසා, ඔයාගේ Productivity එක 100% ක්ම Control කරගන්න පුළුවන්!

---

## ⚡ Key Features

```text
 ┌──────────────────────────────────────────────────────────┐
 │ 🌌 Dynamic Starfield   • Interactive HTML5 Canvas Render │
 │ 🎯 Target Countdown    • Custom HH:MM:SS Precision Timer  │
 │ 🛑 Stop Tracker        • Downtime & Break Time Counter   │
 │ 💖 Neon Pink Overtime  • Automatic Dynamic Mode Switch   │
 │ 💾 Offline Persistence • Real-time LocalStorage State    │
 └──────────────────────────────────────────────────────────┘
```

* **🌌 Interactive Canvas Starfield:** Background එකේ සජීවීව වෙනස් වන RGB Glowing Stars Animation එකක් ක්‍රියාත්මක වේ.
* **🎯 Precision Countdown System:** වැඩ සඳහා නියමිත කාලය පැය, මිනිත්තු, තත්පර වලින් පහසුවෙන්ම සකසා ගත හැක.
* **🛑 Total Downtime Tracking:** Stop බටන් එක එබූ සැනින්, ඔයා Break එකේ කොපමණ වෙලාවක් ගත කළාද යන්න **Total Stopped** ලෙස වෙනම ගණනය වේ.
* **⚡ Seamless Overtime Mode:** Target එක 00:00:00 වූ පසු ටයිමරය නවතින්නේ නැත! එය ස්වයංක්‍රීයව Neon Pink Glow Theme එකකට මාරු වී **Overtime (+HH:MM:SS)** ලෙස එකතු වේ.
* **💾 Smart LocalStorage Persistence:** Tab එක Refresh කළද, වෙනත් App එකකට ගියද, නැවත පැමිණෙන විට ටයිමරයේ දත්ත අහිමි නොවේ.
* **📱 Responsive Glassmorphism UI:** Mobile, Tablet, සහ Desktop ඕනෑම Screen එකකට ගැලපෙන Digital Numbers Font එකක් සහිත Futuristic Glass UI එකක්.

---

## 🛠️ Tech Stack

<div align="center">

| Component | Technology / Library | Description |
| :--- | :--- | :--- |
| **Structure** | `HTML5` | Semantic elements & Canvas host |
| **Styling** | `CSS3` | Glassmorphism, Neon Glow Effects, Animations |
| **Engine** | `Vanilla JavaScript` | State machine, Interval handlers, LocalStorage sync |
| **Graphics** | `HTML5 Canvas API` | Dynamic particle starfield background |
| **Typography** | `Digital Numbers Font` | Retro Digital Clock Display Aesthetic |

</div>

---

## 📊 Status Panel Breakdown

 dashboard එකේ පහළින් පෙනෙන සජීවී තොරතුරු පුවරුව පිළිබඳ විස්තරය:

```
+------------------+--------------------------------------------------------+
| Metric Label     | Live Description                                       |
+------------------+--------------------------------------------------------+
| Target Time      | ඔයා ආරම්භයේදී Set කළ මුළු ඉලක්කගත කාලය.               |
| Total Elapsed    | ගතවූ සමස්ත කාලය (Counted Time + Overtime).              |
| Total Stopped    | වැඩ අතරතුර Stop කර තිබූ මුළු කාලය (Break Time).         |
| Overtime (අමතර)  | Target එක අවසන් වූ පසු අමතරව වැඩ කළ කාලය (+00:00:00).   |
+------------------+--------------------------------------------------------+
```

---

## 💾 Local Storage Matrix

Browser එක ඇතුළේ දත්ත සුරක්ෂිතව පවත්වා ගැනීමට භාවිතා වන Key Structure එක:

```json
{
  "ttw_initial": "Target duration in seconds",
  "ttw_current": "Remaining countdown seconds",
  "ttw_stop_seconds": "Accumulated downtime seconds",
  "ttw_is_stopped": "Boolean status flag (true/false)",
  "ttw_is_overtime": "Boolean status flag (true/false)",
  "ttw_overtime_seconds": "Accumulated overtime seconds"
}
```

---

## 🚀 Getting Started

1. **Clone or Download:** Repository එක Clone කරගන්න නැතහොත් `index.html` ෆයිල් එක බාගන්න.
2. **Open in Browser:** `index.html` ෆයිල් එක මත Double Click කර ඕනෑම Modern Web Browser එකකින් Open කරගන්න.
3. **Set & Launch:** Target Time එක ලබාදී **Start Timer** ක්ලික් කර ඔයාගේ Supercharged Focus Session එක ආරම්භ කරන්න!

---

<p align="center">
  <sub>Built with Passion for Ultimate Productivity & Minimalist Design ✨</sub>
</p>
