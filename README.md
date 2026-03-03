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

Sebagai tindak lanjut dari analisis eksploratif berbasis *Python* ini, temuan data akan diintegrasikan ke dalam **Dashboard Power BI Interaktif** untuk memudahkan pemantauan harian oleh jajaran Direksi (C-Level).

**Halaman Dashboard yang Direncanakan:**

1. **Executive Overview (The Big Picture):** Melacak indikator makro seperti *Net Revenue*, Total Transaksi, *Global Return Rate*, dan perbandingan Performa Regional (*Revenue* vs *Volume*).
2. **Customer Intelligence (CRM View):** Visualisasi sebaran segmen RFM (*Champions, Cannot Lose Them*, dll.), rasio *Repeat vs One-Time Buyer*, dan profil demografi (AOV berdasarkan umur & gender).
3. **Operational & Product Risk (Supply Chain View):** Memantau *Live Shipping SLA* (<4 hari), daftar *Problem Products* yang harus segera diaudit, dan peta risiko metode pembayaran.

*(Screenshot Dashboard Power BI akan disematkan di sini setelah pengembangan selesai).*

---

## 🛠️ 6. Tech Stack

* **Bahasa Pemrograman:** Python 3.8+
* **Manipulasi Data:** Pandas, NumPy
* **Visualisasi Data:** Matplotlib, Seaborn
* **Business Intelligence:** Microsoft Power BI (Visualisasi Lanjutan)
