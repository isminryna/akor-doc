# Melakukan Transaksi Penjualan Langsung

## Transaksi Penjualan Langsung
Transaksi penjualan langsung merupakan transaksi penjualan yang terjadi antara kasir dan customer di dalam suatu toko dan terjadi secara langsung (tatap muka). Pada tahap ini customer akan melakukan pembelian dan pembayaran di kasir. Maka pada tahap ini akan menggunakan menu Direct Sales.

---

## Membuat Dokumen Direct Sales

1. Untuk membuat transaksi penjualan langsung dapat dilakukan di dalam menu **Direct Sales (DSL)** yang terdapat di dalam module **Sales**.

    ![1](../dokumentasi-akor/transaksi-penjualan-langsung/1.jpg)


2. Maka akan ditampilkan form yang harus diisi. Lengkapi setiap kolom, kemudian klik tombol **Next**.

     ![2](../dokumentasi-akor/transaksi-penjualan-langsung/2.png)

    ```{note} Semua kolom yang bertanda (*) wajib diisi
    ```

**Informasi Kolom:**

| No. | Kolom          | Keterangan                                   |
|-----|----------------|----------------------------------------------|
| 1   | Company        | Kode Perusahaan                              |
| 2   | Bussiness Area | Kode Area Bisnis                             |
| 3   | Point of Sales  | Kasir yang akan Digunakan                    |
| 4   | Customer       | Konsumen yang Melakukan Pembelian           |
| 5   | Storage        | Kode Ruang Penyimpanan                       |
| 6   | Currency       | Mata Uang yang Digunakan                     |

 

3. Maka akan ditampilkan daftar transaksi penjualan yang sudah dilakukan sebelumnya. Untuk membuat transaksi penjualan baru, klik tombol **New**.

    ![3](../dokumentasi-akor/transaksi-penjualan-langsung/3.png)

4. Akan ditampilkan form untuk melakukan transaksi penjualan. Kasir perlu memasukkan barang-barang yang dibeli oleh customer, dan sistem akan otomatis menampilkan harga barang tersebut. Selanjutnya sistem akan otomatis menghitung total harga belanjaan customer. Kemudian klik tombol **Save to Cart**.

    ![4](../dokumentasi-akor/transaksi-penjualan-langsung/4.png)
    

Tombol **Add** untuk menambahkan record (menambahkan barang yang dibeli). Sedangkan tombol **Remove** untuk menghapus record (barang yang sudah dimasukkan).


 ```{note} Semua kolom yang bertanda (*) wajib diisi
```

**Informasi Kolom:**

| No. | Kolom          | Keterangan                                             |
|-----|----------------|--------------------------------------------------------|
| 1   | Document Number| Kode Dokumen Direct Sales                              |
| 2   | Document Date  | Tanggal Pembuatan Dokumen atau Tanggal Transaksi       |
| 3   | Product Id     | Kode Produk                                            |
| 4   | Product Name   | Nama Produk                                            |
| 5   | UOM            | Satuan Barang                                          |
| 6   | Quantity       | Jumlah Barang yang Dibeli                              |
| 7   | Total Price    | Total Harga Pembelian Produk (Per Produk)              |
| 8   | Total Order    | Total Harga Belanjaan (Keseluruhan Harga Barang + PPN) |
| 9   | Value Added Tax| Pajak Pertambahan Nilai (PPN)                          |

 

5. Selanjutnya akan tertera total harga belanjaan yang perlu dibayarkan customer (sudah termasuk PPN). Kemudian klik tombol **Check Out** untuk melakukan pembayaran. 

    ![5](../dokumentasi-akor/transaksi-penjualan-langsung/5.png)
    
6. Setelah itu, masukan metode pembayaran yang digunakan (cash atau transfer), lalu klik tombol **Accept Payment**. Apabila customer memilih metode pembayaran cash, kolom Cash diisi untuk total uang yang diterima dari pembeli, dan kolom Exchange terisi otomatis oleh sistem mengenai uang kembalian yang harus diberikan kepada pembeli.

    ![6](../dokumentasi-akor/transaksi-penjualan-langsung/6.png)

7. Dan apabila customer memilih transfer, maka untuk kolom Account diisi sesuai dengan pilihan pembeli, dapat melalui bank atau e-wallet. Lalu klik tombol **Accept Payment*. 

    ![7](../dokumentasi-akor/transaksi-penjualan-langsung/7.png)

8. Maka akan muncul notifikasi bahwa pembayaran berhasil.

    ![8](../dokumentasi-akor/transaksi-penjualan-langsung/8.png)

## Dokumen dan Jurnal  yang Terbentuk

1. Setiap melakukan transaksi penjualan barang melalui **Direct Sales**. Maka akan otomatis membentuk dokumen di dalam produk transfer. Dokumen tersebut dapat dilihat di dalam menu **Product Transfer (PRTS)** yang berada di dalam module **Product Management**. Berikut dokumen Product Transfer yang terbentuk.

    ![9](../dokumentasi-akor/transaksi-penjualan-langsung/9.png)

2. Selain itu, tidak hanya membentuk dokumen **Product Transfer**, tetapi juga membentuk dokumen di dalam Internal Account. Dokumen tersebut dapat dilihat di dalam menu **Internal Account (INCT**) yang berada di dalam module Accounting. Maka berikut dokumen Internal Account yang terbentuk dari transaksi **Direct Sales** tersebut.

    ![10](../dokumentasi-akor/transaksi-penjualan-langsung/10.png)

3. Transaksi Direct Sales yang dilakukan tidak hanya membentuk dokumen **Product Transfer** dan **Internal Account** saja, tetapi juga membentuk dokumen jurnal. Dokumen tersebut dapat dilihat di dalam menu **Journal (JNL)** yang berada di dalam module **Accounting**. Maka berikut akan ditampilkan jurnal yang terbentuk dari transaksi **Direct Sales** tersebut.

    ![11](../dokumentasi-akor/transaksi-penjualan-langsung/11.png)


```{tableofcontents}
```
