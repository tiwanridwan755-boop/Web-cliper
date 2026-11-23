# Web Video Clipper Pro — Auto-Build APK (GitHub Actions + Capacitor)

Paket ini sudah dikonfigurasi lengkap untuk langsung di-compile menjadi file `.apk` Android secara otomatis di cloud GitHub (tanpa perlu instal Android Studio di laptop/PC).

## Cara Compile Jadi File `.apk` (Gratis, ±3 Menit)

1. **Ekstrak** file `web-video-clipper-pro-apk.zip`.
2. Buka **GitHub.com** (bisa lewat browser HP atau laptop), buat **Repository baru** (misal: `web-video-clipper-apk`), set ke **Public** atau **Private**.
3. Upload seluruh isi folder ini (pastikan folder `.github/workflows/build-apk.yml`, `www/index.html`, `package.json`, dan `capacitor.config.json` ikut ter-upload).
4. Buka tab **Actions** di repository GitHub kamu → workflow **Build Android APK** akan otomatis berjalan.
5. Setelah centang hijau (sekitar 2–3 menit), klik workflow tersebut → gulir ke bagian **Artifacts** di paling bawah → klik **`Web-Video-Clipper-Pro-APK`** untuk mengunduh file `app-debug.apk`.
6. Ekstrak ZIP artifact dan instal **`app-debug.apk`** langsung di HP Android kamu.
