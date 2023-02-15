<p align="center"><a href="https://github.com/saikocode/forumly" target="_blank"><img src="public/img/logo/logo.svg" width="400"></a></p>


## Tentang Forumly


Forumly adalah platform diskusi online berbasis web yang ditujukan untuk para mahasiswa yang mudah digunakan dan punya banyak fitur keren buat meningkatkan pengalaman kamu. Dengan Forumly, kamu bisa ikutan ngomongin, ikutan diskusi topik yang kamu sukai, dan terhubung dengan pengguna lain.
## Fitur Utama
* Login/Register: Mudah banget buat daftar atau login buat akses semua fitur di platform.
* Bikin Diskusi: Mulai ngomongin apa aja yang kamu sukai atau ikutan ngomongin yang udah ada di banyak topik.
* Kelola Postingan: Edit atau hapus postingan kamu sendiri biar diskusinya tetep keren.
* Sukai Diskusi: Tampilin apresiasi kamu buat diskusi dengan menyukai.
* Langganan Topik: Terus update dengan diskusi terbaru yang kamu sukai.
* Komentar: Bagikan pendapat dan opini kamu pada diskusi dengan pengguna lain.
* Ikuti Pengguna: Pantau diskusi yang dibuat dengan pengguna yang kamu ikuti.
* Cari Topik: Temukan diskusi yang kamu sukai dengan mudah dan cepat.
* Profil Pribadi: Sesuaikan profil kamu buat menampilkan kepribadian dan minat kamu.
* Fitur Admin: Admin bisa akses fitur spesial seperti buat kategori, lihat pengguna aktif, dan kelola semua thread pengguna.

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

[Reichan Muhamad Maulana](https://github.com/N0iire)</br>
[Angga Cahya Abadi](https://github.com/angjaay)</br>



## License

Forumly is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
