# 🎂 Birthday Reveal

<div align="center">

```
 ██████╗ ██╗██████╗ ████████╗██╗  ██╗██████╗  █████╗ ██╗   ██╗
 ██╔══██╗██║██╔══██╗╚══██╔══╝██║  ██║██╔══██╗██╔══██╗╚██╗ ██╔╝
 ██████╔╝██║██████╔╝   ██║   ███████║██║  ██║███████║ ╚████╔╝
 ██╔══██╗██║██╔══██╗   ██║   ██╔══██║██║  ██║██╔══██║  ╚██╔╝
 ██████╔╝██║██║  ██║   ██║   ██║  ██║██████╔╝██║  ██║   ██║
 ╚═════╝ ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═════╝ ╚═╝  ╚═╝   ╚═╝
              R E V E A L  ✨
```

**Create magical birthday experiences with scannable QR codes**

[🚀 Live Demo](https://crowfly22.github.io/birthday-reveal/) · [Report Bug](https://github.com/crowfly22/birthday-reveal/issues)

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

</div>

---

## ✨ How It Works

1. **Create** — Enter name, birthday message, pick a theme
2. **Generate** — Get a QR code with the surprise embedded
3. **Share** — Print the QR, send it, or put it on a gift
4. **Reveal** — When scanned, reveals a full interactive birthday experience!

## 🎯 Features

- **🎨 8 Beautiful Themes** — Sparkle, Galaxy, Sakura, Ocean, Sunset, Forest, Candy, Royal
- **📱 QR Code Generator** — Download QR image, share link
- **🎊 Confetti Explosions** — Canvas-based particle effects
- **🎵 Birthday Melody** — Web Audio API generated music
- **💝 Wish Cards** — Tap-to-reveal surprise wishes
- **🎂 Blow Candles** — Interactive cake with candle blowing
- **✨ Floating Particles** — Theme-matched ambient particles
- **📝 Personal Messages** — Custom name, age, message, sender
- **🔗 URL Hash Encoding** — All data encoded in URL (no server needed)
- **📲 Mobile First** — Optimized for phone screens

## 🚀 Quick Start

```bash
git clone https://github.com/crowfly22/birthday-reveal.git
cd birthday-reveal
open index.html
```

**Zero dependencies. Zero backend. Just open `index.html`.**

## 🏗️ Architecture

```
Single HTML File (~28KB)
├── Creator Mode
│   ├── Name / Age / Message / From inputs
│   ├── 8 Theme selector (emoji grid)
│   ├── 5 Wish card inputs
│   └── QR Code generator (custom minimal impl)
├── Reveal Mode
│   ├── Tap-to-start overlay
│   ├── Animated name + age reveal
│   ├── Quote/message fade-in
│   ├── Tap-to-reveal wish cards
│   ├── Interactive cake + candle blowing
│   └── Final love message
├── Audio Engine
│   ├── Web Audio API oscillator tones
│   └── Happy Birthday melody
└── Visual Engine
    ├── Canvas background gradients
    ├── Floating particle system
    └── Confetti explosion system
```

## 🎨 Themes

| Theme | Vibe | Colors |
|-------|------|--------|
| ✨ Sparkle | Classic celebration | Gold, Pink, Purple, Cyan |
| 🌌 Galaxy | Cosmic wonder | Cyan, Purple, Pink, Lavender |
| 🌸 Sakura | Japanese cherry blossom | Pink, Rose, Blush |
| 🌊 Ocean | Deep sea calm | Cyan, Teal, Aqua |
| 🌅 Sunset | Warm golden hour | Orange, Amber, Red, Gold |
| 🌿 Forest | Nature peace | Green, Lime, Gold |
| 🍬 Candy | Sweet & playful | Hot Pink, Magenta, Orchid |
| 👑 Royal | Elegant & regal | Gold, Dark Gold, Purple |

## ⚠️ Disclaimer

This is a fun project for personal celebrations. All data is stored in the URL hash only — nothing is sent to any server.

---

<div align="center">

**Powered by MiMo V2.5 Pro** · Built with ❤️ by [crowfly22](https://github.com/crowfly22)

</div>
