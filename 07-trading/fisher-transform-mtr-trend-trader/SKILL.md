---
name: fisher-transform-mtr-trend-trader
description: "Pine Script strategy 'Fisher Transform MTR Trend trader' for TradingView (wrapped indicator, F7 trading). Source: vikaschouhan-algotrade (pinescript/fisher_transform_mtr_trend_trader.psc)."
---

# Fisher Transform MTR Trend trader (Pine Script strategy)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `strategy` untuk TradingView
- **Sumber:** repo `vikaschouhan-algotrade`, berkas `pinescript/fisher_transform_mtr_trend_trader.psc`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `fisher_transform_mtr_trend_trader.psc` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: Fisher Transform trend trader strategy. This applies Fisher transform on higher time frames to get long term cycles and tries to trade them via trend following.

Fitur yang terdeteksi dari kode: menggambar 2 seri plot di chart; berisi perintah entry strategi (long/short) yang bisa di-backtest.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
