# TUGAS PRAKTIKUM 3
- **Nama**    : Kangga Fajarulhakim
- **Kelas**   : TI.23.A.4
- **NIM**     : 312310430
- **Mata Kuliah**: Pemprograman Web 1

**PRAKTIKUM**

*MEMBUAT LAYOUT SEDERHANA*

1. Buat folder baru kemudian di dalamnya tambahkan file **home.html** dan file css **style.css**
   ![Screenshot_5](https://github.com/user-attachments/assets/a1627f00-0b77-4855-ad87-47a205bae195)<br>
   *lalu tambahkan kode berikut*<br>
   ![Screenshot_7](https://github.com/user-attachments/assets/e2d6b8ab-e767-42d2-a267-199ba1df1c43) <br>
   Kode HTML ini adalah dasar dari sebuah halaman web dengan elemen-elemen tata letak sederhana.
   - header, berfungsi untuk menampilkan konten di bagian atas halaman, seperti judul atau logo.
   - nav, Bagian ini adalah area navigasi. Biasanya digunakan untuk menampilkan menu atau tautan ke halaman lain di dalam situs web.
   - section id="hero", Bagian ini biasanya digunakan untuk elemen besar di bagian atas halaman (seperti gambar hero atau konten penting yang menarik perhatian).
   - section id="wrapper", adalah pembungkus atau wadah untuk elemen-elemen lain. Di dalamnya terdapat elemen lain seperti **main** dan **aside**.
   - section id="main", Bagian utama konten halaman/bagian ini biasanya memuat artikel atau informasi utama yang ingin disampaikan di halaman tersebut.
   - aside id="sidebar", Bagian samping (sidebar) sering digunakan untuk menampilkan konten sekunder seperti tautan, iklan, atau informasi tambahan yang tidak berada di bagian utama.
   - footer, Bagian paling bawah dari halaman web yang biasanya berisi informasi seperti hak cipta atau informasi tentang pemilik situs web.<br>
   *kemudian tambahkan kode css untuk untuk layoutnya*<br>
   ![Screenshot_8](https://github.com/user-attachments/assets/bc0cf565-4d44-44c2-a240-c9ef86d34d3b)<br>
   dalam kode css tersebut menggunakan @import untuk mengambil font dari google font. secara keseluruhan Kode CSS ini mengatur tampilan dasar dari halaman web, termasuk reset CSS, pengaturan font, dan tata letak. Ada pengaturan lebar kontainer untuk menyesuaikan layout halaman, serta efek bayangan pada elemen kontainer. Header dan judul utama memiliki padding dan margin yang menambah ruang di sekitarnya, dan keseluruhan teks pada halaman menggunakan font Open Sans dengan warna abu-abu.<br>
   *berikut hasil dari keseluruhan kode*<br>
   ![Screenshot_9](https://github.com/user-attachments/assets/13c31a6e-6952-4294-a6b5-d7a811c45211)

2. Menambahkan kode CSS untuk mengatur navigasi dan tautan yang ada di dalamnya. berikut kodenya,<br>
   ![Screenshot_10](https://github.com/user-attachments/assets/c554a212-a80f-487b-bc05-6ba1df7b2f8c)<br>
   *dan hasilnya akan seperti ini*<br>
   ![Screenshot_11](https://github.com/user-attachments/assets/5292bd95-9e80-414f-8f29-80ac7eb0bd88)<br>
   Kode CSS ini mendefinisikan tampilan menu navigasi dengan latar belakang biru dan teks putih dan tautan dalam navigasi ditampilkan sebagai blok kecil dengan padding yang cukup besar, membuatnya lebih mudah diklik.

3. Membuat hero panel, "hero section" ini sering digunakan untuk menarik perhatian pengguna. Berikut kodenya, <br>
  ![Screenshot_12](https://github.com/user-attachments/assets/c7fdcde2-530e-42a9-8a97-edd93220340d)<br>
  *dan tambahkan juga kode CSS nya*<br>
  ![Screenshot_13](https://github.com/user-attachments/assets/a70d0497-5319-4ac1-be45-6f82f9b68654)<br>
  ![Screenshot_14](https://github.com/user-attachments/assets/dcecd27c-6f1f-4cc9-a1aa-e521626a6337)

4. Mengatur layout main dan sidebar, dengan CSS float<br>
   ![Screenshot_29](https://github.com/user-attachments/assets/3b376227-adc5-456a-8f50-0f6dc096fc8c)<br>
   #main dan #sidebar menggunakan properti float: left, yang berarti kedua elemen ini akan saling berdampingan di sebelah kiri secara horizontal, dengan konten utama lebih lebar dibandingkan dengan sidebar. kemudian menambahkan sebuah elemen aside dengan ID sidebar yang berisi dua widget atau kotak informasi. berikut kodenya,<br>
   ![Screenshot_15](https://github.com/user-attachments/assets/3e344735-73ab-4385-b178-f7750f823eaa)<br>
   elemen aside ini sering digunakan untuk menampilkan konten tambahan atau sekunder yang mendampingi konten utama di halaman web, seperti tautan, teks tambahan, atau widget lainnya. selanjutnya menambahkan CSS,<br>
   ![Screenshot_30](https://github.com/user-attachments/assets/c2ab7271-10c8-4772-9195-ccb1484d4a15)<br>
   ![Screenshot_31](https://github.com/user-attachments/assets/57a02cf3-dd24-4b16-b96f-c936c8ed5483)<br>
   Kode CSS ini mengatur tampilan untuk elemen widget yang ada di sidebar. beriku hasilnya,<br>
   ![Screenshot_19](https://github.com/user-attachments/assets/2b5a22b3-38af-4f02-a018-d36e64ce8655)

5. Menambahkan CSS untuk mengatur tampilan footer, berikut kode CSS nya,<br>
   ![Screenshot_20](https://github.com/user-attachments/assets/35d1240b-66ce-4810-bd2d-615a29cf9bd5)<br>
   kode ini menciptakan tampilan footer yang sederhana namun bersih dan agar terlihat profesional, cocok untuk desain halaman web yang modern.<br>
   ![Screenshot_21](https://github.com/user-attachments/assets/74ecfbfc-fb55-4f27-8fb5-b5776960e49e)

6.Menambahkan elemen lainnya dalam main content. berikut kodenya,<br>
  ![Screenshot_23](https://github.com/user-attachments/assets/eb0977cc-5b6a-44e0-be85-55d2104ac380)<br>
  Kode di atas mendefinisikan sebuah bagian dari halaman web di dalam elemen <section> dengan ID main, yang menampilkan tiga kotak konten (box) di dalam baris yang sama. Setiap kotak berisi gambar, judul, paragraf teks, dan sebuah tombol untuk detail lebih lanjut. selanjutnya tambahkan kode CSS nya,<br>
  ![Screenshot_24](https://github.com/user-attachments/assets/4eaa0910-68d7-4f46-bd7b-d99c033effe2)<br>
  ![Screenshot_25](https://github.com/user-attachments/assets/d66a4450-b160-4b99-b49c-5bd1c2dbd5e7)<br>
  Kode ini digunakan untuk menata kotak konten (.box) dalam layout grid dengan tiga kolom yang di-float sejajar dalam satu baris. Setiap kotak memiliki gambar berbentuk lingkaran, judul, teks paragraf, dan elemen lain yang ditata dengan jarak yang baik dan terpusat. Teknik clearfix digunakan untuk memastikan baris bekerja dengan baik meskipun ada elemen yang di-float. berikut hasilnya,<br>
  ![Screenshot_22](https://github.com/user-attachments/assets/3b248b4f-78df-482e-9d76-04471ff9e731)

7.Selanjutnya menambahkan konten artikel <br>
  ![Screenshot_26](https://github.com/user-attachments/assets/c25dcd3a-983a-4970-a613-0a98655e6696)<br>
  Kode ini menampilkan dua artikel dengan judul, gambar, dan teks deskripsi.
  -Artikel pertama memiliki gambar yang ditampilkan secara default (kemungkinan besar di atas teks), sedangkan artikel kedua menggunakan kelas right-img untuk menampilkan gambar di sebelah kanan teks.
  -Garis horizontal dengan kelas divider digunakan untuk memisahkan konten antarartikel, memberikan pemisahan visual yang jelas.<br>
  *kemudian tambahkan CSS*<br>
  ![Screenshot_27](https://github.com/user-attachments/assets/b8b40bfa-c6bd-44d5-a2cf-b49ed5635286)<br>
  Gaya .divider digunakan untuk membuat garis pemisah yang bersih dan sederhana dengan jarak yang cukup antar konten. sedangkan Gaya .entry dan elemen-elemen di dalamnya (seperti heading, paragraf, dan gambar) diatur agar konten artikel terlihat terstruktur dan mudah dibaca. Gambar dalam artikel diatur agar bisa mengapung ke kiri atau kanan, memberikan fleksibilitas dalam tata letak konten. berikut hasilnya,<br>
  ![Screenshot_28](https://github.com/user-attachments/assets/2856c3ce-01c6-451a-b69f-2b3e40354ee3)


**Pertanyaan dan Tugas**
1. Tambahkan Layout untuk menu About
=> buat single layout yang berisi deskripsi, portfolio, dll
  ![Screenshot_34](https://github.com/user-attachments/assets/07087fdc-5f3a-44b8-91fb-bc272ae378f1)<br>
  ![Screenshot_33](https://github.com/user-attachments/assets/9088ae5b-3663-4026-b55a-86316f8906bc)<br>
  ![Screenshot_32](https://github.com/user-attachments/assets/fe718fa5-4baa-4510-8558-f49d74c44688)<br>
  *berikut hasilnya*<br>
  ![Screenshot_35](https://github.com/user-attachments/assets/5bd2e3a5-6fff-465e-ad23-bd1b1ac31f09)

2. Tambahkan layout untuk menu Contact
=> yang berisi form isian: nama, email, message, dll
  ![Screenshot_37](https://github.com/user-attachments/assets/3ed2d49f-ebaa-41db-84ba-ac8fca642811)<br>
  ![Screenshot_38](https://github.com/user-attachments/assets/fa489f1b-2fea-4550-aec0-7aef20205a36)<br>
  ![Screenshot_39](https://github.com/user-attachments/assets/eab8bdeb-6798-4907-84c3-409c43f656e5)<br>
  ![Screenshot_36](https://github.com/user-attachments/assets/b9766ee6-76ce-4ad5-b4d1-f7abaab5e1c4)<br>
  ![Screenshot_40](https://github.com/user-attachments/assets/d7c04196-1964-4d96-a059-15efbb8b8f04)






















  







  



  

