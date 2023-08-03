# Eksplorasi_dan_Analisis_Data_COVID-19_Indonesia

# Latar Belakang Project
COVID-19 merupakan penyakit yang saat ini telah menjadi pandemi secara global. Kondisi menjadi semakin mengkhawatirkan karena hingga detik ini masih belum ditemukan vaksin yang efektif untuk virus penyebab COVID-19. Pemerintah di berbagai negara umumnya dengan sigap membentuk gugus tugas (task force unit) untuk menangani penyebaran COVID-19 di masyarakat, termasuk pemerintah di Indonesia.

Salah satu bentuk aksi yang dilakukan oleh pemerintah adalah dengan mengumpulkan dan menyediakan data pertumbuhan kasus COVID-19 kepada publik. Data pertumbuhan kasus tersebut tidak jarang juga dilengkapi dengan dasbor dan grafik visualisasi pendukung dengan harapan masyarakat dapat memahami informasi dengan lebih mudah. Sebagai contoh adalah portal covid19.go.id besutan Gugus Tugas Penanganan COVID-19 Nasional dan portal PIKOBAR milik pemerintah Provinsi Jawa Barat. Serta banyak portal data COVID-19 lainnya yang disediakan oleh masing-masing pemerintah daerah.

# Menunjukkan Melalui Gambar

Setelah memiliki data yang jinak, Mengekspresikan data tersebut dalam bentuk lain yang harapannya lebih mudah dicerna: grafik. 

Memulai merancang visualisasi yang memiliki estetika dengan menggunakan library matplotlib.

![alt text](https://github.com/muhammadrafi18/Eksplorasi_dan_Analisis_Data_COVID-19_Indonesia/blob/main/Slide1.JPG?raw=true)

# Informasi pada Grafik

Berhasil membuat bar-chart yang diminta. Namun grafik tersebut belum memiliki informasi yang jelas serta cenderung membosankan untuk dilihat. Membuat kembali grafik tersebut dengan menggunakan baris kode yang telah dimodifikasi berikut.

![alt text](https://github.com/muhammadrafi18/Eksplorasi_dan_Analisis_Data_COVID-19_Indonesia/blob/main/Slide2.JPG?raw=true)

# Grafik untuk Kasus Sembuh
Buat grafik serupa dengan menggunakan data kasus sembuh menggunakan warna olivedrab.

![alt text](https://github.com/muhammadrafi18/Eksplorasi_dan_Analisis_Data_COVID-19_Indonesia/blob/main/Slide3.JPG?raw=true)

# Grafik untuk Kasus Meninggal
Buat grafik serupa dengan menggunakan data kasus meninggal menggunakan warna slategrey.

![alt text](https://github.com/muhammadrafi18/Eksplorasi_dan_Analisis_Data_COVID-19_Indonesia/blob/main/Slide4.JPG?raw=true)

# Membuat Bar Chart

Dengan menggunakan data hasil perhitungan tersebut maka sekarang dapat membuat bar-chat penambahan kasus pekanan yang ditambahkan informasi baru untuk menjawab pertanyaan: "Apakah pekan ini lebih baik?"

![alt text](https://github.com/muhammadrafi18/Eksplorasi_dan_Analisis_Data_COVID-19_Indonesia/blob/main/Slide5.JPG?raw=true)

# Membuat Line Chart

Buat line-chart pola kasus aktif dengan menggunakan method plot pada ax.

![alt text](https://github.com/muhammadrafi18/Eksplorasi_dan_Analisis_Data_COVID-19_Indonesia/blob/main/Slide6.JPG?raw=true)

# Grafik komparasi antara akumulasi kasus aktif, kasus sembuh, dan kasus meninggal.

Ada dua pilihan cara yang dapat ditempuh untuk membuat grafik tersebut:
1. Menggunakan data frame cov_jabar_akumulasi, dengan kolom bertipe datetime diset menjadi index sehingga kita memiliki time series dataframe. Kemudian kita secara langsung dapat melakukan line plot dan memilih warna garis yang sesuai untuk membedakan; atau
2. Menggunakan ax.plot() dan mengisikan kolom-kolom yang masing-masingnya menjadi x dan y dengan data=cov_jabar_akumulasi, dan kemudian menset warna berbeda untuk ketiga line plot.

![alt text](https://github.com/muhammadrafi18/Eksplorasi_dan_Analisis_Data_COVID-19_Indonesia/blob/main/Slide7.JPG?raw=true)

# Kesimpulan & Penutup

Telah berhasil melakukan impor data melalui API, melakukan transformasi data, serta membuat visualisasi untuk mengkomunikasikan hasil analisis data tentang COVID-19.

Semoga Anda tetap sehat, waspada dan tetap tenang dalam menghadapi pandemi COVID-19. Selamat dan sukses selalu!
