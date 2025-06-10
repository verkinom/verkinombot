# VerkinomBot - Bot WhatsApp

Bot WhatsApp sederhana untuk manajemen pembuatan akun website. Dibuat dengan Node.js dan TypeScript.

## Fitur
- Pembuatan akun otomatis
- Informasi bot
- Sistem bantuan

## Prasyarat
- Node.js v14 atau lebih tinggi
- npm atau yarn
- Chrome/Chromium (untuk WhatsApp Web)

## Cara Install

### Windows
1. Clone repository
```bash
git clone https://github.com/verkinom/verkinombot.git
```

2. Install dependencies
```bash
npm install
```

3. Jalankan bot
```bash
npm run dev
```

### Android (Termux)
1. Install Termux dari F-Droid
2. Buka Termux dan jalankan perintah berikut:
```bash
termux-setup-storage
pkg update && pkg upgrade -y
pkg install nodejs-lts git chromium -y
```

3. Clone repository
```bash
git clone https://github.com/verkinom/verkinombot.git
cd verkinombot
```

4. Install dependencies
```bash
npm install
```

5. Jalankan bot
```bash
npx ts-node src/index.ts
```

## Perintah yang Tersedia
- `!createaccount username password` - Buat akun baru
- `!help` - Tampilkan daftar perintah
- `!info` - Tampilkan informasi bot

## Pengembang
- Nama: Verkinom
- Versi: 1.0.0
- Dibuat: Juni 2025

## Lisensi
© 2025 Verkinom - All rights reserved
