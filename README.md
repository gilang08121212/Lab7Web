# Lab7Web
------------------------------------------------------------------PRAKTIKUM 1 ------------------------------------------------------------

Setelah semua latihan selesai dan dokumentasi lengkap, saya commit hasil kerja saya ke dalam repository. Ini adalah cara untuk menyimpan dan merekam semua perubahan yang saya buat di dalam repository. Untuk mendokumentasikan progres saya, setiap kali saya selesai dengan satu bagian latihan, saya mengambil screenshot sebagai bukti perubahan yang saya buat. Ini penting untuk menunjukkan bahwa setiap langkah berhasil dijalankan dengan baik.:)
![Image](https://github.com/user-attachments/assets/60de252d-f3e5-49c0-8687-b0b7633c4a45)
![Image](https://github.com/user-attachments/assets/213c2197-52cc-4dc3-aad5-44ea1096ff0d)
![Image](https://github.com/user-attachments/assets/c20f7495-df79-4cdf-bca6-e119e11d2f77)
![Image](https://github.com/user-attachments/assets/117bc3f2-0c3e-4366-8742-17b771672a53)
![Image](https://github.com/user-attachments/assets/86c3d566-faa4-40c8-ba48-a2c38d3c7aef)
![Image](https://github.com/user-attachments/assets/51d5cc77-b65c-47b7-bd2a-ef59760e9c95)
![Image](https://github.com/user-attachments/assets/f5c4bbf7-898d-4fd6-bde1-74d389ce1ea4)



----------------------------------------------------------PRAKTIKUM 2-------------------------------------------------------------------


Memulai dengan praktikum CRUD (Create, Read, Update, Delete) menggunakan CodeIgniter 4. Pada halaman ini, fokusnya adalah pada pembuatan database dan tabel artikel yang memiliki beberapa kolom seperti judul, isi, slug, dan status. Juga mencakup pengaturan koneksi database melalui file .env.
![image](https://github.com/user-attachments/assets/20dfd2f5-1f32-47b7-b82f-a44e1f02d9e5)

Mengajarkan cara membuat tampilan detail artikel yang dapat diakses melalui slug artikel, sehingga setiap artikel bisa dilihat lebih mendalam dengan mengklik judul artikel. Halaman ini juga mencakup cara menampilkan artikel berdasarkan slug dengan menambahkan fungsi view() dalam controller.
![Image](https://github.com/user-attachments/assets/bdedabea-46b9-4a09-9dc6-049e28ca19b7)
Tampilan Artikel pertama
![image](https://github.com/user-attachments/assets/c4941d15-2cdb-46af-abff-d795995857a8)
Tampilan Artikel kedua
![image](https://github.com/user-attachments/assets/c3e0bf21-f992-4f3d-8628-02139c393d8e)
Tampilan Admin: Dibuat tampilan admin_index.php yang menampilkan artikel dalam tabel dengan opsi aksi (ubah, hapus).
![image](https://github.com/user-attachments/assets/2a8bbf81-148b-47d7-850f-43d2799804cb)
Tampilan Form Tambah, Tampilan untuk menambah dengan validasi inputan dan penyimpanan data menggunakan model.
![image](https://github.com/user-attachments/assets/e57d903f-c858-4b56-8cde-3f11be3963f7)
Tampilan Form Edit, Tampilan untuk mengedit dengan validasi inputan dan penyimpanan data menggunakan model.
![image](https://github.com/user-attachments/assets/7d04bf62-b70c-4867-beea-3c334c8447da)



----------------------------------------------------------PRAKTIKUM 3-------------------------------------------------------------------



![image](https://github.com/user-attachments/assets/9d52fe3c-7917-43b8-8f12-4f907402ea20)
![image](https://github.com/user-attachments/assets/76879078-1cea-451f-a521-ff360a198805)
Apa manfaat utama dari penggunaan View Layout dalam pengembangan aplikasi? 
Manfaat utama dari penggunaan View Layout dalam pengembangan aplikasi adalah untuk memisahkan tampilan aplikasi menjadi bagian-bagian yang dapat digunakan kembali (reusable). Dengan View Layout, kita dapat mendefinisikan struktur dasar halaman (seperti header, footer, dan sidebar) dalam satu tempat dan memuat konten yang berbeda untuk setiap halaman. Hal ini membuat pengelolaan tampilan menjadi lebih efisien dan mudah dipelihara.

Jelaskan perbedaan antara View Cell dan View biasa.?
*View biasa adalah file tampilan statis yang langsung menampilkan data yang diteruskan dari controller, dan digunakan untuk menampilkan halaman secara keseluruhan.
*View Cell adalah komponen tampilan yang dapat dipanggil secara modular di berbagai bagian aplikasi, seperti sidebar atau widget. Ini memungkinkan pengelolaan bagian kecil tampilan yang digunakan ulang dengan lebih efisien, serta memudahkan integrasi elemen dinamis tanpa merubah keseluruhan layout


----------------------------------------------------------PRAKTIKUM 4-------------------------------------------------------------------


![image](https://github.com/user-attachments/assets/ff58eada-9b55-48ac-98d1-bb78fdc891cc)
![image](https://github.com/user-attachments/assets/7f48d2e2-cc69-4e7e-82da-5ebeb0471959)
![image](https://github.com/user-attachments/assets/c95e9af6-970b-40d5-b404-d46aa639ef95)
![image](https://github.com/user-attachments/assets/ef795a0f-392a-4892-ad2b-4ca609033f75)
Modul Praktikum 4 dalam pemrograman web dengan menggunakan framework CodeIgniter 4 berfokus pada pembuatan sistem login. Tujuan utamanya adalah untuk memahami konsep autentikasi (Auth) dan penggunaan filter dalam aplikasi, serta membangun modul login yang memungkinkan pengguna untuk masuk ke dalam aplikasi.



----------------------------------------------------------PRAKTIKUM 5-------------------------------------------------------------------
Modul Praktikum 5 ini membahas tentang implementasi Pagination dan Pencarian menggunakan framework CodeIgniter 4. Tujuan praktikum ini adalah agar mahasiswa dapat memahami dan mengaplikasikan konsep dasar pagination untuk membatasi tampilan data, serta teknik pencarian untuk memfilter data berdasarkan kata kunci.

saya dapat Membuat pagination untuk menampilkan data dalam beberapa halaman.
saya dapat Menambahkan fitur pencarian untuk memfilter data berdasarkan input pengguna.
saya juga dapat  melakukan uji coba dengan menambahkan data dan memastikan pagination dan pencarian berfungsi dengan baik.
![image](https://github.com/user-attachments/assets/b00083c5-c71c-4bf7-880f-24eaa3f3a400)

----------------------------------------------------------PRAKTIKUM 6-------------------------------------------------------------------
Pada Praktikum 6, Anda mempelajari cara mengimplementasikan fitur upload gambar pada artikel menggunakan Framework CodeIgniter 4.
Membuat validasi data pada controller artikel untuk memastikan data yang diinputkan valid.
Menggunakan metode getFile() untuk menangani file gambar yang diupload, dan memindahkan file tersebut ke folder publik.
Menyimpan data artikel (judul, isi, slug, dan nama gambar) ke dalam database.
Menambahkan input file pada form di tampilan untuk memungkinkan pengguna meng-upload gambar saat menambah artikel.
![image](https://github.com/user-attachments/assets/bc8a59a3-506c-41f0-a61a-df01f4085104)
![image](https://github.com/user-attachments/assets/cc19dd32-6de9-4ec0-bd52-caeb0140f37f)


----------------------------------------------------------PRAKTIKUM 7-------------------------------------------------------------------
Modul Praktikum 7 mengajarkan cara membuat relasi antar tabel di database menggunakan CodeIgniter 4. Fokus utama adalah pada relasi One-to-Many, seperti menghubungkan tabel artikel dengan kategori. Praktikum ini mencakup langkah-langkah berikut:

Membuat tabel kategori dan menambahkannya sebagai foreign key di tabel artikel.

Menggunakan Query Builder untuk melakukan join antar tabel dan menampilkan data artikel beserta kategori.

Mengubah model, controller, dan view untuk menampilkan kategori pada artikel.

Menambahkan fitur seperti pencarian artikel berdasarkan kategori dan menampilkan kategori di halaman depan.

Memodifikasi View: View diubah agar data kategori ditampilkan bersama artikel, baik di halaman depan maupun di halaman admin.

<img width="1365" height="729" alt="image" src="https://github.com/user-attachments/assets/929b54ee-546b-4421-8b12-9e4b8ad028cb" />
<img width="1365" height="728" alt="image" src="https://github.com/user-attachments/assets/380377f0-e4ca-4269-8aa4-60059c0b3c64" />
<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/1d2453b9-6287-447b-ac08-25fa3d6f5734" />
<img width="1365" height="726" alt="image" src="https://github.com/user-attachments/assets/3b4de24b-dd13-42cc-86b8-956bf7e39a1f" />

----------------------------------------------------------PRAKTIKUM 9-------------------------------------------------------------------
Modul Praktikum 9 ini bertujuan untuk membantu mahasiswa memahami dan mengimplementasikan AJAX untuk pagination dan search dalam aplikasi web berbasis CodeIgniter 4. Praktikum ini bertujuan meningkatkan performa dan pengalaman pengguna (UX) aplikasi web dengan cara memperkenalkan teknik pemrograman yang lebih efisien dan interaktif.
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/c1aafd74-9a7e-45a3-bcbf-1ce78c68e914" />

----------------------------------------------------------PRAKTIKUM 10-------------------------------------------------------------------
Modul ini memberikan pemahaman praktis tentang bagaimana membuat dan menguji REST API menggunakan CodeIgniter 4, serta bagaimana menghubungkan backend dengan aplikasi frontend melalui API. Praktikum ini penting untuk memperkenalkan cara kerja API dalam aplikasi web dan memberikan keterampilan untuk membangun aplikasi berbasis API yang efisien.
<img width="1125" height="767" alt="image" src="https://github.com/user-attachments/assets/0e8e7661-54da-418f-b010-228a5fac8490" />
<img width="1365" height="717" alt="image" src="https://github.com/user-attachments/assets/f37032ca-16e2-498e-a753-c22329e3cd05" />

----------------------------------------------------------PRAKTIKUM 11-------------------------------------------------------------------
Modul ini mengajarkan cara membuat REST API menggunakan CodeIgniter 4. Tujuannya adalah memahami konsep API dan RESTful, serta membuat API yang dapat digunakan untuk mengakses data (menambah, mengubah, menghapus) menggunakan metode HTTP (GET, POST, PUT, DELETE). Langkah-langkahnya meliputi pembuatan model, controller, routing, dan pengujian API menggunakan Postman. Tugas praktikum mencakup pengembangan API dan dokumentasi perubahan pada repository.
<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/9bb6b712-6fb4-4a02-a5ae-b566578ecf58" />
<img width="1365" height="728" alt="image" src="https://github.com/user-attachments/assets/6769576f-75de-4744-9ffc-41bc87ca3569" />
<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/94baa1a1-e789-40e6-94b4-e3670bd3e892" />
<img width="1365" height="726" alt="image" src="https://github.com/user-attachments/assets/edb51110-1ddd-471a-ad66-83186b965cd3" />

















