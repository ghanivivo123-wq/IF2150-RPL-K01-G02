<h1>
IF2150 REKAYASA PERANGKAT LUNAK
<br>
TUGAS 1
<br>
TOPIC BRAINSTORMING
</h1>
<br>

## *ITBELI*

### Untuk: *Kak Mikha*

Dipersiapkan oleh:
| Informasi | Keterangan |
| --- | --- |
| Kelas | *\K-01\* |
| Kelompok | *\2\*  |

| NIM | Nama |
|---|---|
| *13525106* | *Ghaniyul Amri Caulava* |
| *13525124* | *Sulthan Dhiyazka Suwandi* |
| *13525034* | *Dhanesworo Muhammad Datiputro* |
| *13525115* | *Nazhif Hilmi Kistijantoro* |
| *13525121* | *I Made Adi Kusuma Ardana* |
---

<br>
<br>

# BAB 1: Analisis Permasalahan

## 1.1 Latar Belakang Masalah
Konsumsi barang di kalangan mahasiswa, khususnya mahasiswa ITB, memiliki karakteristik siklus pakai yang pendek namun frekuensi pembelian yang tinggi. Contoh nyatanya seperti jas praktikum dan alat lab yang hanya relevan selama masa perkuliahan tertentu, buku mata kuliah yang menumpuk begitu semester berakhir, kalkulator scientific, hingga perlengkapan kos yang sering ditinggalkan atau dibuang saat mahasiswa pindah kos maupun lulus. Barang-barang ini secara fisik masih layak pakai, namun kehilangan relevansi penggunaan bagi pemiliknya dalam waktu yang cukup singkat.

Pola konsumsi seperti ini sejalan dengan isu global yang diangkat dalam Sustainable Development Goals (SDG) 12: Responsible Consumption and Production, khususnya target 12.5 yang menekankan pengurangan timbulan limbah melalui pencegahan, pengurangan, daur ulang, dan penggunaan kembali (reuse). Di tingkat nasional, permasalahan ini terkonfirmasi oleh data Sistem Informasi Pengelolaan Sampah Nasional (SIPSN) KLHK, yang menunjukkan bahwa limbah kain atau tekstil menyumbang sekitar 2,6% dari total timbulan sampah nasional, sementara limbah kertas dan karton  menyumbang angka yang lebih besar, yakni 10,7%. Angka ini merepresentasikan jutaan ton barang yang sebenarnya memiliki potensi sirkularitas tinggi. Sebagian besar dari barang-barang tersebut secara fungsi masih sangat layak dipakai ulang, namun berakhir di tempat pembuangan semata-mata karena ketiadaan ekosistem perpindahan kepemilikan yang efektif kepada mereka yang membutuhkan.

Urgensi masalah ini terletak pada dua sisi. Di sisi lingkungan, barang yang tidak di-reuse berkontribusi pada limbah dan mendorong produksi barang baru yang tidak perlu. Lalu pada sisi ekonomi mahasiswa, banyak barang bernilai justru dibiarkan menumpuk atau dibuang padahal bisa dijual atau dipakai ulang oleh mahasiswa lain yang justru hanya membutuhkan versi bekas dengan harga yang lebih terjangkau.

## 1.2 Analisis Kondisi Saat Ini
Saat ini, transaksi jual beli barang preloved di kalangan mahasiswa ITB umumnya berlangsung secara informal melalui grup WhatsApp atau Line per angkatan atau himpunan, story Instagram pribadi, atau marketplace umum yang tidak dikhususkan untuk lingkungan ITB.

Beberapa celah dari kondisi ini:
- **Fragmentasi informasi**: listing barang tersebar di puluhan grup berbeda tanpa sistem pencarian terpusat, sehingga calon pembeli sulit menemukan barang yang dicari dan penjual sulit menjangkau pembeli potensial di luar lingkaran pertemanannya.
- **Minim kepercayaan**: tidak ada sistem verifikasi identitas atau riwayat transaksi, sehingga rawan penipuan atau miskomunikasi harga ataupun kondisi barang.
- **Tidak ada kategori/filter khusus kebutuhan kampus**: marketplace umum tidak punya kategori seperti "jas praktikum", "buku mata kuliah [kode MK]", atau "perlengkapan kos", membuat pencarian barang relevan-kampus menjadi tidak efisien dan lebih susah.
- **Proses transaksi manual**: nego harga, kesepakatan COD, dan konfirmasi dilakukan manual via chat pribadi tanpa histori atau standar yang jelas, memperlambat proses dan meningkatkan risiko miskomunikasi.

---

# BAB 2: Analisis Solusi

## 2.1 Deskripsi Perangkat Lunak
Abstraksikan solusi perangkat lunak yang diusulkan dari sudut pandang pengguna. Jelaskan target platform yang akan digunakan (misalnya: desktop application) beserta alasan pemilihannya. Deskripsikan juga nilai unik (inovasi inti) dari perangkat lunak kalian dan apa yang membedakannya dari solusi yang sudah ada.

## 2.2 Asumsi dan Batasan
Definisikan secara tegas asumsi (baik teknis maupun dari sisi pengguna) yang menjadi dasar pengembangan. Tuliskan batasan seperti regulasi/hukum, keterbatasan sumber daya, dan ruang lingkup solusi.

---

# BAB 3: Spesifikasi Kebutuhan dan Proses Bisnis

## 3.1 Identifikasi Aktor
Buatlah daftar seluruh aktor (pengguna) yang akan berinteraksi langsung dengan sistem solusi yang kalian kembangkan. Berikan penjelasan singkat mengenai peran dan karakteristik dari masing-masing aktor tersebut.

| Aktor | Deskripsi |
| :--- | :--- |
| *Kasir* | *Pengguna ini bertindak sebagai pihak yang bertanggung jawab untuk memproses transaksi harian dan melayani pembayaran pelanggan. Karakteristik dari pengguna ini adalah mengutamakan kecepatan dan keakuratan saat bertransaksi.* |
| ... | ... |


## 3.2 Kebutuhan Pengguna Awal
Definisikan apa yang ingin dicapai oleh pengguna saat menggunakan sistem ini dalam format *User Story* (Sebagai [Aktor], saya ingin [Aktivitas/Kebutuhan], sehingga [Tujuan/Nilai]). Pastikan kalian berfokus pada "apa yang ingin dilakukan pengguna".

| ID | Aktor | Kebutuhan / Aktivitas | Tujuan / Nilai |
| :--- | :--- | :--- | :--- |
| US-01 | *Kasir* |  *Memindai barcode barang* | *Proses pembayaran berjalan cepat dan akurat* |
| US-02 | *[Nama Aktor]* | *[Kebutuhan pengguna]* | *[Tujuan yang dicapai pengguna]* |
| ... | ... | ... | ... |

## 3.3 Model Proses Bisnis
Buatlah *Activity Diagram* atau *Swimlane Diagram* yang menunjukkan alur kerja proses bisnis dari sistem solusi. Diagram ini harus memvisualisasikan bagaimana alur operasional di dunia nyata berjalan lebih efisien dengan adanya interaksi antara aktor (yang didefinisikan pada poin 3.1) dan sistem perangkat lunak. Perhatikan notasi yang digunakan dalam pembuatannya.
<br>

<p align="center">
<img alt="Contoh Activity Diagram" src="./assets/diagram/diagram-act-1.avif" width="70%">
</p>
<p align="center">
<i>Gambar 1. Contoh Activity Diagram</i>
</p>

<br>

# Referensi
- Diagram UML: https://www.drawio.com/, https://staruml.io/