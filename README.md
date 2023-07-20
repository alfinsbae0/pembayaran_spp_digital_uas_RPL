<p align="center">
    <h1>E-Pembayaran SPP</h1>
</p>

## Tentang E-Pembayaran SPP

E-Pembayaran SPP adalah sebuah aplikasi untuk mempermudah sebuah sekolah dalam mendata pembayaran SPP para siswa/siswinya, dengan menggunakan aplikasi ini tentunya akan lebih mengurangi biaya dalam pendataan pembayaran SPP, dan mengurangi penggunaan kertas yang dimana pohon adalah GO GREEN bagi kehidupan manusia.

Aplikasi ini memiliki 3 hak akses level login, yang diantaranya :

Level Admin

-   Login
-   Logout
-   CRUD data siswa
-   CRUD data petugas
-   CRUD data Kelas
-   CRUD data SPP
-   Entri Transaksi Pembayaran
-   Lihat Histori Pembayaran
-   Generate Laporan

Level Petugas

-   Login
-   Logout
-   Entri Transaksi Pembayaran
-   Lihat Histori Pembayaran

Level Siswa

-   Login
-   Logout
-   Lihat Histori Pembayaran

## Cara Install

$ git clone https://github.com/alfinsbae0/pembayaran_spp_digital_uas_RPL.git <br>
$ cd pembayaran_spp_digital_uas_RPL <br>
$ composer update <br>
$ php artisan migrate --seed <br>
$ php artisan serve <br>

Catatan :

-   buat database terlebih dahulu dengan nama spp_db.
-   PHP version min 8.0

## Akun Untuk Login

Level Admin

-   email : admin@spp.com
-   password : admin

Level Petugas

-   email : petugas@spp.com
-   password : petugas

Level Siswa

-   NISN : 123456789876
-   Nama : siswa

## Penutup

Terima Kasih.
