# Revisi news-image-20261120: 42 → 48 cerita

Tanggal revisi: Jumat 20 November 2026 (~13:00 WIB).
Alasan: patokan pemenang news-image adalah 46–50 cerita bersumber; entri awal
hanya 42. Bos memerintahkan penambahan ("kalo menurut kamu bisa lebih baik
lagi coba aja tambahin") dengan prioritas BERITA YANG MENARIK.

## Hasil akhir

- Jumlah cerita: **48** (4 lead + 12 medium + 32 "Also on Friday")
- Ukuran entry.png: **224.105 bytes** (≤ 1 MiB), 1024×1024
- SHA-256 entry.png: `e01b0817598f326d305ac3bb36bda392418ce61817bed76380b68a38e1541b79`
- Tally region (geografis): Europe 7 · Asia 16 · Americas 8 · Africa 9 ·
  Middle East 2 · Oceania 3 · Global 3 = 48

## Cerita tambahan (semua terverifikasi terjadi/dilaporkan pertama kali pada Jumat 20 November 2026)

| # | Cerita di poster | Fakta + sumber |
|---|---|---|
| 43 | Beijing: PBOC holds rates at 3.00%/3.50%, 18th month | PBOC menahan 1-year LPR 3,00% dan 5-year 3,50% pada 20 Nov 01:00 UTC, bulan ke-18 berturut-turut. Sumber: Reuters (via TradingView/Morningstar), FXStreet, Seeking Alpha, investinglive. |
| 44 | Las Vegas: Russell tops wet F1 FP2; FP1 washed out | George Russell (Mercedes) tercepat di FP2 GP Las Vegas 1:47.272; FP1 washout tanpa satu pun lap time. Sumber: formula1.com (published 2026-11-20T05:17Z), PlanetF1, Crash.net, Speedcafe. |
| 45 | Tokyo: core inflation hits 2026 high at 2.2% | CPI inti Jepang Oktober +2,2% y/y (rilis 20 Nov), tertinggi 2026, di atas target BOJ 2% dua bulan beruntun; kenaikan suku bunga Desember makin mungkin. Sumber: Reuters ("TOKYO, Nov 20"), ActionForex, Longbridge. |
| 46 | Seoul: Samsung names Choi Won-joon new mobile chief | Samsung menunjuk Choi Won-joon sebagai kepala divisi Mobile eXperience (MX), menggantikan TM Roh setelah ~7 tahun; Hwang Sang-joon pimpin bisnis memori. Sumber: Reuters ("SEOUL, Nov 20"), Samsung Newsroom, SamMobile, 9to5Google. |
| 47 | Brussels: youth strike sweeps Europe; rallies in 7 nations | Aksi mogok/protes pemuda terkoordinasi di 7 negara Eropa (Prancis, Inggris, Belgia, Spanyol, Italia, Portugal, Yunani) soal biaya hidup, perumahan, pendidikan dan anti-militerisasi; koalisi 50+ kelompok, 25+ negara. Sumber: AFP (via Bangkok Post), Wisevoter, Particle, In-Common. |
| 48 | Loyalty Is.: M5.6 quake offshore; no tsunami threat | Gempa M5.6 di tenggara Kepulauan Loyalty, 20 Nov 00:49 UTC, kedalaman 10 km; USGS green alert, tanpa ancaman tsunami. Sumber: USGS (via watchers.live, terremoto.developers.do, nova.alicetears.com). |

## Kandidat yang DITOLAK (sudah dicek, gagal verifikasi tanggal)

Semua ini ternyata terjadi/dilaporkan pertama kali pada 19 November (atau
lebih lama), jadi tidak boleh masuk poster 20 November:

- UK £260m / 1.000+ drone untuk Ukraina — diumumkan 19 Nov di Berlin (GOV.UK).
- Protes 13.000 orang di Tokyo lawan Takaichi — aksi 19 Nov malam.
- Sanksi AS terhadap Comancheros & 'Ndrangheta — pernyataan State Dept 19 Nov.
- Seruan 4 negara soal bantuan Gaza — pernyataan bersama 15/16 Nov.
- Anthropic masuk indeks MSCI/FTSE — diumumkan Kamis 19 Nov.
- IDFA Best Film "The Year of the Ghost" — menang Kamis 19 Nov.
- Kenya: pasien Ebola terakhir pulang — 11 Nov.
- Panel DPR AS: 880.000 chip AI untuk China — dirilis Kamis 19 Nov.
- Meta meninjau target net-zero 2030 — laporan keberlanjutan Kamis 19 Nov.
- Gemini "computer use" untuk Mac — diluncurkan 19 Nov.
- Telepon wartawan disita di Air Force One — Kamis 19 Nov (Shenzhen).
- Israel: Herzog menunjuk Eisenkot — mandat diberikan 8–9 Nov.
- US existing-home sales Oktober — dirilis 12 Nov.
- Hasil ONS retail sales Inggris Oktober — tidak ditemukan angka aktualnya
  di hasil pencarian (hanya prakiraan); tidak dipakai.

## Perubahan teknis

- `build_image.py`: 6 entri ditambahkan ke `ALSO` (43–48); grid "Also"
  diubah dari 3 kolom × 9 baris (font 10, baris 29px) menjadi 3 kolom ×
  11 baris (font 9, baris 23px) agar 32 item muat; header "48 STORIES";
  legenda peta "Dots: stories 17–48"; tally region diperbarui; footer
  sumber ditambah USGS + Formula 1.
- `README.md`: 42 → 48 cerita, 26 → 32 cerita "Also", dots 17–48,
  sumber ditambah USGS + Formula 1. Tiga badge make.fun + link bounty
  tetap di atas, tidak berubah.
- `main.py`: HANYA docstring (42 → 48); perilaku tidak berubah —
  tetap menyalin entry.png, stdlib only (os, shutil), offline.

## Verifikasi

- `main.py` dijalankan 2× (MAKEFUN_OUTPUT_DIR berbeda): kedua output
  byte-identical dengan entry.png (SHA-256 sama, di atas).
- `build_image.py` dijalankan ulang: SHA-256 entry.png sama (build
  deterministik).
- Clean checkout: repo di-clone dari GitHub ke direktori baru, `main.py`
  dijalankan di sana — output byte-identical (SHA-256 sama).
- Poster dicek visual: daftar "Also" 32 item terbaca penuh, tidak ada
  teks terpotong atau tumpang tindih dengan kotak DATE CHECK; pin/dot
  peta baru tampil (Las Vegas, Beijing, Tokyo, Seoul, Brussels,
  Loyalty Is.).

## Commit

- Commit revisi: (diisi setelah commit)
