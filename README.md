<p align="center">
  <a href="https://github.com/CoderJalanan">
    <img src="https://avatars.githubusercontent.com/u/48448220" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Installasi Laravel Framework on Windows</h3>

  <p align="center">
    This repositories, showing up step by step how to install the Laravel Framework in Windows 10.
    <br /><br />
    <a href="https://github.com/CoderJalanan?tab=repositories" target="_blank"><strong>Explore Repositories »</strong></a>
    <br />
    <br />
    <a href="https://www.youtube.com/c/CoderJalanan" target="_blank">Youtube</a>
    ·
    <a href="https://www.facebook.com/CoderJalanan" target="_blank">Facebook</a>
    ·
    <a href="https://www.instagram.com/coder_jalanan" target="_blank">Instagram</a>
  </p>
</p>

## | Video Tutorial (YouTube)

| Title | Link |
| ------ | ------ |
| Watch Tutorial Laravel Installatioon | <a href="https://www.youtube.com/watch?v=cUs4gcTrHJM" target="_blank"> Click Me </a> |


<details open="open">
   <summary><h2 style="display: inline-block"> | Petunjuk Installasi</h2></summary>

* Download XAMPP ( Versi Bebas )
  | File Name | Link |
  | ------ | ------ |
  | XAMPP | <a href="https://www.apachefriends.org/download.html" target="_blank"> Download </a> |
* Download Composer
  | File Name | Link |
  | ------ | ------ |
  | Composer | <a href="https://getcomposer.org/Composer-Setup.exe" target="_blank"> Download </a> |
* Install XAMPP Yang telah di download
* Instal Composer Yang Telah Di Download
* Restart Perangkat ( Jika dibutuhkan )
* Buka Command Prompt ( CMD ) Arahkan ke Directory 
  ```sh
  $ cd C:/xampp/htdocs
  ```
* Jalankan Perintah di Command Prompt
  ```sh
  $ composer create-project laravel/laravel Lara-CJID
  #Note : "Lara-CJID" merupakan nama folder / lokasi installasi laravel
  ```
* Tunggu Proses Installasi Selesai
* Setelah Selesai , Buka Command Prompt ( CMD ) arahkan ke folder installasi laravel
  - ***Lara-CJID***
* Untuk Menjalankan Laravel Ketikan Perintah
  ```sh
  $ php artisan serve
  ```
* Akses Halaman Laravel Default di URL 
  - ***localhost:8000 / 127.0.0.1:8000***
* Host dan Port untuk mengakses laravel dapat diganti ( Sesuaikan kebutuhan ).
  ```sh
  $ php artisan serve --host=IP_Perangkat --port=Bebas
  ```
</details>
  
  
## | License

This repositories license is "None License".
