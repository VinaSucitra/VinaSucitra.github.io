**KAHN'S ALGORITHM**
**Kahn’s Algorithm** adalah algoritma yang digunakan untuk
melakukan topological sort pada graf berarah tanpa siklus (DAG)
yang diperkenalkan oleh Arthur B. Kahn pada tahun 1962.

**KONSEP UTAMA**
Graf Berarah
(Directed Graph)
1. DAG (Directed Acyclic Graph) adalah graf berarah tanpa siklus yang
digunakan untuk memodelkan hubungan dependensi atau urutan
tugas. Algoritma seperti Kahn's memanfaatkan DAG untuk
menghasilkan urutan topologis, memastikan tidak ada ketergantungan
yang bertentangan. Keunggulan DAG terletak pada kemampuannya
merepresentasikan struktur kompleks secara efisien tanpa
perulangan.

2. Acyclic
Acyclic (Tanpa Siklus) berarti graf tidak boleh memiliki rangkaian edge
yang membentuk loop (jalur berulang ke node yang sama). Dalam
Kahn's Algorithm, sifat acyclic ini kritis karena topological sort hanya
mungkin dilakukan pada graf tanpa siklus (DAG). Jika ada siklus, node
dalam siklus akan saling bergantung secara circular, sehingga tidak
bisa diurutkan secara linier.

3. In-degree
In-degree dalam Kahn's Algorithm mengukur dependensi node,
menentukan urutan eksekusi, dan mendeteksi siklus dengan
memantau node yang tidak pernah mencapai in-degree=0, sehingga
memungkinkan penyusunan urutan topologis untuk DAG.

4. topological Sort
Topological sort adalah metode pengurutan node dalam graf berarah
tanpa siklus (DAG) berdasarkan ketergantungan hierarkis, di mana
setiap node harus muncul sebelum node yang bergantung padanya.
Algoritma ini memiliki karakteristik utama: (1) hanya berlaku untuk
DAG, (2) dapat menghasilkan beberapa urutan valid yang berbeda,
dan (3) memiliki kompleksitas waktu linear O(V+E) yang efisien.

Algoritma ini melakukan topological sort dengan memulai dari node
yang memiliki in-degree 0 (tidak memiliki dependensi). Pertama, hitung
in-degree setiap node (misal: node 4 dan 5 memiliki in-degree 0).
Masukkan node-node tersebut ke dalam queue, lalu proses satu per 
satu: keluarkan node dari queue, tambahkan ke hasil, lalu kurangi in-
degree node tetangganya. Jika in-degree tetangga menjadi 0, masukkan
ke queue. Ulangi hingga queue kosong. Jika semua node terproses,
hasilnya adalah urutan topologis (contoh: [4, 5, 0, 2, 3, 1]); jika tidak,
graf memiliki siklus. Kompleksitasnya O(V+E), cocok untuk penjadwalan
tugas atau kompilasi program.

Kahn’s Algorithm adalah metode efisien untuk
menyusun topological order dalam DAG.
Sangat cocok untuk penjadwalan, dependency
resolution, dan kompilasi proyek.
Mengandalkan perhitungan in-degree dan queue
sebagai kunci utama.
Tidak dapat digunakan jika graf mengandung siklus.
Implementasinya mudah dipahami baik dalam Python,
C++, atau bahasa lainnya.
