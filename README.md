# HealthyLife AI - Flutter starter

Project ini berisi prototipe aplikasi HealthyLife AI dengan Flutter. UI memakai data demo lokal (di memori), sehingga data akan kembali ke nilai awal saat aplikasi ditutup sepenuhnya.

## Cara menjalankan
1. Install Flutter SDK dan Android Studio (untuk Android SDK/emulator) atau siapkan HP Android dengan USB debugging.
2. Ekstrak ZIP ini.
3. Buka folder `healthylife_ai` di Visual Studio Code.
4. Pastikan ekstensi Flutter dan Dart terpasang.
5. Buka Terminal di VS Code, lalu jalankan:
   ```bash
   flutter doctor
   flutter pub get
   flutter run
   ```
6. Jika ada beberapa perangkat, cek dengan `flutter devices`, lalu pilih emulator/HP yang aktif.

## Fitur demo
- Splash, registrasi/login demo, isi profil, pilihan target
- Dashboard dan navigasi bawah
- Meal plan, favorit menu, jadwal mingguan
- Olahraga, Water Tracker, Sleep Tracker
- Progress & statistik dengan grafik sederhana
- AI Assistant dengan balasan demo lokal
- Pencapaian/streak demo dan pengaturan pengingat

## Catatan penting
- Login belum menggunakan Firebase. Tombol Google/Apple hanya menampilkan keterangan.
- Data profil, aktivitas, dan chat masih disimpan di memori, bukan database permanen.
- Pengingat belum menjadwalkan notifikasi sistem.
- Chatbot belum terhubung ke AI/API.
- Data kalori dan grafik adalah contoh UI, bukan saran medis. Sesuaikan informasi kesehatan dengan sumber tepercaya.
- Untuk produksi, tambahkan Firebase Authentication/Firestore, notifikasi lokal, backend untuk API AI, validasi input, privasi, dan pengujian.
