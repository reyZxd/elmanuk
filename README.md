<!-- GITHUB SULTAN STYLE README -->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&multiline=true&width=435&lines=Welcome+to+Elmanuk+Repo+by+ReyZxd!;Baileys+API+Bot+Power+Up!+🚀" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://media.tenor.com/Qc6v_Ft8zOQAAAAC/anime-hacker.gif" width="400"/>
</p>

<p align="center">
  <a href="https://github.com/reyZxd">
    <img src="https://img.shields.io/github/followers/reyZxd?label=Follow&style=social" alt="GitHub Followers" />
  </a>
  <img src="https://img.shields.io/github/stars/reyZxd/elmanuk?style=social" alt="GitHub Stars" />
  <img src="https://img.shields.io/badge/Maintained-Yes-brightgreen" />
  <img src="https://img.shields.io/badge/Baileys-Custom-red?style=flat&logo=whatsapp" />
  <img src="https://img.shields.io/badge/Made%20With-Termux-blueviolet?logo=gnu-bash" />
</p>

---

# 🐔 EL-MANUK BAILEYS API BOT

> Dibikin iseng buat ngulik WhatsApp API — Full custom, smooth, dan pastinya beda!  
> 🔧 Based dari project kerennya **@KagenouReal** — semua kredit tetap ke dia ya!  
> 💌 Recode & edit by **ReyZxd** – biar makin 🔥

---

## 🖼️ Preview Keren

![Preview](https://media.tenor.com/qD9Qbd1GxVIAAAAC/hacker-anime.gif)

---

## ✨ Fitur Khusus

- ✅ **Custom Pairing Code** (tanpa scan QR lagi!)
- ✅ Kirim pesan interaktif canggih (card, shop, poll, album, dll)
- ✅ Otomatisasi grup, broadcast, dan lain-lain
- ✅ Lebih ringan dan cepat dari Baileys biasa
- ✅ Dukungan `Multi-Device` dan `ViewOnce`

---

## 🧠 Cara Pakai

```bash
npm install github:PutraWibu/baileys
```

Lalu buat file koneksi:

```js
import makeWASocket from "@PutraWibu/baileys"

const sock = makeWASocket({
  printQRInTerminal: true
})

// Connect seperti biasa
```

---

## 🎯 Contoh Fitur Interaktif

```ts
sock.sendMessage(m.chat, {
    text: "Hello!",
    footer: "Powered by Elmanuk",
    buttons: [
      { buttonId: ".help", buttonText: { displayText: "HELP" }, type: 1 }
    ],
    headerType: 1
}, { quoted: m })
```

---

## ⚡ Glitch Banner

```diff
+  ███████╗██╗     ███╗   ███╗ █████╗ ███╗   ██╗██╗   ██╗██╗  ██╗
+  ██╔════╝██║     ████╗ ████║██╔══██╗████╗  ██║██║   ██║╚██╗██╔╝
+  ███████╗██║     ██╔████╔██║███████║██╔██╗ ██║██║   ██║ ╚███╔╝
+  ╚════██║██║     ██║╚██╔╝██║██╔══██║██║╚██╗██║██║   ██║ ██╔██╗
+  ███████║███████╗██║ ╚═╝ ██║██║  ██║██║ ╚████║╚██████╔╝██╔╝ ██╗
+  ╚══════╝╚══════╝╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝  ╚═╝
```

---

## 🙏 Kredit

- 👤 Creator Asli: [@KagenouReal](https://github.com/KagenouReal)
- 💻 Mod by: [@ReyZxd](https://github.com/reyZxd)

---

## 🧩 Kontak

📫 Email: rey.zxdmods@gmail.com  
🌐 Web: [soon]

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=1000&center=true&vCenter=true&multiline=true&width=435&lines=Thanks+for+visiting!+%F0%9F%91%8B" />
</p>
