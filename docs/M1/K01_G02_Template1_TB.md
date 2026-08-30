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
| Kelas | *K1* |
| Kelompok | *2*  |

| NIM | Nama |
|---|---|
| *13525124* | *Sulthan Dhiyazka Suwandi* |
| *13525034* | *Dhanesworo Muhammad Datiputro* |
| *13525115* | *Nazhif Hilmi Kistijantoro* |
| *13525121* | *I Made Adi Kusuma Ardana* |
| *13525106* | *Ghaniyul AMri Caulava* |
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
- **Tidak ada kategori/filter khusus kebutuhan kampus**: marketplace umum tidak punya kategori seperti "jas praktikum", "buku mata kuliahtertentu", atau "perlengkapan kos", membuat pencarian barang relevan-kampus menjadi tidak efisien dan lebih susah.
- **Proses transaksi manual**: nego harga, kesepakatan COD, dan konfirmasi dilakukan manual via chat pribadi tanpa histori atau standar yang jelas, memperlambat proses dan meningkatkan risiko miskomunikasi.

---

# BAB 2: Analisis Solusi

## 2.1 Deskripsi Perangkat Lunak
Abstraksikan solusi perangkat lunak yang diusulkan dari sudut pandang pengguna. Jelaskan target platform yang akan digunakan (misalnya: desktop application) beserta alasan pemilihannya. Deskripsikan juga nilai unik (inovasi inti) dari perangkat lunak kalian dan apa yang membedakannya dari solusi yang sudah ada.

## 2.2 Asumsi dan Batasan
**Asumsi :**
- Pengguna memiliki perangkat modern dengan akses internet yang memadai seperti handphone, tablet, maupun laptop/pc
- Pengguna merupakan mahasiswa aktif ITB yang memiliki email dengan domain @itb.ac.id 
- Transaksi pembayaran dan serah terima barang sepenuhnya dilakukan secara langsung antara penjual dan pembeli(COD), diluar tanggung jawab sistem dan pengembang

**Batasan :**
- Sistem tidak dapat melayani proses pembayaran secara digital atau sebagai perantara pembayaran antara penjual dan pembeli
- Platform ini hanya ditujukaan untuk civitas dan mahasiswa ITB(bukan untuk khalayak umum)
- Sistem keamanan dan banyaknya bug kemungkinan bisa terjadi karena durasi pengerjaan yang singkat
---

# BAB 3: Spesifikasi Kebutuhan dan Proses Bisnis

## 3.1 Identifikasi Aktor
| Aktor | Deskripsi |
| :--- | :--- |
| Penjual (Mahasiswa ITB) | Pengguna yang berniat untuk menjual barang preloved miliknya. Mengutamakan kemudahan proses listing, jangkauan listing kepada pembeli, dan reliabilitas sistem. |
| Pembeli (Mahasiswa ITB) | Pengguna yang berniat untuk membeli barang preloved. Mengutamakan keamanan transaksi, pencarian yang jelas dan informasi yang jelas, dan reliabilitas sistem. |
| Admin | Pihak yang mengelola platform. Mengutamakan reliabilitas sistem, kemudahan untuk tracking masalah atau bug, sistem report/laporan yang mudah diverifikasi dan ditangani. |

## 3.2 Kebutuhan Pengguna Awal
Definisikan apa yang ingin dicapai oleh pengguna saat menggunakan sistem ini dalam format *User Story* (Sebagai [Aktor], saya ingin [Aktivitas/Kebutuhan], sehingga [Tujuan/Nilai]). Pastikan kalian berfokus pada "apa yang ingin dilakukan pengguna".

| ID | Aktor | Kebutuhan / Aktivitas | Tujuan / Nilai |
| :--- | :--- | :--- | :--- |
| US-01 | Penjual/Pembeli |  Mendaftar menggunakan email ITB | Hanya warga ITB yang dapat mendaftar dan memiliki informasi yang jelas sehingga menambahkan rasa keamanan |
| US-02 | Penjual | Membuat listing barang | Barang dapat ditunjukkan kepada calon pembeli. |
| US-03 | Pembeli | Mencari barang yang diinginkan berdasarkan nama, harga, kategori, dll. | Pembeli dapat mencari barang sesuai yang diinginkan dengan mudah. |
| US-04 | Penjual/Pembeli | Berkomunikasi dengan penjual/pembeli. | Penjual dan pembeli dapat bernegosiasi dan menyepakati transaksi tanpa keluar platform. |
| US-05 | Penjual/Pembeli | Sistem komunikasi yang aman dan tidak dapat dilihat oleh admin. | Menjaga privasi pengguna platform. |
| US-06 | Penjual | Menandai barang sudah terjual | Listing tidak lagi muncul di pencarian pembeli dan menghindari kesalahpahaman |
| US-07 | Admin | Melihat laporan masalah dari pengguna | Menjaga kualitas dan keamanan platform |
| US-08 | Admin | Memblokir atau menghapus listing dan akun yang dilaporkan bermasalah | Menjaga kualitas dan keamanan platform |

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
