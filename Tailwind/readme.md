# Tugas: Profil Instagram — Implementasi dengan Tailwind CSS

## Penjelasan Desain :
- Desain website dengan latar belakang hitam dan teks abu-abu serta putih menciptakan kesan minimalis, elegan, dan mudah dibaca. Kontras yang dihasilkan memudahkan pengunjung untuk fokus pada konten. Kesederhanaan desain memberikan tampilan modern dan profesional, serta nyaman di mata, terutama dalam kondisi pencahayaan rendah.

## Pertanyaan Reflektif:

#### ❓Bagaimana desain warna hitam, putih, dan abu-abu mempengaruhi kenyamanan pengguna dalam membaca konten di website?

- Desain dengan warna latar belakang hitam dan teks abu-abu serta putih memberikan kontras yang baik, sehingga memudahkan pengguna untuk membaca konten. Warna abu-abu yang lebih lembut tidak terlalu tajam di mata, sementara teks putih memberikan kejelasan tanpa menimbulkan silau.

#### ❓ Apakah kesederhanaan desain ini membantu pengunjung lebih fokus pada informasi yang disampaikan, atau justru terasa terlalu monoton?
- Kesederhanaan desain ini justru sangat membantu pengunjung untuk fokus pada informasi yang disampaikan. Dengan menghindari penggunaan elemen visual yang berlebihan, desain ini mengurangi gangguan dan memungkinkan konten menjadi pusat perhatian.

##

## 💬 Pertanyaan README:

#### ❓ Jelaskan keputusan grid-cols/gap di tiap breakpoint — kenapa begitu?

- Penggunaan grid-cols dan gap memungkinkan kita untuk membuat tata letak grid yang responsif, di mana jumlah kolom dan jarak antar elemen dapat disesuaikan berdasarkan ukuran layar. Dengan menerapkan breakpoint yang berbeda seperti sm, lg, dan xl, kita dapat mengoptimalkan desain untuk berbagai perangkat. Misalnya, pada layar kecil (mobile), kita menggunakan 1 kolom dengan jarak yang lebih sempit, sedangkan pada layar besar (desktop), jumlah kolom dan jarak antar elemen ditingkatkan untuk memanfaatkan ruang yang lebih besar. Pendekatan ini memastikan tampilan yang rapi, efisien, dan nyaman dilihat, serta memberikan pengalaman pengguna yang optimal di berbagai perangkat.


#### ❓ Bagaimana kamu memanfaatkan utility responsive Tailwind untuk memecahkan masalah layout yang muncul di mobile?

- Dengan memanfaatkan utility responsive Tailwind CSS, kita dapat dengan mudah mengatasi masalah layout yang muncul di perangkat mobile. Tailwind memungkinkan kita untuk menyesuaikan elemen-elemen seperti grid, flexbox, ukuran teks, padding, dan margin pada berbagai ukuran layar menggunakan breakpoint seperti sm, md, lg, dan xl. Pendekatan ini memastikan tampilan tetap efisien dan nyaman dibaca di layar kecil (mobile), sambil memanfaatkan ruang yang lebih luas di perangkat dengan ukuran layar lebih besar.


#### ❓ Jelaskan trade-off antara memakai banyak utility classes vs membuat component CSS tersendiri.

- Pemilihan antara menggunakan utility classes atau komponen CSS bergantung pada kebutuhan dan skala proyek. Utility classes memungkinkan pengembangan yang lebih cepat dan fleksibel, ideal untuk prototyping atau proyek kecil, namun dapat membuat HTML menjadi tidak rapi dan sulit dipelihara dalam jangka panjang. Di sisi lain, komponen CSS menawarkan keuntungan dalam hal reusabilitas, modularitas, dan pemeliharaan, meskipun memerlukan lebih banyak waktu dan kode untuk implementasinya. Oleh karena itu, pendekatan yang seimbang antara keduanya sering kali menjadi solusi terbaik, di mana utility classes digunakan untuk pengaturan layout yang cepat, sementara komponen CSS digunakan untuk elemen yang membutuhkan konsistensi dan pemeliharaan lebih baik.

