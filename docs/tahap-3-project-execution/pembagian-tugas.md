# Tahap 3 — Pembagian Tugas dan Bukti Pelaksanaan

[⬅️ README](../../README.md) &nbsp;|&nbsp; [Progres Pengembangan ➡️](progres-pengembangan.md)

---

Dokumen ini mengubah rencana Tahap 2 menjadi daftar kerja yang dijalankan. Penanggung jawab (PIC), tanggal, dan dependensi mengikuti [Jadwal dan Gantt Chart](../tahap-2-project-planning/jadwal-gantt.md) dan [Resource Plan](../tahap-2-project-planning/resource-plan.md). Kolom **Status** dan **Bukti** diperbarui oleh PIC masing-masing setiap kali pekerjaan berubah.

**Keterangan status:** ✅ selesai · 🔄 berjalan · ⏳ belum dimulai

## 1. Ringkasan Beban per Anggota

| Anggota | NIM | Peran | Pekerjaan pada periode Tahap 3 (19–30 Okt) |
| --- | --- | --- | --- |
| Andi Saputra | `230504081` | Analis kebutuhan dan penyusun laporan | 2.5, 2.9, 3.2, 3.3, 6.1 |
| Muhammad Hafiz Akbar | `230504077` | Pengelola repositori dan pengembang | 2.3, 2.7, 2.9, 4.3, 5.1, 5.4 |
| Arya Diansyah | `230504063` | Perancang tampilan dan pengembang UI | 2.8, 4.1, 4.2, 5.2 (kerangka awal) |
| Kharisa Ariyana | `230504069` | Pengelola konten dan presentasi | 2.6, 3.1 |

## 2. Daftar Pekerjaan dan Bukti

| Kode | Pekerjaan | PIC | Rencana | Status | Bukti pelaksanaan |
| --- | --- | --- | :-: | :-: | --- |
| 2.3 | Jadwal dan Gantt Chart | Hafiz | 19–20 Okt | ✅ | [jadwal-gantt.md](../tahap-2-project-planning/jadwal-gantt.md), [index.html](../../index.html) |
| 2.5 | Resource & Responsibility Plan | Andi | 19–20 Okt | ✅ | [resource-plan.md](../tahap-2-project-planning/resource-plan.md) |
| 2.6 | Estimasi manday | Kharisa | 21 Okt | ✅ | [effort-manday.md](../tahap-2-project-planning/effort-manday.md) |
| 2.7 | Estimasi biaya | Hafiz | 22 Okt | ✅ | [estimasi-biaya.md](../tahap-2-project-planning/estimasi-biaya.md) |
| 2.8 | Risk Register | Arya | 19–20 Okt | ✅ | [risk-register.md](../tahap-2-project-planning/risk-register.md) |
| 2.9 | Review dan unggah dokumen Tahap 2 | Andi, Hafiz | 23 Okt | 🔄 | Riwayat commit repositori (lihat [bukti kolaborasi](bukti-kolaborasi.md)) |
| 3.1 | Mengumpulkan data menu, harga, foto, info kedai | Kharisa | 26–28 Okt | ⏳ | *isi: foto/tangkapan layar kunjungan atau chat dengan pemilik* |
| 3.2 | Menentukan kebutuhan pengguna | Andi | 26–27 Okt | ⏳ | *isi: tautan berkas di `docs/`* |
| 3.3 | Kebutuhan fungsional dan nonfungsional | Andi | 28–29 Okt | ⏳ | *isi: tautan berkas di `docs/`* |
| 4.1 | Struktur informasi/halaman | Arya | 26–27 Okt | ⏳ | *isi: tautan berkas di `docs/`* |
| 4.2 | Wireframe/mockup | Arya | 28–30 Okt | ⏳ | *isi: tautan Figma/Canva atau gambar di `assets/`* |
| 4.3 | Menentukan teknologi | Hafiz | 26 Okt | ⏳ | *isi: tautan berkas di `docs/`* |
| 5.1 | Lingkungan pengembangan | Hafiz | 27 Okt | ⏳ | *isi: tautan commit awal* |
| 5.2 | Tampilan halaman | Arya | 2–9 Nov | 🔄 | Kerangka awal: [prototype/index.html](../../prototype/index.html) |
| 5.4 | Pengelolaan versi di GitHub | Hafiz | 27 Okt–13 Nov | 🔄 | [bukti-kolaborasi.md](bukti-kolaborasi.md) |
| R1 | Rapat koordinasi minggu ke-1 | Semua | 21 Okt | 🔄 | [catatan-rapat.md](catatan-rapat.md) |
| R2 | Rapat koordinasi minggu ke-2 | Semua | 28 Okt | ⏳ | [catatan-rapat.md](catatan-rapat.md) |

> Pekerjaan 5.2 sengaja dibuka lebih awal lewat kerangka halaman v0.1 agar tim punya bentuk nyata untuk dibahas di rapat dan ditunjukkan ke pemilik kedai (mitigasi risiko R10). Jadwal 5.2 penuh tetap 2–9 November.

## 3. Aturan Pembaruan

1. PIC memperbarui kolom Status dan Bukti pada hari pekerjaan berubah, bukan di akhir.
2. Setiap bukti berupa tautan ke berkas atau commit di repositori, atau gambar di folder `assets/`.
3. Bila pekerjaan mundur lebih dari 2 hari kerja, PIC mencatatnya di [catatan rapat](catatan-rapat.md) pada pertemuan berikutnya dan di Risk Register (pemicu R02).
