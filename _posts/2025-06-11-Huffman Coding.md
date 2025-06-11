Materi 3
**Huffman Coding Kelompok 3**
1. Andi Khaerunnisa Oddang
2. Anugrah Fitri Novanda
3. Andi Sophie Banuna Amrie
4. Angel Catrina Sobbu
   
**Deskripsi Singkat**
Huffman Coding  adalah algoritma kompresi data lossless (tanpa kehilangan data) yang
digunakan untuk mengurangi ukuran data dengan mengganti setiap karakter/simboi dengan 
representasi biner berdasarkan frekuensi kemunculannya. Algoritma ini ditemukan oleh
David A. Huffman pada tahun 1952, dan hingga kini digunakan dalam berbagai sistem kompresi 
seperti file ZIP, format gambar, hingga protokol transmisi data.

**Konsep Utama**
1. Berdasarkan frekuensi karakter dalam data.
2. Karakter dengan frekuensi tinggi → kode pendek.
3. Karakter dengan frekuensi rendah → kode panjang.
4. Representasi data menggunakan pohon biner.

**Proses Pembuatan Kode**
1.	Hitung frekuensi tiap karakter dalam data.
2.	Buat simpul untuk setiap karakter.
3.	Gabungkan dua simpul dengan frekuensi terkecil.
4.	Ulangi hingga terbentuk satu pohon Huffman.
5.	Tentukan kode biner untuk tiap karakter (0: kiri, 1: kanan).
   
**Aplikasi Dunia Nyata**
1. Kompresi File (ZIP, GZIP, 7z)
2. Format Gambar (JPEG, PNG)
3. Format Video dan Audio (MP3, MPEG, H.264)
4. Transmisi Data (Telekomunikasi & Satelit)
5. Sistem Informasi & Penyimpanan Dokumen
   
**Kelebihan dan Kekurangan**
**Kelebihan**
1. Lossless: tidak ada data yang hilang.
2. Efisien untuk data dengan distribusi karakter tidak merata.
3. Digunakan luas di sistem kompresi file.
4. 
**Kekurangan**
1. Kurang optimal jika frekuensi karakter merata.
2. Memerlukan tabel kode untuk dekompresi
3. 
**Kesimpulan**
Huffman Coding merupakan salah satu algoritma kompresi data lossless paling efisien dan
banyak digunakan dalam berbagai aplikasi dunia nyata, seperti kompresi file (ZIP, GZIP),
format multimedia (JPEG, MP3), serta transmisi data digital. Dengan pendekatan berbasis
frekuensi karakter, algoritma ini menghasilkan representasi biner yang lebih pendek untuk
simbol yang sering muncul, sehingga mampu mengurangi ukuran data secara signifikan tanpa kehilangan informasi.
 
