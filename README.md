# Lab14web
untuk memenuhi tugas pemogramman web

Nama     : Antini permatasari<br>
NIM      : 312010095<br>
kelas    : TI.20.B.1<br>

# Praktikum 14
# Pagination dan Pencarian

# Membuat Pagination

Pagination merupakan sebuah fitur web yang digunakan untuk membatasi tampilan data agar tidak
terlalu panjang dan lebih rapih.<br>

1.Pada Codeigniter 4, fungsi pagination sudah tersedia pada Library sehingga cukup
mudah menggunakannya.<br>

selanjutnya Untuk membuat pagination, buka Kembali Controller Artikel,lalu kemudian modifikasi
kode pada method admin_index seperti berikut.<br>

![Gambar](Gambar/Gambar1.png)

2.Kemudian buka file views/artikel/admin_index.php dan tambahkan kode berikut
dibawah deklarasi tabel data.<br>

![Gambar](Gambar/Gambar2.png)

Selanjutnya buka kembali menu daftar artikel, tambahkan data lagi untuk melihat
hasilnya.<br>

![Gambar](Gambar/Gambar3.png)

# Membuat Pencarian

1.Pencarian merupakan fitur yang sangat membantu bagi pengguna sebuah aplikasi untuk mendapatkan,
sebuah informasi dengan cepat dan mudah.<br>
selanjutnya Untuk membuat pencarian data, buka kembali **Controller Artikel**, pada method
**admin_index** ubah kodenya seperti berikut.<br>

![Gambar](Gambar/Gambar4.png)

2.Kemudian buka kembali file views/artikel/admin_index.php dan tambahkan form
pencarian sebelum deklarasi tabel seperti berikut:<br>

![Gambar](Gambar/Gambar5.png)

Dan pada link pager ubah seperti berikut.<br>

![Gambar](Gambar/Gambar6.png)

Lalu kita ujicoba dengan membuka kembali halaman admin artikel, masukkan kata
kunci tertentu pada form pencarian.<br>

![Gambar](Gambar/Gambar7.png)

3.Lalu kita Menambahkan fungsi unggah gambar pada tambah artikel. Buka kembali **Controller Artikel**, sesuaikan kode pada method **add** seperti berikut:<br>

![Gambar](Gambar/Gambar8.png)

lalu Kemudian pada file views/artikel/form_add.php tambahkan field input file seperti
berikut.<br>

![Gambar](Gambar/Gambar9.png)

4.kemudian Pada file views/artikel/form_add.php tambahkan field input file seperti berikut. Dan sesuaikan tag form dengan menambahkan ecrypt type seperti berikut.<br>

![Gambar](Gambar/Gambar10.png)

Ujicoba file upload dengan mengakses menu tambah artikel.<br>

![Gambar](Gambar/Gambar11.png)