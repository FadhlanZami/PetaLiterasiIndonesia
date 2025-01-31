# Peta Tingkat Melek Huruf Indonesia

Proyek ini adalah aplikasi web interaktif yang menampilkan analisis tingkat Melek Huruf Indonesia berdasarkan data dari tahun 2021 hingga 2023. Aplikasi ini menyediakan peta, grafik, dan tabel untuk memberikan gambaran yang jelas tentang tingkat literasi di berbagai kabupaten di Indonesia.

## Fitur Utama

1. **Peta Interaktif**: Pengguna dapat memilih tahun untuk melihat peta tingkat Melek Huruf  Indonesia pada tahun tersebut. Peta ini ditampilkan melalui elemen `iframe`, yang sumbernya dapat diubah sesuai dengan pilihan tahun yang dipilih pengguna.

2. **Dropdown Pilihan Tahun**: Terdapat dropdown yang memungkinkan pengguna untuk memilih tahun (2021, 2022, atau 2023) untuk melihat data  tingkat Melek Huruf  Indonesia pada tahun yang berbeda.

3. **Grafik Tingkat Literasi**:
   - **Grafik Rata-rata Literasi per Tahun**: Menampilkan grafik batang yang menggambarkan tingkat Melek Huruf rata-rata Indonesia untuk setiap tahun.
   - **Grafik Tingkat Literasi per Wilayah**: Menampilkan grafik batang yang menggambarkan tingkat Melek Huruf di berbagai wilayah di Indonesia, yang dapat dipilih melalui dropdown wilayah.

4. **Tabel Tingkat Literasi Tertinggi dan Terendah**:
   - Tabel yang menunjukkan 10 kabupaten dengan tingkat Melek Huruf tertinggi dan terendah di Indonesia berdasarkan data tahun yang dipilih.

## Struktur File

- **HTML**: File utama (`index.html`) yang menampilkan peta, grafik, dan tabel.
- **CSS**: Gaya halaman yang ditulis dalam tag `<style>` untuk membuat tampilan yang responsif dan menarik.
- **JavaScript**:
   - **Grafik**: Menggunakan pustaka `Chart.js` untuk membuat grafik batang yang dinamis.
   - **Dropdown Interaktivitas**: Menggunakan JavaScript untuk menangani perubahan pada dropdown tahun dan wilayah.
   - **Tabel Dinamis**: Menggunakan JavaScript untuk mengambil data dari file JSON dan menampilkan tabel dengan kabupaten dengan literasi tertinggi dan terendah.
- **File JSON**:
   - `literacy_data.json`: Data tingkat literasi rata-rata untuk setiap tahun.
   - `literacy_by_region.json`: Data tingkat literasi per wilayah.
   - `literacy_2021.json`, `literacy_2022.json`, `literacy_2023.json`: Data tingkat literasi per kabupaten berdasarkan tahun.

## Cara Menggunakan

1. **Pilih Tahun**: Pilih tahun melalui dropdown untuk melihat peta tingkat Melek Huruf Indonesia pada tahun tersebut.
2. **Pilih Wilayah**: Pilih wilayah tertentu dari dropdown untuk melihat grafik tingkat Melek Huruf di wilayah tersebut.
3. **Lihat Grafik dan Tabel**: Grafik tingkat literasi per tahun dan per wilayah akan ditampilkan, serta tabel yang menunjukkan kabupaten dengan tingkat Melek Huruf tertinggi dan terendah.

## Teknologi yang Digunakan

- **HTML5** untuk struktur halaman.
- **CSS3** untuk desain responsif dan estetika.
- **JavaScript** untuk interaktivitas dan manipulasi data.
- **Chart.js** untuk visualisasi grafik.
- **JSON** untuk penyimpanan dan pengambilan data.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, Anda bisa mengirimkan pull request dengan perubahan atau perbaikan yang Anda usulkan.

## Catatan

Pastikan file data (JSON) yang diperlukan sudah ada di server atau sistem Anda agar peta dan grafik dapat ditampilkan dengan benar. Anda bisa mengganti link pada elemen `iframe` untuk menampilkan peta sesuai dengan file HTML yang relevan.

---

© 2025 Literasi Indonesia - Data Sumber: [BPS INDONESIA] - Made By Fadhlan Zam Zami
