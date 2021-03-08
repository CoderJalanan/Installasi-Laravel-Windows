
# INSTALLASI LARAVEL FRAMEWORK DI WINDOWS

## Video Tutorial Here : [ https://www.youtube.com/watch?v=cUs4gcTrHJM ]

## 1. Download XAMPP ( Versi Bebas )

| File Name | Link |
| ------ | ------ |
| XAMPP | [ https://www.apachefriends.org/download.html ] |
   
## 2. Download Composer

| File Name | Link |
| ------ | ------ |
| Composer | [ https://getcomposer.org/Composer-Setup.exe ] |
   
## 3. Install XAMPP Yang telah di download

## 4. Instal Composer Yang Telah Di Download

## 5. Restart Perangkat ( Jika dibutuhkan )

## 6. Buka Command Prompt ( CMD ) Arahkan ke Directory 
```sh
$ cd C:/xampp/htdocs
```

## 7. Jalankan Perintah di Command Prompt
```sh
$ composer create-project laravel/laravel Lara-CJID

#Lara-CJID merupakan nama folder / lokasi installasi laravel
```
   
## 8. Tunggu Proses Installasi Selesai

## 9. Setelah Selesai , Buka Command Prompt ( CMD ) arahkan ke folder installasi laravel
   - ***Lara-CJID***
   
## 10. Untuk Menjalankan Laravel Ketikan Perintah 
```sh
$ php artisan serve
```

## 11. Akses Halaman Laravel Default di URL 
   - ***localhost:8000 / 127.0.0.1:8000***
   
## 12. Host dan Port untuk mengakses laravel dapat diganti ( Sesuaikan kebutuhan ).
```sh
$ php artisan serve --host=IP_Perangkat --port=Bebas
```
