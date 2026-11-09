---
name: amfm-ehlers-am-detector-fm-demodulator
description: "Pine Script indicator 'AMFM - Ehlers AM Detector / FM Demodulator' for TradingView (wrapped indicator, F7 trading). Source: mihakralj/QuanTAlib (lib/cycles/amfm/amfm.pine)."
---

# AMFM - Ehlers AM Detector / FM Demodulator (Pine Script indicator)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `indicator` untuk TradingView
- **Sumber:** repo `mihakralj/QuanTAlib`, berkas `lib/cycles/amfm/amfm.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `amfm.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: AMFM: Ehlers AM Detector / FM Demodulator John F. Ehlers — "A Technical Description of Market Data for Traders" TASC, May 2021 (AM + FM) / June 2021 (strategy application) Source: https://www.mesasoftware.com/papers/AMFM.pdf Decomposes price movement into amplitude (AM) and frequency (FM) components using digital signal processing techniques from radio engineering. AM Detector: extracts volatility

Fitur yang terdeteksi dari kode: menggambar 2 seri plot di chart.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
