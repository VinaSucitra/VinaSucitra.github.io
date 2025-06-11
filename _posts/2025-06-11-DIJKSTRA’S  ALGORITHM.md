**DIJKSTRA’SALGORITHM**
Dijkstra’s Algorithm merupakan sebuah
algoritma untuk menyelesaikan masalah
dengan tujuan mencari lintasan terpendek
dalam sebuah graf berarah dengan bobot-bobot sısı yang bernilai 
positif atau taknegatif. Algoritma dijkstra merupakan jenis
darı "Greedy Algorithm" atau algoritma rakus
Dijkstra’s algorithm ditemukan oleh seorang ilmuwan komputer, Edsger Dijkstra.
Algoritma dijkstra pertama kali di publikasikan pada tahun 1959.

**Dijkstra’s algorithm** digunakan untuk
menentukan jalur terpendek dari satu titik
(simpul) ke titik lainnya dalam sebuah graf
yang memiliki bobot positif.
Dengan kata lain, algoritma ini membantu
kita menemukan rute tercepat atau
termurah dari satu tempat ke tempat lain.

**Cara Kerja**
Cara kerja Dijkstra’s algorithm melibatkan beberapa langkah sederhana yang dijalankan secara
berulang-ulang:
1. Inisialisasi : Tentukan simpul awal. Simpul ini diberi nilai jarak 0, sementara semua simpul
lainnya diberi nilai jarak tak terhingga (∞).
2. Periksa simpul tetangga : Dari simpul awal, periksa semua simpul tetangga dan hitung jarak
total dari simpul awal ke simpul tersebut.
3. Perbarui jarak minimum : Jika jarak yang baru dihitung lebih kecil daripada jarak sebelumnya,
perbarui nilai jarak minimum simpul tersebut.
4. Tandai simpul sebagai ‘terkunci’ : Setelah semua tetangga simpul diperiksa, simpul ini
ditandai sebagai “terkunci” (sudah diperiksa), dan algoritma akan beralih ke simpul berikutnya
dengan jarak terpendek yang belum diperiksa.
5. Ulangi langkah 2-4 : Langkah ini diulang hingga semua simpul telah diperiksa atau jarak
terpendek ke simpul tujuan telah ditemukan.
Dengan pendekatan ini, algoritma memastikan jalur terpendek dari simpul awal ke simpul tujuan.

**Dijkstra’s algorithm** adalah salah satu algoritma pencarian jalur
terpendek yang sangat penting dalam dunia komputasi dan teknologi.
Algoritma ini bekerja dengan prinsip Greedy untuk menemukan rute
terpendek dari satu simpul ke simpul lain dalam graf berbobot positif.
Dengan langkah-langkah yang sistematis—seperti inisialisasi,
pemeriksaan tetangga, pembaruan jarak, dan penguncian simpul—
Dijkstra menjamin hasil yang optimal dalam menentukan lintasan
terpendek. Algoritma ini memiliki berbagai penerapan nyata, mulai
dari sistem navigasi (seperti Google Maps), jaringan komputer,
pengembangan game, logistik, hingga kecerdasan buatan. Melalui
implementasi yang baik, seperti dalam bahasa pemrograman C++,
kita dapat mengaplikasikan Dijkstra untuk memecahkan
permasalahan kompleks secara efisien dan tepat.
