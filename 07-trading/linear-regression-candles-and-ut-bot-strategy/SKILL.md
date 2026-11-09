---
name: linear-regression-candles-and-ut-bot-strategy
description: "Pine Script strategy 'Linear Regression Candles and UT Bot Strategy' for TradingView (wrapped indicator, F7 trading). Source: geraked-tradingview (strategies/LRCUTB.pine)."
---

# Linear Regression Candles and UT Bot Strategy (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `geraked-tradingview`, berkas `strategies/LRCUTB.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `LRCUTB.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: A strategy using Linear Regression Candles and UT Bot Alerts The strategy has been explained in this video: https://youtu.be/0ZzLlA9NFxo It should be noted that the inversion of the strategy works better! :D © 2023 Geraked, Rabist Licensed under MIT Backtesting result: Symbol:             USDCHF Timeframe:          15 MIN Range:              2023-08-01 — 2023-10-27 Percent Profitable: 70.57% Total

Fitur yang terdeteksi dari kode: menggambar 1 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest; memiliki logika sinyal beli/long; memiliki logika sinyal jual/short.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
