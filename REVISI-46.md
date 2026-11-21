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

- Commit revisi: `d2286b987f6b28ffcfd365be6fa9a047b2817cde` (branch `main`,
  commit sebelumnya `7b273338e700e4e26ce538d6f55b2e52af32b393`)

---

# Revisi refresh 21 Nov 2026 (Sabtu ~08:00 WIB)

Tanggal revisi: Sabtu 21 November 2026 (~08:00 WIB).
Alasan: berita telat Jumat 20 Nov (sore/malam waktu AS) masuk poster
sebelum deadline Minggu 22 Nov 2026 07:00 WIB — penutupan Wall Street,
pengumuman resmi GTA 6, rudal Rusia jatuh di Polandia, hasil ATP Finals.

## Hasil akhir

- Jumlah cerita: **48** (4 lead + 12 medium + 32 "Also on Friday") — tetap
- Ukuran entry.png: **230.006 bytes** (≤ 1 MiB), 1024×1024
- SHA-256 entry.png: `5be721a038aec22eb192c125a6cfc1c6a3561c5fd45f8e16042f4ad680c65fea`
- Tally region (geografis; ATP di Turin dihitung Europe): Europe 8 ·
  Asia 10 · Americas 14 · Africa 9 · Middle East 2 · Oceania 2 ·
  Global 3 = 48

## Cerita baru / diubah

| # | Cerita di poster | Fakta + sumber |
|---|---|---|
| 3 (lead) | Pasar: body diperbarui ke penutupan Wall Street Jumat | S&P −3,7% ke 6.910,39, Nasdaq −5,28% ke 22.617,73, Dow −1,93%; S&P dan Dow masuk koreksi −10% dari rekor. Angka Asia (Nikkei −4,5%, KOSPI −4,7%, SoftBank −14%) tetap. Sumber: AP (penutupan Jumat 20 Nov). |
| 6 (medium, baru) | GTA 6 makes $3.79bn in a day | Take-Two/Rockstar umumkan Jumat 20 Nov 2026: day-one retail sales $3,79 miliar, 32,5 juta kopi pre-release — "biggest entertainment launch in history". Angka RESMI perusahaan. Sumber: Take-Two / Rockstar. Ilustrasi baru `ill_gta` (panel gelap + "$3.79bn" + gamepad). |
| 12 (medium, baru) | Russian missiles crash in Poland | Jumat 20 Nov pagi, dua rudal Rusia + satu drone jet jatuh di Polandia tenggara saat serangan besar ke Ukraina (Kh-101 terkonfirmasi di Nowy Lipowiec ~05:30 GMT; satu lagi di Rudnik nad Sanem; puing drone di Mołodycz). Tanpa korban. PM Tusk: "intentional provocation". Sekjen NATO Rutte kecam pelanggaran wilayah udara. Sumber: Reuters; Polish govt. Ilustrasi baru `ill_poland` (jejak rudal + ledakan). |
| 10 (medium) | Alcaraz, Medvedev reach ATP semis | Alcaraz d. Cobolli 6-4, 6-1; Medvedev d. Tiafoe 6-3, 6-4 (Jumat 20 Nov). Semifinal: Alcaraz v Shelton, Zverev v Medvedev. Sumber: ATP Tour + Reuters. |
| 18 (Also) | Copenhagen: Denmark expels Russian attaché over Kyivstoner plot | Denmark usir atase pertahanan Rusia Jumat 20 Nov setelah PET ungkap plot intelijen Rusia bunuh rapper Kyivstoner (konser 25 Sep, 2 orang didakwa percobaan pembunuhan). Sumber: Reuters/DR. |
| 19 (Also) | London: Fairford plot suspects to face trial in Nov 2027 | Dua pria kasus insiden RAF Fairford ditetapkan sidang Nov 2027 oleh hakim Jumat 20 Nov. Sumber: Reuters. |
| 30 (Also) | New York: Bitcoin falls below $60,000, first time since July | Bitcoin di bawah $60.000 Jumat 20 Nov, pertama sejak Juli (terendah intraday ~$57.700–$58.800). Sumber: Reuters. |
| 31 (Also) | New York: Indian man gets 19½ years in Pannun murder plot | Nikhil Gupta divonis 235 bulan Jumat 20 Nov di pengadilan Manhattan atas plot bunuh-bayaran terhadap aktivis Sikh Pannun. Sumber: US DOJ / Reuters / AP. |
| 33 (Also) | Washington: Senate passes energy permitting bill, 62-33 | Senat AS loloskan Bipartisan American Affordability and Jobs Act 62-33 (pemungutan Kamis malam AS = 03:17 UTC Jumat 20 Nov). Sumber: NPR / Senat. |
| 34 (Also) | Washington: Trump: Iran wants a deal, 'not one I'll accept' | Trump di konferensi pers Gedung Putih Jumat 20 Nov: Iran mau deal "but not one that's acceptable to me", "real deal, not a fake deal". Sumber: AP 20 Nov 21:54 UTC. |
| 36 (Also) | Huntsville: execution takes 63 minutes; prisoner moans in pain | Eksekusi Reinaldo Dennes di Texas Kamis malam (selesai 19:07 CST = 01:07 UTC Jumat 20 Nov), 63 menit, petugas sulit cari vena. Sumber: NPR / Reuters. |
| 37 (Also) | Port Orange: record floods; St. Johns River tops 1953 mark | Banjir rekor Florida Jumat 20 Nov: Port Orange 17+ inci, St. Johns River 18,7 kaki lampaui rekor 1953, peringatan NWS. Sumber: NWS Melbourne. |
| 17, 20–29, 32, 35, 38–48 (Also) | Daftar Also diganti seluruhnya (32 item) | Item yang dipertahankan dari Also lama (tetap 20 Nov): Kyiv/Dutch embassy (#17), Taipei dollar (#21), Seoul chips (#23), Tokyo Takaichi (#25), Dhaka (#28), Washington funding cliff (#32), Cincinnati Fiona (#35), Las Vegas F1 (#38), Praia (#39), Derna (#40), Kampala (#41), Abuja (#42), Pretoria (#43), Cairo (#44), Accra (#45), Brasilia (#46), Loyalty Is. quake (#48); ditambah Taiwan short-sale cap (#22, pindahan dari medium lama #6), Samsung mobile chief (#24), Tokyo inflasi (#26), Beijing PBOC (#27), New York futures (#29), Brussels youth strike (#20, pindahan dari #47 lama), Cyclone Xavier (#47, pindahan dari medium lama #12). |

Item yang DIHAPUS dari daftar Also lama (lebih lemah/stale): Mumbai
Sensex, Tokyo Topix, Wellington Test, Hong Kong Satwik/Chirag,
Bhubaneswar hoki, New Delhi bank negara, New Delhi PUC, Antalya
"Europe tells Africa...", Antalya "COP31 talks may run past Friday
deadline" (usang — COP31 sudah ditutup, lead #4).

## DATE CHECK

- Klausa "Not yet: the COP31 final text, the ATP Finals
  semi-finalists." DIHAPUS — keduanya sudah terjadi Jumat 20 Nov.
- Ditambah 4 item 19 Nov yang ditolak pada refresh ini: Bukele's
  third-term registration, the Haiti raid (34 dead), the Trump–NYT
  ruling, the cyber chief's ouster. 7 item lama tetap ada (dipadatkan:
  "Trump-Xi-Putin summit" tanpa "and 'peace declaration'", "ICJ
  Rohingya ruling", "Anthropic's IPO debut", "Gaza scorecard",
  "Senate's 51-48 war-powers vote"). Total 11 item, tetap muat 3 baris.

## Kandidat yang DITOLAK pada refresh ini (sudah dicek tanggalnya)

- Bukele's third-term registration — daftar Kamis 19 Nov (Reuters).
- Polandia nuklir $50M — LOI 19 Nov, wawancara Dow Jones 19 Nov
  14:09 GMT.
- Haiti 34 tewas — operasi Kamis 19 Nov.
- Pilot B-2 Midnight Hammer — diterbitkan 18 Nov.
- Pentagon biaya perang Iran $48,3M — diungkap di sidang Kamis 19 Nov.
- Gugatan Trump $15M vs NYT — putusan hakim Kamis 19 Nov.
- Cairncross mundur — dilaporkan Kamis 19 Nov.
- Walmart — laporan Kamis 19 Nov.
- Kapal Senegal 4 tewas — tenggelam Rabu 18 Nov, 4 jenazah
  dikonfirmasi Kamis 19 Nov.
- Razia judi Korsel 6.310 / $116jt — diumumkan Kamis 19 Nov.
- Pengakuan Chicago temple plot — sidang Kamis 19 Nov.
- Estimasi Sensor Tower GTA 6 $2,36M — DIGANTI angka resmi Take-Two
  $3,79M (bukan estimasi).
- Krisis BBM Malawi — fitur Al Jazeera 20 Nov tapi peristiwa intinya
  16–17 Nov / krisis berbulan-bulan — tidak dipakai.
- Rencana tutup Rikers oleh Mamdani — diumumkan Jumat malam NY =
  00:01 UTC 21 Nov, di luar hari 20 Nov UTC.

## Perubahan teknis

- `build_image.py`: lead #3 body → penutupan Wall Street (src
  "Reuters; AP"); medium #6 → GTA 6 + ilustrasi baru `ill_gta`;
  medium #12 → Polandia + ilustrasi baru `ill_poland`; medium #10 →
  hasil ATP Finals; daftar `ALSO` diganti seluruhnya (32 item,
  nomor 17–48); `DATE_CHECK` diperbarui (11 item, 3 baris);
  tally → Europe 8 · Asia 10 · Americas 14 · Africa 9 · Middle East 2
  · Oceania 2 · Global 3; footer sumber + Take-Two, US DOJ;
  timeline + slot ke-7 "EVENING / GTA 6: $3.79bn record launch"
  (lebar kolom dihitung dari `len(TIMELINE)`, semua 7 event tetap
  muat 2 baris); body medium kini boleh 3 baris (`max_lines` 2 → 3)
  karena body #6 dan #12 butuh baris ketiga pada lebar kolom 159 px —
  baris medium 136 px tetap muat (head-2 + body-3 = 126 px,
  head-3 + body-2 = 129 px), jadi fakta tidak dipotong.
- `README.md`: lead pasar kini mencakup penutupan Wall Street; medium
  baru GTA 6 ($3,79 miliar, resmi Take-Two) dan rudal Polandia;
  Taiwan short-selling dan Cyclone Xavier kini di daftar Also; hasil
  ATP Finals; sumber + Take-Two dan US DOJ; timeline overnight →
  evening. Tiga badge make.fun + link bounty di atas TETAP, tidak
  diubah. Jumlah cerita tetap 48.
- `main.py`: TIDAK diubah — tetap menyalin entry.png, stdlib only,
  offline.

## Verifikasi

- `build_image.py` dijalankan: entry.png 1024×1024, 230.006 bytes
  (≤ 1 MiB), SHA-256
  `5be721a038aec22eb192c125a6cfc1c6a3561c5fd45f8e16042f4ad680c65fea`.
- `main.py` dijalankan 2× (MAKEFUN_OUTPUT_DIR berbeda): kedua output
  byte-identical dengan entry.png (SHA-256 sama).
- `build_image.py` dijalankan ulang: SHA-256 entry.png sama (build
  deterministik).
- Cek muat teks (programatik, sebelum build): DATE CHECK tepat 3
  baris; ke-32 item Also ≤ 2 baris; ke-7 slot timeline ≤ 2 baris;
  tally terhitung dari data = Europe 8 · Asia 10 · Americas 14 ·
  Africa 9 · Middle East 2 · Oceania 2 · Global 3 (total 48).
- Poster dicek visual: tidak ada teks terpotong/tumpang tindih;
  body 3 baris #6 dan #12 terbaca penuh ("...entertainment launch
  ever." / "...no injuries."); ilustrasi baru rapi ("$3.79bn" +
  gamepad; "SE POLAND" + jejak rudal); ke-32 item Also terbaca penuh;
  pin/dot peta tampil (pin 6 di New York, pin 12 di Polandia);
  kotak DATE CHECK muat 3 baris; footer sumber satu baris.
- Catatan layout (sudah ada sebelumnya, bukan akibat refresh ini):
  baris sumber kecil di bawah lead #3 dan #4 tidak tampil karena
  head 3 baris + body 3 baris memenuhi blok lead (batas y+230);
  sumbernya tetap tercatat di kode dan README.
- TIDAK di-bundle / TIDAK di-submit ke make.fun (menunggu acc bos).

## Commit

- Commit refresh: (diisi setelah push — lihat `git log`)
