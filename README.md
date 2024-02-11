# Web Phising Classification
<p align='justify'>Projek ini bertujuan untuk mengidentifikasi dan mengklasifikasikan situs web phishing menggunakan teknik Deep Learning, dengan menganalisis URL dan konten HTML untuk mendeteksi ciri-ciri phishing/penipuan seperti kesalahan pengejaan nama domain, subdomain yang mencurigakan, formulir yang meminta data sensitif, skrip mencurigakan, dan desain halaman, dikarenakan phishing detector tradisional hanya menggunakan URL saja.</p>

<p align='justify'>Menurut laporan Indonesian Anti-Phishing Data Exchange (IDADX) untuk periode selama tahun 2023, <b>laporan url phishing tertinggi</b> terjadi pada <b>bulan Februari</b> sebanyak <b>15.050</b> dan terendah <b>bulan November</b> sebanyak <b>1.729</b>. Menurut laporan terbaru dari Indonesian Anti-Phishing Data Exchange (IDADX) untuk <b>periode Oktober hingga Desember 2023</b>, terdapat <b>8.161</b> laporan URL phishing. <b>Bulan Desember</b> mencatat jumlah pelaporan <b>phishing tertinggi</b> dibandingkan bulan lainnya selama Q4 2023.</p>

## Pengumpulan Dataset
<p align='justify'>Merupakan dataset yang terdiri dari 45,373 contoh, mewakili halaman web benign dan phishing secara merata. Setiap contoh mencakup berbagai elemen dokumen HTML seperti teks, hyperlink, gambar, tabel, daftar, dan berbagai komponen URL mulai dari subdomain hingga query. Terdapat dua file excel pada dataset ini, yakni URL.xlsx dan HTML.xlsx. Tiap file excel memiliki dua kolom, yakni ‘Category’ dan ‘Data’ Dataset ini terdiri dari data yang dikumpulkan dari Alexa.com untuk halaman web yang sah dan phishtank.com untuk halaman web phishing</p>

## EDA
<p align='justify'> Dataset terdiri dari : </p>
`Banyak baris dataset url 45373 dan kolom 2`
<br>`Banyak baris dataset html 45373 dan kolom 2`
