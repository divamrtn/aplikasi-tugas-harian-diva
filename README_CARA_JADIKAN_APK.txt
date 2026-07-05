PANDUAN APLIKASI ANDROID TUGAS HARIAN

Nama aplikasi:
Tugas Harian Diva

Jenis aplikasi:
Aplikasi Android, bukan website.

Fitur:
1. Tambah tugas harian.
2. Edit tugas.
3. Hapus tugas.
4. Tandai tugas selesai atau belum selesai.
5. Cari tugas.
6. Filter tugas berdasarkan status.
7. Statistik total tugas, selesai, dan belum selesai.
8. Data tersimpan otomatis di HP menggunakan SharedPreferences.

CARA MEMBUKA PROJECT:

1. Install Android Studio di laptop.
2. Extract file ZIP ini.
3. Buka Android Studio.
4. Pilih Open.
5. Pilih folder:
   aplikasi_tugas_harian_android_diva
6. Tunggu proses Gradle selesai.

CARA MENJADIKAN APK:

1. Di Android Studio, buka menu:
   Build > Generate Signed Bundle / APK

2. Pilih:
   APK

3. Pilih:
   Create new keystore
   Isi data keystore bebas, misalnya:
   - Key store path: tugas_harian.jks
   - Password: 123456
   - Alias: tugas_harian
   - Validity: 25

4. Klik Next.
5. Pilih release.
6. Klik Finish.

CARA INSTALL KE HP:

1. Setelah APK berhasil dibuat, cari file APK di folder:
   app/build/outputs/apk/release/

2. Kirim file APK ke HP.
3. Buka file APK di HP.
4. Jika muncul peringatan, aktifkan:
   Izinkan install dari sumber tidak dikenal.

5. Install aplikasi.
6. Aplikasi bisa digunakan langsung di HP.

CARA RUN LANGSUNG KE HP TANPA BUAT APK:

1. Aktifkan Developer Options di HP.
2. Aktifkan USB Debugging.
3. Sambungkan HP ke laptop pakai kabel USB.
4. Di Android Studio klik tombol Run.
5. Pilih device HP.
6. Aplikasi akan langsung terpasang ke HP.

CATATAN:
- Project ini dibuat pakai Java Android native.
- Tidak memakai database online.
- Tidak perlu internet.
- Data tersimpan di memori aplikasi HP.
- Jika aplikasi dihapus, data ikut hilang.
