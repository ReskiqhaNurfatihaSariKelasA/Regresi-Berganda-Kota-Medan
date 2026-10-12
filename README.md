# Analisis Regresi Linear Berganda – Kota Medan

## Deskripsi Proyek

Proyek ini merupakan analisis data menggunakan Python untuk mengkaji hubungan antara tingkat pengangguran, Indeks Pembangunan Manusia (IPM), dan tingkat kemiskinan di Kota Medan.

Analisis dilakukan sebagai bagian dari pembelajaran pemrograman untuk analisis data dan penerapan metode statistik dalam bidang ekonomi dan bisnis.

## Tujuan Analisis

* Menganalisis hubungan tingkat pengangguran dengan kemiskinan.
* Menganalisis hubungan IPM dengan kemiskinan.
* Menguji hubungan kedua variabel independen dengan kemiskinan secara simultan.
* Mengevaluasi kemampuan model regresi dalam menjelaskan variasi kemiskinan.

## Variabel Penelitian

| Jenis           | Variabel                         |
| --------------- | -------------------------------- |
| Dependen (Y)    | Kemiskinan                       |
| Independen (X1) | Pengangguran                     |
| Independen (X2) | Indeks Pembangunan Manusia (IPM) |

## Metode dan Tools

* Bahasa pemrograman: Python
* Pengolahan data: Pandas
* Analisis statistik: Statsmodels (OLS)
* Visualisasi data: Matplotlib
* Metode: Regresi linear berganda

## Hasil Analisis

Berdasarkan hasil estimasi model, variabel pengangguran dan IPM tidak menunjukkan hubungan yang signifikan secara statistik dengan kemiskinan pada taraf signifikansi 5%. Model memiliki koefisien determinasi (R²) sebesar 10,9%, sehingga kemampuan model dalam menjelaskan variasi kemiskinan masih terbatas.

Hasil ini perlu ditafsirkan secara hati-hati karena jumlah observasi tahunan yang dianalisis relatif kecil dan tidak secara langsung membuktikan hubungan sebab-akibat.

## Struktur Proyek

* `Regresi_Berganda_Reskiqha.ipynb` — notebook analisis, pengolahan data, regresi, dan visualisasi.
* `README.md` — dokumentasi proyek.

## Cara Menjalankan

1. Unduh notebook dan dataset yang diperlukan.
2. Buka notebook menggunakan Google Colab atau Jupyter Notebook.
3. Pastikan dataset tersedia pada lokasi yang sesuai dengan kode.
4. Jalankan setiap sel secara berurutan.

## Catatan

Proyek ini dibuat untuk tujuan pembelajaran dan analisis akademik. Interpretasi hasil didasarkan pada data dan model yang digunakan.
