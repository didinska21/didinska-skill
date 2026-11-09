---
name: daily-high-low-and-andean-oscillator-strategy
description: "Pine Script strategy 'Daily High/Low and Andean Oscillator Strategy' for TradingView (wrapped indicator, F7 trading). Source: geraked-tradingview (strategies/DHLAOS.pine)."
---

# Daily High/Low and Andean Oscillator Strategy (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `geraked-tradingview`, berkas `strategies/DHLAOS.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `DHLAOS.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: A strategy using Daily High/Low and Andean Oscillator indicators for scalping The strategy has been explained in this video: https://youtu.be/IZVSb1kjduQ © 2023 Geraked, Rabist Licensed under MIT Backtesting result: Symbol:             AUDUSD Timeframe:          5 MIN Range:              2023-08-06 21:00 — 2023-09-03 21:00 Percent Profitable: 69.5% Total Trades:       23 Profit Factor:      3.098

Fitur yang terdeteksi dari kode: menggambar 2 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest; memiliki logika sinyal beli/long; memiliki logika sinyal jual/short.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
