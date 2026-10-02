# 🚀 Alas Ramus MD v3.0.0

WhatsApp Bot Multi-Device berbasis **ESM Plugins** dengan fitur **Pairing Code**, **Limit System**, dan tampilan menu interaktif. Menggunakan library [@itsliaaa/baileys](https://www.npmjs.com/package/@itsliaaa/baileys).

## ⚡ Fitur Utama
- **ESM & Plugin Case**: Struktur kode modern dan mudah dimodifikasi.
- **Auto Pairing**: Login cukup dengan nomor telepon (tanpa scan QR).
- **Limit System**: Pembatasan command harian untuk user biasa & premium.
- **Interactive Menu**: Menu button dengan header video lokal.
- **Termux Support**: Ringan dan optimal untuk dijalankan di Android.

## 🛠️ Cara Install

### 1. Clone & Install Dependensi
Buka terminal (PC atau Termux) dan jalankan:

```bash
git clone https://github.com/ArdikaOfc/Alas-Ramus-Md.git
cd Alas-Ramus-Md
npm install
```

### 2. Konfigurasi Nomor (Wajib)
Edit file `config.js`. Ubah bagian `pairingNumber` dengan nomor WhatsApp Anda (gunakan kode negara, contoh: `628...`).

```javascript
export const config = {
  pairingNumber: "", // Ganti nomor ini!
  ownerNumber: ["6283115862272"],
  // ...
};
```

### 3. Jalankan Bot
```bash
npm start
```

## 🔑 Cara Pairing
1. Setelah menjalankan `npm start`, bot akan otomatis meminta kode ke WhatsApp.
2. Lihat **Kode 8 Digit** yang muncul di terminal.
3. Buka WhatsApp Anda > **Setelan** > **Perangkat Tertaut** > **Tautkan Perangkat**.
4. Pilih **"Hubungkan dengan nomor telepon"** dan masukkan kode tersebut.

## 📂 Struktur Penting
```text
Alas-Ramus-Md/
├── config.js          # Atur nomor, prefix, dan limit di sini
├── plugins/           # Tambah fitur baru di folder ini
├── lib/               # Sistem inti bot
└── session/           # Data login (jangan dihapus saat bot aktif)
```

## ➕ Cara Tambah Fitur Baru
Buat file `.js` baru di folder `plugins/` dengan format berikut:

```javascript
let handler = async (m, { conn, text }) => {
  m.reply("Halo! Ini fitur baru.");
};

handler.help = ['fiturbaru']
handler.tags = ['General']
handler.command = /^(fiturbaru)$/i
handler.limit = true // Aktifkan limit jika perlu

export default handler
```

## ❓ Troubleshooting
- **Gagal Pairing?** Pastikan nomor di `config.js` benar dan hapus folder `session` lalu restart bot.
- **Error Module?** Jalankan ulang `npm install`.
- **Bot Offline?** Cek koneksi internet dan pastikan Node.js versi >= 20.

---
*Dibuat dengan ❤️ oleh ArdikaOfc Dev*