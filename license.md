# ⏱️ Toastmasters Speech Timer

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,3,18&height=210&section=header&text=Toastmasters%20Speech%20Timer&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Every%20Second%20Tells%20Your%20Story&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.0.0-800F2F?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Web%20%7C%20Mobile%20%7C%20PWA-A4133C?style=for-the-badge&logo=pwa&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-FFB3C1?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Timing](https://img.shields.io/badge/±0.01s%20precision-FF4D6D?style=for-the-badge&logo=clockify&logoColor=white)](https://github.com)

<br/>

### 🎤 A precision timer built for Toastmasters clubs, speakers & evaluators

*🟢 Green • 🟡 Yellow • 🔴 Red • 🔔 Bell Alerts • 📊 Speech Reports*

<br/>

<a href="https://share.google/IQjNBEcAJ6guNsGWd">
  <img src="https://img.shields.io/badge/🚀_OPEN_TIMER-800F2F?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=590A21" alt="Open Timer" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/IQjNBEcAJ6guNsGWd">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_APP-A4133C?style=for-the-badge&logo=pwa&logoColor=white&labelColor=6E0D28" alt="Download App" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/IQjNBEcAJ6guNsGWd">
  <img src="https://img.shields.io/badge/📚_GUIDE-FF4D6D?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=CC3E57" alt="Guide" height="45"/>
</a>

</div>

<img width="1672" height="941" alt="7219e7d1-ed6b-45f8-a4f1-e3563e430567" src="https://github.com/user-attachments/assets/a8aa57f3-d7ac-48b0-af8f-4931a1cadfe3" />

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Toastmasters Speech Timer** is a clean, distraction-free timer designed **exactly** for the Toastmasters timing format. It displays the classic **green-yellow-red** color signals, plays gentle chimes at each threshold, and helps speakers and evaluators keep every speech **on time and on point**.

Works beautifully on a laptop on the timer's table, a projector for the whole room, or a tablet in the speaker's view — no installation required.

> 💡 **The Toastmasters color system:** 🟢 **Green** = minimum time reached. 🟡 **Yellow** = you're in the target range — start wrapping up. 🔴 **Red** = maximum time — finish now!

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🟢 **Color Signals** | 🔔 **Bell Alerts** | ⏱️ **Precision** |
|:---:|:---:|:---:|
| Classic green, yellow<br/>& red indicators | Custom chimes at<br/>each threshold | ±0.01s accuracy<br/>with drift correction |

| 📊 **Speech Reports** | 🎛️ **Custom Timings** | 📱 **Works Everywhere** |
|:---:|:---:|:---:|
| Export timing summary<br/>for the evaluator | Icebreaker, Table Topics,<br/>any speech type | Web, mobile<br/>& PWA install |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Timer

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🎯 **Toastmasters-Native** | Built with the official timing rules — no manual setup needed for standard speeches |
| 🎨 **Distraction-Free UI** | Huge, high-contrast display readable from across any room |
| 🔔 **Gentle Alerts** | Configurable chimes — subtle for small clubs, loud for big halls |
| 📊 **Evaluator-Ready Reports** | Export a clean timing summary to attach to evaluation forms |
| 🌐 **Offline First** | Works fully offline once loaded — perfect for venues with poor Wi-Fi |
| 🎛️ **Fully Customizable** | Adjust any speech type: Icebreaker, Evaluations, Table Topics, and more |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Timer in Action

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  ⏱️  Toastmasters Speech Timer  v2.0.0           ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║              🎤 Prepared Speech                  ║
║                                                  ║
║                00:05:32                          ║
║                                                  ║
║           ┌───────────────────┐                  ║
║           │  🟡  YELLOW ZONE  │                  ║
║           └───────────────────┘                  ║
║                                                  ║
║   Green   5:00   ✅ passed                       ║
║   Yellow  6:00   ⏳ in range — wrap up soon      ║
║   Red     7:00   🔔 bell at max                  ║
║                                                  ║
║   [ ⏸ Pause ]  [ 🔔 Reset ]  [ 📊 Report ]      ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
⏱️ toastmasters-speech-timer/
├── 🎨 src/
│   ├── components/            # UI components
│   │   ├── Timer.tsx
│   │   ├── ColorSignal.tsx
│   │   └── Report.tsx
│   ├── hooks/                 # Timer & audio hooks
│   ├── config/                # Speech timing presets
│   └── utils/                 # Time formatting
├── 🎯 public/
│   ├── sounds/                # Bell & chime audio
│   └── icons/                 # PWA assets
├── 🧪 tests/                  # Vitest & Playwright
└── 📖 docs/                   # Usage & timing rules
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Using this timer in your club? Have a feature idea? Let us know!

<div align="center">

<a href="https://share.google/IQjNBEcAJ6guNsGWd">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/IQjNBEcAJ6guNsGWd">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-FF4D6D?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/IQjNBEcAJ6guNsGWd">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-800F2F?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 🎤 Made with ⏱️ by the Speech Timer Team

*Helping speakers stay on time, one speech at a time.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,3,18&height=120&section=footer" width="100%"/>

</div>

---
