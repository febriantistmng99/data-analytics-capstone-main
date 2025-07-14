# data-analytics-capstone-main

Web Scraping dengan BeautifulSoup
Proyek ini dikembangkan sebagai bagian dari Capstone Project dalam program Data Analytics Specialization oleh Algoritma Academy. Tujuan dari proyek ini adalah melakukan web scraping sederhana untuk mengambil informasi tertentu dari sebuah situs web. Untuk panduan langkah demi langkah, silakan kunjungi repositori instruktur saya di GitHub.

Kita juga akan menggunakan dashboard sederhana berbasis Flask untuk menampilkan hasil scraping dan visualisasinya.

Dependencies
Berikut adalah beberapa library yang dibutuhkan untuk menjalankan proyek ini:

beautifulsoup4

pandas

flask

matplotlib

Untuk menginstal semua dependensi sekaligus, Anda cukup menjalankan perintah berikut:

bash
Copy
Edit
pip install -r requirements.txt
Rubrik Penilaian
Persiapan lingkungan kerja (2 poin)

Menemukan elemen yang tepat untuk di-scrape & mengekstrak informasi yang dibutuhkan (5 poin)

Membuat dataframe & melakukan data wrangling (5 poin)

Menyusun laporan dalam notebook Python yang rapi (2 poin)

Mengimplementasikan hasilnya dalam dashboard Flask (2 poin)

Apa yang Harus Anda Lakukan
Cobalah melakukan scraping terlebih dahulu menggunakan BeautifulSoup di Jupyter Notebook.

Clone repositori ini ke komputer lokal Anda.

Buka notebook template yang disediakan, lalu isi sesuai dengan instruksi yang diberikan. Pastikan Anda juga menyertakan analisis dari data yang Anda ambil.

Struktur folder pada repo ini sudah disiapkan untuk membantu Anda membangun dashboard menggunakan Flask.

Lengkapi bagian-bagian kode yang masih kosong.

Contoh:

Mengambil elemen dari HTML:

python
Copy
Edit
table = soup.find(___)
tr = table.find_all(___)
Membuat dataframe dari hasil scraping:

python
Copy
Edit
df = pd.DataFrame(nama_tuple, columns=[nama_kolom1, nama_kolom2, ...])
Gunakan fungsi scrap() dengan mengisi URL target:

python
Copy
Edit
df = scrap("URL yang ingin di-scrape")
Anda juga bisa menyesuaikan tampilan UI melalui file index.html. Ikuti komentar yang ada di file tersebut untuk mengetahui bagian mana saja yang bisa dimodifikasi.

Misi Utama
Silakan pilih salah satu dari dua opsi berikut untuk dikerjakan dalam capstone ini:

1. Kurs USD ke Rupiah
Sumber: exchange-rates.org

Ambil data harga harian dan tanggal

Buat visualisasi grafik pergerakan kurs USD terhadap Rupiah

2. Film Rilis Tahun 2019
Sumber: https://imdb.com/search/title/?release_date=2019-01-01,2019-12-31

Ambil data: judul film, IMDB rating, metascore, dan jumlah votes

Buat visualisasi 7 film terpopuler tahun 2019 berdasarkan jumlah votes
