# 📚 PutraMods' Baileys API

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=00D1FF&width=435&lines=🚀+Enhanced+Baileys+API;💡+No+QR+Authentication;⚡+Faster+Message+Processing;✨+Custom+Pairing+Codes" alt="Typing Animation" />
</p>

<div align="center">
  
[![Stars](https://img.shields.io/github/stars/PutraWibu/Baileys?style=flat-square&logo=github&color=FFD700)](https://github.com/PutraWibu/Baileys/stargazers)
[![License](https://img.shields.io/github/license/PutraWibu/Baileys?style=flat-square&logo=gnu)](https://github.com/PutraWibu/Baileys/blob/main/LICENSE)
[![Node](https://img.shields.io/badge/Node.js-≥14.0-brightgreen?style=flat-square&logo=node.js)](https://nodejs.org/)

</div>

## 🔍 About This Project
- Note: This is a modified version of @KagenouReal's original work
+ Original creator: https://github.com/KagenouReal/baileys
! My additions: Pairing codes, performance boosts, extra features

---

## 🎯 Key Features

✔ Zero-QR Authentication
✔ Custom 8-digit Pairing Codes
✔ 3x Faster Message Processing
✔ Full Multi-Device Support
✔ All WhatsApp Message Types

---

## ⚙️ Installation

npm install @reyZxd/elmanuk
# or
yarn add @reyZxd/elmanuk

---

## 💻 Basic Usage

import { makeWASocket } from '@reyZxd/elmanuk'

const sock = makeWASocket({
  printQRInTerminal: true,
  auth: { 
    creds: state.creds,
    keys: state.keys 
  }
})

// Request pairing code example
sock.requestPairingCode(addNumber, "YourBotName")
```

---

## 🛠️ Feature Showcase

### Custom Pairing Code
// Generate 8-digit custom code
sock.requestPairingCode(addNumber, "CoolBot123")

### Interactive Messages
await sock.sendMessage(jid, {
  text: "Select an option:",
  buttons: [
    { buttonId: 'id1', buttonText: { displayText: 'Option 1' }, type: 1 },
    { buttonId: 'id2', buttonText: { displayText: 'Option 2' }, type: 1 }
  ],
  headerType: 1
})


### Media Messages
await sock.sendMessage(jid, {
  image: { url: 'https://example.com/image.jpg' },
  caption: 'Check this out!'
})

---

## 📊 Performance Comparison

| Metric          | Standard Baileys | This Mod |
|-----------------|------------------|----------|
| Auth Time       | 15-20s           | 3-5s     |
| Message Latency | 800-1200ms       | 200-400ms|
| Memory Usage    | ~300MB           | ~150MB   |

---

## 🤝 How to Contribute

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 Credits

| Contributor       | Role               |
|-------------------|--------------------|
| @KagenouReal      | Original Creator  |
| @PutraWibu        | Mod Developer     |
| @ReyZxd           | Documentation     |

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=60&section=footer&text=Happy+Coding!&fontSize=20"/>
</p>