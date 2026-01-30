# 📦 Product Demand, Innovation & Cannibalization Analysis*
(Forecasting & Strategic Recommendation Project)

📌 Project Overview
Project ini menganalisis performa produk FMCG dengan pendekatan data-driven, mencakup:
- Pola demand produk
- Innovation Index sebagai indikator performa pasar
- Risiko product cannibalization
- Forecasting penjualan untuk perencanaan strategi
Hasil analisis digunakan untuk menyusun rekomendasi strategis terkait promosi, positioning produk, inventory, dan channel marketing.

---

🛠️ Tech Stack & Tools
- Python – bahasa utama analisis
- Pandas, NumPy – data processing & feature engineering
- Scikit-learn – preprocessing, normalisasi, evaluasi
- SMOTE (Imbalanced-learn) – menangani class imbalance
- Statsmodels (ARIMA) – time series forecasting
- Granger Causality – analisis hubungan sebab–akibat antar brand
- Matplotlib & Seaborn – visualisasi insight
- Jupyter Notebook & GitHub – eksplorasi, dokumentasi, dan version control

---

🎯 Business Objectives
- Mengklasifikasikan produk berdasarkan siklus demand (Decline–Mature–Growth)
- Mengukur Innovation Index untuk menjelaskan perubahan demand
- Mendeteksi potensi cannibalization antar produk & brand
- Melakukan forecasting penjualan untuk pengambilan keputusan strategis

---

📊 Key Analysis & Insights
- Demand Classification
- Decline → kandidat diskon / reposisi
- Mature → fokus efisiensi harga & margin
- Growth → dorong promosi & awareness

Contoh:
- Sunsilk Smooth & Shine Shampoo → Decline
- Sunsilk Conditioner → Mature
- Lifebuoy Body Wash → Growth

## Innovation Index & Innovation Radar
Produk dipetakan berdasarkan:
- Market Performance (penjualan)
- Innovation Index

Hasilnya membantu identifikasi:
- Produk unggulan (high performance & innovation)
- Produk inovatif tapi market rendah → perlu dorongan marketing
- Produk lemah → reposisi atau discontinue

## Demand Imbalance Handling
- Distribusi awal demand tidak seimbang (High hanya ±18%).
- Masalah ini ditangani dengan SMOTE, sehingga dataset lebih adil dan model lebih robust.

---

## Forecasting (ARIMA)
- Brand stabil → model fit dengan baik (Clear, Vaseline)
- Brand fluktuatif → error lebih tinggi karena promo & campaign (Dove, Sunsilk, Lifebuoy)

Metrik utama:
- MAPE < 4%
- MASE < 1
- RMSE tinggi pada brand besar → wajar karena volume & volatilitas tinggi

**Product Cannibalization**
Pendekatan: Correlation & Granger Causality

Temuan utama:
- Tidak ada cannibalization signifikan
- Brand umumnya bergerak independen
Hubungan signifikan bersifat komplementer:
- Lifebuoy → Sunsilk
- Vaseline → Rexona

---

🧠 Strategic Recommendations
- Smart Bundling (B1G1 / B2G1) tanpa risiko cannibalization
- Calendar-based promo (payday, weekend, tanggal kembar)
- Dorong produk inovatif lewat storytelling & short video content
- Optimasi stok berdasarkan hasil forecasting
- Fokus cross-selling, bukan promo saling memakan market

---

✅ Conclusion
Analisis menunjukkan:
- Risiko cannibalization rendah
- Produk utama masih memiliki ruang pertumbuhan
- Potensi terbesar ada pada innovation-driven marketing & channel optimization
- Strategi yang tepat memungkinkan peningkatan penjualan tanpa mengganggu stabilitas ekosistem brand.
