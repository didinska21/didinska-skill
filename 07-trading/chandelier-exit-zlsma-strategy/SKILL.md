---
name: chandelier-exit-zlsma-strategy
description: "Pine Script strategy 'Chandelier Exit & ZLSMA Strategy' for TradingView (wrapped indicator, F7 trading). Source: geraked-tradingview (strategies/CEZLSMA.pine)."
---

# Chandelier Exit & ZLSMA Strategy (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `geraked-tradingview`, berkas `strategies/CEZLSMA.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `CEZLSMA.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: This is the implementation of the strategy explained in this video: https://youtu.be/2U5VTWBBK8U It uses the Chandelier Exit and ZLSMA indicators. It is based on the Heikin Ashi candles. © 2023 Geraked, Rabist Licensed under MIT Backtesting result: Symbol:             EURJPY Timeframe:          1 MIN Range:              2023-07-02 21:05 — 2023-07-12 14:38 Percent Profitable: 70.24% Total Trades:  

Fitur yang terdeteksi dari kode: menggambar 1 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
