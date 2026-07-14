# Restaurant-Sales-Analysis

## Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis data transaksi restoran menggunakan Python dan Power BI guna memahami pola pembelian pelanggan serta menghasilkan insight yang dapat mendukung pengambilan keputusan bisnis. Analisis dilakukan berdasarkan rekomendasi yang diberikan oleh penyedia dataset, sehingga seluruh proses pengolahan data, analisis, dan visualisasi difokuskan untuk menjawab pertanyaan bisnis yang telah ditentukan.

## Latar Belakang

Dalam industri restoran, memahami perilaku pelanggan merupakan salah satu faktor penting dalam meningkatkan kualitas layanan dan strategi bisnis. Data transaksi dapat dimanfaatkan untuk mengetahui menu yang paling diminati, waktu operasional tersibuk, hingga kategori menu yang memiliki potensi untuk dikembangkan. Melalui proyek ini dilakukan proses pembersihan data, analisis, dan visualisasi sehingga menghasilkan informasi yang dapat digunakan sebagai dasar pengambilan keputusan bisnis.

## Tujuan Analisis

Analisis ini dilakukan untuk menjawab beberapa pertanyaan bisnis yang direkomendasikan oleh penyedia dataset.

1. What were the least and most ordered items? What categories were they in?

2. What do the highest spend orders look like? Which items did they buy and how much did they spend?

3. Were there certain times that had more or less orders?

4. Which cuisines should we focus on developing more menu items for based on the data?

## Dataset

Dataset terdiri dari dua tabel utama.

Dataset	Deskripsi
menu_items	Berisi informasi menu restoran seperti nama menu, kategori, dan Harga.
order_details	Berisi data transaksi pelanggan yang meliputi tanggal, waktu, dan item yang dipesan.


Setelah proses pembersihan data, kedua tabel digabungkan menjadi satu dataset baru bernama **restaurant_clean.csv** yang digunakan pada proses analisis dan visualisasi menggunakan Power BI.

## Tools yang Digunakan

- Python
- Pandas
- Google Colab
- Power BI

## Persiapan Data

Tahapan persiapan data yang dilakukan meliputi:

- Memuat dataset ke dalam Python.
- Memahami struktur dataset.
- Memeriksa missing value.
- Memeriksa duplicate data.
- Menangani missing value.
- Mengubah tipe data agar sesuai dengan kebutuhan analisis.
- Menggabungkan dataset **order_details** dan **menu_items**.
- Menambahkan kolom **hour** untuk analisis berdasarkan jam transaksi.
- Menyimpan dataset hasil pembersihan menjadi **restaurant_clean.csv**.

## Exploratory Data Analysis

Analisis dilakukan untuk menjawab seluruh pertanyaan bisnis yang diberikan oleh penyedia dataset, yaitu:

- Menu paling banyak dipesan.
- Menu paling sedikit dipesan.
- Pesanan dengan pengeluaran tertinggi.
- Jumlah pesanan berdasarkan jam.
- Jumlah penjualan berdasarkan kategori menu.

## Dashboard Power BI

Dashboard dibuat untuk menyajikan hasil analisis secara interaktif sehingga memudahkan pengguna dalam memahami pola penjualan restoran.

## Dashboard Power BI

![Dashboard](images/dashboard.png)

## Business Insight

Beberapa insight yang diperoleh dari hasil analisis antara lain:

Menu Paling Banyak dan Paling Sedikit Dipesan, hamburger merupakan menu dengan jumlah pemesanan tertinggi, sedangkan Cheese Quesadillas menjadi menu dengan jumlah pemesanan terendah. Temuan ini dapat menjadi dasar untuk mempertahankan menu yang populer serta mengevaluasi menu dengan permintaan rendah.
Pesanan dengan Pengeluaran Tertinggi, pesanan dengan nilai pengeluaran tertinggi terdiri dari beberapa menu dalam satu transaksi, pola ini dapat dimanfaatkan untuk menyusun paket menu atau strategi bundling.
Jumlah Transaksi Berdasarkan Jam, aktivitas transaksi meningkat pada jam makan siang dan kembali meningkat pada jam makan malam, sehingga kedua periode tersebut merupakan waktu operasional tersibuk. Informasi ini dapat digunakan untuk membantu perencanaan staf dan persediaan bahan baku.
Jumlah Penjualan per Kategori Menu, Kategori Asian memiliki jumlah penjualan tertinggi dibandingkan kategori lainnya, sehingga berpotensi menjadi fokus pengembangan menu di masa mendatang. Sebaliknya, kategori dengan penjualan lebih rendah dapat dievaluasi untuk meningkatkan daya tarik pelanggan.


## Rekomendasi Bisnis

Berdasarkan hasil analisis, beberapa rekomendasi yang dapat dipertimbangkan adalah:

- Mengembangkan variasi menu pada kategori dengan permintaan tinggi.
- Mengoptimalkan jumlah staf pada jam operasional yang paling ramai.
- Menyusun strategi promosi berdasarkan pola pembelian pelanggan.
- Mengevaluasi menu dengan tingkat pemesanan rendah untuk meningkatkan performa penjualan.
