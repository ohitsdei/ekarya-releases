# eKarya NGC untuk Android

Repository ini adalah kanal distribusi resmi APK **eKarya NGC**. Gunakan halaman [Releases](https://github.com/ohitsdei/ekarya-releases/releases) untuk mengunduh versi aplikasi terbaru dan membaca catatan perubahannya.

> Repository ini hanya menyimpan artefak rilis dan metadata pembaruan. Kode sumber aplikasi tidak dipublikasikan di sini.

## Instal aplikasi

1. Buka [rilis terbaru](https://github.com/ohitsdei/ekarya-releases/releases/latest).
2. Pada bagian **Assets**, unduh file bernama `ekarya-<versi>-<versionCode>.apk`.
3. Buka file APK setelah unduhan selesai.
4. Jika Android meminta izin, izinkan pemasangan aplikasi dari browser atau pengelola file yang digunakan.
5. Ikuti konfirmasi pemasangan Android. Saat memperbarui aplikasi, data dan akun yang ada tetap dipertahankan.

Unduh APK hanya dari halaman Releases repository ini atau melalui notifikasi pembaruan di dalam aplikasi. Jangan memasang APK dari tautan yang tidak dikenal.

## Pembaruan dari dalam aplikasi

eKarya NGC memeriksa metadata rilis terbaru untuk menentukan ketersediaan pembaruan Android. Jika versi yang lebih baru tersedia, aplikasi dapat mengunduh APK rilis dan membuka installer Android.

Setiap rilis memuat dua aset berikut:

| Aset | Kegunaan |
| --- | --- |
| `ekarya-<versi>-<versionCode>.apk` | Paket instalasi Android. |
| `app-update.json` | Metadata versi, changelog, dan tautan APK yang dibaca oleh aplikasi. |

Tag rilis menggunakan format `v<versi>+<versionCode>`, misalnya `v1.1.2+12`. Nilai `versionCode` harus lebih tinggi dari rilis sebelumnya agar Android menerima pembaruan.

## Catatan untuk pengguna

- Pastikan ruang penyimpanan dan koneksi internet mencukupi sebelum mengunduh APK.
- Pembaruan APK dapat meminta konfirmasi pemasangan dari Android. Ini adalah perilaku normal untuk instalasi di luar Play Store.
- Bila proses pemasangan gagal, hapus file APK yang tidak lengkap, unduh ulang dari rilis terbaru, lalu coba lagi.
- Untuk kendala akun atau fitur aplikasi, hubungi administrator eKarya NGC melalui kanal dukungan internal perusahaan.
