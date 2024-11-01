Tugas Praktikum Mata Kuliah Program Komputer dan Praktek

Algoritma Latihan1:

Tampilkan Pesan:

Menampilkan pesan ke pengguna untuk menginformasikan bahwa program akan menghasilkan bilangan acak yang kurang dari 0.5.

Input Jumlah:

Meminta pengguna untuk memasukkan jumlah bilangan acak yang ingin dihasilkan. Nilai yang dimasukkan disimpan dalam variabel jumlah.

Inisialisasi Variabel Maksimum:

Membuat variabel max dan menginisialisasinya dengan nilai 0. Meskipun variabel ini tidak digunakan dalam kode yang diberikan,
kemungkinan besar ini adalah sisa dari kode sebelumnya yang bertujuan untuk mencari nilai maksimum. 
Kita akan abaikan untuk saat ini.

Import Modul random:

Mengimpor modul random yang menyediakan fungsi-fungsi untuk menghasilkan bilangan acak.

Perulangan:

Melakukan perulangan sebanyak jumlah kali:

Mencetak nomor urut data (i+1).

Menggunakan fungsi random.uniform(0, 0.5) untuk menghasilkan bilangan acak antara 0 (inklusif) dan 0.5 (eksklusif).
Mencetak bilangan acak yang dihasilkan.

Hasil Program 

![image](https://github.com/user-attachments/assets/b3345cb7-b1f6-4edb-8e52-c342b8ae4c6d)

Algoritma Latihan2 : ** Inisialisasi Variabel:**

max diinisialisasi dengan nilai 0. Variabel ini akan digunakan untuk menyimpan bilangan terbesar yang ditemukan sejauh ini. Perulangan Tak Terbatas:

Input Bilangan:

Meminta pengguna untuk memasukkan sebuah bilangan. Bilangan ini akan disimpan dalam variabel a. Perbandingan: Membandingkan nilai a dengan nilai max yang sudah ada. Jika a lebih besar dari max: Nilai max diperbarui menjadi nilai a. Jika a sama dengan 0: Perulangan dihentikan (break). ** Output:**

Setelah perulangan selesai, nilai max (bilangan terbesar yang ditemukan) dicetak ke layar.

Penjelasan Algoritma:

Algoritma ini bekerja dengan cara terus-menerus meminta pengguna untuk memasukkan bilangan. Setiap bilangan yang dimasukkan akan dibandingkan dengan bilangan terbesar yang sudah
ditemukan sejauh ini. Jika bilangan yang baru dimasukkan lebih besar, maka bilangan terbesar akan diperbarui. Proses ini akan terus berulang sampai pengguna memasukkan angka 0 sebagai tanda berhenti.

Contoh Pelaksanaan:

Misalkan pengguna memasukkan bilangan-bilangan berikut: 5, 9, 3, 11, 0.

max awalnya bernilai 0.

Angka 5 dimasukkan, max menjadi 5.

Angka 9 dimasukkan, max menjadi 9.

Angka 3 dimasukkan, max tetap 9.

Angka 11 dimasukkan, max menjadi 11.

Angka 0 dimasukkan, perulangan berhenti.

Program mencetak "Bilangan terbesar adalah: 11".

Hasil Program

![image](https://github.com/user-attachments/assets/15d37c1b-f243-4c34-80ad-4a078e70cf6b)

---------------------------------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------- ----------------------------------------------------------------------------------------------------------------------------------------

Definisi Fungsi hitung_laba:

Fungsi ini menerima dua parameter: modal_awal (jumlah uang yang diinvestasikan) dan bunga (tingkat bunga dalam bentuk desimal).

Fungsi ini menghitung laba dengan mengalikan modal awal dengan suku bunga.

Fungsi ini mengembalikan nilai laba yang telah dihitung.

Input Data:

Meminta pengguna untuk memasukkan nilai modal awal dan suku bunga.

Nilai modal awal disimpan dalam variabel modal_awal sebagai bilangan bulat.

Nilai suku bunga disimpan dalam variabel bunga sebagai bilangan desimal.

Pemanggilan Fungsi:

Memanggil fungsi hitung_laba dengan argumen modal_awal dan bunga.

Hasil yang dikembalikan oleh fungsi disimpan dalam variabel laba.

Tampilkan Hasil:

Mencetak nilai laba ke layar.

Hasil Program

![image](https://github.com/user-attachments/assets/f02ed2a1-09fc-4d0f-9c31-6084dbbedf2a)


