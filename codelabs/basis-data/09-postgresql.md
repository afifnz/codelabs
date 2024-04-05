summary: PostgreSQL
id: 09-postgresql
categories: Basis Data
tags: Basis Data
status: Published 
authors: Achmad Afiffudin Nurzein


## Instalasi PostgreSQL
### Unduh Installer PostgreSQL
Kunjungi situs resmi PostgreSQL di [https://www.postgresql.org/downnload/windows](https://www.postgresql.org/download/windows/). Pilih versi PostgreSQL yang sesuai dengan sistem operasi Windows Anda (32-bit atau 64-bit).
### Jalankan Installer
Setelah selesai mengunduh, buka file installer PostgreSQL yang sudah diunduh. Klik dua kali pada file installer untuk memulai proses instalasi.
![](images/09-install.webp)
### Pilih kompenen yang ingin anda install


Pilih lokasi di mana Anda ingin menginstal PostgreSQL. Secara default, ini akan menjadi `C:\Program Files\PostgreSQL\<version>`. Klik "Next" untuk melanjutkan.
![](images/09-install-1.webp)


5. Atur kata sandi untuk pengguna postgres, yang merupakan pengguna administratif default. Klik `Next`.
![](images/09-install-4.webp)
    > aside positive
    > Pastikan untuk mengingat kata sandi yang Anda pilih.
6. Pilih port yang akan digunakann oleh server PostgreSQL. Port default adalah  `54321`.
![](images/09-install-5.webp)
7. Pilih apakah Anda ingin menginstal Stack Builder dan/atau command line tools tambahan. Klik `Next`.
8. Klik "Next" untuk memulai instalasi. Tunggu sampai proses instalasi selesai.
9. Setelah instalasi selesai, Anda akan melihat layar konfirmasi.
Pastikan untuk memeriksa opsi untuk memulai Stack Builder jika Anda memilih untuk menginstalnya.
Klik "Finish" untuk menutup installer.


Setelah instalasi selesai, Anda dapat memulai menggunakan PostgreSQL di Windows Anda. Pastikan untuk memulai layanan PostgreSQL setelah instalasi selesai untuk dapat mengakses server database.