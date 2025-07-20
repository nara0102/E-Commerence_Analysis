# Baking Data into Strategy: E-Commerce Purchase Time Analysis for Retail Discount Optimization
Proyek ini menganalisis data transaksi e-commerce UK tahun 2010–2011 untuk mengklasifikasi waktu pembelian menjadi “Day” dan “Night” menggunakan model Random Forest. Hasil evaluasi menunjukkan bahwa transaksi siang hari sangat dominan dan mudah diprediksi, sehingga insight ini digunakan untuk menyusun strategi promosi jam terbatas — seperti diskon roti pukul 11:00–15:00.
IBM Granite digunakan untuk menghasilkan insight bisnis otomatis dari hasil evaluasi model. Proyek ini menggabungkan analisis data, machine learning, prompt engineering, dan narasi AI untuk membangun rekomendasi bisnis yang actionable dan relevan bagi sektor retail.

## 🔗 Raw Dataset Link
Dataset: [https://www.kaggle.com/datasets/carrie1/ecommerce-data](url)

Detail:
- Periode: Desember 2010 – Desember 2011
- 500,000+ transaksi
- Variabel utama: **InvoiceNo**, **StockCode**, **Quantity**, **UnitPrice**, **InvoiceDate**, **CustomerID**, **Country**

## 📈 Insight & Findings
### 1. Evaluasi Model
|Label|Precision|Recall|F1-Score|Support|
|---|---|---|---|---|
|Day|0.98|1.00|0.99|78,168|
|Night|0.22|0.00|0.01|1,417|
|Akurasi Total|98%|–|–|–|-|

### 2. Insight Bisnis
- Transaksi siang hari sangat dominan dan mudah diprediksi
- Cocok dijadikan landasan promosi waktu terbatas (diskon roti jam siang)
- Model bisa digunakan untuk penjadwalan campaign berdasarkan waktu belanja
- Insight bias dijadikan kekuatan: fokus promosi di jam aktif pelanggan

### 3. Visualisasi Pendukung
- Confusion Matrix
- Bar Chart evaluasi tiap label
- Pie Chart distribusi waktu pembelian

## 🤖 AI Support Explanation
1. IBM Granite digunakan sebagai komponen AI pendukung yang:
- Menyusun insight naratif otomatis dari evaluasi model
- Memberi rekomendasi bisnis sesuai pola transaksi
- Menyederhanakan hasil analitik teknis menjadi strategi yang mudah dipahami stakeholder non-teknis
2. AI Support powered by Microsoft Copilot
