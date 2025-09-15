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

## Hasil Praktikum
### Tampilan saat login

<img width="505" height="1020" alt="image" src="https://github.com/user-attachments/assets/f9359bb6-09a6-47b7-af68-6fe498946ef1" />

Praktikum berhasil membuat halaman login interaktif dengan tampilan modern. Fitur utama seperti input email & password, tombol login, navigasi ke register, dan hide/show password sudah berjalan.

### Tampilan Saat Register

<img width="504" height="1024" alt="image" src="https://github.com/user-attachments/assets/9ae72c2f-f38d-4d08-9764-3de233cf07db" />

Register Page yang berhasil dibuat dalam praktikum Flutter dengan fungsi utama untuk pendaftaran akun baru. Pada halaman ini tersedia ikon pengguna sebagai identitas halaman, teks judul “Create Account”, tiga input field untuk Full Name, Email, dan Password dengan tambahan fitur tampil/sembunyikan password, tombol utama Tombol Register untuk menyimpan data akun, serta tautan “Sign In” untuk kembali ke halaman login.

### Tampilan Jika Login Berhasil

<img width="497" height="1014" alt="image" src="https://github.com/user-attachments/assets/75ed71f5-4d90-4465-9ef6-baee5ba23bb0" />

Praktikum ini menampilkan hasil saat pengguna berhasil melakukan registrasi pada aplikasi Flutter. Setelah mengisi data Full Name, Email, dan Password dengan benar, sistem menampilkan dialog konfirmasi (AlertDialog) dengan judul “Info” dan pesan “Registrasi berhasil, silakan login”. Dialog ini menjadi feedback kepada pengguna bahwa akun baru sudah tersimpan dan mereka dapat melanjutkan ke proses login.

<img width="505" height="1030" alt="image" src="https://github.com/user-attachments/assets/2eea77bf-354e-4307-9e94-701719ef1006" />

Pada Ganmbar diatas Usera Berhasil Melakukan Login tnapa adanya eror, dengan tampilan "Selamat datang Rafli"

### Tampilan Jika Pengisian Tidak Sesuai
### Email/Gmail Tidak @

<img width="507" height="1039" alt="image" src="https://github.com/user-attachments/assets/cb6f668d-55df-492d-8ea4-a91965dbaef1" />

Pada Hasil ini User mencoba melakukan registrasi namun input email tidak sesuai format yang benar. Sistem menampilkan sebuah AlertDialog dengan judul “Info” dan pesan “Email tidak valid” sebagai bentuk validasi input. Pesan ini muncul karena email yang dimasukkan tidak mengandung karakter atau struktur yang sesuai standar (misalnya tidak ada tanda @).

### Password

<img width="505" height="1012" alt="image" src="https://github.com/user-attachments/assets/fe62c689-02fc-4753-870d-318ba338d41f" />

pada hasil Berikut ini User Mencoba Mendaftar, Namun Gagal dikarenakan Password minimal  harus memiliki 6 karakter, maka dari itu muncullah info seperti yang ada pada gambarr "password minimal 6 karakter

## Kesimpulan
Dari praktikum pembuatan Aplikasi Login dan Register ini dapat disimpulkan bahwa aplikasi berhasil dibangun dengan tampilan antarmuka (UI) yang interaktif serta fungsionalitas dasar autentikasi pengguna. Pengguna dapat melakukan registrasi akun baru dengan input nama, email, dan password, serta melakukan login menggunakan data yang sudah terdaftar. Fitur tambahan seperti validasi input (email valid dan password minimal 6 karakter), tampil/sembunyikan password, navigasi antar halaman, hingga feedback berupa dialog (AlertDialog) telah berjalan dengan baik. Dengan implementasi ini, praktikum memberikan pemahaman tentang penggunaan widget dasar Flutter (Scaffold, TextField, ElevatedButton, Navigator), pengelolaan state dengan TextEditingController, serta cara mengatur alur autentikasi sederhana sehingga aplikasi siap dikembangkan lebih lanjut, misalnya integrasi dengan database atau penyimpanan sesi login.

