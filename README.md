# StoryRescue - Pengunduh Arsip Story Instagram

[![Python3](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

![StoryRescue](https://github.com/user-attachments/assets/87af3cda-38fd-44f3-838c-59f491013cee)

**StoryRescue** adalah solusi praktis berbasis Python untuk menyimpan Story dan Reel Instagram secara otomatis. Ideal bagi pengguna yang ingin mengamankan konten sebelum fitur arsip hilang dari platform.

## Fitur Utama

- **Manajemen Kesalahan**: Skrip dilengkapi dengan mekanisme untuk menangani kesalahan seperti kesalahan koneksi atau permintaan yang gagal.
- **Pengunduhan Gambar dan Video**: Mendukung pengunduhan gambar dalam format `jpg` dan video dalam format `mp4`.
- **Pengumpulan Arsip Story & Reel**: Skrip ini dapat mengakses arsip Instagram untuk mengumpulkan daftar Story dan Reel.
- **Penyimpanan Otomatis**: Hasil unduhan secara otomatis disimpan ke dalam folder yang Anda pilih.
- **Mode Pilihan Video**: Anda dapat memilih untuk menyertakan atau mengabaikan video saat mengunduh arsip.

## Prasyarat

Sebelum Anda menjalankan skrip ini, pastikan Anda telah memenuhi persyaratan berikut:

- **Pustaka Python yang Diperlukan**:
  - `requests`
  - `rich`
- **Python 3.x**.

Jika Anda sudah memiliki Python dan pustaka tersebut, Anda siap menjalankan skrip.

## Cara Menggunakan

1. **Clone repository ini ke dalam komputer Anda**:
   
   ```bash
   git clone https://github.com/RozhakLabs/StoryRescue.git
   cd StoryRescue
   ```
2. **Instal dependensi yang diperlukan**:
   
   ```bash
   pip install -r requirements.txt
   ```
3. **Jalankan skrip dengan perintah**:
   
   ```bash
   python Run.py
   ```
4. **Masukkan Cookies Instagram**: Ketika diminta untuk, masukkan cookies yang valid dari akun Instagram Anda. Contohnya:
   
   ```css
   [?] Your Cookies: sessionid=xxxxxxxxxxxxxxxxxxxx
   ```
5. **Pilih Sertakan Video atau Tidak**: Anda bisa memilih apakah ingin mengunduh juga video dengan mengetikkan `Y` untuk "Ya" atau `N` untuk "Tidak".
   
   ```css
   [?] Sertakan Video (Y/N): Y
   ```
6. **Pilih Folder Penyimpanan**: Pilih direktori tujuan untuk menyimpan hasil unduhan.
   
   ```css
   [?] Folder (Ex: Penyimpanan/): Penyimpanan/
   ```
7. Skrip akan berjalan dan mengunduh Story/Reel sesuai dengan pilihan Anda. Setelah selesai, semua hasil unduhan akan tersimpan di folder yang Anda tentukan.

## Struktur Proyek

- `Penyimpanan/`: Folder default tempat menyimpan hasil unduhan (gambar dan video).
- `Temporary/`: Folder sementara untuk menyimpan file JSON yang berisi tautan story/reel yang terkumpul.
- `requirements.txt`: File yang berisi daftar pustaka yang diperlukan oleh skrip.
- `Run.py`: Skrip utama yang mengelola semua proses pengumpulan dan pengunduhan Story/Reel.

## Troubleshooting

- **Masalah Akun Terlogout**: Jika akun Anda terlogout saat menggunakan skrip, Anda bisa menggunakan **MODE DEKSTOP** di browser untuk mendapatkan kembali cookies yang valid. Pastikan juga akun Anda **ONLINE** di browser tersebut sebelum mengambil cookies baru.
- **Masalah Login**: Jika skrip menampilkan pesan "Login Diperlukan!", itu berarti cookies yang Anda masukkan tidak valid atau telah kadaluwarsa. Pastikan untuk mendapatkan cookies baru dari akun Instagram Anda.
- **Pengunduhan Terputus**: Jika pengunduhan gagal, cek kembali koneksi internet Anda atau pastikan Instagram tidak sedang mengalami masalah.

## Tangkapan Layar

![FunPic_20240929-1](https://github.com/user-attachments/assets/775f3ae9-7f42-4c8d-988a-cbf58b574bf6)

![FunPic_20240929-2](https://github.com/user-attachments/assets/aed17e72-a6e6-4818-ae07-0b934841f8f1)

## Dukungan

Jika Anda merasa terbantu dengan skrip ini, Anda bisa memberikan dukungan melalui:

- [Trakteer](https://trakteer.id/rozhak_official/tip)
- [PayPal](https://paypal.me/rozhak9)

## ⚠️ Peringatan Etis

Proyek ini dibuat semata-mata untuk tujuan edukasi dan pembelajaran teknis. Penggunaan skrip untuk mengakses atau mengunduh konten dari Instagram harus tetap mematuhi kebijakan layanan dan hukum yang berlaku. Pengembang tidak bertanggung jawab atas penyalahgunaan alat ini. Gunakan secara bijak dan bertanggung jawab.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).