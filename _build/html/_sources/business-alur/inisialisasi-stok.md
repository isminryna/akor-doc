# Menginisialisasi Stok


## Buat Initial Stok

Inisialisasi Stok merupakan tahapan untuk mengidentifikasi atau memasukkan data barang akhir yang telah tercatat pada sistem sebelumnya dan dipindahkan ke dalam sistem AKOR. Sebelum membuat inisial stok tentukan terlebih dahulu untuk bisnis area dan storage yang akan digunakan sebagai tempat penyimpanan produk atau barang. Pada tahap ini, langkah pertama yaitu menambahkan area bisnis dan storage di dalam menu **Accounting Setting**. Kemudian setelah itu, masuk ke dalam menu Product Transfer untuk membuat dokumen product transfer dengan tipe transaksi initial stock. 

---

## Menambahkan Business Area

Untuk membuat business area dapat dilakukan di menu **Accounting Setting (ACS)** pada modul **Accounting**.

1. Jalankan menu **Accounting Setting (ACS)** pada modul Accounting.

    ![1](../dokumentasi-akor/buat-inisialisiasi-stok/1.jpg)

    
2. Pilih dan klik sub menu **Business Area**

    ![2](../dokumentasi-akor/buat-inisialisiasi-stok/2.png)


3. Klik tombol **Add** maka akan muncul kolom kosong yang siap diisikan data baru.

    ![3](../dokumentasi-akor/buat-inisialisiasi-stok/3.png)

    ```{note} * Isi semua kolom yang terdapat tanda (*)
	  * Kolom Code harus unik.
    ```

**Informasi Kolom:**

| No. | Kolom        | Keterangan            |
|-----|--------------|-----------------------|
| 1   | Company      | Kode Perusahaan       |
| 2   | Code         | Kode Area Bisnis      |
| 3   | Name         | Nama Area Bisnis      |
| 4   | Description  | Keterangan            |


4. Klik tombol **Save** untuk menyimpan data.

    ![4](../dokumentasi-akor/buat-inisialisiasi-stok/4.png)

Secara default sudah tersedia business area yang bisa langsung digunakan. Untuk mengubah data business area yang sudah ada klik pada kolom yang akan diubah.


5. Klik pada salah satu kolom Name lalu ubah nama area bisnis nya.

    ![5](../dokumentasi-akor/buat-inisialisiasi-stok/5.png)

6. Klik tombol **Save** untuk menyimpan perubahan.

    ![6](../dokumentasi-akor/buat-inisialisiasi-stok/6.png)

## Menambahkan Storage
Untuk membuat storage dapat dilakukan di menu **Product Setting (PRS)** pada modul **Product Management**.

1. Jalankan menu **Product Setting (PRS)** pada modul **Product Management**.

    ![7](../dokumentasi-akor/buat-inisialisiasi-stok/7.jpg)

2. Pilih dan klik sub menu **Storage**.

    ![8](../dokumentasi-akor/buat-inisialisiasi-stok/8.png)

3. Klik tombol **Add** maka akan muncul kolom kosong yang siap diisikan data baru.

    ![9](../dokumentasi-akor/buat-inisialisiasi-stok/9.png)

    ```{note} 	* Isi semua kolom yang terdapat tanda (*)
	          * Kolom Storage ID harus unik.
	* Kolom Company dan Business Area jenisnya adalah pilihan, maka perlu ditambahkan data terlebih dahulu. Untuk menambahkan Company dapat dilihat pada modul System menu General Setting(GNS) Sub Menu Company. Sedangkan untuk menambahkan Business Area dapat dilihat pada modul Accounting menu Setting(ACS) Sub Menu Business Area
	* Kolom Company dan Business Area bisa dipilih melalui tombol **list**
    ```


Informasi Kolom:

| No. | Kolom           | Keterangan                 |
|----:|-----------------|----------------------------|
| 1   | Storage ID      | Kode Gudang                |
| 2   | Storage Name    | Nama Gudang                |
| 3   | Company         | Kode Perusahaan            |
| 4   | Business Area   | Kode Area Bisnis           |
| 5   | Description     | Keterangan                 |


4. Klik tombol **Save** untuk menyimpan data.

    ![10](../dokumentasi-akor/buat-inisialisiasi-stok/10.png)

 

Secara default sudah tersedia storage yang bisa langsung digunakan. Untuk mengubah data storage yang sudah ada klik pada kolom yang akan diubah.

5. Klik pada salah satu kolom Storage Name lalu ubah nama storage nya.

    ![11](../dokumentasi-akor/buat-inisialisiasi-stok/11.png)

6. Klik tombol **Save** untuk menyimpan perubahan.

     ![12](../dokumentasi-akor/buat-inisialisiasi-stok/12.png)

## Membuat Initial Stock

1. Jalankan menu **Product Transfer (PRTS)** pada modul Product Management.

    ![13](../dokumentasi-akor/buat-inisialisiasi-stok/13.jpg)

2. Klik tombol **New**.

    ![14](../dokumentasi-akor/buat-inisialisiasi-stok/14.png)

3. Pilih opsi “Initial Stock” pada kolom Txn. Type lalu klik tombol **Next**.

   ![15](../dokumentasi-akor/buat-inisialisiasi-stok/15.png)

4. Maka akan muncul tampilan form seperti berikut.

    ![16](../dokumentasi-akor/buat-inisialisiasi-stok/16.png)

5. Untuk menambahkan data barang klik tombol **Add** maka akan muncul 1 baris kolom kosong yang siap diisi data.

    ![17](../dokumentasi-akor/buat-inisialisiasi-stok/17.png)

    ```{note} 	* Isi semua kolom yang bertanda (*)
	* Perlu diperhatikan pada kolom "Unit Price" diisi dengan nilai "Harga Pokok Penjualan" terakhir. Pastikan total jumlah kolom Unit Price dikali Quantity sama dengan nilai pada akun "Inventory" yang telah diisi pada bagian "Buat Saldo Awal Jurnal"
    ```

**Informasi Kolom:**

| No. | Kolom          | Keterangan                    |
|----:|----------------|-------------------------------|
| 1   | Txn. Type      | Jenis Transaksi               |
| 2   | Company        | Kode Perusahaan               |
| 3   | Business Area  | Kode Area Bisnis              |
| 4   | Storage        | Kode Penyimpanan              |
| 5   | Description    | Keterangan Dokumen            |
| 6   | Document Number| Nomor Dokumen                 |
| 7   | Document Date  | Tanggal Pembuatan Dokumen     |
| 8   | Document Ref.  | Nomor Dokumen Referensi       |
| 9   | Seq            | Nomor Urut Record             |
|10   | Product ID      | Kode Produk atau Barang        |
|11   | Product Name    | Nama Produk                    |
|12   | UOM             | Satuan Barang                 |
|13   | Unit Price      | Harga Pokok Penjualan         |
|14   | Quantity        | Jumlah Barang                 |
|15   | Business Center | Kode Tempat Bisnis Berlangsung |
|16   | Description     | Keterangan Barang              |


6. Klik tombol **Save** untuk menyimpan data.

    ![18](../dokumentasi-akor/buat-inisialisiasi-stok/18.png)

```{tableofcontents}
```
