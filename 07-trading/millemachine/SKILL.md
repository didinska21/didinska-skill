---
name: millemachine
description: "Pine Script strategy 'MilleMachine' for TradingView (wrapped indicator, F7 trading). Source: fmzquant/strategies (MilleMachine.md)."
---

# MilleMachine (Pine Script strategy)

Skill ini adalah strategi/indikator Pine Script yang diekstrak dari blok kode berkas Markdown repo sumber dan dibungkus (wrapped), bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `fmzquant/strategies`, berkas `MilleMachine.md` (blok kode Pine di dalamnya)
- **Isi paket:** `SKILL.md` ini + berkas kode asli `strategy.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: © Milleman strategy("MilleMachine", overlay=true, default_qty_type = strategy.percent_of_equity, default_qty_value = 100, initial_capital=10000, commission_type=strategy.commission.percent, commission_value=0.06) Additional settings

Fitur yang terdeteksi dari kode: menggambar 7 seri plot di chart; berisi perintah entry/close strategi yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
