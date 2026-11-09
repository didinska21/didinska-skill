---
name: grid-bot-simulator-alorse
description: "Pine Script strategy 'Grid Bot Simulator [Alorse]' for TradingView (wrapped indicator, F7 trading). Source: Alorse-pinescript-strategies (strategies/grid/GridBotDir [Alorse].pine)."
---

# Grid Bot Simulator [Alorse] (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `Alorse-pinescript-strategies`, berkas `strategies/grid/GridBotDir [Alorse].pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `GridBotDir [Alorse].pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: ------------------------------------------------------------------------------------------------<> This source code is subject to the terms of the Mozilla Public License 2.0 https://mozilla.org/MPL/2.0/ ©mvs1231 || xxattaxx Updated 06/05/2021 to fix Transp deprecation indicator('Grid Bot Simulator [Alorse]', shorttitle='GridBotDir [Alorse]', overlay=true)

Fitur yang terdeteksi dari kode: menggambar 4 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest; memiliki logika sinyal beli/long; memiliki logika sinyal jual/short.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
