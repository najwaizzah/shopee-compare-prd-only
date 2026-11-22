# CHANGELOG - Shopee Product Comparison (PRD Only)
Semua perubahan penting dan riwayat iterasi pengembangan antarmuka pada repositori ini dicatat dalam berkas ini.

Format pencatatan mengacu pada standar [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) dan [Conventional Commits](https://www.conventionalcommits.org/).

---

## [1.0.0] - 2026-11-22
### Ditambahkan (Added)
- `docs(prd)`: Dokumentasi integrasi spesifikasi kebutuhan fungsional (FR-01 s/d FR-06) dan User Stories (US-01 s/d US-06) dari Worksheet 08.
- `feat(catalog)`: Tampilan katalog 6 produk earphone TWS Bluetooth dengan layout grid standar.
- `feat(selection)`: Checkbox *"Bandingkan"* pada setiap kartu produk dengan validasi minimal 2 dan maksimal 4 produk.
- `feat(tray)`: Bilah bawah melayang (*floating bottom tray*) dengan indikator hitungan `(0/4)`, thumbnail mini produk terpilih, dan tombol hapus semua.
- `feat(matrix)`: Modal perbandingan produk menampilkan tabel berdampingan (*side-by-side*) mencakup: Nama, Harga, Toko, Rating, Baterai, Bluetooth, Driver, ANC, Latensi, dan Garansi.
- `feat(cart)`: Tombol *"Masukkan Keranjang"* pada tabel dengan notifikasi *toast* sederhana.
- `docs(readme)`: Panduan menjalankan prototipe murni peramban (*zero-config*) dan evaluasi batasan antarmuka PRD-only.

### Catatan Evaluasi Usability (Usability Review)
- Antarmuka memenuhi seluruh kriteria fungsional PRD, namun tampilan visual masih bergaya generic HTML.
- Header tabel belum bersifat *sticky* (hilang saat digulir ke bawah).
- Belum tersedia fitur otomatisasi penanda perbedaan spesifikasi teknis (*Highlight Differences*).
