# Data Cleansing Dataset Hasil Praktikum Mahasiswa Teknik Informatika

## Deskripsi

Repository ini berisi proyek Data Cleansing yang dilakukan pada dataset hasil praktikum mahasiswa Teknik Informatika.

Dataset awal merupakan dataset kotor yang memiliki beberapa permasalahan, seperti perbedaan format penulisan, data kosong, format tanggal yang tidak seragam, data numerik yang perlu dikonversi, dan data duplikat.

Proses data cleansing dilakukan menggunakan Python melalui Google Colab dengan library Pandas, NumPy, dan Regular Expression (re).

## Tujuan

Tujuan dari proyek ini adalah:

- Mengidentifikasi permasalahan pada dataset.
- Membersihkan data yang tidak konsisten.
- Menangani missing value.
- Menyeragamkan format data.
- Menghapus data duplikat.
- Melakukan validasi terhadap data yang telah dibersihkan.
- Menyimpan dataset hasil cleansing dalam format Excel dan CSV.

## Dataset

Dataset yang digunakan berjudul:

Dataset Hasil Praktikum Mahasiswa Teknik Informatika

Dataset terdiri dari 12 kolom, yaitu:

1. ID Praktikum
2. NIM
3. Nama Mahasiswa
4. Mata Praktikum
5. Modul
6. Tanggal Praktikum
7. Nilai
8. Kehadiran
9. Durasi Praktikum (Menit)
10. Jumlah Percobaan
11. Status Praktikum
12. Status Kelulusan

Dataset awal terdiri dari 120 data.

## Permasalahan Data

Beberapa permasalahan yang ditemukan pada dataset antara lain:

- Penulisan data teks tidak seragam.
- Format tanggal berbeda-beda.
- Terdapat missing value.
- Data nilai perlu dikonversi menjadi numerik.
- Terdapat nilai yang perlu divalidasi berdasarkan rentang 0–100.
- Format durasi praktikum berbeda-beda.
- Data jumlah percobaan memiliki variasi penulisan.
- Status praktikum dan status kelulusan perlu distandarkan.
- Data duplikat diperiksa dan dihapus jika ditemukan.

## Proses Data Cleansing

Tahapan data cleansing yang dilakukan meliputi:

1. Import library.
2. Koneksi Google Colab dengan Google Drive.
3. Membaca dataset Excel.
4. Eksplorasi dataset.
5. Pengecekan missing value.
6. Pengecekan data duplikat.
7. Membersihkan data teks.
8. Menstandarkan Mata Praktikum.
9. Membersihkan Modul.
10. Membersihkan Tanggal Praktikum.
11. Membersihkan Nilai.
12. Membersihkan Kehadiran.
13. Membersihkan Durasi Praktikum.
14. Membersihkan Jumlah Percobaan.
15. Menstandarkan Status Praktikum.
16. Menstandarkan Status Kelulusan.
17. Menghapus data duplikat.
18. Melakukan validasi data bersih.
19. Menyimpan hasil cleansing dalam format Excel dan CSV.

## Tools dan Library

Proyek ini menggunakan:

- Python
- Google Colab
- Google Drive
- Pandas
- NumPy
- Regular Expression (re)

## Hasil

Setelah proses data cleansing dilakukan, dataset diperiksa kembali untuk memastikan:

- Data memiliki format yang lebih konsisten.
- Missing value telah ditangani sesuai kebutuhan.
- Data numerik telah dikonversi dengan benar.
- Format tanggal telah diseragamkan.
- Data duplikat telah diperiksa.
- Nilai telah divalidasi pada rentang 0–100.
- Dataset bersih berhasil disimpan dalam format Excel dan CSV.

## Output

Hasil data cleansing disimpan dalam dua format:

- `dataset_bersih.xlsx`
- `dataset_bersih.csv`

File hasil berada pada folder:

`Google Drive/Data Cleansing/`

## Google Drive

Dataset dan file hasil data cleansing dapat diakses melalui folder Google Drive berikut:

[Folder Google Drive](https://drive.google.com/drive/folders/19osIvOvhBN8eVd4MFrjXic14S_roNleg?usp=drive_link)

## Google Colab

Seluruh proses data cleansing dilakukan menggunakan Google Colab.

[Google Colab - Data Cleansing](https://colab.research.google.com/drive/100Xlr0MapCCQHt3PgGcYd2wa_KkwzANE?usp=sharing)
