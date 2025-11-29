<h1 align="center">Selamat datang di SIFORLA! 👋</h1>

## Apa itu SIFORLA?

Web SIFORLA (Sistem Informasi Sekolah) adalah web yang original dibuat oleh <a href="https://github.com/lacsapadnan">lacsapadnan</a>. **Sistem Informasi Sekolah merupakan aplikasi web yang dikembangkan untuk membantu pengelolaan administrasi sekolah secara digital. Sistem ini dirancang untuk mempermudah proses manajemen data akademik, administrasi guru, siswa, dan kegiatan pembelajaran di lingkungan sekolah.**

## Fitur apa saja yang tersedia di Sistem Informasi Sekolah?

-   Autentikasi Multi-Role (Admin, Guru, Siswa)
-   Jurusan & CRUD
-   Mata Pelajaran & CRUD
-   Guru & CRUD
-   Kelas & CRUD
-   User & CRUD
-   Materi & CRUD
-   Tugas & Jawaban & CRUD
-   Jadwal Sekolah & CRUD
-   Desain Responsif

## Tanggal Rilis

**Rilis : 29 November 2025**

## Akun Default Untuk Mencoba

**Akun Default Admin**

-   Email: admin@mail.com
-   Password: admin123

**Akun Default Guru**

-   Email: budi@mail.com
-   Password: budi123

**Akun Default Siswa**

-   Email: kevin@mail.com
-   Password: kevin123

## Instalasi

### Yang Harus Dipersiapkan Untuk Menjalankan Aplikasi :

-   [git](https://git-scm.com/install/)
-   [php >= 8.2](https://www.php.net/downloads.php)
-   laravel v11
-   web server (XAMPP/Laragon)
-   [node js](https://nodejs.org/en/download)
-   [composer](https://getcomposer.org/download/)
-   MySQL

### Langkah-langkah :

1. **Clone Repository**

```bash
git clone https://github.com/lacsapadnan/Sistem-Informasi-Sekolah.git
cd Sistem-Informasi-Sekolah
npm install
```

2. **buat dan buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
cp .env.example .env
```

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=si_sekolah
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi composer**

```bash
composer install
```

4. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan website**

```bash
php artisan serve
```

## Screenshots

![Login](assets/login%20rpl.jpeg)
_Halaman login untuk admin, guru, dan siswa_

![Dashboard_admin](assets/dasbor%20admin%20rpl.jpeg)
_Dashboaard admin_

![Dashboard_guru](assets/dasbor%20guru%20rpl.jpeg)
_Dasboard guru_

![Dashboard_siswa](assets/dasbor%20siswa%20rpl.jpeg)
_dasboard siswa_

## Pembuat

**GitHub :**

-   <a href="https://github.com/farizziezhi"> Muh. Farizzi</a>
-   <a href="https://github.com/Heinzzz001"> Kavrian Syah</a>
-   <a href="https://github.com/MadeBagas21"> Made Bagas Mardiana</a>
-   <a href="https://github.com/HackerWibu69"> Muh. Apriawan</a>
-   <a href="https://github.com/DarkPhantom24"> Muhammad Aqil Fathurrahman</a>

## Lisensi

-   Copyright © 2024 Pascal Adnan.
-   **Sistem Informasi Sekolah is open-sourced software licensed under the MIT license.**
