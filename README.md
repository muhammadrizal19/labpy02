# Latihan 1 : Membuat proggram menentukan nilai akhir
![Screenshot_20241103_104300_Chrome](https://github.com/user-attachments/assets/3ad6fca6-b860-48d0-a80f-c62a77e396f3)
- input data :
   - meminta pengguna untuk memasukan nilai UTS (Ujian Tengah Semester), nilai UAS (Ujian Akhir Semester), dan nilai tugas
- Perhitungan nilai akhir :
    - nilai akhir di hitung berdasarkan bobot nilai tugas sebesar 20%, UTS 40%, dan UAS 40%
Fungsi int() digunakan untuk mengkonversi input string menjadi integer
- Penentuan keterangan nilai lulus atau tidak
   - Keterangan lulus diberikan berdasarkan nilai akhir. Jika nilai akhir lebih dari 60, maka keterangan akan menjadi "LULUS", jika tidak akan menjadi "TIDAK LULUS".
- Penentuan nilai huruf
    A jika lebih dari 80
    B jika lebih dari 70 C jika lebih dari 50
    D jika lebih dari 40 E jika di bawah atau sama dengan 40
- Output hasil
![Screenshot_20241103_104315_Chrome](https://github.com/user-attachments/assets/af1df4d7-ca73-4888-944c-2dd9d235c990)
- Kode ini menampilkan hasil, termasuk nilai UTS, UAS, tugas, nilai akhir, nilai huruf, dan keterangan lulus atau tidak lulus.

Hasil Program: Pada contoh output di sisi gambar, jika nilai tugas, UTS, dan UAS adalah 95, 85, dan 80, maka

Nilai akhir adalah 88. Nilai huruf adalah "A". Keterangan: "LULUS".

# Latihan 2 : Membuat Proggram Menampilkan Status Gaji Karyawan
![Screenshot_20241103_105722_Chrome](https://github.com/user-attachments/assets/af70c9e2-9352-4a87-b371-98f0a6fe26ce)
- Input data :
   - Kode ini meminta pengguna untuk memasukkan gaji, status keluarga, dan kepemilikan rumah. Variabel gaji menyimpan nilai gaji sebagai integer.
 - Variabel berkeluarga akan bernilai True jika pengguna memasukkan "Y" (sudah berkeluarga) dan False jika "T". Variabel punya rumah akan bernilai True jika pengguna memasukkan "Y" (punya rumah) dan False jika "T".
- Pengecekkan gaji :
  - Jika gaji lebih dari 3.000.000, maka program akan mencetak "Gaji sudah di atas UMR". Jika tidak, program akan langsung mencetak "Gaji belum UMR" pada bagian else.
- Pengecekkan status keluarga :
 - Jika berkeluarga bernilai True,program akan menampilkan "Wajib ikutan asuransi dan menabung untuk pensiun". Jika berkeluarga bernilai False, program akan menampilkan "Tidak perlu ikutan asuransi".
- Pengecekkan kepemilikan rumah :
  - Jika punya_rumah bernilai True, program akan menampilkan "Wajib bayar pajak rumah". Jika punya_rumah bernilai False, program akan menampilkan "Tidak wajib bayar pajak rumah".
  - Jika gaji tidak lebih dari 3.000.000, program akan langsung menampilkan "Gaji belum UMR" tanpa melakukan pengecekan tambahan
- Output hasil :
![Screenshot_20241103_105732_Chrome](https://github.com/user-attachments/assets/2afe0e6a-57c7-4abf-b3ee-dc28c8a7e988)
- Pada contoh output pada gambar, jika gaji 9.000.000, status berkeluarga "T", dan punya rumah "Y":Program menampilkan bahwa gaji di atas UMR. Menampilkan bahwa pengguna tidak perlu ikut asuransi dan Menampilkan bahwa pengguna wajib membayar pajak rumah.

# Latihan 3 : Penggunaan kondisi OR Program membandingkan 3 input bilangan lainnnya, maka cetak pernyataan "BENAR"
![Screenshot_20241103_110456_Chrome](https://github.com/user-attachments/assets/f608d235-5c7a-4662-911a-e4e4a7436f2a)
- Input data :
 - Kode ini meminta pengguna untuk memasukkan tiga bilangan: a, b, dan c. Input dari pengguna dikonversi ke tipe int agar dapat digunakan dalam operasi aritmatika.
- Pengecekan kondisi :
  -  Kode ini memeriksa apakah salah satu dari kondisi berikut terpenuhi: a + b == c b + c == a c + a == b Jika salah satu kondisi di atas benar, program akan mencetak "BENAR". Jika tidak ada kondisi yang terpenuhi, program akan mencetak "SALAH".
   -  Kode ini mengecek apakah salah satu dari tiga bilangan (a, b, atau c) dapat merupakan hasil penjumlahan dari dua bilangan lainnya. Pada contoh output pada gambar: Jika a = 5, b = 5, dan c = 10, maka kondisi terpenuhi, sehingga hasilnya adalah "BENAR".
- Output hasil :
![Screenshot_20241103_110507_Chrome](https://github.com/user-attachments/assets/5c4133d5-67cc-4a36-8e11-cd03f3d0e9ad)

# Kasus 1 : Program pemesanan tiket bioskop, Program ini meminta input dari user untuk tipe tiket (reguler atau VIP) dan status member (memiliki kartu member atau tidak).
![Screenshot_20241103_111156_Chrome](https://github.com/user-attachments/assets/3c876969-4ab4-46e5-b4e5-84c992fcd58b)
- flowchart
 ![IMG-20241103-WA0005](https://github.com/user-attachments/assets/3a2c8afd-eb6f-4aa0-ab81-4d6fc5c17aed)
- Mendefinisikan harga tiket :
   - harga_tiket_reguler: Harga tiket reguler didefinisikan sebesar 50000 harga_tiket_vip: Harga tiket VIP didefinisikan sebesar 100000 diskon_member: Besar diskon untuk member didefinisikan sebesar 0.20 (20%)
- Meminta input dari user :
    - Program meminta user untuk memasukkan tipe tiket (reguler/vip) dan menyimpannya ke dalam variabel tipe_tiket.
   - Program meminta user untuk memasukkan status member (ya/tidak) dan menyimpannya ke dalam variabel status_member.
  - Kedua input dari user diubah menjadi huruf kecil menggunakan fungsi lower().
- Menghitung harga tiket berdasarkan tipe :
    - Jika tipe_tiket adalah "reguler", maka harga_tiket diset menjadi harga_tiket_reguler.
    - Jika tipe_tiket adalah "vip", maka harga_tiket diset menjadi harga_tiket_vip.
    - Jika tipe_tiket bukan "reguler" atau "vip", maka program menampilkan pesan "Tipe tiket tidak valid" dan keluar dari program.
- Mengecek status untuk member diskon :
    - Program memeriksa nilai status_member: Jika status_member adalah "ya", maka total_harga dihitung dengan rumus harga_tiket * (1 - diskon_member), yang memberikan diskon kepada member.
   - Jika status_member bukan "ya", maka total_harga diset sama dengan harga_tiket tanpa diskon.
- Output hasil :
![Screenshot_20241103_111205_Chrome](https://github.com/user-attachments/assets/58c95385-cd2e-4334-87d9-cc8e283cfb7a)

# Kasus 2 : program kalkulator sederhana,Kode program ini dirancang untuk melakukan operasi aritmatika sederhana berdasarkan input pengguna.
![Screenshot_20241103_142410_Chrome](https://github.com/user-attachments/assets/64dce032-8344-4512-a34e-59012390d7b9)
- flowchart
  ![IMG-20241103-WA0006](https://github.com/user-attachments/assets/ff499d85-2170-4483-8f4d-36f9281ad28a)
- Input: Kode program meminta pengguna untuk memasukkan operator aritmatika (+, -, *, /) dan dua angka.
- Validasi Operator: Kode menggunakan struktur if-elif-else untuk memvalidasi operator yang dimasukkan.
- Operasi Aritmatika: Berdasarkan operator yang valid, kode melakukan operasi aritmatika yang sesuai dan menyimpan hasilnya dalam variabel hasil.
- Validasi Pembagian dengan Nol: Kode mengecek apakah angka kedua adalah nol untuk menghindari pembagian dengan nol. Jika angka kedua nol, program akan menampilkan pesan error dan menghentikan eksekusi.
Output hasil :
