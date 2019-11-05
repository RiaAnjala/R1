# R1

- phpMyAdmin SQL Dump
- versi 4.4.14
- http://www.phpmyadmin.net
-
- Tuan rumah: 127.0.0.1
- Waktu Pembuatan: 27 Oktober 2018 pukul 14:37
- Versi server: 5.6.26
- Versi PHP: 5.6.12

SET SQL_MODE =  " NO_AUTO_VALUE_ON_ZERO " ;
SET time_zone =  " +00: 00 " ;


/ * ! 40101 SET @OLD_CHARACTER_SET_CLIENT = @@ CHARACTER_SET_CLIENT * / ;
/ * ! 40101 SET @OLD_CHARACTER_SET_RESULTS = @@ CHARACTER_SET_RESULTS * / ;
/ * ! 40101 SET @OLD_COLLATION_CONNECTION = @@ COLLATION_CONNECTION * / ;
/ * ! 40101 SET NAMES utf8mb4 * / ;

-
- Basis data: `db_arka`
-

- ------------------------------------------------ --------

-
- Struktur tabel untuk tabel `komentar`
-

MENCIPTAKAN  TABLE  IF  NOT  EXISTS  ` komentar ` (
  ` Id `  int ( 11 ) NOT  NULL ,
  ` Komentar `  teks  TIDAK  NULL ,
  ` PostID `  int ( 11 ) NOT  NULL
) ENGINE = InnoDB AUTO_INCREMENT = 51 DEFAULT CHARSET = latin1;

-
- Membuang data untuk tabel `komentar`
-

INSERT  INTO  ` komentar ` ( ` id ` , ` komentar ` , ` postID ` ) VALUES
( 1 , ' ah masa?' , 1 ),
( 2 , ' serius?' , 1 ),
( 3 , ' lol' , 5 ),
( 4 , ' haha' , 5 ),
( 5 , ' manatap jiwa' , 5 ),
( 7 , ' jangan lupa selamat dan koma titik' , 3 ),
( 41 , ' hmmmmmm ...' , 4 ),
( 42 , ' hahahaha' , 4 ),
( 43 , ' mantap' , 2 ),
( 44 , ' ko bisa?' , 2 ),
( 45 , ' dsad' , 2 ),
( 46 , ' sedih' , 2 ),
( 47 , ' hahahaha' , 3 ),
( 48 , ' lucu' , 3 ),
( 49 , ' tes lagi ah' , 0 ),
( 50 , ' tes lagi ah' , 5 );

- ------------------------------------------------ --------

-
- Struktur tabel untuk tabel `posting`
-

MENCIPTAKAN  TABLE  IF  NOT  EXISTS  ` posting ` (
  ` Id `  int ( 11 ) NOT  NULL ,
  ` Judul `  varchar ( 255 ) NOT  NULL ,
  ` Konten `  teks  TIDAK  NULL ,
  ` Createdby `  int ( 11 ) NOT  NULL
) ENGINE = InnoDB AUTO_INCREMENT = 6 DEFAULT CHARSET = latin1;

-
- Membuang data untuk tabel `posting`
-

INSERT  INTO  ` posting ` ( ` id ` , ` judul ` , ` konten ` , ` createdby ` ) VALUES
( 1 , ' Wanita Itu Diserang Kadal Saat Mengunjungi Kebun Binatang' , ' Lorem ipsum dolor sit amet, consectetur adipisicing elite, sed do eiusmod \ r \ ntempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, \ rquis nquis Latihan khusus adalah cara yang tepat bagi Anda untuk melakukan hal yang sama. Anda dapat menggunakan berbagai cara di bawah ini untuk meningkatkan kecepatan Anda dengan lebih cepat atau lebih baik daripada kecepatan, kecuali jika Anda ingin melakukannya, kecuali jika Anda ingin melakukannya. deserunt mollit anim id est laborum. ' , 1 ),
( 2 , ' Azab Tukang Tikung Kuburan Direbut Orang' , 'Anda juga dapat memilih warna-warni, melihat-lihat berbagai fitur, dan melakukan pekerjaan lain untuk mendapatkan lebih banyak dan lebih baik dengan cara seperti itu. Jika Anda ingin menggunakan minimal, lakukan latihan non-aktif dengan menggunakan fitur ini dan pastikan untuk melakukan hal yang sama. Tambahkan semua warna di halaman ini dalam waktu dekat atau klik untuk melihat gambar di bawah ini. Pengecualian tersedia untuk orang lain, kecuali jika Anda memilih ponsel Anda untuk melihat lebih lanjut. Baca lebih lanjut tentang semua, lebih baik pilih baik-baik saja, lakukan juga lebih baik untuk melakukan pekerjaan lain di labore dan dolore magna aliqua. Jika Anda ingin menggunakan minimal, lakukan latihan non-aktif dengan menggunakan fitur ini dan pastikan untuk melakukan hal yang sama. Tambahkan semua warna di halaman ini dalam waktu dekat atau klik untuk melihat gambar di bawah ini. Pengecualian untuk cupidatat bukan khusus,, 1 ),
( 3 , ' Bangkit Dari Kubur Karena Lupa Titik Koma' , 'Anda juga dapat memilih warna-warni, melihat-lihat berbagai fitur, dan melakukan pekerjaan lain untuk mendapatkan lebih banyak dan lebih baik dengan cara seperti itu. Jika Anda ingin menggunakan minimal, lakukan latihan non-aktif dengan menggunakan fitur ini dan pastikan untuk melakukan hal yang sama. Tambahkan semua warna di halaman ini dalam waktu dekat atau klik untuk melihat gambar di bawah ini. Pengecualian tersedia untuk orang lain, kecuali jika Anda memilih ponsel Anda untuk melihat lebih lanjut. Baca lebih lanjut tentang semua, lebih baik pilih baik-baik saja, lakukan juga lebih baik untuk melakukan pekerjaan lain di labore dan dolore magna aliqua. Jika Anda ingin menggunakan minimal, lakukan latihan non-aktif dengan menggunakan fitur ini dan pastikan untuk melakukan hal yang sama. Tambahkan semua warna di halaman ini dalam waktu dekat atau klik untuk melihat gambar di bawah ini. Pengecualian untuk cupidatat bukan khusus,, 1 ),
( 4 , ' Kakakku Ternyata Anak Dari Ayahku' , 'Anda juga dapat memilih warna-warni, melihat-lihat berbagai fitur, dan melakukan pekerjaan lain untuk mendapatkan lebih banyak dan lebih baik dengan cara seperti itu. Jika Anda ingin menggunakan minimal, lakukan latihan non-aktif dengan menggunakan fitur ini dan pastikan untuk melakukan hal yang sama. Tambahkan semua warna di halaman ini dalam waktu dekat atau klik untuk melihat gambar di bawah ini. Pengecualian tersedia untuk orang lain, kecuali jika Anda memilih ponsel Anda untuk melihat lebih lanjut. Baca lebih lanjut tentang semua, lebih baik pilih baik-baik saja, lakukan juga lebih baik untuk melakukan pekerjaan lain di labore dan dolore magna aliqua. Jika Anda ingin menggunakan minimal, lakukan latihan non-aktif dengan menggunakan fitur ini dan pastikan untuk melakukan hal yang sama. Tambahkan semua warna di halaman ini dalam waktu dekat atau klik untuk melihat gambar di bawah ini. Pengecualian untuk cupidatat bukan khusus,, 2 ),
( 5 , ' Temanku Pengemis Online' , 'Anda juga dapat memilih warna-warni, melihat-lihat berbagai fitur, dan melakukan pekerjaan lain untuk mendapatkan lebih banyak dan lebih baik dengan cara seperti itu. Jika Anda ingin menggunakan minimal, lakukan latihan non-aktif dengan menggunakan fitur ini dan pastikan untuk melakukan hal yang sama. Tambahkan semua warna di halaman ini dalam waktu dekat atau klik untuk melihat gambar di bawah ini. Pengecualian tersedia untuk orang lain, kecuali jika Anda memilih ponsel Anda untuk melihat lebih lanjut. Baca lebih lanjut tentang semua, lebih baik pilih baik-baik saja, lakukan juga lebih baik untuk melakukan pekerjaan lain di labore dan dolore magna aliqua. Jika Anda ingin menggunakan minimal, lakukan latihan non-aktif dengan menggunakan fitur ini dan pastikan untuk melakukan hal yang sama. Tambahkan semua warna di halaman ini dalam waktu dekat atau klik untuk melihat gambar di bawah ini. Pengecualian untuk cupidatat bukan khusus,, 3 );

- ------------------------------------------------ --------

-
- Struktur tabel untuk tabel `pengguna`
-

MENCIPTAKAN  TABLE  IF  NOT  EXISTS  ` pengguna ` (
  ` Id `  int ( 11 ) NOT  NULL ,
  ` Nama `  varchar ( 32 ) NOT  NULL
) ENGINE = InnoDB AUTO_INCREMENT = 4 DEFAULT CHARSET = latin1;

-
- Membuang data untuk tabel `pengguna`
-

INSERT  INTO  ` pengguna ` ( ` id ` , ` nama ` ) VALUES
( 1 , ' Hamdan Ibrahim' ),
( 2 , ' Arka' ),
( 3 , ' Demy' );

-
- Indeks untuk tabel yang dibuang
-

-
- Indeks untuk tabel `komentar`
-
ALTER  TABLE  ` komentar `
  ADD PRIMARY  KEY ( ` id ` );

-
- Indeks untuk `posting` tabel
-
ALTER  TABLE  ` posting `
  ADD PRIMARY  KEY ( ` id ` );

-
- Indeks untuk `pengguna` tabel
-
ALTER  TABLE  ` pengguna `
  ADD PRIMARY  KEY ( ` id ` );

-
- AUTO_INCREMENT untuk tabel yang dibuang
-

-
- AUTO_INCREMENT untuk tabel `komentar`
-
ALTER  TABLE  ` komentar `
  MENGUBAH  ` id `  int ( 11 ) NOT  NULL AUTO_INCREMENT, AUTO_INCREMENT = 51 ;
-
- AUTO_INCREMENT untuk tabel `posting`
-
ALTER  TABLE  ` posting `
  MENGUBAH  ` id `  int ( 11 ) NOT  NULL AUTO_INCREMENT, AUTO_INCREMENT = 6 ;
-
- AUTO_INCREMENT untuk tabel `pengguna`
-
ALTER  TABLE  ` pengguna `
  MENGUBAH  ` id `  int ( 11 ) NOT  NULL AUTO_INCREMENT, AUTO_INCREMENT = 4 ;
/ * ! 40101 SET CHARACTER_SET_CLIENT = @ OLD_CHARACTER_SET_CLIENT * / ;
/ * ! 40101 SET CHARACTER_SET_RESULTS = @ OLD_CHARACTER_SET_RESULTS * / ;
/ * ! 40101 SET COLLATION_CONNECTION = @ OLD_COLLATION_CONNECTION * / ;
