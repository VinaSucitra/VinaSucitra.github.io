**DEPTH-FIRST SEARCH (DFS)**

Depth-First Search (DFS) adalah salah satu metode penelusuran dalam
struktur data seperti graf atau pohon. Cara kerja DFS mirip seperti
menyusuri jalan bercabang, di mana kita akan terus berjalan ke arah satu
cabang hingga mencapai ujung, sebelum kembali dan mencoba cabang
lainnya. Artinya, algoritma ini akan mengunjungi simpul (node) sedalam
mungkin terlebih dahulu, baru kemudian kembali ke belakang (backtrack)
jika sudah tidak ada jalur lain yang bisa dilalui. DFS bisa dijalankan
menggunakan rekursi atau dengan bantuan struktur data seperti tumpukan
(stack). Algoritma ini banyak digunakan dalam berbagai aplikasi, seperti
mencari jalur dalam labirin, memeriksa apakah sebuah graf memiliki siklus,
atau membagi graf menjadi beberapa bagian yang saling terhubung. DFS
sederhana dan efisien, tetapi membutuhkan perhatian agar tidak
mengunjungi simpul yang sama berulang kali, terutama pada graf yang
memiliki banyak siklus.

**JENIS JENIS**
1. DFS Rekursif
2. DFS Iteratif (menggunakan stack)
3. DFS untuk Deteksi Siklus
4. DFS untuk Topological Sort
5. DFS untuk Menemukan Komponen Terhubung / SCC
6. DFS Terbatas Kedalaman dan Iterative Deepening DFS (IDDFS)

**BATASAN**
1. Tidak efisien untuk graf besar dan kompleks.
2. Hanya menjelajah satu komponen terhubung saja.
3. Tidak cocok untuk mencari jalur terpendek.
4. Berisiko stack overflow pada graf dengan
kedalaman besar (rekursi dalam)
5. Tidak otomatis menangani graf dengan
siklus tanpa penanda kunjungan.

**PENERAPAN DALAM DUNIA NYATA**
1. Menjelajah folder & subfolder di komputer.
2. Menyelesaikan puzzle seperti Sudoku
& N-Queens.
3. Deteksi siklus pada graf dependensi.
4. Analisis hubungan di jejaring sosial.
5. Eksplorasi jalur di maze atau peta game.

**Depth First Search (DFS)** adalah algoritma penelusuran graf yang
bekerja dengan menjelajahi simpul sedalam mungkin sebelum kembali
(backtrack) untuk menelusuri jalur lain. Algoritma ini efektif untuk
menemukan jalur atau komponen yang terhubung, serta sering
digunakan dalam aplikasi seperti deteksi siklus, topological sorting, dan
pemecahan maze. Meskipun DFS sederhana dan hemat memori, ia
tidak menjamin menemukan jalur terpendek dan dapat menyebabkan
stack overflow jika graf sangat dalam.
