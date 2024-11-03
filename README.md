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
