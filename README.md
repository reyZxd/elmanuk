
# 📚 𝓗𝓮�𝓵𝓵𝓸 𝓤𝓼𝓮𝓻𝓼! 

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Roboto+Mono&size=25&duration=3000&pause=500&color=FF7F50&center=true&vCenter=true&width=435&lines=✨+𝓟𝓾𝓽𝓻𝓪𝓶𝓸𝓭𝓼+𝓗𝓮𝓻𝓮!;🐧+𝓑𝓪𝓲�𝓮𝔂𝓼𝓼+𝓜𝓸𝓭+𝓟�𝓸𝓳𝓮𝓬𝓽;💫+𝓕𝓸𝓻+𝓦𝓱𝓪�𝓼𝓐𝓹𝓹+𝓑𝓸𝓽𝓼" alt="Typing Animation" />
</p>

<p align="center">
  <img src="https://media.tenor.com/5jyI5wXT1tAAAAAC/anime-typing.gif" width="300"/>
</p>

<div align="center">
  
[![Stars](https://img.shields.io/github/stars/PutraWibu/Baileys?style=for-the-badge&logo=reverbnation&color=FF69B4)](https://github.com/PutraWibu/Baileys/stargazers)
[![License](https://img.shields.io/github/license/PutraWibu/Baileys?style=for-the-badge&logo=gnu&color=00FF7F)](https://github.com/PutraWibu/Baileys/blob/main/LICENSE)
[![Node](https://img.shields.io/badge/Node.js-≥14.0-important?style=for-the-badge&logo=node.js)](https://nodejs.org/)

</div>

## 💌 𝓐 𝓛𝓲𝓽𝓽𝓵𝓮 𝓜𝓮𝓼𝓼𝓪𝓰𝓮

- 𝓘 𝓳𝓾𝓼𝓽 𝓶𝓸𝓭𝓭𝓮𝓭 𝓽𝓱𝓲𝓼 𝓯𝓸𝓻 𝓯𝓾𝓷! 
- 𝓐𝓵𝓵 �𝓻�𝓮𝓭𝓲𝓽 𝓰𝓸𝓮𝓼 𝓽𝓸 @𝓚𝓪𝓰𝓮𝓷𝓸𝓾𝓡𝓮𝓪𝓵
+ 𝓥𝓲𝓼𝓲𝓽 𝓸𝓻𝓲𝓰𝓲𝓷𝓪𝓵 𝓬𝓻𝓮�𝓪𝓽𝓸�𝓻: 
! https://github.com/KagenouReal/baileys


---

# 🚀 𝓑𝓪𝓲𝓵𝓮𝔂𝓼 𝓦𝓱𝓪𝓽𝓼𝓐𝓹𝓹 𝓐𝓟𝓘 

<p align="center">
  <img src="https://media.tenor.com/5CbGX1h7Nc0AAAAd/code-anime.gif" width="450"/>
</p>

## 🎯 𝓜𝔂 𝓤𝓷𝓲𝓺𝓾𝓮 𝓐�𝓭�𝓭𝓼

+ 🔓 Pairing Code Support (Customizable!)
+ ⚡ Blazing Fast Response Times
+ 🎨 Extra Message Types
+ 🤖 Better Bot Integration


---

## 🎮 𝓗𝓸𝔀 𝓽𝓸 𝓒𝓾𝓼𝓽𝓸𝓶 𝓟𝓪𝓲𝓻𝓲𝓷𝓰 𝓒𝓸𝓭𝓮

// 𝓒𝓾𝓼𝓽𝓸𝓶𝓲𝔃𝓮 𝔂𝓸𝓾𝓻 𝓟𝓪𝓲𝓻𝓲𝓷𝓰 𝓒𝓸𝓭𝓮!
sock.requestPairingCode(
  phoneNumber.trim(), 
  "𝓨𝓸𝓾𝓻𝓒𝓸𝓸𝓵𝓝𝓪𝓶𝓮" // 8-digit max
);


<p align="center">
  <img src="https://media.tenor.com/2jdR5J0gL_0AAAAC/computer-typing.gif" width="300"/>
</p>

---

## ✨ 𝓕𝓮𝓪𝓽𝓾𝓻𝓮𝓼

<div align="center">
  
| 𝓕𝓮𝓪𝓽𝓾𝓻𝓮 | 𝓓𝓮𝓼𝓬𝓻𝓲𝓹𝓽𝓲𝓸𝓷 |
|----------|-------------|
| 🔐 **No QR Auth** | Session-based login |
| 🚀 **Multi-Device** | Latest MD support |
| 💬 **Rich Messages** | Send all media types |
| 👥 **Group Tools** | Full group management |
| ⚡ **Event System** | Real-time updates |

</div>

---

## 🛠️ 𝓘𝓷𝓼𝓽𝓪𝓵𝓵𝓪𝓽𝓲𝓸𝓷

npm install @PutraWibu/baileys
# 𝓞𝓻
yarn add @PutraWibu/baileys


<p align="center">
  <img src="https://media.tenor.com/0ZR2Bz5iJAMAAAAC/loading-waiting.gif" width="200"/>
</div>

---

## 💻 𝓑𝓪𝓼𝓲𝓬 𝓤𝓼𝓪𝓰𝓮

import { makeWASocket } from '@reyZxd/elmanuk'

const sock = makeWASocket({
  printQRInTerminal: true,
  auth: { 
    creds: state.creds,
    keys: state.keys 
  }
})

sock.ev.on('messages.upsert', async m => {
  console.log('✉️ New message!')
  await sock.sendMessage(m.key.remoteJid, { 
    text: '𝓗𝓮𝔂 𝓽𝓱�𝓻�𝓮! 👋' 
  })
})

---

## 🎨 𝓒𝓸𝓸𝓵 𝓔𝔁𝓪𝓶𝓹𝓵𝓮𝓼

### 𝓢𝓮𝓷𝓭 𝓘𝓷𝓽𝓮𝓻𝓪𝓬𝓽𝓲𝓿𝓮 𝓜𝓮𝓼𝓼𝓪𝓰𝓮
await sock.sendMessage(jid, {
  text: "𝓒𝓱𝓸𝓸𝓼𝓮 𝔂𝓸𝓾𝓻 𝓯𝓪𝓽𝓮!",
  buttons: [
    { 
      buttonId: 'id1', 
      buttonText: { 
        displayText: '⭐ 𝓢𝓽𝓪𝓻 𝓜𝓮!' 
      }, 
      type: 1 
    }
  ],
  headerType: 1
})


<p align="center">
  <img src="https://media.tenor.com/9LQwAdRz1jYAAAAC/anime-message.gif" width="300"/>
</p>



## 🤝 𝓒𝓸𝓷𝓽𝓻𝓲𝓫𝓾𝓽𝓲𝓷𝓰

𝓕𝓮𝓮𝓵 𝓯𝓻𝓮𝓮 𝓽𝓸:
1. 🍴 Fork this repo
2. 🌿 Create new branch
3. 📦 Make your changes
4. 🔄 Open a PR

<p align="center">
  <img src="https://media.tenor.com/1bN1lZmbwWAAAAAC/anime-phone.gif" width="200"/>
</p>

---

## 📮 𝓒𝓸𝓷𝓽�𝓪𝓬𝓽

<div align="center">

| 𝓒𝓻𝓮𝓪𝓽𝓸𝓻 | 𝓒𝓸𝓷𝓽𝓪𝓬𝓽 |
|----------|-------------|
| @KagenouReal | kagenoureal@gmail.com |
| @PutraMods | putramodss@gmail.com |
| @ReyZxd | queenmwmwk123@gmail.com |

</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=60&section=footer&text=𝓢𝓮𝓮 𝔂𝓸𝓾 𝓷𝓮𝔁𝓽 𝓽𝓲𝓶𝓮!&fontSize=20"/>
</p>
