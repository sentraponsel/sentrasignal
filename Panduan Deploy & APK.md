# SENTRA CRYPTOSIGNAL PWA Deployment Guide

## 📁 1. Struktur Folder File ZIP Anda

Pastikan Anda membuat folder bernama `sentra-cryptosignal` dan memasukkan file-file berikut sebelum dikompres menjadi `.zip`:

```
sentra-cryptosignal/
├── index.html
├── manifest.json
├── sw.js
└── icons/
    ├── icon-192.png  (Ukuran 192x192 px)
    └── icon-512.png  (Ukuran 512x512 px)
```

---

## 🚀 2. Deploy Gratis ke GitHub Pages

1. Buat repository baru di [GitHub](https://github.com) dengan nama `sentra-cryptosignal`.
2. Unggah/Upload semua file di atas ke repository tersebut.
3. Masuk ke **Settings** > **Pages** di repository GitHub Anda.
4. Di bagian **Build and deployment** -> **Branch**, pilih `main` atau `master`, lalu klik **Save**.
5. Tunggu 1-2 menit. Aplikasi Anda akan aktif di URL: `https://username_github_anda.github.io/sentra-cryptosignal/`

---

## 📲 3. Cara Install di Google Chrome (Desktop / Mobile)

### Google Chrome Android & iOS:
1. Buka URL GitHub Pages aplikasi Anda di Chrome Android/Safari iOS.
2. Klik titik tiga (atau tombol Share di Safari).
3. Pilih **"Add to Home Screen"** atau **"Install App"**.

### Google Chrome Desktop:
1. Buka URL aplikasi di Chrome Desktop.
2. Klik ikon instalasi (layar komputer dengan panah bawah) di sebelah kanan *address bar*.

---

## 🤖 4. Cara Mengubah Aplikasi Menjadi APK Android

Ada dua cara mudah tanpa perlu koding Android Studio:

### Cara A (Menggunakan PWABuilder - Sangat Disarankan):
1. Buka situs [PWABuilder.com](https://www.pwabuilder.com/).
2. Masukkan URL GitHub Pages aplikasi Anda (misal: `https://username.github.io/sentra-cryptosignal/`) lalu klik **Start**.
3. Setelah pindaian selesai, klik tombol **Package for Store**.
4. Pilih **Android** -> Klik **Generate Package**.
5. Anda akan mendapatkan file `.apk` dan `.aab` yang siap di-install ke HP Android atau di-upload ke Google Play Store!

### Cara B (Menggunakan Web2App Builder Online):
1. Buka layanan seperti [AppsGeyser](https://appsgeyser.com/) atau [Web2App Builder].
2. Masukkan URL website aplikasi Anda.
3. Upload gambar logo ikon `icon-512.png`.
4. Klik **Build APK** untuk mendownload file APK langsung.