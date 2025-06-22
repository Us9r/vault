# Analisis Distribusi Toko Indomaret di Palembang

## Cara Melihat Peta Interaktif 🗺️

Peta interaktif distribusi toko Indomaret di Palembang disimpan dalam format file HTML. Untuk melihat peta ini, silakan unduh file `palembang_indomaret_stores_map.html` dari repositori ini. Setelah file berhasil diunduh, buka file tersebut menggunakan browser web pada umumnya seperti Google Chrome, Mozilla Firefox, Microsoft Edge, atau browser lainnya. Peta akan ditampilkan di browser Anda, memungkinkan Anda untuk memperbesar, memperkecil, dan mengklik marker toko untuk melihat detailnya.

## Executive Summary

Proyek ini bertujuan untuk menganalisis dan memvisualisasikan distribusi toko Indomaret di Kota Palembang. Data toko Indomaret, bersama dengan data toko Alfamart dan data populasi, dikumpulkan dari berbagai sumber dan dibersihkan serta diproses untuk memastikan konsistensi dan akurasi, khususnya dalam mengidentifikasi lokasi toko berdasarkan kecamatan. 🏪

**Tujuan Utama:**

*   Mengidentifikasi dan membersihkan data toko Indomaret, terutama terkait informasi kecamatan yang tidak konsisten. ✨
*   Mengklasifikasikan toko Indomaret ke dalam kecamatan yang sesuai di Kota Palembang.
*   Memvisualisasikan distribusi spasial toko Indomaret di Palembang menggunakan peta interaktif.
*   Menyediakan ringkasan jumlah toko Indomaret per kecamatan. 📈

**Metodologi:**

1.  **Pengumpulan Data:** Mengumpulkan data toko Indomaret dan Alfamart dari sumber online, serta data populasi.
2.  **Pemilihan Fitur:** Memilih kolom data yang relevan untuk analisis.
3.  **Ekstraksi Kecamatan:** Mengekstraksi nama kecamatan dari informasi lingkungan (neighborhood).
4.  **Pembersihan Data Kecamatan:** Mengidentifikasi dan memperbaiki inkonsistensi pada nama kecamatan, termasuk mengidentifikasi toko yang seharusnya berada di kecamatan tertentu berdasarkan informasi lingkungan lainnya. 🧹
5.  **Deteksi dan Penghapusan Duplikasi/Data Tidak Relevan:** Mengidentifikasi dan menghapus entri data yang tidak relevan seperti duplikasi toko atau entri yang bukan Indomaret. ❌
6.  **Analisis Deskriptif:** Menghitung jumlah toko Indomaret per kecamatan.
7.  **Visualisasi Spasial:** Membuat peta interaktif untuk memvisualisasikan lokasi setiap toko Indomaret di Palembang.

**Temuan Utama:**

*   Data awal memiliki ketidaksesuaian dalam informasi kecamatan yang memerlukan pembersihan cermat. 🚧
*   Beberapa toko berhasil diklasifikasikan ke kecamatan yang benar setelah analisis mendalam. ✅
*   Proses pembersihan data menghasilkan dataset final yang lebih akurat. 👍
*   Analisis menunjukkan sebaran toko Indomaret di berbagai kecamatan.

Dataset final sebanyak 346 toko indomaret yang telah diperbaiki dan dianalisis dapat digunakan untuk analisis lebih lanjut terkait potensi pasar, persaingan, atau perencanaan ekspansi. 📊
