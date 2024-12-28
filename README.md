### Cohort-Analysis
#### langkah-Langkah Pengerjaan:
##### 1. Add data
Notes:
pandas dan Numpy adalah library yang akan digunakan dalam praktek kali ini.
"Data.csv" merupakan nama file yang kita upload.
Data.head() adalah kodingan ketika anda ingin menampilkan 5 data teratas dari data tersebut.

##### 2. Reformat Timestamp
Reformat Timestamp terletak di kolom InvoiceDate dan diperlukan dalam pembuatan cohort analysis karena data yang tersedia biasanya memiliki format waktu yang detail, seperti harian, mingguan, atau bulanan.

Jika data waktu ini tidak direformat, akan sulit mengelompokkan pengguna ke dalam cohort berdasarkan periode tertentu, seperti minggu atau bulan, yang merupakan elemen penting dalam analisis cohort.

Melalui reformat timestamp, data waktu yang awalnya berupa informasi timestamp dapat diubah menjadi informasi yang lebih terstruktur, seperti bulan atau minggu, sehingga memungkinkan pengelompokan pengguna berdasarkan periode mereka mulai menggunakan produk atau layanan.

##### 3. Membuat Cohort (bisa diliat di repository mengenai step-step nya

##### 4. Membuat Header Cohort
Mengapa perlu menggunakan header?

Membuat header untuk setiap cohort dalam kodingan python pada analisis cohort analysis berguna untuk memberikan konteks dan informasi yang lebih jelas tentang cohort yang sedang dianalisis.

Informasi pada header:

- Periode waktu kategori cohort tertentu yang sedang di analisis
- Ukuran sampel
- Rentang usia
- Jenis kelamin cohort yang sedang di analisis
Informasi yang ada pada header dapat memudahkan kita dalam memahami hasil analisis yang ditampilkan dan membuat keputusan bisnis yang lebih tepat berdasarkan hasil analisis.

##### 5. Pivot Data Cohort
Dalam cohort analysis, pivot table digunakan untuk menganalisis dan membandingkan perilaku pelanggan di berbagai cohort. Contohnya:

Membandingkan persentase pelanggan yang melakukan pembelian ulang pada setiap cohort. Membandingkan rata-rata jumlah pembelian di setiap cohort. Melalui pivot data, informasi penting dapat dikelompokkan dan dibandingkan, memberikan wawasan yang lebih mendalam tentang kinerja bisnis berdasarkan cohort.

Kemudian, kita lakukan pivot table dengan index ‘first_cohort’, kolom ‘cohort_distance’, dan values ‘CustomerID’.

##### 6. Visualisasi Cohort pada Heatmap

Link data: https://www.kaggle.com/datasets/carrie1/ecommerce-data
