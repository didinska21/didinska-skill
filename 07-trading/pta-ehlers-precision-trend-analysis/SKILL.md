---
name: pta-ehlers-precision-trend-analysis
description: "Pine Script indicator 'PTA - Ehlers Precision Trend Analysis' for TradingView (wrapped indicator, F7 trading). Source: mihakralj/QuanTAlib (lib/dynamics/pta/pta.pine)."
---

# PTA - Ehlers Precision Trend Analysis (Pine Script indicator)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `indicator` untuk TradingView
- **Sumber:** repo `mihakralj/QuanTAlib`, berkas `lib/dynamics/pta/pta.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `pta.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: PTA: Ehlers Precision Trend Analysis Category: Dynamics Based on: John F. Ehlers, "Precision Trend Analysis," TASC September 2024 Dual highpass filter bandpass approach for near-zero-lag trend extraction. Trend = HP(longPeriod) - HP(shortPeriod) where HP is a 2-pole Butterworth highpass filter. Preserves cyclic components between shortPeriod and longPeriod. Output: zero-centered, positive = uptren

Fitur yang terdeteksi dari kode: menggambar 1 seri plot di chart.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
