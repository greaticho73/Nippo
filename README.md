# Catatan Nippo — Android

Versi native Android yang membungkus aplikasi offline dengan WebView lokal.

Fitur yang diubah:
- Bahasa default Jepang.
- Riwayat kegiatan default hanya tanggal hari ini; tanggal lain dipilih melalui pemilih tanggal.
- To Do juga default hanya tanggal hari ini dan dapat difilter berdasarkan tanggal.
- Kegiatan diurutkan dari jam mulai paling awal.
- To Do diurutkan dari waktu paling awal.
- To Do terintegrasi dengan AlarmManager Android sehingga pengingat dapat muncul saat aplikasi tidak sedang terbuka.
- Data web disimpan di localStorage; seluruh HTML/CSS/JS berada di assets sehingga fungsi utama offline.
- Setelah reboot, alarm yang masih tersimpan dijadwalkan kembali.
- Ikon aplikasi menggunakan gambar yang diberikan pengguna.

Build: buka folder ini di Android Studio, lalu Build > Build APK(s). Target SDK 35. Android 13+ meminta izin notifikasi. Android 12+ mungkin meminta izin alarm tepat (exact alarm).
