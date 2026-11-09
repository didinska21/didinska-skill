---
name: ehlers-fisher-transform-2004-fisher04
description: "Pine Script indicator 'Ehlers Fisher Transform 2004 (FISHER04)' for TradingView (wrapped indicator, F7 trading). Source: mihakralj/QuanTAlib (lib/oscillators/fisher04/fisher04.pine)."
---

# Ehlers Fisher Transform 2004 (FISHER04) (Pine Script indicator)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `indicator` untuk TradingView
- **Sumber:** repo `mihakralj/QuanTAlib`, berkas `lib/oscillators/fisher04/fisher04.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `fisher04.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: Licensed under the Apache License, Version 2.0 © mihakralj Fisher04: Ehlers Fisher Transform (2004 Cybernetic Analysis) Source: John Ehlers, "Cybernetic Analysis for Stocks and Futures", Wiley, 2004, Chapter 1 Key differences from 2002 TASC article (fisher.pine): Normalization: 1.0 * ((price-low)/range - 0.5) vs 0.66 * (...) IIR feedback on Value1: 0.5 vs 0.67 Clamp threshold: 0.9999 vs 0.99→0.999

Fitur yang terdeteksi dari kode: menggambar 2 seri plot di chart.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
