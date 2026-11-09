---
name: wclprice-weighted-close-price
description: "Pine Script indicator 'WCLPRICE: Weighted Close Price' for TradingView (wrapped indicator, F7 trading). Source: mihakralj/QuanTAlib (lib/core/wclprice/wclprice.pine)."
---

# WCLPRICE: Weighted Close Price (Pine Script indicator)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `indicator` untuk TradingView
- **Sumber:** repo `mihakralj/QuanTAlib`, berkas `lib/core/wclprice/wclprice.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `wclprice.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: WCLPRICE: Weighted Close Price (High + Low + 2 * Close) / 4 TA-Lib compatible — equivalent to TBar.HLCC4

Fitur yang terdeteksi dari kode: menggambar 1 seri plot di chart.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
