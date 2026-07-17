# SEKALA : Sistem Evaluasi Kawasan Analitik Lokal

Dashboard diagnosis transformasi ekonomi Maluku Utara dan rancangan monitoring outcome KEK Halmahera. 

## Berkas dalam repo ini

| Berkas | Wajib untuk dashboard? | Fungsi |
|---|---|---|
| `index.html` | Ya, satu-satunya yang wajib | Dashboard lengkap. Database, gaya, dan logika sudah tertanam di dalamnya sehingga berfungsi tanpa server dan tanpa berkas lain. |
| `sekala-database-final.json` | Tidak, tapi disarankan tetap ada | Salinan berdiri sendiri dari data yang sama persis dengan yang tertanam di `index.html`. Disertakan untuk transparansi dan audit data tanpa perlu membedah kode HTML. |
| `README.md` | Tidak | Dokumen ini. |

## Cara menjalankan

Buka `index.html` langsung di peramban modern, secara lokal maupun lewat GitHub Pages. Tidak diperlukan instalasi, server, atau koneksi ke berkas eksternal apa pun untuk fungsi inti dashboard.

## Cara menjalankan lewat GitHub Pages

1. Unggah `index.html` ke root repository, bukan di dalam folder.
2. Buka menu Settings kemudian Pages.
3. Pilih branch `main` dengan folder `/root` sebagai sumber.
4. Tunggu beberapa saat hingga alamat `https://[nama-pengguna].github.io/[nama-repo]/` aktif.

## Cakupan data

- Sepuluh kabupaten/kota, tujuh belas lapangan usaha, dan tahun 2016 sampai 2025.
- 1.700 observasi inti wilayah-sektor-tahun.
- LQ tahunan dengan pembanding provinsi dan leave-one-out.
- DLQ utama, DLQ endpoint sebagai pembanding, serta shift-share tiga periode.
- Indikator kesejahteraan, rekonsiliasi data, metadata, kamus variabel, GeoJSON, desain kebijakan, enam gerbang keputusan, dan register monitoring.

## Catatan interpretasi

- Dashboard bersifat deskriptif dan komparatif, bukan estimasi kausal.
- LQ menunjukkan spesialisasi relatif, bukan produktivitas.
- PPW negatif menunjukkan pelemahan posisi relatif, bukan otomatis kontraksi absolut.
- PDRB per kapita bukan pendapatan median atau pendapatan rumah tangga.
- Status pada panel kebijakan dan monitoring adalah alat kerja, bukan keputusan resmi.
- Data 2024 berstatus sementara dan data 2025 berstatus sangat sementara mengikuti publikasi BPS.

## Sumber data

Badan Pusat Statistik, PDRB Provinsi dan Kabupaten/Kota Maluku Utara menurut lapangan usaha, atas dasar harga konstan 2010, periode 2016-2025.

## Versi

Dashboard final · Skema SEKALA-2026.2 · Formula SEKALA-METODE-2026.2