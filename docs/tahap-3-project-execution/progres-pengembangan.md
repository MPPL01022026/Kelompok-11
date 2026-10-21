# Tahap 3 — Progres Pengembangan Aplikasi/Prototipe

[⬅️ Pembagian Tugas](pembagian-tugas.md) &nbsp;|&nbsp; [Catatan Rapat ➡️](catatan-rapat.md)

---

Per **21 Oktober 2026** kelompok sudah memiliki kerangka halaman web Kedai Pujasera versi 0.1 di [`prototype/index.html`](../../prototype/index.html). Berkas ini berdiri sendiri (HTML, CSS, JavaScript dalam satu berkas) sehingga bisa dibuka langsung di peramban tanpa pemasangan apa pun.

## 1. Yang Sudah Ada di Prototipe v0.1

| Bagian | Keterangan | Kode WBS |
| --- | --- | :-: |
| Kepala halaman | Nama kedai, kalimat pengantar, penanda versi prototipe | 5.2 |
| Daftar menu | Lima item awal sesuai README (nasi ayam caplak, nasi goreng, jus, es teh, minuman sachet) | 5.2, 5.3 |
| Filter menu | Tombol Semua, Makanan, Minuman | 5.2 |
| Informasi kedai | Alamat, jam buka, kontak | 5.3 |
| Data terpusat | Seluruh isi menu dan info kedai ada dalam satu objek `DATA` di bagian bawah berkas, sehingga pembaruan harga tidak menyentuh tampilan (mitigasi R09) | 5.3 |

## 2. Yang Belum Ada

| Hal | Alasan | Rencana |
| --- | --- | --- |
| Harga, alamat, jam buka, kontak | Belum dikonfirmasi pemilik; ditampilkan sebagai "menyusul" | Diisi setelah 3.1 (26–28 Okt) |
| Foto produk | Belum diambil | Diganti saat 5.3 (10–13 Nov) |
| Menu lainnya | README menyebut "menyusul" | Menunggu data pemilik |
| Tampilan final | Wireframe 4.2 belum selesai | Prototipe disesuaikan setelah wireframe disetujui |

## 3. Cara Menjalankan

1. Salin atau unduh repositori.
2. Buka `prototype/index.html` di peramban.
3. Untuk mengubah isi menu, edit objek `DATA` di bagian `<script>`; tidak perlu mengubah bagian lain.

## 4. Pembaruan Berikutnya

| Tanggal | Target |
| --- | --- |
| 28 Okt | Isi `DATA` dengan data hasil 3.1; sesuaikan struktur halaman dengan 4.1 |
| 30 Okt | Selaraskan tampilan dengan wireframe 4.2 |
| 2–9 Nov | Pengembangan tampilan penuh (5.2) |
| 10–13 Nov | Pemasukan foto dan konten final (5.3) |

*Catat setiap pembaruan di tabel ini beserta tautan commit-nya.*
