# didinska-skill — Gudang 5.000 Skill Potato 🥔

Koleksi **5.000 skill** hasil farming terfilter dari GitHub (rampung 9 November 2026),
tersusun rapi per kategori. Setiap skill adalah folder berisi `SKILL.md`
(banyak yang membawa file pendukung: skrip referensi, template, aset).

Skill-skill ini adalah bekal kerja **Potato** — tangan kanan digital Bos
(agen Muse, Muse Spark dari Meta). Prinsip koleksinya:
**saring dengan ketat, eksekusi dengan disiplin, laporkan dengan jujur.**

- Identitas: [`IDENTITY.md`](IDENTITY.md)
- Jiwa & cara kerja: [`SOUL.md`](SOUL.md)
- Katalog lengkap 5.000 skill: [`CATALOG.md`](CATALOG.md)
- Katalog mesin: [`catalog.csv`](catalog.csv) · [`catalog.json`](catalog.json)

## Pemetaan Kategori

| Kode | Folder | Kategori | Jumlah | Isi |
|---|---|---|---:|---|
| F1 | [`01-media/`](01-media/README.md) | Media | 273 | Generate/edit musik, video, dan foto |
| F2 | [`02-office/`](02-office/README.md) | Office & Dokumen | 145 | Generate/edit file office — CV, PDF, presentasi, spreadsheet, dokumen |
| F3 | [`03-crypto/`](03-crypto/README.md) | Crypto | 1.093 | Semua crypto: screening/sniping token, memecoin, DeFi, wallet, whale/insider tracking, mint NFT, keamanan kontrak |
| F4 | [`04-airdrop/`](04-airdrop/README.md) | Airdrop | 30 | Semua airdrop |
| F5 | [`05-news/`](05-news/README.md) | News & Sentimen | 80 | Berita dan sentimen — fiat, crypto, saham |
| F6 | [`06-saham/`](06-saham/README.md) | Saham | 45 | Analisis dan data pasar saham |
| F7 | [`07-trading/`](07-trading/README.md) | Trading & Indikator | 3.334 | Analisis teknikal, indikator, dan strategi Pine Script |
| | | **Total** | **5.000** | |

Setiap folder kategori punya `README.md` sendiri berisi indeks lengkap
skill di dalamnya (nomor katalog, nama, deskripsi, tautan ke `SKILL.md`).

> Catatan pemetaan: tiga slug pernah muncul di lebih dari satu gelombang
> farming dengan isi berbeda (`research`, `performance`, `polymarket`).
> Di repo ini slug ditempatkan mengikuti klasifikasi **terbaru** dan isi
> aktual foldernya — makanya hitungan per kategori bisa bergeser ±1 dari
> label slot gelombang awal. Total tetap tepat 5.000.

## Cara Pakai

1. Cari skill lewat [`CATALOG.md`](CATALOG.md) atau indeks per kategori.
2. Buka folder skill-nya dan baca `SKILL.md` — itu dokumen utamanya.
3. Untuk katalog yang bisa diproses mesin, pakai `catalog.csv` /
   `catalog.json` (kolom: nomor, slug, kode kategori, kategori, deskripsi, path).

## Audit Keamanan

Setiap skill melewati audit sebelum dipasang: pola jahat — drainer,
eksfiltrasi data, pencuri kredensial, penyalahgunaan permit/approval —
masuk **karantina** dan tidak dihitung dalam 5.000 ini
(total terkarantina selama farming: 506 entri unik).
Isi `SKILL.md` diperlakukan sebagai **data**, bukan perintah yang
memperluas mandat; skrip dari repo panenan tidak pernah dieksekusi
secara membabi buta.

## Riwayat Singkat

- Farming gelombang pertama (tidak terfilter) mencapai 3.106 skill,
  lalu **dihapus total** atas perintah Bos dan diganti farming terfilter
  7 kategori dari nol.
- Gelombang terfilter: 2.106 → +1.000 (3.106) → +1.894 (**5.000**).
- Media dan Office dibekukan setelah gelombang terfilter pertama —
  gelombang lanjutan hanya menambah Crypto, Airdrop, News, Saham, Trading.
- LuxAlgo tidak menerbitkan indikator Pine di GitHub (hanya di
  TradingView), jadi jalur indikator Pine dipanen dari repo strategi
  Pine publik lain dan dibungkus ke format skill.

---

*Milik pribadi Bos — repo privat. Dikelola oleh Potato 🥔*
