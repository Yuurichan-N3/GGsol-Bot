
# GGsol Bot

![GGsol Bot Banner](https://img.shields.io/badge/GGsol%20Bot-Automated%20Account%20Creation-blueviolet?style=for-the-badge)

**GGsol Bot** adalah alat otomatisasi untuk membuat akun di platform GGSol dengan menggunakan Solana wallet. Bot ini dirancang untuk membantu pengguna dalam menghasilkan akun baru dengan nickname unik, kode referral, dan menyimpan detail wallet ke file JSON. Skrip ini ditujukan untuk keperluan pembelajaran dan pengujian.

> **Peringatan**: Bot ini memiliki masa kedaluwarsa hingga **24 April 2025 pukul 02:00 WIB**. Setelah waktu tersebut, bot tidak akan berfungsi.

## ✨ Fitur
- **Pembuatan Wallet Solana**: Menghasilkan Solana keypair dan mnemonic secara otomatis.
- **Nickname Unik**: Membuat nickname acak menggunakan kombinasi nama dan angka.
- **Integrasi API GGSol**: Mengotomatisasi proses autentikasi dan pembaruan profil melalui API GGSol.
- **Penyimpanan Wallet**: Menyimpan detail wallet (alamat dan mnemonic) ke file `wallets.json`.
- **Penundaan Acak**: Menambahkan jeda acak (60-120 detik) antar permintaan untuk menghindari deteksi.
- **Kode Referral**: Mendukung penggunaan kode referral untuk pendaftaran.

## 🛠 Prasyarat
Pastikan Anda memiliki alat berikut sebelum menjalankan bot:
- **Node.js** (versi 16 atau lebih tinggi)
- **NPM** (biasanya terinstal bersama Node.js)

## 📦 Instalasi
1. Clone repository ini:
   ```bash
   git clone https://github.com/Yuurichan-N3/GGsol-Bot.git
   cd GGsol-Bot
   ```

2. InstalVen dependencies:
   ```bash
   npm install
   ```

3. Pastikan Anda memiliki dependensi berikut:
   - `axios`
   - `@solana/web3.js`
   - `bs58`
   - `tweetnacl`
   - `bip39`
   - `crypto`
   - `unique-names-generator`
   - `fs`
   - `timers`

## 🚀 Cara Penggunaan
1. Jalankan skrip menggunakan perintah berikut:
   ```bash
   node bot.js
   ```

2. Masukkan kode referral saat diminta di terminal.

3. Bot akan mulai membuat akun secara otomatis dengan jeda acak antara 60-120 detik untuk setiap permintaan.

4. Detail akun (alamat wallet dan mnemonic) akan disimpan di file `wallets.json`.

## ⚠️ Catatan Penting
- **Masa Kedaluwarsa**: Bot ini hanya berfungsi hingga **23 April 2025 pukul 23:59 WIB**.
- **Keamanan**: Jaga kerahasiaan mnemonic dan private key Anda. Jangan bagikan file `wallets.json` dengan siapa pun.
- **Penggunaan API**: Pastikan Anda mematuhi kebijakan penggunaan API GGSol untuk menghindari pemblokiran.
- **Tanggung Jawab**: Pengguna bertanggung jawab penuh atas penggunaan bot ini.


## 📜 Lisensi
Script ini didistribusikan untuk keperluan pembelajaran dan pengujian. Penggunaan di luar tanggung jawab pengembang.

Untuk update terbaru, bergabunglah di grup **Telegram**: [Klik di sini](https://t.me/sentineldiscus).

---

## 💡 Disclaimer
Penggunaan bot ini sepenuhnya tanggung jawab pengguna. Kami tidak bertanggung jawab atas penyalahgunaan skrip ini.
