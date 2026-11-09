---
name: dynamic-pivot-point-backtest
description: "Pine Script strategy 'Dynamic Pivot Point Backtest' for TradingView (wrapped indicator, F7 trading). Source: fmzquant/strategies (动态支撑阻力回测策略Dynamic-Pivot-Point-Backtest-Strategy.md)."
---

# Dynamic Pivot Point Backtest (Pine Script strategy)

Skill ini adalah strategi/indikator Pine Script yang diekstrak dari blok kode berkas Markdown repo sumber dan dibungkus (wrapped), bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `fmzquant/strategies`, berkas `动态支撑阻力回测策略Dynamic-Pivot-Point-Backtest-Strategy.md` (blok kode Pine di dalamnya)
- **Isi paket:** `SKILL.md` ini + berkas kode asli `strategy.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: Copyright by HPotter v1.0 14/06/2018 This Pivot points is calculated on the current day. Pivot points simply took the high, low, and closing price from the previous period and divided by 3 to find the pivot. From this pivot, traders would then base their calculations for three support, and three resistance levels. The calculation for the most basic flavor of pivot points, known as ‘floor-trader pi

Fitur yang terdeteksi dari kode: menggambar 2 seri plot di chart; berisi perintah entry/close strategi yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
