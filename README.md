# Capstone Project 2
# Supermarket Customer Analysis

## Project Overview
Project ini bertujuan untuk menganalisis pola pembelian pelanggan menggunakan dataset **Supermarket Customers** untuk mengidentifikasi peluang strategi **product bundling** yang dapat meningkatkan penjualan dan profitabilitas.

Karena dataset tidak memiliki data transaksi per invoice (item-level), pendekatan yang digunakan adalah **customer-level behavior analysis**, yaitu melihat pola kategori produk yang dibeli oleh pelanggan yang sama.

---

## Business Problem
Produk apa yang sering dibeli bersamaan, dan bagaimana strategi bundling dapat meningkatkan total penjualan serta profitabilitas?

Pertanyaan utama:
- Produk/kategori apa yang memiliki potensi untuk dibundling?
- Bagaimana pola pembelian pelanggan dapat dimanfaatkan untuk strategi bundling?
- Bagaimana meningkatkan nilai transaksi pelanggan melalui bundling?

---

##  Dataset
Dataset yang digunakan: **Supermarket Customers.csv**

Dataset ini berisi:
- Data demografi pelanggan
- Pengeluaran pelanggan per kategori produk
- Perilaku pembelian pelanggan

Catatan:
Dataset tidak memiliki data transaksi per invoice, sehingga analisis dilakukan pada level pelanggan, bukan transaksi.

---

## Libraries
Project ini menggunakan library berikut:

- pandas
- numpy
- matplotlib
- seaborn

---

## Project Workflow

1. **Data Understanding**
   - Memahami struktur dan isi dataset

2. **Data Cleaning**
   - Menangani missing values
   - Memastikan tidak ada data duplikat
   - Memastikan format data sesuai

3. **Analisis Deskrptif**
   - Analisis rata-rata pengeluaran per kategori
   - Analisis median pengeluaran per kategori
   - Analisis total pengeluaran per kategori
   - Analisis pelanggan unik yang membeli setiap produk
   - Analisis Proporsi kontribusi tiap kategori terhadap total penjualan produk

4. **Customer Behavior Analysis**
   - Identifikasi kategori utama yang sering dibeli
   - Analisis kategori lain yang dibeli oleh pelanggan yang sama
  
5. **Analisis Segmentasi untuk Targe Bundling**
   - Membagi pelanggan berdasarkan status anak
   - Analisa perbedaan perilaku pelanggan berdasarkan income
  
6. **Analisis Korelasi Variabel Pelanggan dan Pengeluaran Produk**
   - Merkuat hasil dari kesimpulan analisis deskriptif dan analisis segmentasi
---

## Key Insights
- Terdapat kategori produk dengan kontribusi penjualan tinggi dan jumlah pelanggan besar.
- Pelanggan yang membeli kategori tertentu cenderung membeli kategori lain tertentu.
- Pola ini dapat dimanfaatkan untuk strategi bundling dan cross-selling.

---

## Kesimpulan
- Analisis berbasis perilaku pelanggan dapat digunakan sebagai alternatif market basket analysis.
- Hubungan antar kategori dapat digunakan untuk menentukan strategi bundling.
- Bundling yang tepat dapat meningkatkan nilai transaksi dan penjualan.

---

## Rekomendasi
Berdasarkan hasil analisis, beberapa strategi yang direkomendasikan:

- **Product Bundling**
  Menggabungkan produk dengan pola pembelian yang berkaitan.

- **Cross-Selling**
  Menawarkan produk tambahan berdasarkan kebiasaan pelanggan.

- **Targeted Promotion**
  Menargetkan pelanggan berdasarkan pola pembelian mereka.

- **Profit Optimization**
  Menggabungkan produk high-demand dengan produk margin tinggi.

---

## Project Files

Notebook:  
`Capstone Project Modul 2.ipynb`

Dataset:  
`Supermarket Customers.csv`



