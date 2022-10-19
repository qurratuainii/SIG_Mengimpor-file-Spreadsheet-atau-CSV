# SIG_Mengimpor-file-Spreadsheet-atau-CSV

1. Cara mengimpor file spreadsheet atau CSV, pertama download terlebih dahulu earthquake_2021_11_25_14_31_59_+0530.tsv

2. Selanjutnya periksa sumber data tabular. Basis data gempa yang diunduh berisi bidang Lintang dan Bujur yang menunjukkan lokasi pusat gempa dan atribut yang lainnya. Buka data dalam editor teks seperti Notepad/TextMate/Excel untuk melihat isinya (*Gambar 1)

3. Pada QGIS menyediakan pengelola data yang memungkinkan memuat semua berbagai format data yang didukung. Klik Open Data Source Manager (Ctrl+L) pada bilah alat sumber data (*Gambar 2)

4. Pada jendeka Data Source Manager, klik Delimited Text lalu klik tombol disebelah file name atau browse (*Gambar 3, *Gambar 4)

5. Tergantung pada sistem operasi, mungkin atau tidak melihat file yang diunduh. Dalam format file, alihkan ke All files untuk melihat file tsv. (*Gambar 5)

6. Selanjutnya pilih file yang diunduh, lalu Klik Open (*Gambar 6)

7. Pada Data Source Manager akan tersedia File name. Ubah layer name menjadi 1900_2000_earthquakes. Pada bagian File format pilih Custom delimiters dan centang pada bagian Tab. Selanjutnya pada bagian Geometry Definition pilih Point coordinates pada bagian X field pilih Longitude, pada Y field pilih Latitude dan pada Bagian Geometry CRS pilih EPSG:4326 - WGS 84. SElanjutnya klik Add (*Gambar 7)

8. Sekarang kita dapat melihat data akan diimpor dan ditampilkan pada kanvas QGIS sebagai layer baru yang disebut 1900_2000_earthquakes dengan CRS EPSG:4326 (*Gambar 8)
