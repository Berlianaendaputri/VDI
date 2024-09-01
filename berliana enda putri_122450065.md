  # Tugas 1 VDI
# RESUME ARTIKEL

**Nama**: Berliana Enda Putri
**NIM**: 122450065
**Kelas**: RB
--------
**Judul:** [Making data visualization more efficient and effective: a survey](https://sci-hub.se/https://link.springer.com/article/10.1007/s00778-019-00588-3)  
**Jurnal:** The VLDB Journal  
**Penulis:** Xuedi Qin, Yuyu Luo, Nan Tang, Guoliang Li  
**Penerbit:** Springer-Verlag GmbH Germany, part of Springer Nature 2019

----------
## I. Pendahuluan

Visualisasi Data dapat membantu menyajikan data menjadi lebih baik, visualisais data cocok digunakan untuk data yang lebih besar dan dapat mempermudah interpretasi hasil analisis data, sehingga visualisasi data sangat diperlukan untuk bisa memahami data secara lebih baik dan juga dalam membuat keputusan .
Visualisasi data merupakan proses mengubah sebuah data abstrak menjadi representasi visual. visualisasi data bisa dilakukan untuk memberikan gambaran umum untuk visual data yang lebih besar. 
Pada umumnya visualisasi data digunakakan dalam aplikasi terkait database seperti  Excel, Google Sheets , Oracle Data Visualization Desktop, IBM DB2, Amazon Quicksight, Microsoft Power BI, dan banyak lainnya.

## Alur Visualisasi Data

![Alur visualisasi data](https://github.com/Berlianaendaputri/foto/raw/b79ffee666063423518022b8217841da5aa0c304/Step%20visualisasi%20data.png)

*Gambar 1. Alur visualisasi data*

1. Impor data adalah untuk mengambil data yang diperlukan dari sumber data yang
diinginkan.
2. Persiapan data adalah untuk mempersiapkan data yang diimpor untuk visualisasi,
misalnya, dengan menormalkan nilai, mengoreksi entri yang salah, dan
menginterpolasi nilai yang hilang.
3. Manipulasi data adalah untuk memilih data yang akan divisualisasikan (alias
memfilter dari komunitas visualisasi) dan mungkin dengan operasi umum lainnya
seperti menggabungkan dan mengelompokkan.
4. Pemetaan adalah untuk memetakan data yang diperoleh dari proses di atas ke
primitif geometris (misalnya, titik dan garis), bersama dengan atributnya
(misalnya, warna, posisi, dan ukuran).
5. Rendering adalah mengubah data geometris di atas menjadi representasi visual

**Tiga arah yang membuat visualisasi data lebih efisien dan efektif**

(1) Spesifikasi Visualisasi
spesifikasi visualisasi data bisa membuat pengguna menentukan apa yang diinginkan,terdapat dua alasan tentang spesifikasi data yaitu yang pertama kelengkapan diri dan perspektif desain bahasa terutama dalam pemetaan dari alur kerja.

(2) Pendekatan Efesien untuk Visualisasi Data
Pada Pembuatan visualisasi data dapat diskalakan menjadi dua komponen yaitu manipulasi dan pemetaan. Terdapat beberapa solusi perkiraan  dan juga solusi progresif  yang digunakan dalam mengatasi big data sehingga dapat memberikan respons yang baik.

(3) Rekomendasi Visualisasi Data 
Sistem visualisasi data dapat memungkinkan pengguna untuk memberikan sistem secara otomatis untuk menyelesaikan visualisasi dan memberikan rekomendasi visualisasi dari berbagai bidang.


# II Spesifikasi Visualisasi 
 **Spesifikasi Visualisasi data**
Bahasa visualisasi data terdiri dari tiga bagian yaitu data,tanda,dan pemetaan. Adapun contoh dari data antara lain filter dan sortir yang digunakan untuk mengubah rekaman data yang sudah ditentukan. Contoh dari tanda atau isyarat visual dapat dilihat dari jenisnya seperti batang,garis,dan titik, ukuran seperti lebar,tinggi visualisasi, legenda seperti informasi legenda, dan juga bisa diliat dari properti seperti lebar dan warna batang. Pemetaan digunakan untuk mematakan ke tanda yang sesuai.

**Kategori bahasa visualisasi daata**
Bahasa visualisasi data didasarkan pada ekspresivitasny semakin rendah level suatu bahasa semakin ekspresif bahasa tersebut. 

![Spesifikasi Visualisasi Data](https://github.com/Berlianaendaputri/foto/raw/b79ffee666063423518022b8217841da5aa0c304/Spesifikasi%20visualisasi%20data.png)
*Gambar 2. Spesifikasi visualisasi data*


**Operasi Visual berbasis GUI**
Cara yang mudah digunakan untuk memberikan spesifikasi dengan mengikuti prinsip manipulasi langsung yaitu sebuah konsep yang digunakan untuk aspek interaksi manusia dan komputer.
Daftar alat berbasi GUI antara lai Qlik, Excel, Google Sheets,Amazon Quick sight, Microsoft power, Google fusion tables, dan banyak lagi.


# III Pendekatan Efisien Untuk Visualisasi Data
Visualisasi data eksak yang dapat menghitung visualisasi presisi dengan cara yang cepat, namun menyediakan visualisasi eksak yang memungkinkan tidak terlalu dapat dilakukan karena ukuran data yang besar dan kompleksitas kueri yang tinggi.

**Visualisasi Data yang Tepat**
Sistem visualisasi data dapat membaca data dari basis data dan juga dapat memanipulasi data dengan SQL dan kemudian menggunakan alat visualisasi untuk menampilkan visualisasi. Adapun juga 

**Mengintegrasikan Sistem Visualisasi dengan DBMS**
Sistem visualisasi dengan menggunakan DBMS dilakukan dengan menggunakan terjemahan queri misalnya DeepEye, Polaris, SeeDB untuk mendapatkan data dengan mengeluarkan SQL ke basis data. Bahasa visualisa dapat diubah menjadi bahasa kueri SQL. Penggunaan DBMS tidak terlalu baik, terdapat beberapa kekurangan seperti  fungsi yang diulang, sehingga menghasilkan hasil yang teknik pengoptimalan yang tidak sama dengan server. Selain DBMS ada juga manajemen visualisasi data seperti DVMS yang melibatkan data dan skala.

Teknik optimasi visualisasi interaktif DVMS

* Penyimpanan kolam dalam manajemen data faktor utamanya adalah tata letak dat, misalnya berbasis baris dan berbasis kolam tata letak.
* Indeks digunakan untuk meningkatkan kinerja pencarian dengan mengurangi jumlah rekaman dan baris.
* Komputasi paralel digunakan untuk pemrosesan kueri dalam sistem visualisasi data.
* Prediksi dan prapengambilan merupakan salah satu yang sangat penting dalam visualisasi untuk mendapatkan gambaran yang akan di visualisasikan.

**Studi kasus menggunakan kyrix dan tableau**
* Kyrix adalah sistem visualisasi data interaktif yang dapat disklakan. kyrix menyediakan antarmuka spesifikasi visualisasi deklaratif di front end dan pemrosesan visualisasi yang efektid dan dapat disklakan di back end di mana pengguna memperbesar tampilan untuk melihat informasi terperinci dan menampilkan gambaran umum.
* TDE adalah mesin data yang disesuaikan untuk visualisasi dan bisa mengoptimalkan mesin data terutama dalam perspektif yaitu penyimpanan dan kompresif beriorentasi kolam, penataan ulang operator, pengurangan kardinalitas, dukukangan visualisasi lainnya.

**Visualisasi data perkiraan**
 Visualisasi data mempunyai tiga perspektif yaitu:
 * berbasis AQP : cara untuk menghasilkan visualisasi dalam waktu interaktif . pada teknik AQP menggunakan subset represeentatif dari data yang dapat memberikan pengguna visualisasi perkiraan.
 * Berbasis persepsi manusia visualisasi yang dapat di perkirakan menghasilkan hasil perkiraan berdasarkan sampel representatif tetapi dengan dampak minimal pada kualitas visualisasi.
 
 
# IV Rekomendasi Visualisasi

**Rekomendasi berbasis spesifikasi**
**~spesifikasi tidak lengkap**
klasifikasi tersebut tidak memerlukan input pengguna namun menerima input spesifikasi elemen visualisasi persial pengguna untuk visualisasi yang diinginkan, misalnya APT menerima tujuan tampilan data sebelumnnya.

**Metode umum yang digununakan untuk memberikan peringkat kandiddat visualisasi**

* Peringkat visualisasi berbasis aturan
* Aturan perseptual
* Pemeringkatan visualisasi berbasis pembelajaran mesin
* Belajar dengan kendala lunak
* Belajar dengan contoh

**~spesifikasi berbasis referensi**
spesifikasi ini merekomendasikan visualisasi berdasarkan data referensi atau visualisasi referensi. Pada spesifikasi ini merekomendasikan SeeDB berbasis deviasi dan berbasis anormal.

# V Ringkasan
Terdapat sistem rekomendasi visualisasi dengan spesifikasi kosong, seperti draco, Data2Vis, dan Rank by feature dapat membantu pengguna untuk menjelajahi data dengan ceoat untuk pengguna dengan data yang diinginkan visualisasi.

Tabel 1 Ringkasan sistem rekomendasi visualisasi : jenis visualisasi, input, dan matrik peringkat utama.
![Tabel 1](https://github.com/Berlianaendaputri/foto/raw/b79ffee666063423518022b8217841da5aa0c304/Screenshot%202024-08-31%20204413.png)





# VI Arah penelitian lainnya
**Persiapan data untuk visualisasi data**
Data yang divisualisasikan harus bersih seperti normalisasi nilai, duplikat, imputasi nilai yang hilang, dan deteksi outlier.

Adapun untuk menyelidiki dampak data kotor pada visualisasi data sebagai berikut:
* scorpion
* Data yang hilang
* Mendeteksi visualisasi bias
* pembersihan data yang memperhatikan tugas.

# VII Kesimpulan

Visualisasi data merukapakab suatu bidang yang berkembang dengan sistem yang dikembangkann dimasa sekarang yang sangat berkontribusi pada era digital. Terdapat banyak persprektif yang diberikan oleh visualisasi data yang lebih efesien dan efektif.






