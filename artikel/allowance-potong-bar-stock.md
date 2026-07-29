---
article_id: BESB-03-A05
title: "Cutting Allowance, Kerf, Remnant, dan Waste"
slug: "allowance-potong-bar-stock"
description: "Memperhitungkan panjang stok, kerf, facing, potongan uji, cacat, remnant, dan ketertelusuran"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-27"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BESB-03
primary_intent: "Plan takeoff"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/allowance-potong-bar-stock.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/60321.html"
  - "https://www.iso.org/standard/87851.html"
  - "https://www.iso.org/standard/86032.html"
  - "https://www.iso.org/standard/85464.html"
  - "https://www.iso.org/standard/64622.html"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-001`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `harga besi as` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Cutting Allowance, Kerf, Remnant, dan Waste

Halo, Kawan Besi.co.id! Jangan memesan bar stock hanya dengan menjumlahkan panjang komponen pada gambar. Jumlah itu belum memperhitungkan material yang hilang oleh sayatan (kerf), ujung yang harus diratakan (facing), potongan percobaan, cacat yang harus diisolasi, dan sisa pendek yang tidak lagi berguna. Cara aman adalah membuat rencana potong dari panjang stok aktual, lalu memisahkan kebutuhan komponen, allowance, remnant, dan waste.

Jawaban singkatnya: buat satu baris per batang stok, hitung urutan potong dan total panjang yang benar-benar termakan, kemudian cocokkan dengan kebijakan sisa dan bukti identitas material. Nilai allowance bukan persentase baku. Ia berubah menurut proses, tebal material, ketelitian gambar, kondisi ujung, serta apakah sisa dapat dipakai kembali. Parameter potong dan toleransinya harus disetujui lewat gambar/prosedur proyek; [NEEDS GATE-01: verifikasi allowance dan toleransi pada dokumen proyek yang berlaku].

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

*Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.*

Gambar ini hanya ilustrasi umum untuk membantu orientasi pembaca, bukan dokumentasi proyek atau bukti kondisi material tertentu.

## Definisi dan batas objek

**Cutting allowance** adalah panjang tambahan yang sengaja disediakan sebelum komponen mencapai ukuran akhir. **Kerf** ialah lebar material yang berubah menjadi celah atau serbuk akibat alat potong; kerf muncul pada setiap sayatan dan tidak menjadi bagian dari komponen. **Facing allowance** adalah tambahan untuk merapikan atau mengikis ujung sehingga panjang akhir baru diukur setelah proses itu. **Trial allowance** menutup kebutuhan potongan uji saat operator menyetel mesin atau prosedur. **Defect allowance** mengantisipasi bagian yang harus ditolak karena cacat yang ditemukan saat inspeksi. **Remnant** adalah sisa yang masih dapat diidentifikasi dan dipakai; **waste** adalah sisa yang tidak ekonomis atau tidak memenuhi syarat untuk pekerjaan ini.

Batas artikel ini adalah perencanaan takeoff dan pengendalian sisa, bukan instruksi mengoperasikan mesin. Urutan keselamatan, parameter panas, pemilihan mata potong, dan teknik eksekusi termasuk prosedur pemotongan tersendiri. Standar ISO 9013 membahas kualitas dan klasifikasi potongan termal, termasuk edisi amandemennya; halaman standar hanya membantu mengidentifikasi dokumen, bukan memberi izin memakai satu kelas toleransi untuk semua pekerjaan ([ISO 9013:2017](https://www.iso.org/standard/60321.html), [Amd 1:2024](https://www.iso.org/standard/87851.html)).

## Cara kerjanya

Mulailah dari daftar potong (cut list) yang memuat nomor komponen, profil, grade, panjang bersih, jumlah, dan toleransi. Kelompokkan item yang benar-benar boleh berasal dari satu batang: profil dan grade berbeda tidak boleh dicampur hanya demi menghemat sisa. Catat juga panjang stok yang dijanjikan pemasok sebagai panjang nominal atau panjang aktual; keduanya bukan hal yang sama.

Jika grade pada daftar potong belum jelas, pisahkan kebutuhan sebelum meminta penawaran—misalnya [besi AS S45C di Yogyakarta](/jual-as-s45c-yogyakarta) dan [besi ST42 di Yogyakarta](/jual-as-st42-yogyakarta) tidak boleh diperlakukan sebagai satu kelompok hanya karena sama-sama berbentuk batang.

Untuk satu batang, rumus kerja sederhananya:

`panjang termakan = Σ panjang bersih komponen + (jumlah sayatan × kerf) + allowance facing + allowance trial + allowance defect`

Bandingkan panjang termakan dengan panjang stok yang dapat dipakai. Jika ada trim di kedua ujung, masukkan trim itu sebagai facing, bukan kerf. Jika komponen dipotong dari sisa batang, buat baris stok baru agar identitas dan panjang sisanya tetap terlacak.

Urutan potong memengaruhi hasil. Letakkan komponen terpanjang lebih dulu, sisakan bagian yang cukup untuk penjepitan dan facing, lalu susun potongan lebih pendek di ruang yang tersisa. Setelah setiap sayatan, operator atau pemeriksa mengukur dan menandai hasil aktual. Catatan minimum meliputi nomor heat/lot atau tanda material yang tersedia, nomor batang asal, tanggal, ukuran sebelum dan sesudah potong, status komponen, serta panjang remnant.

Kerf tidak boleh ditebak dari katalog alat bila keputusan pembelian bergantung padanya. Ambil nilai dari prosedur atau uji yang disetujui untuk kombinasi mesin, material, dan ketebalan yang dipakai. Bila data itu belum ada, gunakan asumsi konservatif untuk perencanaan sementara dan tandai untuk konfirmasi; jangan mengubah asumsi menjadi jaminan hasil.

## Faktor yang mengubah hasil

Pertama, **geometri stok**. Ujung yang tidak siku, bengkok, atau terkorosi dapat memaksa trim lebih panjang. Panjang aktual tiap batang juga dapat berbeda dari label. Kedua, **persyaratan fungsi**. Komponen yang akan disambung atau dimesin mungkin memerlukan tambahan berbeda dari komponen yang langsung dipakai setelah potong. General tolerances pada konstruksi las tidak otomatis berlaku untuk seluruh proses atau semua dimensi; kecocokan harus ditautkan ke gambar dan metode ukur yang disetujui ([ISO 13920:2023](https://www.iso.org/standard/86032.html)).

Ketiga, **proses dan urutan kerja**. Sayatan yang lebih banyak menaikkan total kerf. Potongan uji diperlukan bila setelan belum tervalidasi. Sebaliknya, menggabungkan beberapa item dalam satu program mungkin mengurangi trial, tetapi hanya jika orientasi, penjepitan, dan akses inspeksi tetap memenuhi prosedur.

Keempat, **kualitas dan cacat**. Jangan memakai allowance defect untuk menutupi material yang sejak penerimaan sudah tidak sesuai. Pisahkan temuan penerimaan dari cacat yang muncul saat proses, lalu buka nonconformance bila diperlukan. Untuk keputusan lot, rencana inspeksi harus mendefinisikan populasi, identitas sampel, metode, kriteria, keputusan, dan rekaman; ukuran sampel atau AQL tidak boleh diambil dari tebakan ([ISO 2859-1](https://www.iso.org/standard/85464.html), [ISO 28590](https://www.iso.org/standard/64622.html)).

Terakhir, **remnant dan traceability**. Sisa yang akan dipakai ulang harus punya label yang tahan dipindahkan: grade, heat/lot, dimensi tersisa, tanggal, dan status pemeriksaan. Sisa tanpa identitas bukan penghematan; ia menjadi risiko salah material. Jika sisa disimpan untuk pekerjaan lain, pastikan kriteria penerimaan dan kondisi penyimpanannya disepakati.

## Contoh keputusan praktis

Bayangkan satu batang dengan panjang stok yang sudah diverifikasi. Daftar potong berisi tiga komponen panjang berbeda. Anda tidak langsung membagi panjang stok dengan panjang komponen. Buat beberapa skenario urutan:

| Skenario | Yang dihitung | Keputusan |
|---|---|---|
| A | Tiga panjang bersih, tiga kerf, facing di kedua ujung | Dipakai bila total masih di bawah panjang pakai dan sisa dapat dilabeli |
| B | Urutan berbeda, jumlah kerf sama, tetapi trim ujung lebih besar | Pilih hanya jika mengurangi risiko cacat atau memudahkan inspeksi |
| C | Satu potongan uji sebelum komponen pertama | Tambahkan trial; jika tidak ada prosedur uji, tahan keputusan dan minta persetujuan |

Angka aktual untuk kerf, facing, trial, dan defect diisi dari prosedur, data uji, atau rekaman proses yang berlaku. Jangan mengisi contoh dengan angka generik lalu menggunakannya sebagai kuantitas pembelian. Jika hasil nesting menyisakan potongan di bawah panjang minimum yang ditetapkan proyek, klasifikasikan sebagai waste meskipun secara fisik masih panjang. Jika lebih panjang dan identitasnya utuh, klasifikasikan sebagai remnant dan masukkan ke inventaris.

Kawan Besi.co.id, saat membuat purchase takeoff, tampilkan setidaknya empat kolom terpisah: kebutuhan bersih, allowance proses, remnant yang bisa dikreditkan, dan waste yang tidak dikreditkan. Dengan begitu pembeli dapat membedakan “bar tambahan karena pola potong” dari “cadangan karena ketidakpastian desain”. [NEEDS GATE-04: tetapkan aturan kredit remnant, panjang minimum, dan otorisasi penggunaan ulang bersama engineering/procurement].

## Kesalahan umum dan cara memeriksanya

**Menggunakan satu persentase waste untuk semua profil.** Persentase tidak menangkap jumlah sayatan, panjang stok, atau cacat ujung. Periksa kembali dengan simulasi batang per batang.

**Menganggap kerf sama dengan allowance total.** Kerf hanya celah tiap sayatan; facing dan trial adalah pos lain. Tandai jumlah sayatan pada cut list.

**Mencampur sisa tanpa label.** Minta foto/rekaman label sebelum sisa dipindahkan, lalu cocokkan dengan heat/lot dan dimensi baru.

**Menghitung dari panjang nominal pemasok.** Konfirmasi basis panjang pada dokumen pembelian dan ukur sampel penerimaan sesuai ITP. Teori massa atau label ukuran bukan pengganti pemeriksaan aktual.

**Menganggap standar umum sebagai toleransi otomatis.** Sobat Besi.co.id, setiap penyimpangan yang memengaruhi sambungan atau fungsi harus kembali ke gambar, prosedur, dan metode ukur yang disetujui. Jika dokumen konflik, hentikan rilis cut list sampai penanggung jawab teknis memutuskan.

Gunakan daftar periksa sebelum pesanan dilepas:

- Semua komponen memiliki grade, profil, panjang bersih, jumlah, dan toleransi.
- Panjang stok aktual, facing, kerf, trial, dan defect dicatat terpisah.
- Urutan potong dan sisa tiap batang dapat diaudit.
- Remnant diberi identitas dan status; waste dipisahkan.
- Bukti penerimaan, inspeksi, dan nonconformance tertaut ke nomor batang.
- Asumsi yang belum disahkan ditandai untuk review, bukan disembunyikan dalam angka waste.

## Jalan pintas yang perlu diwaspadai

Shortcut yang sering dipilih adalah memesan “tambahan 5%” lalu membiarkan operator mengatur sisanya di workshop. Ini bisa gagal karena 5% tidak menjelaskan apakah tambahan tersebut menutup dua trim ujung, beberapa kerf, satu trial, atau cacat tertentu. Pada batang pendek, satu sayatan ekstra dapat lebih berarti daripada persentase itu; pada batang panjang, sisa yang tidak berlabel dapat menjadi waste administratif.

Alternatif yang lebih dapat dipertanggungjawabkan adalah membuat cut list berbasis batang, menyatakan asumsi proses, lalu meminta persetujuan ketika parameter belum tervalidasi. Gunakan data proses yang benar-benar ada dan pisahkan keputusan teknis dari kebijakan pembelian. Jika ketidakpastian memengaruhi kecukupan material atau keselamatan, [NEEDS GATE-02: minta review kompeten sebelum pemesanan atau pemotongan].

## Langkah penutup

Cutting allowance bukan angka cadangan tunggal. Hitung panjang bersih komponen, tambahkan kerf per sayatan, facing, trial, dan defect sesuai bukti proyek, lalu bedakan remnant beridentitas dari waste. Tindakan berikutnya: bekukan cut list, minta prosedur atau data uji kerf, tetapkan aturan kredit remnant, dan tautkan setiap batang ke rekaman penerimaan serta inspeksi. Untuk menyelaraskan dokumen kerja, gunakan [beranda Besi.co.id](/) sebagai titik masuk tim.

Teman Besi.co.id, bila salah satu parameter itu belum tersedia, keluarkan cut list sebagai “menunggu review”, bukan sebagai kuantitas final. Batas artikel ini adalah perencanaan; keputusan toleransi, metode potong, penerimaan, dan pelepasan material tetap mengikuti gambar, prosedur, dan persetujuan profesional yang berlaku.
