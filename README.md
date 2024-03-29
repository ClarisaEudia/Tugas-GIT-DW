# Tugas-GIT-DW
Pada Tugas GIT Day 15 SIB Data Warehousing 6 ini kita akan membuat repository dan mengupload Tugas Python 5: OOP pada repository yang telah dibuat. Adapun penjelasan Tugas Python 5: OOP adalah sebagai berikut:

## OOP

### Class
Pada Tugas Python 5: OOP kita akan membuat 2 kelas yaitu:
1. class MarketingDataETL
2. class TargetedMarketingETL

#### class MarketingDataETL
Pada class MarketingDataETL terdiri dari 3 metode:
1. extract(): akan membaca data dari sebuah file CSV (Misalkan, marketing_data.csv)
2. transform(): akan melakukan pembersihan dan transformasi sederhana pada data (seperti mengubah format tanggal atau membersihkan nilai yang kosong)
3. store(): akan menyimpan data yang telah ditransformasi ke dalam struktur data DataFrame

#### class TargetedMarketingETL
Setelah membuat class MarketingDataETL yang kemudian dilakukan extract, transform, dan store ke dalam struktur DataFrame. Selanjutnya: 
1. Akan digunakan inheritance untuk membuat class TargetedMarketingETL yang mewarisi dari MarketingDataETL. 
2. Tambahkan metode segment_customers() yang mengelompokkan pelanggan berdasarkan kriteria tertentu (misalnya, pengeluaran total atau kategori produk yang dibeli).
3. Demonstrasi polymorphism dengan meng-override metode transform() dalam TargetedMarketingETL untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi.


