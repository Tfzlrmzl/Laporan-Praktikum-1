Laporan Praktikum 1
Jawaban Pertanyaan
1. Perubahan kode dan error pada penulisan tag
Jika ada kesalahan penulisan tag (misalnya <p>ditutup dengan </pp>atau <im>bukannya <img>), browser biasanya tidak menampilkan error langsung seperti bahasa pemrograman.
Dampaknya: tampilan halaman bisa berantakan (teks tidak terformat, gambar tidak muncul, dll), namun tidak ada pesan error yang muncul.
2. Perbedaan <p>dan<br>
<p>→ Membuat paragraf baru . Browser otomatis memberi jarak (margin) di atas dan bawah teks.
<br>→ Hanya membuat baris baru (line break) tanpa memberi jarak antar paragraf.
Contoh:

<p>Ini paragraf pertama.</p>
<p>Ini paragraf kedua.</p>

Ini baris pertama.<br />
Ini baris kedua.
3. Perbedaan atribut title dan alt pada
alt: Teks alternatif yang muncul jika gambar gagal dimuat, juga digunakan untuk aksesibilitas (dibaca oleh pembaca layar).

title: Teks yang muncul sebagai tooltip ketika kursor diarahkan ke gambar.

Contoh:

Copy code
<img src="gambar.jpg" alt="Foto Gunung" title="Ini adalah gambar gunung" />
4. Atribut lebar dan tinggi pada gambar
pilih hanya salah satu yang diisi (misalnya hanya lebar), supaya browser menyesuaikan sisi lainnya agar proporsional.

Jika keduanya diisi dengan nilai yang tidak sesuai rasio asli gambar, maka gambar akan terdistorsi (gepeng/melar).

5. Atribut target pada link
_blank→ Membuka tautan di tab/jendela baru.

_self→ Membuka link di tab yang sama (default).

_top→ Membuka link di halaman penuh, menimpa semua frame.

_parent→ Membuka link di frame induk dari frame tempat link itu berada.

Contoh:

Copy code
<a href="https://example.com" target="_blank">Buka Tab Baru</a>
<a href="https://example.com" target="_self">Buka di Tab Ini</a>
<a href="https://example.com" target="_top">Buka di Halaman Penuh</a>
<a href="https://example.com" target="_parent">Buka di Frame Induk</a>

Penjelasan Setiap Langkah
1. Membuat Paragraf
Tag <p>untuk menuliskan paragraf
<img width="1313" height="708" alt="image" src="https://github.com/user-attachments/assets/5a5f5aa4-86e7-411c-bc31-ad341a096139" />
2. Menambahkan Judul
Tag <h1>untuk menambahkan judul, memiliki 6 level sampai h6 Langkah Kedua
<img width="1310" height="719" alt="image" src="https://github.com/user-attachments/assets/e377da2d-403e-4df1-9448-b0b01904dd0a" />
3. Memformat Teks
Tag <mark>untuk menyorot teks, <u>untuk membuat garis bawah, <i>untuk membuat miring, <b>untuk membuat menjadi tebal
<img width="1306" height="201" alt="image" src="https://github.com/user-attachments/assets/d2b1e871-db75-44a8-bfc8-5ff7c577c344" />
4. Menyisipkan Gambar
Tag <img>digunakan untuk menyisipkan gambar, link gambar disimpan di dalam propertisrc Langkah keempat
<img width="1313" height="723" alt="image" src="https://github.com/user-attachments/assets/2acbe1dd-761a-40df-8b9f-b6c4cb7bdb8e" />
5. Menambahkan Hyperlink
Tag <a>digunakan untuk menjadi hyperlink, sedangkan link tujuannya disimpan dalam propertihref Langkah Kelima
<img width="1320" height="65" alt="image" src="https://github.com/user-attachments/assets/2f8b9a1f-029f-48ac-9622-d7a54359e7b0" />

