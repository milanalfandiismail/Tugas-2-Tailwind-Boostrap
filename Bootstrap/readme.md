# Tugas: Profil Instagram — Implementasi dengan Bootstrap Grid

## Penjelasan Singkat

### 🔧 Struktur File:
Penjelasan Struktur Folder:

📁 **Folder Root: Bootstrap**  
Ini adalah folder utama tempat semua file proyek Anda disimpan. Di dalam folder ini, menyimpan semua file dan folder yang membentuk website profil Instagram menggunakan Bootstrap.

📂 **assets/**  
Folder ini berfungsi untuk menyimpan semua file aset yang digunakan.

📁 **assets/img/**  
Folder ini khusus digunakan untuk menyimpan gambar-gambar yang akan ditampilkan di website, seperti gambar profil, gambar postingan, dan gambar untuk story. Folder ini memiliki beberapa sub-folder untuk mengorganisir gambar berdasarkan jenisnya.

  📂 **assets/img/posts/**  
  Sub-folder ini menyimpan gambar-gambar yang digunakan untuk postingan.

  📂 **assets/img/profile_picture/**  
  Sub-folder ini menyimpan gambar-gambar yang digunakan untuk **profile_picture**.

  📂 **assets/img/story/**  
  Folder ini digunakan untuk gambar-gambar yang akan ditampilkan sebagai **Instagram Stories**. Gambar-gambar ini umumnya merupakan gambar sementara yang ditampilkan dalam format stories.

📂 **assets/css/**  
Folder ini digunakan untuk menyimpan file-file **CSS**. Di dalam folder ini, Anda bisa memiliki file **CSS utama** untuk mendesain tampilan halaman, serta file **CSS kustom** untuk penyesuaian elemen-elemen tertentu pada halaman web Anda.


Build/Run: 
Disini Menggunakan CDN sebagai run nya, disini kita hanya menaruh pada file htmlnya saja, jadi lansung ngerun cdn bootstrap tersebut 

Dependensi: Bootstrap

## 💬 Pertanyaan README:

### ❓ Mengapa memilih konfigurasi **col** tertentu untuk tiap **breakpoint**?

Untuk menyesuaikan tata letak konten dengan ukuran layar yang berbeda, sehingga memastikan bahwa tampilan web tetap **responsif** dan mudah dijangkau oleh pengguna di berbagai device/perangkat.

### ❓ Bagaimana kamu memastikan tombol **Follow** / **Edit Profile** tetap mudah dijangkau di mobile? Jelaskan pendekatannya.

Untuk memastikan tombol **Follow** dan **Edit Profile** tetap mudah dijangkau di mobile, kita dapat menggunakan **Flexbox**. Dengan memanfaatkan kelas seperti `d-flex`, `flex-column`, dan `flex-sm-row`, tombol akan disusun secara **vertikal** di perangkat kecil (mobile) dan **horizontal** di perangkat besar (tablet/desktop). Ini memastikan tombol tidak saling bertumpuk, tetap proporsional, dan mudah diakses tanpa harus menggulir secara horizontal.

### ❓ Jika postingan bertambah jadi **50**, apa potensi masalah dan bagaimana solusi gridmu mengatasinya?

Potensi masalah yang terjadi adalah memastikan gambar memiliki ukuran yang **konsisten** agar grid tetap rapi. Solusi dari itu, kita menggunakan dari framework bootstrap yaitu fungsi dari **row** dan juga **grid**, dimana gridnya menggunakan: 

`col-12 col-sm-6 col-lg-3`


Grid ini membantu untuk memastikan kolom menyesuaikan ukurannya dengan baik di berbagai ukuran layar, menjaga desain tetap responsif meski jumlah postingan bertambah banyak.

