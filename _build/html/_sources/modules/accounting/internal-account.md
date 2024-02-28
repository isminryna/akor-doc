# Internal Account

## Menu Internal Account
Menu internal account digunakan untuk menampilkan, membuat, dan menghapus transaksi keuangan (Cash/Bank).

Daftar Isi :
1. Cara menjalankan menu internal account
2. Menampilkan informasi saldo
3. Membuat transaksi
4. Menampilkan dan menghapus transaksi
5. Membuat transaksi transfer saldo

## Cara Menjalankan Menu Internal Account (INCT)
1. Buka module **Accounting** pada halaman utama sistem.
    ![internal-account](../../dokumentasi-akor/internal-account/1.png)

2. Kemudian pilih menu **Internal Account**.
     ![internal-account](../../dokumentasi-akor/internal-account/2.png)

3. Selain itu, dapat juga membuka modul Internal Account dengan mengetikkan kode program **INCT** pada kolom pencarian, kemudian klik ikon **Panah** atau tombol **Enter** pada keyboard.
    ![internal-account](../../dokumentasi-akor/internal-account/3.png)

## Menampilkan Informasi Saldo
1. Pada halaman utama Internal Account pilih salah satu jenis kas/bank yang diinginkan, lalu klik tombol **Open**.
    ![internal-account](../../dokumentasi-akor/internal-account/4.png)

2. Kosongkan tanggal pada kolom Start dan kolom End. Lalu klik pada **Balance**, maka akan menampilkan informasi saldo pada penyimpanan tersebut.
     ![internal-account](../../dokumentasi-akor/internal-account/5.png)

     ![internal-account](../../dokumentasi-akor/internal-account/7.png)

**Informasi Kolom**
| No. | Kolom          | Keterangan                     |
| --- | -------------- | ------------------------------ |
| 1   | Account        | Kode Internal Account                |
| 2   | Start      | Tanggal Awal                   |
| 3   | End           | Tanggal Akhir                   |
| 4   | Begining    | Saldo pada Tanggal Awal                  |
| 5   | Ending     | Saldo pada Tanggal AKhir Dokumen                   |
| 6   | Debit             | Jumlah Transaksi Debit pada rentang Tanggal Awal sampai Tanggal Akhir                   |
| 7   | Credit         | Jumlah Transaksi Credit pada rentang Tanggal Awal sampai Tanggal Akhir          |
| 8   | Dif. | Selisih Debit dan Credit       |

## Membuat Transaksi
1. Pada halaman utama Internal Account pilih kas/bank yang diinginkan untuk melakukan transaksi, lalu klik tombol **Open**.
    ![internal-account](../../dokumentasi-akor/internal-account/8.png)

2. Klik tombol **Transaction**.
    ![internal-account](../../dokumentasi-akor/internal-account/9.png)

3. Kemudian akan ditampilkan form untuk membuat transaksi baru. Isi dan lengkapi kolom-kolom yang ada. Lalu klik tombol **Save**.
    ![internal-account](../../dokumentasi-akor/internal-account/10.png)

tombol **Add** untuk menambahkan (menambahkan brang yang dibeli). sedangkan tombol **Remove** untuk menghapus record (barang yang sudah di masukan)

   ```{note} * Semua kolom yang bertanda (*) wajib di isi.
   ```

    **Informasi Kolom**
|No. | Kolom               | Keterangan                     |
|--- | ------------------- | ------------------------------ | 
| 1  | Company             | Kode Perusahaan                |
| 2  | Business Area       | Kode Area Bisnis/Cabang        |
| 3  | Account             | Kode Kas/Bank                  |
| 4  | Currency            | Mata Uang                      |
| 5  | Description         | Keterangan Transaksi           |
| 6  | Doc. Number         | ID Dokumen Sistem              |
| 7  | Doc. Date           | Tanggal Dokumen                |
| 8  | Doc. Reference      | Referensi Terhadap Dokumen Lain/       Eksternal                                                   |
| 9  | Transaction         | Nama Jenis Transaksi           |
| 10 | Description         | Keterangan Detail Transaksi    |
| 11 | D/C                 | Debit/Credit                   |
| 12 | Amount              | Nilai Transaksi                |
| 13 | Business Center     | Kode Business center           |

4. Setelah Transaksi tersimpan, maka sistem akan memposting jurnal secara otomatis dengan hasil seperti gambar berikut:
     ![internal-account](../../dokumentasi-akor/internal-account/11.png)

## Menampilkan Dan Menghapus Transaksi
1. Pada halaman utama Internal Account pilih kas/bank yang diinginkan untuk melakukan transaksi, lalu klik tombol **Open**
    ![internal-account](../../dokumentasi-akor/internal-account/12.png)

2. Kemudia klik tombok **Document**
    ![internal-account](../../dokumentasi-akor/internal-account/13.png)

3. Maka akan di tampilkan daftar dokumen transaksi yang terjadi di Internal Account. Pilih salah satu transaksi yang ingin di buka, lalu klik tombol **Open**
    ![internal-account](../../dokumentasi-akor/internal-account/14.png)

4. Akan di tampilkan detail dan dokumen tersebut, seperti berikut.
    ![internal-account](../../dokumentasi-akor/internal-account/15.png)

5. Apabila ingin menghapus dokumen transaksi, maka dapat dilakukan dengan klik tombol **Remove**.
    ![internal-account](../../dokumentasi-akor/internal-account/16.png)

6. Maka akan tampil notifikasi konfirmasi penghapusan dokumen. Klik tombol **OK** apabila ingin menghapus dokumen.
    ![internal-account](../../dokumentasi-akor/internal-account/17.png)

7. Klik tombol **Cancel** untuk membatalkan penghapusan dokumen.
    ![internal-account](../../dokumentasi-akor/internal-account/18.png)

## Membuat Transaksi Transfer Saldo
1. Klik Tombol **Transfer**
    ![internal-account](../../dokumentasi-akor/internal-account/19.png)

2. Kemudian akan menamplikan form seperti berikut.
    ![internal-account](../../dokumentasi-akor/internal-account/20.png)

**Informasi Kolom**
|No.  | Kolom          | Keterangan                            |
| --- | -----------    | -----------------------------         |
|  1  | Company        | Kode Perusahaan                       |
|  2  | Business Area  | Kode Area Bisnis                      |
|  3  | Account        | Kode internal Account                 |
|  4  | Currency       | Kode Mata Uang                        |
|  5  | Doc. Number    | Nomor Dokumen, terisi otmatis setelah klik tombol Save                                                           |
|  6  | Doc. Date      | Tanggal Dokumen Dibuat                |
|  7  | Doc. Reference | Nomor Dokumen Referensi               |
|  8  | Destination Account  | Kode Akun Tujuan                |
|  9  | Amount         | Nominal Saldo Di Transfer             |
|  10 | Description    | Keterangan                            |

3. Klik tombol **Save** utuk menyimpan transaksi.
    ![internal-account](../../dokumentasi-akor/internal-account/21.png)