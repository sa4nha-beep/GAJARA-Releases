# GAJARA

Brankas akun media sosial HAEN GROUP: platform, nama akun, email/no. HP login, dan password — dipakai bersama oleh admin per unit usaha.

Repo ini hanya berisi **installer resmi**. GAJARA memeriksa pembaruan dari sini dan memasangnya hanya setelah Anda menekan **ⓘ → Unduh & pasang**.

## Unduh
Ambil `GAJARA_<versi>_x64-setup.exe` dari [rilis terbaru](https://github.com/sa4nha-beep/GAJARA-Releases/releases/latest).

- Windows 10/11 64-bit.
- Installer belum ber-code-signing, jadi Windows SmartScreen mungkin memperingatkan. Klik **Info selengkapnya → Tetap jalankan**.
- Cocokkan hash dengan `SHA256SUMS.txt` di halaman rilis: `Get-FileHash .\GAJARA_<versi>_x64-setup.exe` (PowerShell).
- Akun GAJARA dibuat lewat **kode undangan** dari Pemilik; tanpa undangan aplikasi tidak bisa dipakai.

### Android
Ambil `GAJARA_<versi>_android.apk` dari [rilis terbaru](https://github.com/sa4nha-beep/GAJARA-Releases/releases/latest) langsung di HP.

- Android 7 ke atas. Saat memasang, Android meminta izin **"Instal aplikasi tidak dikenal"** untuk browser — izinkan untuk GAJARA saja.
- Setelah login pertama dengan password utama, GAJARA menawarkan **buka dengan sidik jari**.
- Versi baru ditandai tombol oranye di aplikasi; unduh APK baru dan pasang menimpa yang lama (data tetap ada).
- Menu Pemilik (undang/cabut admin, log) dan impor/ekspor hanya ada di versi Windows.

## Privasi & keamanan
- Semua data akun dienkripsi **di perangkat Anda** sebelum dikirim. Server hanya menyimpan data acak terenkripsi; password utama tidak pernah dikirim.
- Password yang disalin tidak masuk riwayat clipboard Windows (di Android: tidak tampil di pratinjau clipboard) dan dihapus otomatis setelah 30 detik.
- Di Android, layar GAJARA tidak bisa di-screenshot dan terkunci bila ditinggal lebih dari 1 menit.
- Tanpa telemetri. Internet dipakai untuk server GAJARA HAEN GROUP dan cek pembaruan.

Daftar komponen pihak ketiga: `THIRD_PARTY_LICENSES.txt` di tiap rilis.
