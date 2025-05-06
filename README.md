<p align="center">
  <img src="icon.png" alt="Drakor CLI Icon" width="300" height="300" style="object-fit: cover;">
</p>

# Drakor CLI

**Drakor CLI** adalah aplikasi berbasis command line (CLI) yang dibuat dengan Python. Aplikasi ini memungkinkan pengguna untuk mencari judul drama Korea (drakor) berdasarkan keyword yang dimasukkan oleh user, menampilkan daftar episode, dan menyediakan link download dari drama Korea yang dipilih.

## Fitur

- Mencari drama Korea berdasarkan kata kunci yang diinput oleh pengguna.
- Menampilkan daftar episode drama yang dicari.
- Menyediakan link download untuk setiap episode yang dipilih.

## Persyaratan Sistem

- Aplikasi ini hanya tersedia untuk sistem operasi Windows.
- Tidak diperlukan Python atau library eksternal, karena aplikasi telah di-*build* menjadi executable (`drakor_CLI.exe`).

## Cara Menggunakan

1. **Unduh aplikasi**: Download archive `Drakor CLI Windows Portable V1.0.0.zip` dari [Release Page](https://github.com/Arifmaulanaazis/Drakor-CLI/releases/latest) di GitHub.
2. **Unduh database**: Download `database.txt` dari dari [Release Page](https://github.com/Arifmaulanaazis/Drakor-CLI/releases/latest) di GitHub.
4. **Ekstrak file**: Ekstrak file ZIP yang telah diunduh.
5. **Konfigurasi database**: Letakkan `database.txt` yang telah diunduh di folder `_internal/data` sehingga path database akan menjadi `_internal/data/database.txt`
6. **Jalankan aplikasi**: Buka folder hasil ekstraksi dan klik dua kali pada `drakor_CLI.exe` untuk menjalankan aplikasi melalui terminal atau command prompt.
7. **Masukkan kata kunci**: Ketik kata kunci untuk mencari judul drama Korea yang Anda inginkan.
8. **Pilih drama dan episode**: Aplikasi akan menampilkan daftar drama yang sesuai dengan kata kunci Anda, kemudian menampilkan episode yang tersedia setelah Anda memilih salah satu drama.
9. **Dapatkan link download**: Aplikasi akan memberikan link download untuk episode yang Anda pilih.

## Instalasi

Aplikasi ini tidak memerlukan instalasi khusus. Anda cukup mengunduh file ZIP dan database, mengekstraknya, dan menjalankannya.

## Catatan

- Aplikasi ini hanya tersedia dalam bentuk executable untuk Windows. Saat ini saya tidak menyediakan source code ataupun versi untuk Linux atau macOS.
- Jika Anda mengalami masalah saat menggunakan aplikasi ini, silakan laporkan melalui [Issues](https://github.com/Arifmaulanaazis/Drakor-CLI/issues) di GitHub.

## Kontribusi

Saya tidak menerima kontribusi berupa source code untuk saat ini, namun jika Anda memiliki saran atau menemukan bug, jangan ragu untuk mengajukan issue.

## Lisensi

Proyek ini dilisensikan di bawah lisensi GNU General Public License v3.0. Lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.
