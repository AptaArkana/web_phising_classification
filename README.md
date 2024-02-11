# Web Phising Classification
<p align='justify'>Projek ini bertujuan untuk mengidentifikasi dan mengklasifikasikan situs web phishing menggunakan teknik Deep Learning, dengan menganalisis URL dan konten HTML untuk mendeteksi ciri-ciri phishing/penipuan seperti kesalahan pengejaan nama domain, subdomain yang mencurigakan, formulir yang meminta data sensitif, skrip mencurigakan, dan desain halaman, dikarenakan phishing detector tradisional hanya menggunakan URL saja.</p>

<p align='justify'>Menurut laporan Indonesian Anti-Phishing Data Exchange (IDADX) untuk periode selama tahun 2023, <b>laporan url phishing tertinggi</b> terjadi pada <b>bulan Februari</b> sebanyak <b>15.050</b> dan terendah <b>bulan November</b> sebanyak <b>1.729</b>. Menurut laporan terbaru dari Indonesian Anti-Phishing Data Exchange (IDADX) untuk <b>periode Oktober hingga Desember 2023</b>, terdapat <b>8.161</b> laporan URL phishing. <b>Bulan Desember</b> mencatat jumlah pelaporan <b>phishing tertinggi</b> dibandingkan bulan lainnya selama Q4 2023.</p>

## Pengumpulan Dataset
<p align='justify'>Merupakan dataset yang terdiri dari 45,373 contoh, mewakili halaman web benign dan phishing secara merata. Setiap contoh mencakup berbagai elemen dokumen HTML seperti teks, hyperlink, gambar, tabel, daftar, dan berbagai komponen URL mulai dari subdomain hingga query. Terdapat dua file excel pada dataset ini, yakni URL.xlsx dan HTML.xlsx. Tiap file excel memiliki dua kolom, yakni ‘Category’ dan ‘Data’ Dataset ini terdiri dari data yang dikumpulkan dari Alexa.com untuk halaman web yang sah dan phishtank.com untuk halaman web phishing</p>

## EDA
<p align='justify'>Dataset terdiri dari : </p>
``Banyak baris dataset url 45373 dan kolom 2``
<br>`Banyak baris dataset html 45373 dan kolom 2`

<img style="display:flex; width:auto; height:auto;" alt="Word Cloud Berita Fakta" src="https://github.com/AptaArkana/web_phising_classification/assets/79633073/93484cd3-ef48-4d25-bd26-e7144b3baf39">
<p align='justify'>Dataset ini termasuk ke dalam data yang balance, karena ini terlihat dari perbedaan antara kategori <b>phising (spam)</b> dan kategori <b>non-phishing (ham)</b> hanya terdapat pada <b>satu data saja</b></p>

<img style="display:flex; width:auto; height:auto;" alt="Word Cloud Berita Fakta" src="https://github.com/AptaArkana/web_phising_classification/assets/79633073/3a56c46b-a3ef-48db-9ef6-7a52de9001ec">
<p align='justify'>Berdasarkan pola yang diamati pada dataset, <b>kategori phishing (spam)</b> cenderung memiliki <b>karakter yang panjang</b>, sementara <b>kategori non-phishing (ham)</b> cenderung memiliki <b>karakter yang pendek.</b></p>

## Hasil dan Evaluasi

## Link Model dan Dataset
Link model bisa diakses <a href="https://drive.google.com/drive/folders/1RUUWq0dpp8orM0dhdYCsYCuPDG-5nvtU?usp=drive_link">disini</a>
