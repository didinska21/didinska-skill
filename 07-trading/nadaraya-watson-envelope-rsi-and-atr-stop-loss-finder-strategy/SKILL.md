---
name: nadaraya-watson-envelope-rsi-and-atr-stop-loss-finder-strategy
description: "Pine Script strategy 'Nadaraya-Watson Envelope, RSI, and ATR Stop Loss Finder Strategy' for TradingView (wrapped indicator, F7 trading). Source: geraked-tradingview (strategies/NWERSIASF.pine)."
---

# Nadaraya-Watson Envelope, RSI, and ATR Stop Loss Finder Strategy (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `geraked-tradingview`, berkas `strategies/NWERSIASF.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `NWERSIASF.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: A strategy using Nadaraya-Watson Envelope, RSI, and ATR Stop Loss Finder indicators The strategy has been explained in this video: https://youtu.be/Olb47nBRSSo © 2023 Geraked, Rabist Licensed under MIT Backtesting result: Symbol:             USDJPY Timeframe:          15 MIN Range:              2023-08-15 — 2023-10-20 Percent Profitable: 50.52% Total Trades:       97 Profit Factor:      1.327

Fitur yang terdeteksi dari kode: menggambar 4 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
