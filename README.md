# Data Cleansing Smart Farming IoT

## Identitas
- Nama: Kosmas Anyeq Beraan
- NIM: 2418057
- Dataset: Smart Farming Crop Yield 2024

## Deskripsi
Proyek ini merupakan proses data cleansing pada dataset Smart Farming Crop Yield 2024 menggunakan Python dan Google Colab.

Dataset digunakan untuk melakukan pembersihan dan pemeriksaan kualitas data sebelum digunakan untuk proses analisis lebih lanjut.

## Dataset
Dataset memiliki:
- 500 baris data
- 22 kolom
- Data pertanian dan sensor IoT
- Data kategori, numerik, dan tanggal

## Proses Data Cleansing

Tahapan yang dilakukan:

1. Import library Pandas dan NumPy
2. Menghubungkan Google Drive
3. Membaca dataset
4. Menampilkan data awal
5. Mengecek informasi dataset
6. Mengecek missing value
7. Mengecek data duplikat
8. Menangani missing value
9. Verifikasi missing value
10. Mengubah tipe data tanggal
11. Verifikasi tipe data
12. Mengecek statistik data numerik
13. Mengecek konsistensi tanggal
14. Menampilkan data setelah cleansing
15. Menyimpan dataset hasil cleansing
16. Verifikasi dataset hasil cleansing

## Hasil Cleansing

Setelah proses cleansing:

| Pemeriksaan | Hasil |
|---|---:|
| Jumlah data | 500 baris |
| Jumlah kolom | 22 |
| Missing value | 0 |
| Data duplikat | 0 |
| Tanggal tidak valid | 0 |

Missing value pada kolom `irrigation_type` dan `crop_disease_status` ditangani dengan mengisi nilai kosong menggunakan `Unknown`.

## File Repository

- `Smart_Farming_Crop_Yield_2024_Cleansed.csv` — dataset setelah proses cleansing
- `DATA_CLEANSING_SMART_FARMING_IoT.ipynb` — notebook Google Colab yang berisi proses data cleansing

## Tools

- Python
- Google Colab
- Pandas
- NumPy
- Google Drive
- GitHub
