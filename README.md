# Kegiatan Perkuliahan

# Pertemuan Pertama

- Perkenalan mata kuliah robotika
- Penjelasan sistem pembelajaran
- Gambaran materi robotik yang akan diajarkan
- Informasi tentang pengerjaan UTS dan UAS

# Pertemuan Kedua

- Instalasi aplikasi yang diperlukan untuk mata kuliah robotik
- Install board manager esp32 pada arduino
- Pembagian e-book untuk arduino
- Instruksi untuk pengaturan awal arduino

# Pertemuan Ketiga

- Percobaan program yang disediakan Pak Basuki untuk mesin ITCLab
- Mesin ITCLab adalah mesin yang memberikan respon panas ketika dihidupkan

# Pertemuan Keempat

- Melanjutkan percobaan ITCLab untuk mematikan dan menghidupkan lampu LED
- Lampu LED adalah indikator aktif atau tidak mesin ITCLab

# Pertemuan Kelima

- Melakukan percobaan dengan mesin IMCLab
- Mesin IMCLab adalah mesin yang memberikan respon perputaran ketika dihidupkan
- Kecepatan perputaran mesin IMCLab dapat diatur melalui kode di arduino

# Pertemuan Keenam

- Mengkoneksikan IoT MQTT Panel dengan arduino agar sistem bisa dikendalikan melalui handphone
- Koneksi dibantu oleh library PubSubClient agar dapat berkomunukasi melalui jaringan internet
- Diperlukan hotspot dari handphone serta nama dan password pada kode dalam arduino

# Pertemuan Ketujuh

- Praktek mengendalikan robot BNU V2 menggunakan IoT MQTT Panel

# tugas-robotik-ecosense

# Pembelajaran di Kelas

- Belajar menginstall arduino IDE dan beberapa library yang dibutuhkan
- Belajar arduino dengan itclab yang dimana pada waktu itu belajar agar bisa menghidupkan dan mematikan lampu lewat itclab
- Belajar arduino dengan imclab yakni mencoba menggerakkan motor dengan menggunakan control arduino
- Belajar Penerapan IOT dengan mendownload IOT Mqtt Panel pada android dan menginstall library PubSubClient untuk menghubungkan program arduino dengan broker.
- Belajar menggunakan robot BNU V2 menggunakan kontrol IOT pada IOT Mqtt Panel

# Pengerjaan Final Project

# Pada Minggu 1 :

- Mencari dataset Waste Classification Data di kaggle [Lihat dataset](https://www.kaggle.com/datasets/techsash/waste-classification-data).
- Mulai membangun model CNN dari awal yakni dengan menggabungkan beberapa layer convolutional dengan beberapa layer yang lainnya.
- Melakukan training terhadap dataset training yang telah ditemukan.
- Melakukan evaluasi terhadap dataset testing yang telah ditemukan.
- Mendapatkan hasil yang kurang memuaskan karena dari hasil evaluasi hanya mendapatkan accuracy 0.5.

# Pada Minggu 2 :

- Mencoba meningkatkan nilai accuracy model agar menjadi lebih baik.
- Melakukan training model baru dengan dataset training.
- Melakukan testing model baru dengan dataset testing.
- Mendapatkan Hasil yang lebih baik dengan mendapatkan hasil accuracy pada tahap testing 0.83

# Pada Minggu 3 :

- Terus meningkatkan model klasifikasi sampah dengan akurasi 0.94
- Membuat model computer vision yang menggabungkan model sebelumnya dengan model YOLO v8
- Membuat agar computer vision dapat terhubung dengan serial

# Pada Minggu 4 :

- Uji coba program computer vision yang telah dibuat dengan robot BNU V2.

![Dokumentasi uji coba](tugas-robotika.jpg)
