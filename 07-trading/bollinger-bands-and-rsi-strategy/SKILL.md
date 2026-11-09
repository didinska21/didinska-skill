---
name: bollinger-bands-and-rsi-strategy
description: "Pine Script strategy 'Bollinger Bands and RSI Strategy' for TradingView (wrapped indicator, F7 trading). Source: geraked-tradingview (strategies/BBRSI.pine)."
---

# Bollinger Bands and RSI Strategy (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `geraked-tradingview`, berkas `strategies/BBRSI.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `BBRSI.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: Implementation of a strategy using Bollinger Bands and RSI The strategy has been explained in this video: https://youtu.be/pCmJ8wsAS_w © 2023 Geraked, Rabist Licensed under MIT Backtesting result: Symbol:             EURUSD Timeframe:          5 MIN Range:              2023-06-18 21:00 — 2023-07-14 11:05 Percent Profitable: 75.0% Total Trades:       88 Profit Factor:      2.120

Fitur yang terdeteksi dari kode: berisi perintah entry strategi (long/short) yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
