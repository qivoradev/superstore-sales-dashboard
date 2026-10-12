# Superstore Sales & Profitability Dashboard

Dashboard Excel interaktif yang saya buat untuk menganalisis penjualan dan profit Superstore, terutama untuk melihat apakah diskon ikut menggerus keuntungan. Datanya adalah data contoh Superstore dari Kaggle untuk periode 2014 sampai 2017, dengan nilai dalam USD. Dikerjakan dengan Excel (PivotTable, PivotChart, dan slicer).

<img width="1038" height="700" alt="dashboard_str" src="https://github.com/user-attachments/assets/913ba084-feb5-4341-a961-b4c91ea57106" />
<img width="1045" height="709" alt="dashboard_str2" src="https://github.com/user-attachments/assets/9797dbb4-c898-44b4-ba4c-0db5e05da7d0" />
[Superstore_Sales_and_Profitability_Dashboard_Final.xlsx](https://github.com/user-attachments/files/33320586/Superstore_Sales_and_Profitability_Dashboard_Final.xlsx)






Total sales $2,295,274, total profit $285,988, dan profit margin 12.5%.

## Problem

Margin 12.5% terlihat cukup sehat, tapi sekitar 19% baris transaksi ternyata merugi. Saya ingin tahu di mana profit bocor dan apakah diskon punya peran.

## Action

Saya membersihkan data lebih dulu: memperbaiki format tanggal yang terbaca terbalik (bulan dan hari tertukar) dan mengeluarkan baris yang nilainya kosong. Setelah itu saya menambahkan kolom Year, Month, dan Discount Band (0%, 1 sampai 20%, 21 sampai 40%, dan di atas 40%), lalu membuat PivotTable dan dashboard dengan slicer Year, Region, dan Segment. Empat hal yang saya lihat adalah dampak diskon, pola penjualan bulanan, profit per sub-kategori, dan state dengan kerugian terbesar.

## Result

Diskon 0% menghasilkan profit lebih dari $300K dan diskon 1 sampai 20% sekitar $100K. Begitu diskon melewati 20%, hasilnya berbalik: sekitar minus $40K di rentang 21 sampai 40%, dan lebih dari minus $100K di atas 40%.

Penjualan paling rendah di Januari dan Februari, lalu memuncak di September dan November, dengan pola yang sama di keempat tahun. Copiers, Phones, dan Accessories paling menguntungkan, sedangkan Tables, Bookcases, dan Supplies merugi. Kerugian terbesar ada di Texas, Illinois, Pennsylvania, Ohio, dan North Carolina.

## What, So What, Now What

**Diskon.** **What:** profit positif selama diskon sampai 20%, dan negatif di atasnya. **So what:** diskon besar kemungkinan memangkas profit lebih banyak daripada penjualan tambahan yang dihasilkan. Ini pola dari data, belum bukti sebab akibat. **Now what:** batasi diskon di sekitar 20% dan minta persetujuan untuk yang lebih tinggi, sebaiknya diuji dulu di satu wilayah.

**Musiman.** **What:** kuartal pertama lambat, puncaknya di September dan November. **So what:** kebutuhan stok, tenaga, dan arus kas naik di akhir tahun. **Now what:** siapkan stok sebelum September, dan dorong penjualan kuartal pertama dengan promo yang tetap di bawah batas diskon.

**Sub-kategori.** **What:** Tables merugi paling besar, disusul Bookcases dan Supplies. **So what:** produk yang laku belum tentu untung, dan harga atau diskonnya mungkin belum sesuai dengan biayanya. **Now what:** tinjau harga dan diskon produk yang merugi, dan arahkan promosi ke produk penyumbang profit.

**Wilayah.** **What:** kerugian terpusat di beberapa state, terbesar di Texas. **So what:** perbaikan yang terarah bisa berdampak besar, tapi penyebab di tiap state belum saya ketahui. **Now what:** telusuri state tersebut per sub-kategori dan rentang diskon, mulai dari Texas.

## Keterbatasan

Ini data contoh dari periode lama, jadi temuannya berlaku untuk data ini dan belum tentu menggambarkan kondisi bisnis sekarang. Analisisnya deskriptif, dan dampak dari rekomendasi masih berupa perkiraan yang belum diuji. Data juga tidak memuat stok, jadi bagian yang menyinggung persediaan hanya dugaan.

