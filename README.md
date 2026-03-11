# 🛒 Global E-Commerce Data Analysis & Strategic Customer Segmentation

## 🎯 1. Pengantar & Konteks Bisnis (*Introduction & Business Context*)

* **Overview** Memahami perilaku pelanggan dan efisiensi operasional adalah kunci keberhasilan dalam industri e-commerce. Analisis komprehensif atas 5.000 data transaksi global ini tidak hanya menggali seberapa banyak pendapatan yang masuk (*Gross Revenue*), tetapi juga mengungkap "Kesehatan Bisnis" yang sesungguhnya (*Net Revenue*). Proyek ini mengeksplorasi:

* **Pola Belanja & Sensitivitas Harga:** Menganalisis *Average Order Value* (AOV), elastisitas diskon, dan tren musiman.
* **Segmentasi Pelanggan Berbasis Nilai:** Pemetaan loyalitas menggunakan metode *RFM (Recency, Frequency, Monetary)* murni berdasarkan pendapatan bersih.
* **Performa Produk & Risiko Kualitas:** Identifikasi matriks *Hero vs Problem Products* berdasarkan tingkat pengembalian barang (*Return Rate*).
* **Pengalaman Pelanggan & Logistik:** Menemukan *Tipping Point* (batas toleransi) durasi pengiriman yang merusak kepuasan pelanggan dan memicu retur.
* **Strategi Geografis:** Memetakan volume dan daya beli antar-benua (Fokus pada AS sebagai pilar utama, dan Oseania sebagai pasar potensial ber-AOV tinggi).
* **Audit Integritas Finansial:** Memastikan keandalan data (*Data Governance*) dengan mengaudit konsistensi kalkulasi pendapatan.

## 🎯 2. Tujuan Bisnis (*Business Objectives*)

* **Mengidentifikasi Pelanggan VIP (*High-Value Customers*):** Mengisolasi segmen "Champions" melalui RFM Analysis untuk diberikan layanan eksklusif (*White-glove service*).
* **Menghentikan Kebocoran Profit (*Revenue Leakage*):** Mengevaluasi efektivitas pemberian diskon agar tidak membakar margin pada kategori yang tidak elastis.
* **Mengoptimalkan Operasional Logistik:** Menetapkan *Service Level Agreement* (SLA) pengiriman baru berdasarkan korelasi keterlambatan dengan lonjakan retur barang.
* **Menyelamatkan Biaya Akuisisi (CAC):** Menganalisis rasio *One-Time* vs *Repeat Buyer* untuk merancang strategi retensi pada segmen umur yang paling setia (26-35 tahun).

## 📈 3. Hasil yang Diharapkan (*Expected Outcomes*)

* **Insight Strategis (Actionable Insights):** Rekomendasi taktis untuk tim *Marketing* (penghentian diskon massal), *Supply Chain* (evaluasi vendor produk), dan *Quality Control*.
* **Pembersihan "Fake Revenue":** Menggeser fokus pelaporan manajemen dari Omzet Kotor yang bias karena retur, menjadi Pendapatan Bersih (*Net Revenue*) yang realistis.
* **Pemetaan Korelasi Bisnis Eksekutif:** Memberikan gambaran sebab-akibat lintas departemen (misal: bagaimana opsi pembayaran COD memicu tingginya beban operasional retur).

---

## 🔬 4. Struktur Analisis (*Key Analytical Domains*)

Proyek ini mengacu pada 8 pilar pertanyaan bisnis utama:

1. **Revenue, Pricing & Profitability:** Efektivitas *sales uplift* dari diskon dan sensitivitas harga per kelas produk.
2. **Product Performance & Quality Risks:** Pemetaan kuadran produk (*Hero vs Problem*) dan ekstraksi murni produk dengan *Return Rate* tertinggi/terendah.
3. **Customer Experience & Operations:** Analisis regresi antara durasi pengiriman vs *Rating* kepuasan, serta performa metode pembayaran (COD vs Credit Card).
4. **Temporal Trends & Growth:** Diagnosis pemicu penjualan (Kuartal/Bulan) dan pemetaan perilaku harian (*Day-of-Week*).
5. **Geo-Strategy & Market Health:** Analisis stabilitas *Quarter-over-Quarter* (QoQ) dan penemuan anomali AOV tertinggi di pasar bervolume rendah (Oseania).
6. **Customer Segmentation:** Analisis rasio *Repeat Purchase* dan *Advanced RFM Analysis* untuk pemetaan kampanye CRM.
7. **Data Integrity Check:** Validasi akurasi perhitungan *Total Amount* vs *(Unit Price * Quantity * Discount)*.
8. **Executive Synthesis:** Rangkuman korelasi makro bisnis (Logistik lambat = Retur meroket, COD = Retur ekstrem, Diskon = Diminishing returns).

---

## 📊 5. Integrasi Dashboard Power BI (*Upcoming Feature*)

Sebagai tindak lanjut dari analisis eksploratif berbasis *Python* ini, temuan data akan diintegrasikan ke dalam **Dashboard Power BI Interaktif** untuk memudahkan pemantauan harian.

**Halaman Dashboard:**
#### **1. Executive Overview (The Big Picture)**

* **Gross Revenue & Volume:** Melacak total arus kas masuk sebesar **$203,22 Juta** dari **5.000 transaksi**.
* **Global Return Rate:** Memantau kesehatan kualitas layanan di mana angka retur berada di **9,20%**. Ini adalah indikator utama untuk menjaga kepuasan pelanggan tetap tinggi (saat ini di Rating **4,16**).
* **Regional Dominance:** Fokus pada **North America** sebagai penyumbang pendapatan terbesar (**$65M**) dan **USA** sebagai pemimpin pasar negara tunggal (**$45M**).

#### **2. Customer Intelligence (CRM View)**

* **Demographic Powerhouse:** Visualisasi menunjukkan bahwa segmen usia **26-35 tahun** adalah penggerak utama bisnis dengan kontribusi **$66M**.
* **High-Value Insights:** Dengan **Average Order Value (AOV) sebesar $40.644**, fokus strategi adalah mengonversi *New Customers* menjadi *Champions* melalui pendekatan berbasis RFM yang akan dipetakan pada *view* selanjutnya.

#### **3. Operational & Product Risk (Supply Chain View)**

* **SLA Critical Check:** Rata-rata pengiriman saat ini berada di angka **4,32 hari**. Mengingat toleransi konsumen maksimal adalah 4 hari, bagian ini menjadi alarm bagi logistik untuk mengevaluasi efisiensi pengiriman agar tidak memicu retur tambahan.
* **Product Exposure:** Kategori **Electronics** mendominasi total risiko finansial dengan eksposur pendapatan sebesar **$118M**. Kualitas produk di kategori ini wajib diaudit secara rutin karena setiap retur berdampak signifikan pada margin laba.
* **Payment Risk:** Memantau ketergantungan pada **Credit Card (38,2%)** dan mitigasi biaya pada metode **Cash on Delivery (4,96%)**.
---
<img width="799" height="442" alt="image" src="https://github.com/user-attachments/assets/af07b73d-12cc-4504-a05b-597c3d997cc6" />

---

## 🛠️ 6. Tech Stack

* **Bahasa Pemrograman:** Python 3.8+
* **Manipulasi Data:** Pandas, NumPy
* **Visualisasi Data:** Matplotlib, Seaborn
* **Business Intelligence:** Microsoft Power BI (Visualisasi Lanjutan)
