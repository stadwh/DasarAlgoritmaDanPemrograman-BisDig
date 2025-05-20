1. Penjelasan Penggunaan Struktur Kontrol Percabangan Pemberian Diskon
   Struktur kontrol percabangan (if,elif,else) dapat menentukan apakah seorang berhak mendapatkan diskon. Pemberian dikson bergantung pada kondisi tertentu, yaitu total belanja pelanggan.
-Kondisi utama yang diperiksa: Apakah total_belanja lebih besar dari Rp500.000.
-Percabangan if: jika kondisi total_belanja > 500000 bernilai true, maka program akan menjalankan blok kode yang ada di dalam if. Blok ini berisi instruksi untuk menghitung besaran diskon (10% dari total belanja) lalu hitung total bayar setelah dikurangi diskon.
-Percabangan else: yaitu jika kondisi total_belanja > 500000 bernilai false (artinya total belanja kurang dari atau sama dengan Rp500.000.), lalu program akan menjalankan blok kode yang ada di dalam else. Tidak hanya menampilkan total bayar tanpa diskon, Karena pelanggan tidak memenuhi syarat untuk mendapatkan diskon.
-Program dapat secara otomatis membuat keputusan apakah diskon perlu di terapkan atau tidak yang berdasarkan input total belanja dari pengguna.
2. Penjelasan peran tipe data dan operator
   Perhitungan rata-rata nilai dapat di selesaikan untuk menentukan status kelulusan, dapat digunakan dengan tipe data dan operator sebagai berikut:
   -Float atau int: Tipe data numerik yang digunakan untuk menyimpan nilai dari mata pelajaran. Karena nilai ujian bisa jadi memiliki angka desimal (misalnya 85.5), tipe data float lebih disarankan. Jika nilai berupa bilangan bulat, int juga bisa digunakan.
-str: Tipe data string akan digunakan untuk menyimpan pesan status kelulusan ("Lulus" atau "Tidak Lulus") untuk menampilkan informasi kepada pengguna (misalnya, label input dan output).
* Operator terbagi menjadi tiga yaitu:
* Operator Aritmetika:
  + (Penjumlahan): Digunakan untuk menjumlahkan nilai dari ketiga mata pelajaran.
  / (Pembagian): Digunakan untuk membagi total nilai dengan jumlah mata pelajaran (yaitu 3) untuk mendapatkan rata-rata.
* Operator Perbandingan:
  >= (Lebih Besar dari atau Sama dengan): Digunakan untuk membandingkan rata-rata nilai dengan batas kelulusan (75). Ini adalah operator kunci untuk menentukan apakah siswa lulus atau tidak.
* Operator Penugasan:
  = (Penugasan): Digunakan untuk menyimpan hasil perhitungan (rata-rata) dan status kelulusan ke dalam variabel.
3. Penjelasan Manfaat Penggunaan Fungsi dan Cara Kerja Rekursi:
* Manfaat Penggunaan Fungsi:
-Modularitas: Fungsi yang memungkinkan untuk memecah program menjadi bagian-bagian yang lebih kecil dan terkelola dengan baik. Setiap fungsi bertanggung jawab untuk melakukan tugas tertentu (menghitung faktorial).
-Reusabilitas Kode: Setelah sebuah fungsi dibuat, dapat digunakan kembali di berbagai bagian program tanpa harus menulis ulang kode yang sama. Dapat menghemat waktu dan mengurangi kemungkinan kesalahan.
-Keterbacaan: Fungsi membuat kode lebih mudah dibaca dan dipahami karena setiap bagian kode memiliki tujuan yang jelas yang diidentifikasi oleh nama fungsi.
-Kemudahan Debugging: Jika terjadi kesalahan, kita dapat menyelesaikan masalah pada fungsi tertentu, yang membuat proses debugging menjadi lebih mudah dan cepat.
* Cara Kerja Rekursi dalam Menghitung Faktorial:
-Definisi Rekursi: Rekursi adalah teknik di mana sebuah fungsi dalam definisinya.
-Basis Kasus: Dalam rekursi, basis kasus sangat penting karena menjadi titik berhentinya fungsi agar tidak terus memanggil dirinya sendiri. Contohnya pada faktorial, jika nilainya 0, maka hasilnya adalah 1. Tanpa ini, fungsi akan terus berjalan dan menyebabkan error.
-Langkah Rekursif: Jika nilai n lebih dari 0, maka faktorial n dihitung dengan cara mengalikan n dengan faktorial dari n-1. Ini disebut langkah rekursif, di mana fungsi terus memanggil dirinya sendiri sampai mencapai nilai 0.
-Proses Perhitungan: Saat fungsi sampai ke nilai 0, ia mengembalikan 1. Kemudian nilai tersebut digunakan oleh fungsi sebelumnya untuk menghitung hasil akhir secara bertahap hingga kembali ke nilai awal.
4. Penjelasan Penggunaan Perulangan dan Array/List:
-Perulangan (Looping): Perulangan sangat penting dalam kasus ini karena kita perlu mengulang proses yang sama (meminta input nama dan nilai siswa, serta menyimpannya) sebanyak jumlah siswa yang ada, yaitu 5. Perulangan for adalah pilihan yang tepat karena kita tahu pasti berapa kali iterasi yang dibutuhkan. Perulangan memastikan bahwa kita tidak perlu menulis baris kode yang sama secara berulang untuk setiap siswa.
-Array/List: Dalam Python, kita menggunakan struktur data list untuk menyimpan nilai-nilai dari kelima siswa. List berfungsi seperti array, memungkinkan kita untuk:
. Menyimpan banyak elemen (nilai siswa) dalam satu variabel yang terorganisir.
. Mengakses setiap elemen (nilai siswa tertentu) menggunakan indeksnya (posisinya dalam list, dimulai dari 0).
. Menambah elemen baru ke list (dalam kasus ini, menambahkan nilai siswa saat diinput).
-Dengan menggunakan list, kita dapat dengan mudah mengelola dan memanipulasi koleksi nilai siswa, misalnya untuk mencari nilai tertinggi atau menampilkan semua nilai.
5. Langkah-langkah Algoritma:
-Algoritma adalah urutan langkah-langkah logis untuk menyelesaikan suatu masalah. Berikut adalah langkah-langkah algoritma untuk menghitung total harga pembelian 3 barang:
1.Mulai: Inisiasi proses.
2.Input Harga Barang 1: Terima input harga untuk barang pertama dari pengguna. Simpan nilai ini dalam sebuah variabel (misalnya, harga_barang1).
3.Input Harga Barang 2: Terima input harga untuk barang kedua dari pengguna. Simpan nilai ini dalam sebuah variabel (misalnya, harga_barang2).
4.Input Harga Barang 3: Terima input harga untuk barang ketiga dari pengguna. Simpan nilai ini dalam sebuah variabel (misalnya, harga_barang3).
5.Hitung Total Harga: Jumlahkan ketiga harga barang (harga_barang1 + harga_barang2 + harga_barang3). Simpan hasilnya dalam sebuah variabel (misalnya, total_harga).
6.Tampilkan Total Harga: Tampilkan nilai total_harga kepada pengguna sebagai total pembayaran.

