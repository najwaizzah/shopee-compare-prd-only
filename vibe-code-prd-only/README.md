# Shopee Product Comparison (PRD-Only Implementation)
> **Tugas Praktikum Rekayasa Interaksi (UX) - Worksheet 12: Vibe Coding Project**  
> **Mahasiswa:** Najwah Awwalul Izzah  
> **Metode:** Vibe Coding Generatif berbasis *PRD Only* (Tanpa Skill Eksternal)

---

## 📌 Deskripsi Proyek
Repositori ini berisi implementasi prototipe antarmuka **Fitur Komparasi Produk Terintegrasi di Shopee** yang di-*generate* menggunakan pendekatan **Vibe Coding dengan Prompt murni PRD (Product Requirements Document)** tanpa menyertakan instruksi *Design System* atau *UX Heuristic Skill*.

Prototipe ini membuktikan bagaimana LLM/AI Assistant menerjemahkan kebutuhan fungsional (FR-01 hingga FR-06) dan User Stories dari dokumen PRD menjadi antarmuka web interaktif yang berjalan langsung di peramban (*zero-config / pure vanilla web*).

---

## 🚀 Fitur Fungsional yang Terimplementasi (Sesuai PRD)
- **FR-01 (Katalog & Checkbox Seleksi):** Kotak centang *"Bandingkan"* pada setiap kartu produk dengan batasan minimal 2 dan maksimal 4 produk.
- **FR-02 (Floating Tray):** Bilah bawah melayang yang menampilkan jumlah item terpilih (`0/4`), thumbnail mini, tombol reset, dan tombol pemicu komparasi.
- **FR-03 (Side-by-Side Table Matrix):** Tabel perbandingan berdampingan yang memuat informasi harga, toko, rating bintang, serta 6 parameter teknis TWS (Baterai, Bluetooth, Driver, ANC, Latensi, Garansi).
- **FR-06 (Action CTA):** Tombol *"Masukkan Keranjang"* pada setiap kolom produk dengan notifikasi *toast* konfirmasi.

---

## 🛠️ Tech Stack & Arsitektur
- **Struktur Berkas:** Single-file application (`index.html`) memuat HTML5 semantik, CSS3 murni, dan Vanilla JavaScript.
- **Dependensi:** 0 dependencies (Tidak memerlukan `npm install`, Node.js, atau bundler).
- **Kompatibilitas:** Berjalan di seluruh peramban modern (Chrome, Edge, Firefox, Safari).

---

## 🏃 Cara Menjalankan
1. *Clone* atau unduh repositori ini.
2. Buka berkas `index.html` langsung dengan klik dua kali (atau klik kanan > *Open with Google Chrome / Microsoft Edge*).
3. Anda juga dapat menjalankannya di VS Code menggunakan ekstensi *Live Server*.

---

## 🔍 Evaluasi Hasil "PRD Only" dari Sudut Pandang UX
Meskipun prototipe ini **100% memenuhi persyaratan fungsional (FR)**:
1. **Visual Branding:** Tampilan menggunakan gaya CSS generik, belum mengadopsi bahasa desain resmi Shopee secara presisi (seperti lencana Shopee Mall/Star+, diskon ribbon, dan font SF Pro/Inter).
2. **Heuristik Usability:**
   - Belum memiliki *sticky header* pada tabel, sehingga saat tabel digulir ke bawah, pengguna kehilangan konteks produk mana yang sedang dilihat (*Recognition over Recall* belum optimal).
   - Belum ada fitur *Highlight Differences* untuk mendeteksi perbedaan spesifikasi secara otomatis.
   - Tidak ada penanda *Best Value* (harga termurah / rating tertinggi).
3. **Ergonomi Mobile:** Tampilan tabel desktop belum sepenuhnya adaptif untuk pengalaman sentuh gawai layar sempit (*swipeable card*).

*Peningkatan di atas diselesaikan secara komprehensif pada repositori kedua: **`shopee-compare-prd-plus-skill`**.*
