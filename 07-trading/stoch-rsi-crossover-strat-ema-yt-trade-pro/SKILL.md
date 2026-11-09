---
name: stoch-rsi-crossover-strat-ema-yt-trade-pro
description: "Pine Script strategy 'Stoch RSI Crossover Strat + EMA - YT:Trade Pro' for TradingView (wrapped indicator, F7 trading). Source: Alorse-pinescript-strategies (strategies/momentum/Stoch RSI Crossover Strat + EMA - YT-Trade Pro.pine)."
---

# Stoch RSI Crossover Strat + EMA - YT:Trade Pro (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `Alorse-pinescript-strategies`, berkas `strategies/momentum/Stoch RSI Crossover Strat + EMA - YT-Trade Pro.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `Stoch RSI Crossover Strat + EMA - YT-Trade Pro.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: Strategy posted by Trade Pro on YT: https://www.youtube.com/watch?v=7NM7bR2mL7U&t=299s This strat uses a 3:1 risk reward ratio, but can be changed by setting the ATR multiplier The script has a time range picker added to back test from a specific date. Best results achieved on EURGBP on 15min 3:1 and USDCAD 30m with a 1:3 RRR

Fitur yang terdeteksi dari kode: menggambar 3 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
