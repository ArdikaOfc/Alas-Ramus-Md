# 🤖 Alas Ramus MD V3.0.0

<div align="center">

**Bot WhatsApp Multi-Device yang tangguh, kaya fitur, dan mudah digunakan.**

Dibuat dengan ❤️ oleh **[ArdikaOfc](https://github.com/ArdikaOfc)**

[![Node.js](https://img.shields.io/badge/Node.js-v18%2B-green?logo=node.js)](https://nodejs.org/)
[![Baileys](https://img.shields.io/badge/Library-Baileys-blue)](https://github.com/WhiskeySockets/Baileys)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## 📌 Tentang Bot

**Alas Ramus MD** adalah skrip bot WhatsApp berbasis *Multi-Device* (MD) yang dirancang untuk membantu mengelola grup, mengunduh media, hiburan, hingga kebutuhan transaksi otomatis.

---

## 🔗 Komunitas & Kontak Resmi

* **Website Official**: [ardikastore.ct.ws](https://ardikastore.ct.ws/)
* **WhatsApp Owner**: [Contact Owner (+62 831-1586-2272)](https://wa.me/6283115862272)
* **Grup WhatsApp**: [Gabung Grup WhatsApp](https://chat.whatsapp.com/EaRrgHUqb6p2G2XajDqAsY)
* **Saluran WhatsApp**: [Ikuti Saluran Official](https://whatsapp.com/channel/0029VaF9C4zId7nOTFF8ZK0v)

---

## ✨ Fitur Utama

* 📥 **Downloader**: TikTok, YouTube (MP3/MP4), Instagram, Spotify, Facebook, DLL.
* 🎨 **Maker & Sticker**: Buat stiker otomatis, meme, *brat*, text-to-image.
* 👥 **Group Management**: Kick, add, promote, demote, anti-link, anti-toxic, welcome message.
* 🤖 **AI Support**: Integrasi ChatGPT, Gemini, DALL-E, dan Voice AI.
* 🎮 **Fun & Games**: Tebak gambar, kuis, RPG game sederhana, TTS.
* 🛠️ **Tools & Utility**: Translate, cuaca, SSWeb, Remini (HD image enhancement), QR code maker.

---

## ⚡ Persyaratan Sistem

Sebelum menjalankan bot ini, pastikan Anda telah menginstal:

* [Node.js](https://nodejs.org/) (Versi 20 atau lebih baru)
* [Git](https://git-scm.com/)
* [FFmpeg](https://ffmpeg.org/) (Untuk konversi media & stiker)

---

## 🚀 Cara Instalasi

### 1. Clone Repositori
```bash
git clone https://github.com/ArdikaOfc/Alas-Ramus-MD.git
cd Alas-Ramus-MD
```

### 2. Instal Dependensi
```bash
npm install
```

### 3. Konfigurasi
Buka file `config.js` (atau file pengaturan Anda) dan sesuaikan data berikut:
* **Nomor Owner**: `6283115862272`
* **Nama Bot**: `Alas Ramus MD`
* **Prefix**: Sesuaikan prefix yang ingin digunakan (contoh: `.`, `/`, `!`).

### 4. Jalankan Bot
```bash
npm start
```
> Scan kode QR atau masukkan **Pairing Code** yang muncul di terminal untuk menghubungkan WhatsApp.

---

## 📱 Panduan Instalasi di Termux (Android)

Jika ingin menjalankan bot langsung dari HP Android menggunakan Termux:

```bash
pkg update && pkg upgrade -y
pkg install git -y && plg install nodejs -y && plg install ffmpeg -y
git clone https://github.com/ArdikaOfc/Alas-Ramus-MD.git
cd Alas-Ramus-MD
npm install
npm start
```

---

## 📂 Struktur Folder

```Alas Ramus Md
├── config.js          
├── index.js           
├── media
│      ├── allmenu.mp4
│      └── menu.mp4
├── plugins
│       ├── ai-copilot.js
│       ├── main-allmenu.js
│       ├── main-menu.js
│       ├── sticker-brat.js
│       ├── yt-yta.js
│       └── yt-ytv.js
├── handler.js
├── package.json
├── lib/               
├── READMI.md
├── src
├── tmp
└── database/          
```

---

## 🤝 Kontribusi

Saran, perbaikan *bug*, dan ide fitur baru sangat dialu-alukan! 
1. *Fork* repositori ini
2. Buat *branch* fitur baru (`git checkout -b fitur-baru`)
3. *Commit* perubahan Anda (`git commit -m 'Menambahkan fitur X'`)
4. *Push* ke *branch* (`git push origin fitur-baru`)
5. Buat **Pull Request**

---

## 👨‍💻 Pembuat & Hak Cipta

* **Developer**: [ArdikaOfc](https://github.com/ArdikaOfc)
* **Proyek**: Alas Ramus MD

---

## 📜 Lisensi

Proyek ini dilindungi di bawah lisensi **MIT**. Lihat file `LICENSE` untuk informasi lebih lanjut.
