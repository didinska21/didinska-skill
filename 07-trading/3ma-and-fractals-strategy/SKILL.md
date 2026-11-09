---
name: 3ma-and-fractals-strategy
description: "Pine Script strategy '3MA and Fractals Strategy' for TradingView (wrapped indicator, F7 trading). Source: geraked-tradingview (strategies/3MAF.pine)."
---

# 3MA and Fractals Strategy (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `geraked-tradingview`, berkas `strategies/3MAF.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `3MAF.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: A simple strategy using three Moving Averages and Williams Fractals for scalping. The strategy has been explained in this video: https://youtu.be/bKPs2aOsvsk It should be noted that the reverse of the strategy works better! :D © 2023 Geraked, Rabist Licensed under MIT Backtesting result: Symbol:             USDCAD Timeframe:          1 MIN Range:              2023-07-09 21:00 — 2023-07-13 13:14 Pe

Fitur yang terdeteksi dari kode: menggambar 3 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
