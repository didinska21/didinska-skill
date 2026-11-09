---
name: ha-heikin-ashi
description: "Pine Script indicator 'HA: Heikin-Ashi' for TradingView (wrapped indicator, F7 trading). Source: mihakralj/QuanTAlib (lib/core/ha/ha.pine)."
---

# HA: Heikin-Ashi (Pine Script indicator)

Skill ini adalah indikator/strategi Pine Script yang dibungkus (wrapped) dari repo sumber, bukan skill yang ditulis tangan.

- **Jenis:** Pine Script `indicator` untuk TradingView
- **Sumber:** repo `mihakralj/QuanTAlib`, berkas `lib/core/ha/ha.pine`
- **Isi paket:** `SKILL.md` ini + berkas kode asli `ha.pine` di folder yang sama.

## Apa yang dilakukan kode ini (dari pemindaian kode sumber)

Komentar pembuka berkas: HA: Heikin-Ashi Smoothed candle transformation with recursive open HA_Close = (O + H + L + C) / 4 HA_Open  = (prev_HA_Open + prev_HA_Close) / 2 HA_High  = max(H, HA_Open, HA_Close) HA_Low   = min(L, HA_Open, HA_Close)

Fitur yang terdeteksi dari kode: tidak ada plot/alert/entry eksplisit yang terdeteksi dari pemindaian kode.

## Cara membaca sinyalnya

Baca judul dan logika di berkas kode asli: keluaran visualnya adalah plot/seri yang digambar indikator di chart, dan (bila ada) alert condition serta entry strategi di dalamnya adalah sinyal resminya. Nilai/ambang pastinya mengikuti input dan kondisi yang tertulis di kode — jangan mengasumsikan sinyal di luar yang didefinisikan kode.

## Catatan

Wrapped indicator: deskripsi di atas hanya menyatakan apa yang didukung kode sumbernya. Ini alat analisis teknikal untuk edukasi, bukan nasihat keuangan.
