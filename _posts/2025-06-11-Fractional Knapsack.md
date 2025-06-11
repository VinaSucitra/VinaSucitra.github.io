Fractional Knapsack Kelompok 2
1. Ahmad Farel Alghifari
2. Aisyah Salsabila Sabri
3. Akram Alfadli Tamir
4. Andi Eryn Nur Alisya
5. 	Andi Fa’athir Eka Saputra
 
**Deskripsi Singkat**
Fractional knapsack adalah varian dari masalah knapsack (ransel) dalam algoritma, 
di mana kita boleh mengambil sebagian dari suatu item (misalnya setengah, seperempat, dsb.)
untuk memaksimalkan nilai total barang dalam kapasitas ransel tertentu. Berasal dari kata 
fractional yang berarti pecahan atau bagian. Dalam konteks ini, kamu boleh mengambil sebagian 
dari suatu item (tidak harus utuh) dan dari kata knapsack yang artinya ransel atau tas. Ini adalah metafora 
untuk kapasitas penyimpanan terbatas.

**Konsep Utama**
1. Setiap barang memiliki berat dan nilai.
2. Barang dapat diambil sebagian sesuai kebutuhan.
3. Solusi dapat diselesaikan dengan algoritma greedy.
   
**Konsep Algoritma Greedy**
**Algoritma Greedy** adalah strategi pemecahan masalah optimasi yang bekerja dengan membuat pilihan 
yang tampak paling baik pada setiap langkah, dengan harapan rangkaian pilihan ini akan mengarahkan
pada solusi yang optimal secara keseluruhan. Algoritma ini bersifat serakah karena langsung mengambil 
pilihan terbaik saat itu tanpa mempertimbangkan konsekuensi di masa depan.
Dalam konteks Activity Selection Problem, algoritma greedy merupakan pendekatan untuk memilih opsi terbaik
saat ini demi mencapai solusi optimal. Karakteristik utama: sederhana, efisien, tidak perlu mempertimbangkan
semua kemungkinan. Tapi algoritma greedy tidak selalu menghasilkan solusi optimal global untuk semua kasus. 
Kadang pilihan terbaik lokal menghalangi solusi optimal secara keseluruhan.
 Analisis Kompleksitas

 **Aplikasi Dunia Nyata**
1. Pengangkutan barang di logistik
2. Pengisian tangki minyak atau bahan bakar
3. Investasi portofolio
4. Penggunaan bandwidth atau CPU dalam Cloud Computing
   
 **Kelebihan dan Kekurangan**
**Kelebihan**
1. Solusi optimal dijamin
2. Cepat dan efisien
3. Fleksibel
4. Mudah diimplementasikan
**Kekurangan**
1. Tidak cocok untuk masalah 0/1
2. Tidak menangani batasan lain
3. Hanya maksimalkan nilai, bukan prioritas lain

**Kesimpulan**
Fractional Knapsack adalah salah satu variasi dari Knapsack Problem yang dapat diselesaikan secara
efisien menggunakan algoritma greedy. Dalam versi ini, barang boleh diambil sebagian (fraksional), 
berbeda dengan 0/1 Knapsack yang hanya membolehkan pengambilan penuh atau tidak sama sekali. Dengan 
menghitung rasio nilai terhadap berat (value/weight) untuk setiap barang, lalu mengambil barang dengan
rasio tertinggi hingga kapasitas tas penuh, kita bisa mendapatkan solusi optimal secara cepat dan sederhana.
Pendekatan greedy ini bekerja efektif karena pilihan optimal lokal (berdasarkan rasio) juga mengarah pada solusi 
optimal global dalam kasus Fractional Knapsack.

 
