---
name: mlcel-and-macd-strategy
description: "Pine Script strategy 'MLCEL and MACD Strategy' for TradingView (wrapped indicator, F7 trading). Source: geraked-tradingview (strategies/MLCEL_MACD.pine)."
---

# MLCEL and MACD Strategy (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `geraked-tradingview`, berkas `strategies/MLCEL_MACD.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `MLCEL_MACD.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: A strategy using "Machine Learning : Cosine Similarity & Euclidean + Lorentzian Distance" and MACD indicators The strategy has been explained in this video: https://youtu.be/f2f-Tmf2Eec © 2023 Geraked, Rabist Licensed under MIT Backtesting result: Symbol:             EURUSD Timeframe:          4 HOUR Range:              2022-06-16 — 2023-09-21 Percent Profitable: 51.0% Total Trades:       47 Profi

Fitur yang terdeteksi dari kode: menggambar 1 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest; memiliki logika sinyal beli/long; memiliki logika sinyal jual/short.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
