# Ringkasan Eksekutif: Proyek K-Means Clustering Toko Indomaret di Palembang

Proyek ini bertujuan untuk mengidentifikasi pola dan mengelompokkan toko-toko Indomaret di Kota Palembang menggunakan algoritma **K-Means Clustering**. Analisis ini didasarkan pada data *rating*, jumlah ulasan (dari Google Maps), serta faktor geografis seperti kepadatan penduduk di area sekitar dan keberadaan toko Alfamart sebagai kompetitor. Tujuan utamanya adalah memberikan wawasan berbasis data mengenai distribusi toko dan karakteristiknya bagi calon pelanggan serta pemangku kepentingan.

### Metodologi Singkat:

1.  **Pengumpulan dan Pemrosesan Data:** Mengintegrasikan data toko Indomaret dan Alfamart (dari Google Maps) dengan data kepadatan penduduk. Data kemudian dibersihkan dari *missing values* dan *inconsistent values*, lalu difitur-fitur numerik dinormalisasi.
2.  **Penentuan Jumlah Kluster & Clustering:** Menggunakan **Elbow Method** untuk menentukan jumlah kluster optimal (**k=3**). Algoritma K-Means diterapkan pada data yang telah dipersiapkan.
3.  **Evaluasi Model:** Evaluasi menggunakan **Silhouette Score** menghasilkan nilai **0.60**, menunjukkan kohesi internal kluster yang baik dan pemisahan yang relevan.

### Hasil Utama & Interpretasi Kluster:

Algoritma K-Means berhasil mengidentifikasi 3 kluster toko Indomaret dengan karakteristik yang berbeda:

*   **Kluster 0 ("Rekomendasi"):** Rating tertinggi, jumlah ulasan terendah, di area kepadatan menengah dengan satu kompetitor Alfamart terdekat. Merepresentasikan toko dengan kepuasan pelanggan superior.
*   **Kluster 1 ("Alternatif ke-1"):** Rating menengah, jumlah ulasan sedang, di area kepadatan terendah tanpa Alfamart di dekatnya. Menunjukkan potensi pertumbuhan di lingkungan yang lebih tenang.
*   **Kluster 2 ("Alternatif ke-2"):** Rating sedikit lebih rendah, jumlah ulasan tertinggi, di area kepadatan tertinggi dengan persaingan paling ketat. Mewakili toko populer di lokasi ramai dengan tantangan mempertahankan rating di tengah volume tinggi dan kompetisi.

### Kesimpulan:

Proyek ini berhasil mengungkap pola tersembunyi dalam data toko Indomaret di Palembang

### Peta Interaktif:

Untuk melihat visualisasi lokasi toko Indomaret di Palembang berdasarkan hasil pengelompokan kluster secara interaktif, Anda dapat mengunduh file `indomaret_stores_cluster_map.html` dari repositori ini dan membukanya menggunakan browser web Anda. Peta tersebut akan menampilkan titik-titik lokasi toko yang diwarnai sesuai dengan klusternya, dilengkapi dengan informasi detail saat di-*hover*.
