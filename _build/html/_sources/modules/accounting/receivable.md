# Receivable

## Menu Receivable
Menu receivable digunakan untuk mencatat pembayaran piutang terhadap tagihan yang diberikan kepada customer. Dokumen receivable secara otomatis akan terbentuk ketika melakukan Post Invoice pada proses transaksi penjualan melalui Sales Order.

Daftar Isi:
1. Cara menjalankan menu receivable (RCV)
2. Menampilkan dokumen receivable
3. Membuat transaksi pembayaran piutang

## Cara Menjalankan Menu Receivable
1. Untuk menjalankan menu Receivable. Hal pertama adalah klik module **Accounting** pada halaman utama.
 ![receivable](../../dokumentasi-akor/receivable/1.png)

2. Setelah itu, akan ditampilkan menu-menu yang terdapat di dalam module Accounting. Klik menu **Receivable (RCV)**.
 ![receivable](../../dokumentasi-akor/receivable/2.png)

3. Selain itu, jika cukup hafal dengan kode menu nya dapat membuka menu Receivable dengan melakukan pencarian pada kolom pencarian di aplikasi ClodiOs. Ketikkan kode menu **RCV** lalu klik ikon ->
 ![receivable](../../dokumentasi-akor/receivable/3.png)

## Menampilkan Dokumen Receivable
1. Untuk mencari data masukkan kriteria tertentu pada kolom pencarian 
 ![receivable](../../dokumentasi-akor/receivable/4.png)

2. Pilih salah satu data dari list kemudian klik tombol **Open** untuk menampilkan data seperti berikut.
 ![receivable](../../dokumentasi-akor/receivable/5.png)

**Informasi Kolom:**
| No. | Kolom          | Keterangan                     |
| --- | -------------- | ------------------------------ |
| 1   | Company        | Kode Perusahaan                |
| 2   | Business Area      | Kode Area Bisnis/Cabang                   |
| 3   | Customer           | Kode Customer                   |
| 4   | Currency    | Kode Mata Uang                   |
| 5   | Receivale Acc.     | Akun Receivable                   |
| 6   | Receivable Am.             | Nominal Piutang                   |
| 7   | Payment Acc.         | Metode Pembayaran (Kode Internal Account)           |
| 8   | Status |   -        |
| 9   | Paid        | Nominal yang telah dibayar                   |
| 10  | Doc. Number      | Nomor Dokumen       |
| 11  | Doc. Ref    | Nomor Dokumen Referensi                     |
| 12  | Doc. Date        | Tanggal dokumen dibuat                 |
| 13  | Posting Date         | Tanggal dokumen diposting          |
| 14  | Issue Date          | Tanggal Dokumen (Invoice) dikirim  |
| 15  | Due Date	       | Jatuh Tempo Pembayaran                |
| 16  | Additional Info	          | Informasi Tambahan           |

## Membuat Transaksi Pembayaran Piutang
1. Carilah dokumen dengan status unpaid. Bisa dengan mengetikkan ‘Unpaid’ lalu lakukan pencarian.
 ![receivable](../../dokumentasi-akor/receivable/6.png)

2. Pilih dan klik pada dokumen lalu klik tombol **Open**. Maka akan muncul tampilan seperti berikut.
 ![receivable](../../dokumentasi-akor/receivable/7.png)

3. Klik tombol **Payment**.
 ![receivable](../../dokumentasi-akor/receivable/8.png)

4. Maka akan muncul form seperti berikut.
 ![receivable](../../dokumentasi-akor/receivable/9.png)

    ```{note} * Isi semua kolom yang terdapat tanda (*)
    * Pastikan semua kolom terisi dengan benar dan seuaikan kolom amount dengan nominal pembayaran riil.
    ``

**Informasi Kolom**
| No. | Kolom          | Keterangan                     |
| --- | -------------- | ------------------------------ |
| 1   | Company        | Kode Perusahaan                |
| 2   | Business Area      | Kode Area Bisnis/Cabang                   |
| 3   | Payment Acc.           | Kode Internal Account                   |
| 4   | Currency    | Kode Mata Uang                   |
| 5   | Customer     | Kode Customer                   |
| 6   | Amount             | Nominal yang dibayarkan                   |
| 7   | Doc. Number         | Nomor Dokumen, terisi otomatis setelah klik Save           |
| 8   | Doc. Date | Tanggal Dokumen dibuat        |
| 9   | Doc. Reference        | Nomor Dokumen Referensi                  |
| 10  | Description      | Keterangan       |

5. Klik tombol **Save** untuk menyimpan data transaksi.
 ![receivable](../../dokumentasi-akor/receivable/10.png)