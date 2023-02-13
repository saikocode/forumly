<p align="center"><a href="https://github.com/saikocode/forumly" target="_blank"><img src="public/img/logo/logo.svg" width="400"></a></p>


## Tentang Forumly


Forumly adalah forum online berbasis web yang ditujukan untuk para mahasiswa sebagai sarana untuk berdiskusi dan bertukar pikiran. Forumly juga memudahkan para mahasiswa untuk berbagi ilmu dan pengalaman.
## Fitur Utama
* Login/Register: Mudah mendaftar atau masuk untuk mengakses semua fitur platform.
* Membuat Diskusi: Mulai diskusi Anda sendiri atau berpartisipasi dalam diskusi yang ada pada berbagai topik.
* Mengelola Postingan: Sunting atau hapus postingan Anda sendiri untuk menjaga diskusi tetap terarah.
* Menyukai Diskusi: Tunjukkan apresiasi Anda untuk diskusi dengan menyukainya.
* Berlangganan Topik: Tetap up-to-date dengan diskusi terbaru pada topik yang Anda minati.
* Menulis Komentar: Bagikan pendapat dan opini Anda pada diskusi dengan pengguna lain.
* Mengikuti Pengguna: Pantau diskusi yang dibuat oleh pengguna yang Anda ikuti.
* Mencari Topik: Temukan diskusi yang Anda minati dengan cepat dan mudah.
* Profil Pribadi: Sesuaikan profil Anda untuk merefleksikan kepribadian dan minat Anda.
* Fitur Admin: Admin memiliki akses ke alat khusus seperti membuat kategori, memantau pengguna aktif, dan mengelola semua thread pengguna.
* Dengan Forumly, Anda dapat berpartisipasi dalam diskusi yang ramai dan berinteraksi dengan individu yang memiliki minat yang sama. Mulai jelajahi platform hari ini dan bergabunglah dalam diskusi!

### Dibuat Dengan


* [Laravel](https://laravel.com)
* [Tailwind](https://getbootstrap.com)
* [AlpineJS](https://alpinejs.dev/)
* [Jetstream](https://jetstream.laravel.com/2.x/introduction.html)


<a href="https://cdnlogo.com/logo/laravel_40397.html"><img src="https://cdn.cdnlogo.com/logos/l/23/laravel.svg" width="100" height="100"></a>
<a href="https://cdnlogo.com/logo/tailwindcss_42966.html"><img src="https://cdn.cdnlogo.com/logos/t/58/tailwindcss.svg" width="100" height="100"></a>
<a href="https://laravelnews.imgix.net/images/jetstream.png?ixlib=php-3.3.1"><img src="https://laravelnews.imgix.net/images/jetstream.png?ixlib=php-3.3.1" width="200" height="100"></a>



### Instalasi



1. Clone repo
   ```sh
   git clone https://github.com/saikocode/forumly.git
   ```
2. Install Laravel
   ```sh
   composer install
   ```
3. Copy file `.env.example` lalu ubah menjadi `.env` buka lalu ubah
   ```sh
      DB_CONNECTION=mysql
      DB_HOST=127.0.0.1
      DB_PORT=3306
      DB_DATABASE=forumly
      DB_USERNAME=root
      DB_PASSWORD=';
   ```
4. Buka terminal lalu jalankan perintah ini untuk melakukan key generate
   ```sh
   php artisan key:generate
   ```
5. Import database
   ```sh
   php artisan migrate:fresh --seed
   ```
5. Jalankan server
   ```sh
   php artisan serve
   ```
## Contributor

Reichan Muhamad Maulana</br>
Angga Cahya Abadi</br>



## License

Forumly is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
