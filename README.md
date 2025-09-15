# flutter_register

A new Flutter project.

## Deskripsi

Aplikasi ini merupakan contoh implementasi fitur **Login** dan **Register** sederhana menggunakan Flutter. Data user disimpan secara lokal menggunakan Map dan status login menggunakan Shared Preferences.

## Fitur

- **Login**: Validasi email dan password, menyimpan status login.
- **Register**: Menambah user baru ke data lokal.
- **Home**: Menampilkan nama user yang sedang login.
- **Logout**: Menghapus status login dan kembali ke halaman login.

## Struktur Folder

- `lib/main.dart` : Entry point aplikasi.
- `lib/login_page.dart` : Halaman login.
- `lib/register_page.dart` : Halaman registrasi.
- `lib/home_page.dart` : Halaman utama setelah login.
- `lib/data/user_data.dart` : Data user lokal.

## Cara Menjalankan

1. Pastikan sudah install Flutter SDK.
2. Jalankan perintah berikut di terminal:
   ```
   flutter pub get
   flutter run
   ```

## Catatan

- Data user hanya disimpan secara lokal (Map), bukan database.
- Status login menggunakan Shared Preferences.

## Referensi

- [Flutter Documentation](https://docs.flutter.dev/)
- [Shared Preferences](https://pub.dev/packages/shared_preferences)