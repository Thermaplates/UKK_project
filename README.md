
#    Project Akhir Tahap Awal UKK - Aplikasi Flutter + Laravel  
  
Projek ini merupakan *project akhir tahap awal* dalam rangka persiapan *Uji Kompetensi Keahlian (UKK)*.  
Aplikasi ini menggunakan *Flutter* sebagai frontend (mobile app) dan *Laravel* sebagai backend (API).  
  
---  
  
##  Identitas  
- Nama : Marchelino I Wayan Saputra
- Sekolah: SMK Negeri 1 Bantul  
- Jurusan: Rekayasa Perangkat Lunak (RPL)  
- No absen: 20
  
---  
  
##   Fitur Utama  
- Autentikasi (Register, Login, Logout)  
- Desain tampilan modern dan simple dengan Flutter  
  
---  
  
##  Teknologi yang Digunakan  
### Frontend  
- [Flutter]([https://flutter.dev/](https://flutter.dev/)) (Dart)  
- State management sederhana dengan setState  
  
### Backend  
- [Laravel]([https://laravel.com/](https://laravel.com/)) (PHP Framework)  
- RESTful API  
- MySQL  
  
---  
  
##   Dokumentasi (Screenshots)  
  
### Autentikasi  
- *Login Page*  

<img width="1920" height="1080" alt="Screenshot 2025-08-28 134901" src="https://github.com/user-attachments/assets/7b1acc24-a5e6-4cdc-8a73-07a12604416d" />

  
  
- *Register Page*  

<img width="1920" height="1080" alt="Screenshot 2025-08-28 134929" src="https://github.com/user-attachments/assets/58e32f4b-b807-4126-8fd4-e1f292ae0db0" />

  
- *Dashboard* 

  <img width="1920" height="1080" alt="Screenshot 2025-08-28 135120" src="https://github.com/user-attachments/assets/1d8e5739-5906-4624-9791-b269e18c7dd8" />

---  
  
##    Cara Menjalankan  
### Backend (Laravel)  
1. Clone repository ini  
2. Masuk folder api-flutter/  
3. Jalankan perintah:  

bash:  
>composer install  
cp .env.example .env  
php artisan key:generate  
php artisan migrate --seed  
php artisan serve  
`  
  
Laravel akan berjalan di  [http://127.0.0.1:8000](http://127.0.0.1:8000/)  
  
### Frontend (Flutter)  
  
1. Masuk folder api/  
2. Jalankan:  
  
bash:  
>flutter pub get  
flutter run  
  
  
Pastikan device emulator atau HP terkoneksi.  
  
---  

