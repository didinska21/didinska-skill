---
name: abc-and-parabolic-sar-strategy
description: "Pine Script strategy 'ABC and Parabolic SAR Strategy' for TradingView (wrapped indicator, F7 trading). Source: geraked-tradingview (strategies/ABSAR.pine)."
---

# ABC and Parabolic SAR Strategy (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `geraked-tradingview`, berkas `strategies/ABSAR.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `ABSAR.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: A strategy using ABC and Parabolic SAR indicators The strategy has been explained in this video: https://youtu.be/4H9bmo8IjY0 © 2023 Geraked, Rabist Licensed under MIT Backtesting result: Symbol:             EURUSD Timeframe:          2 HOUR Range:              2022-01-02 22:00 — 2023-09-01 19:00 Percent Profitable: 64.5% Total Trades:       31 Profit Factor:      2.004

Fitur yang terdeteksi dari kode: menggambar 5 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
