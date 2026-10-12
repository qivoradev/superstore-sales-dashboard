# 🛒 Superstore Sales & Profitability Dashboard

Dashboard Excel interaktif untuk menganalisis penjualan dan profitabilitas Superstore (data contoh 2014–2017), dengan fokus pada kebocoran profit akibat diskon.

<img width="1038" height="700" alt="dashboard_str" src="https://github.com/user-attachments/assets/32026542-7463-4794-a20c-384996c62cb3" />
<img width="1045" height="709" alt="dashboard_str2" src="https://github.com/user-attachments/assets/41c6267b-e79c-41e4-9524-bfa7c7ea2459" />




**Tools:** Microsoft Excel (PivotTable, PivotChart, Slicer) · **Dataset:** Superstore Sales (Kaggle, data contoh) · **Nilai dalam USD**

| Total Sales | Total Profit | Profit Margin |
|---|---|---|
| $2,295,274 | $285,988 | 12.5% |

---

## 🎯 PAR: Problem, Action, Result

**Problem**
Dengan margin 12.5%, Superstore terlihat sehat, tetapi sekitar 19% baris transaksi mengalami kerugian. Manajemen perlu tahu di mana profit bocor dan apakah diskon berperan.

**Action**
- Membersihkan data: memperbaiki format tanggal dan mengeluarkan baris dengan nilai kosong.
- Membuat kolom Year, Month, dan Discount Band (0%, 1–20%, 21–40%, >40%).
- Membangun PivotTable dan dashboard interaktif dengan slicer Year, Region, dan Segment, untuk menganalisis diskon, musiman, sub-kategori, dan wilayah.

**Result**
- Diskon 0% menghasilkan profit >$300K dan diskon 1–20% sekitar +$100K, tetapi diskon 21–40% merugi sekitar −$40K dan >40% lebih dari −$100K.
- Penjualan terendah di Januari–Februari dan memuncak di September dan November setiap tahun.
- Copiers, Phones, dan Accessories paling menguntungkan; Tables, Bookcases, dan Supplies merugi.
- Kerugian terbesar terkonsentrasi di Texas, Illinois, Pennsylvania, Ohio, dan North Carolina.

---

## 🔍 3 What: What, So What, Now What

| Analisis | What (temuan) | So What (dampak) | Now What (rekomendasi) |
|---|---|---|---|
| **Diskon** | Profit positif pada diskon 0–20%, negatif di atas 20% | Diskon di atas 20% kemungkinan menggerus profit lebih besar dari tambahan penjualannya | Batasi diskon maksimum sekitar 20% dan wajibkan persetujuan di atasnya; uji dulu pada satu wilayah |
| **Musiman** | Q1 lambat, puncak di September dan November | Kebutuhan
