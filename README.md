# Simulasi Gerak Vertikal & Jatuh Bebas 🚀⚽

Selamat datang! Project ini adalah simulasi fisika interaktif berbasis web untuk memvisualisasikan konsep Gerak Lurus Berubah Beraturan (GLBB), khususnya **Gerak Jatuh Bebas** dan **Gerak Vertikal**. 

Simulasi ini sangat cocok digunakan sebagai alat bantu visual untuk praktikum fisika, tugas sekolah/kampus, atau sekadar eksperimen ringan untuk melihat bagaimana benda jatuh di berbagai planet.

## ✨ Fitur Utama

*   🎛️ **Kustomisasi Parameter:** Kamu bisa mengatur Tinggi Awal ($h_0$) dan Kecepatan Awal ($v_0$) sesuai kebutuhan. Nilai $v_0$ positif untuk lemparan ke atas, negatif untuk ke bawah, dan $0$ untuk jatuh bebas.
*   🪐 **Pilihan Gravitasi:** Penasaran bagaimana benda jatuh di planet lain? Ada opsi gravitasi untuk Bumi, Bulan, Mars, dan Jupiter.
*   📊 **Grafik Real-Time:** Perubahan posisi (y-t) dan kecepatan (v-t) akan langsung tergambar dalam bentuk grafik saat simulasi berjalan.
*   🕹️ **Kontrol Interaktif:** Simulasi bisa di-*pause*, dilanjutkan kembali, atau di-*reset* kapan saja.
*   📱 **Desain Responsif:** Tampilannya rapi dan bisa menyesuaikan ukuran layar, baik di laptop maupun perangkat mobile.

## 🛠️ Teknologi yang Digunakan

Project ini dibuat murni menggunakan teknologi *front-end* tanpa perlu *setup* yang ribet:
*   **HTML5 & CSS3** (Vanilla)
*   **Vanilla JavaScript** (Untuk *logic* fisika dan render Canvas)
*   **[Chart.js](https://www.chartjs.org/)** (Didatangkan via CDN untuk memutar grafik *real-time*)

## 🚀 Cara Menjalankan

Tidak perlu instalasi *library* atau menyalakan *local server*. Cukup ikuti langkah mudah ini:

1. *Clone* repositori ini atau *download* file `index.html`.
2. Klik ganda (buka) file `index.html` tersebut di browser kesayangan kamu (Chrome, Firefox, Safari, Edge, dll).
3. Atur parameter di panel sebelah kiri, lalu klik **Mulai**.

## 📝 Catatan Teori Dasar

Di balik layar, simulasi ini dihitung menggunakan persamaan kinematika murni:
*   $y(t) = h_0 + v_0t - \frac{1}{2}gt^2$ (Posisi terhadap waktu)
*   $v(t) = v_0 - gt$ (Kecepatan terhadap waktu)

---
*Dibuat untuk mempermudah pemahaman konsep fisika secara visual dan menyenangkan!* 💡
