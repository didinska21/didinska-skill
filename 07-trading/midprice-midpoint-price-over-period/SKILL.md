---
name: midprice-midpoint-price-over-period
description: "Pine Script indicator 'MIDPRICE: Midpoint Price over Period' for TradingView (wrapped indicator, F7 trading). Source: mihakralj/QuanTAlib (lib/core/midprice/midprice.pine)."
---

# MIDPRICE: Midpoint Price over Period (Pine Script indicator)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `indicator` untuk TradingView
- **Sumber:** repo `mihakralj/QuanTAlib`, berkas `lib/core/midprice/midprice.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `midprice.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: MIDPRICE: Midpoint Price over Period (Highest(High, N) + Lowest(Low, N)) / 2 TA-Lib compatible — center of the H/L price channel

Fitur yang terdeteksi dari kode: menggambar 1 seri plot di chart.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
