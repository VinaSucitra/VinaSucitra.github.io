Materi 1

Activity Selection Problem Kelompok 1
  •	A.M. Haadi Assa’di
  •	A. Izza Syathra
  •	A Alya Musaenab Asmin
  •	Abdurrahman Dzaky Safrullah
  •	Abd Jabbar Fanshurna Musra
  
Deskripsi Singkat
Activity Selection Problem (ASP) adalah masalah klasik dalam ilmu komputer yang bertujuan untuk memilih serangkaian aktivitas yang dapat dilakukan dalam satu periode waktu, dengan batasan bahwa aktivitas-aktivitas tersebut tidak boleh tumpang tindih.

Konsep Utama
•	Termasuk dalam kategori Greedy Algorithm
•	Strategi: selalu pilih aktivitas yang selesai paling awal
•	Cocok untuk masalah penjadwalan yang efisien

Konsep Algoritma Greedy
Greedy Algorithm adalah pendekatan pemecahan masalah yang membuat keputusan terbaik atau optimal pada setiap langkah, dengan harapan bahwa keputusan-keputusan lokal yang optimal ini akan menghasilkan solusi yang global optimal.
Dalam konteks Activity Selection Problem, algoritma greedy secara efektif diterapkan dengan memilih aktivitas yang memiliki waktu selesai paling awal di setiap langkah.

Input
•	Dua array: waktu mulai dan waktu selesai dari setiap aktivitas
Output
•	Indeks aktivitas yang dapat dipilih tanpa tumpang tindih

Langkah Penyelesaian
1.	Urutkan aktivitas berdasarkan waktu selesai (finish time)
2.	Pilih aktivitas pertama (paling awal selesai)
3.	Pilih aktivitas berikutnya hanya jika waktu mulai ≥ waktu selesai aktivitas terakhir yang dipilih

Problem and Solution Example
Aktivitas, Mulai (s), Selesai (f)
•	A, 3, 6
•	B, 1, 4
•	C , 5, 9
•	D, 8, 10
•	E , 2, 7

Langkah Solusi
1.	Urutkan berdasarkan waktu selesai: [B, A, E, C, D]
2.	Pilih B (selesai paling awal)
3.	Aktifitas yang terpilih adalah B dan C 

Aplikasi Dunia Nyata
•	Penjadwalan & Fasilitas (Jadwal ruang kelas, meeting, lab, olahraga)
•	Sistem Operasi (Jadwal proses CPU, alokasi memori)
•	Logistik (Jadwal pengiriman, rute kendaraan)
•	Telekomunikasi (Alokasi bandwidth, jadwal transmisi data)

Kekuatan dan Keterbatasan

Kekuatan
•	Sederhana dan mudah diimplementasikan
•	Efisien untuk dataset besar
•	Memberikan solusi optimal dalam kasus tanpa batasan kompleks

Keterbatasan
•	Membutuhkan proses pengurutan awal
•	Tidak cocok untuk masalah dengan banyak tambahan (seperti prioritas, jarak, atau biaya)

Kesimpulan
Activity Selection Problem adalah masalah optimasi untuk memilih aktivitas sebanyak mungkin tanpa tumpang tindih. Diselesaikan dengan Algoritma Greedy yang mengurutkan aktivitas berdasarkan waktu selesai, menghasilkan solusi optimal dengan efisiensi O(n log n). Cocok untuk aplikasi penjadwalan, namun untuk kasus kompleks dibutuhkan metode lain seperti pemrograman dinamis atau metaheuristik.
