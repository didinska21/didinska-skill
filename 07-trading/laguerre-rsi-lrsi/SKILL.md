---
name: laguerre-rsi-lrsi
description: "Pine Script indicator 'Laguerre RSI (LRSI)' for TradingView (wrapped indicator, F7 trading). Source: mihakralj/QuanTAlib (lib/oscillators/lrsi/lrsi.pine)."
---

# Laguerre RSI (LRSI) (Pine Script indicator)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `indicator` untuk TradingView
- **Sumber:** repo `mihakralj/QuanTAlib`, berkas `lib/oscillators/lrsi/lrsi.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `lrsi.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: Licensed under the Apache License, Version 2.0 © mihakralj LRSI: Laguerre RSI John Ehlers, "Cybernetic Analysis for Stocks and Futures" (2004) A modified RSI that uses a 4-element Laguerre filter as its core moving average. The gamma parameter controls the damping of the filter stages, trading responsiveness against smoothness. Output is dimensionless [0, 1].

Fitur yang terdeteksi dari kode: menggambar 1 seri plot di chart.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
