# Tahap 2 — Risk Register

[⬅️ Estimasi Biaya](estimasi-biaya.md) &nbsp;|&nbsp; [README ➡️](../../README.md)

---

Skor = probabilitas × dampak (skala 1–5). **≥ 15** Tinggi · **8–14** Sedang · **< 8** Rendah. Penilaian awal ini adalah perkiraan tim dan diperbarui pada Tahap 4.

**Ringkasan:** 🔴 1 tinggi · 🟡 10 sedang · 🟢 2 rendah

## Peta Risiko

| Probabilitas ↓ / Dampak → | 1 | 2 | 3 | 4 | 5 |
|:-:|:-:|:-:|:-:|:-:|:-:|
| **5** | 🟢 | 🟡 | 🔴 | 🔴 | 🔴 |
| **4** | 🟢 | 🟡 R09 | 🟡 R02 | 🔴 R01 | 🔴 |
| **3** | 🟢 | 🟢 R12 | 🟡 R07, R08 | 🟡 R03, R04, R05, R06 | 🔴 |
| **2** | 🟢 | 🟢 | 🟢 | 🟡 R10, R11 | 🟡 |
| **1** | 🟢 | 🟢 | 🟢 R13 | 🟢 | 🟢 |

## Daftar Risiko

| ID | Risiko | Penyebab | WBS | P | I | Skor | Tingkat | Strategi | Mitigasi | Pemilik | Pemicu |
| --- | --- | --- | :-: | :-: | :-: | :-: | :-: | :-: | --- | :-: | --- |
| R01 | Data menu, harga, dan foto kedai terlambat atau tidak lengkap | Pemilik sibuk atau jadwal kunjungan tidak cocok | 3.1, 5.3 | 4 | 4 | 16 | 🔴 Tinggi | Kurangi | Kirim daftar isian data sejak awal, jadwalkan kunjungan di minggu pertama, siapkan data sementara agar pengembangan tidak berhenti | Kharisa | Data belum lengkap pada 28 Okt |
| R02 | Jadwal proyek bentrok dengan kuliah dan tugas lain | Tenggat mata kuliah lain berdekatan | Semua | 4 | 3 | 12 | 🟡 Sedang | Kurangi | Rapat mingguan untuk menata ulang beban, beri ruang cadangan pada jadwal, utamakan jalur kritis | Andi | Aktivitas mundur lebih dari 2 hari kerja |
| R03 | Estimasi manday dan durasi terlalu optimis | Perkiraan O, M, P belum teruji | 2.6, 2.3 | 3 | 4 | 12 | 🟡 Sedang | Kurangi | Pakai PERT tiga titik, tinjau tiap minggu, perbarui estimasi pada Tahap 4 | Hafiz | Manday aktual melebihi estimasi 20% |
| R04 | Perubahan ruang lingkup (mis. pemilik meminta pemesanan online) | Harapan pemilik berkembang di tengah proyek | 3.2, 4.x | 3 | 4 | 12 | 🟡 Sedang | Hindari | Catat sebagai permintaan perubahan, nilai dampak waktu dan biaya, putuskan bersama dosen; tetap pada ruang lingkup Project Charter | Andi | Ada permintaan fitur di luar charter |
| R05 | Anggota berhalangan (sakit atau keperluan keluarga) | Kondisi tak terduga | Semua | 3 | 4 | 12 | 🟡 Sedang | Kurangi | Dokumentasikan pekerjaan di GitHub, tentukan anggota pendukung tiap tugas (lihat matriks RACI) | Andi | Anggota tidak aktif lebih dari 3 hari |
| R06 | Cacat ditemukan banyak saat pengujian dan mepet tenggat | Pengujian baru dilakukan di akhir | 6.2, 6.3 | 3 | 4 | 12 | 🟡 Sedang | Kurangi | Uji bertahap sejak 5.2, sisakan 2 hari perbaikan sebelum penutupan | Arya | Lebih dari 10 temuan pada 6.2 |
| R07 | Anggota belum terbiasa Git/GitHub sehingga berkas tertimpa atau konflik | Pengalaman Git terbatas | 5.4 | 3 | 3 | 9 | 🟡 Sedang | Kurangi | Latihan bersama, aturan branch dan pull request, commit kecil dan sering | Hafiz | Konflik penggabungan berulang |
| R08 | Koneksi internet tidak stabil saat unggah atau rapat daring | Gangguan jaringan | Semua | 3 | 3 | 9 | 🟡 Sedang | Terima | Commit lokal lalu push saat koneksi baik, rapat tatap muka bila perlu | Hafiz | Unggah gagal lebih dari 2 kali |
| R09 | Menu atau harga berubah setelah data dikumpulkan | Penyesuaian harga oleh pemilik | 5.3 | 4 | 2 | 8 | 🟡 Sedang | Kurangi | Konfirmasi ulang sebelum pemasukan konten, rancang konten agar mudah diperbarui | Kharisa | Pemilik menyebut perubahan harga |
| R10 | Harapan pemilik berbeda dengan rancangan tim | Rancangan tidak ditunjukkan lebih awal | 4.2, 6.4 | 2 | 4 | 8 | 🟡 Sedang | Kurangi | Tunjukkan wireframe lebih awal dan minta persetujuan sebelum pengembangan | Arya | Pemilik meminta perubahan besar pada tampilan |
| R11 | Berkas lokal hilang atau rusak | Kerusakan perangkat atau salah hapus | Semua | 2 | 4 | 8 | 🟡 Sedang | Kurangi | Simpan di GitHub dan cadangan di penyimpanan daring | Hafiz | Berkas belum ter-push lebih dari 3 hari |
| R12 | Foto produk kurang berkualitas | Pencahayaan dan latar tidak sesuai | 3.1, 5.3 | 3 | 2 | 6 | 🟢 Rendah | Kurangi | Panduan sederhana pencahayaan, ambil ulang foto bila perlu | Kharisa | Foto buram atau gelap |
| R13 | Layanan hosting gratis tidak tersedia atau bermasalah | Kebijakan layanan berubah | 5.x, 9.1 | 1 | 3 | 3 | 🟢 Rendah | Terima | Siapkan alternatif hosting gratis lain | Hafiz | Situs tidak bisa diakses |

**Strategi:** Hindari = ubah rencana agar risiko tidak terjadi · Kurangi = turunkan peluang atau dampak · Terima = dipantau saja.
