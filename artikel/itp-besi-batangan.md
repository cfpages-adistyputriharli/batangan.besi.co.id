---
article_id: BESB-12-A02
title: "ITP Material dan Proses Besi Batangan"
slug: "itp-besi-batangan"
description: "Panduan menyusun ITP besi batangan dari penerimaan material hingga pemeriksaan proses, NCR, dan pelepasan"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-05-27"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BESB-12
primary_intent: "Build QA plan"
reader_community: "Besi.co.id"
reader_address: "Teman Besi.co.id"
final_route: "/artikel/itp-besi-batangan.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/78322.html"
  - "https://www.iso.org/standard/72529.html"
  - "https://www.iso.org/standard/89449.html"
  - "https://www.iso.org/standard/53736.html"
  - "https://www.iso.org/standard/66912.html"
  - "https://www.iso.org/standard/72532.html"
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

# ITP Material dan Proses Besi Batangan

Halo, Teman Besi.co.id! ITP (Inspection and Test Plan) untuk besi batangan bukan sekadar daftar pengujian atau kolom tanda tangan. Dokumen ini adalah peta kendali: aktivitas apa yang diperiksa, karakteristik apa yang harus dibuktikan, sumber kriterianya, metode dan frekuensinya, siapa yang bertanggung jawab, kapan pekerjaan harus berhenti untuk persetujuan, serta bagaimana NCR dan pelepasan dicatat.

Jawaban singkatnya: susun ITP mengikuti aliran material dari peninjauan pesanan, penerimaan, penyimpanan, fabrikasi, sampai pelepasan. Setiap baris harus menunjuk ke spesifikasi atau dokumen kontrak yang disetujui sebagai pemilik kriteria. Standar metode seperti ISO 6892-1 untuk uji tarik dan ISO 377 untuk pengambilan contoh membantu menjelaskan cara memperoleh hasil, tetapi tidak otomatis menetapkan bahwa suatu batang diterima ([ISO 6892-1:2019](https://www.iso.org/standard/78322.html), [ISO 377:2017](https://www.iso.org/standard/72529.html)). Jika edisi produk, rencana sampling, atau aturan release belum disahkan, tandai `[NEEDS GATE-01/GATE-04: spesifikasi produk dan aturan penerimaan proyek]`.

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

Ilustrasi umum dari aset lokal, bukan dokumentasi proyek tertentu.

## Jawaban singkat dan salah paham utama

Kesalahan paling berbahaya adalah menganggap sertifikat pabrik atau satu hasil uji sudah cukup untuk mewakili seluruh stok. Hasil harus tetap terhubung dengan identitas heat/batch, asal dan lokasi pengambilan contoh, orientasi dan preparasi benda uji, metode, kondisi pengujian, satuan, serta penandaan fisik produk. ISO 377 dan amendemennya membahas contoh serta benda uji; keduanya tidak menggantikan spesifikasi material yang menentukan nilai dan keputusan penerimaan ([ISO 377:2017/Amd 1:2025](https://www.iso.org/standard/89449.html)).

Karena itu ITP perlu membedakan tiga hal. Pertama, verifikasi dokumen dan identitas. Kedua, pemeriksaan atau pengujian karakteristik. Ketiga, keputusan status: diterima, ditahan, ditolak, atau dilepas dengan disposisi yang disetujui. Teman Besi.co.id, bila salah satu hubungan identitas itu putus, status material sebaiknya “hold” sampai rekonsiliasi selesai—bukan langsung dianggap sesuai.

## Definisi dan batas objek

Dalam artikel ini, “material” berarti besi batangan yang datang dan akan dipakai; “proses” mencakup penerimaan, pemindahan, penyimpanan, pemotongan, pembengkokan, penandaan ulang bila diizinkan, dan pemeriksaan sebelum diserahkan. ITP mengatur bukti dan titik keputusan, bukan menggantikan gambar kerja, spesifikasi pembelian, prosedur fabrikasi, atau persetujuan engineer.

Kolom “criterion source” harus menunjuk dokumen yang benar-benar mengatur produk dan pekerjaan: spesifikasi proyek, purchase order, gambar, prosedur yang disetujui, atau standar produk yang disebut kontrak. Jangan menyalin angka dari ringkasan standar tanpa memeriksa teks penuh dan edisi yang berlaku. Jika sumber itu belum tersedia, tulis `[NEEDS GATE-01: criterion source disahkan]` di baris terkait.

## Cara kerjanya

Mulailah dengan memecah aliran kerja menjadi aktivitas yang bisa diamati. Untuk setiap aktivitas, isi paling tidak unsur berikut: karakteristik, sumber kriteria, metode, frekuensi atau ukuran lot, penanggung jawab, pihak yang diberi tahu, titik hold/witness, rekaman, jalur NCR, dan syarat release.

Contoh urutan yang aman:

1. **Sebelum pembelian dan kedatangan.** QA meninjau pesanan terhadap spesifikasi, ukuran, grade, toleransi, kebutuhan sertifikat, dan aturan identifikasi. Status dokumen pemasok dicatat sebelum material dikirim.
2. **Penerimaan.** QC mencocokkan packing list, sertifikat inspeksi, produsen, heat/batch, ukuran, kuantitas, dan marking pada batang. Pemeriksaan visual mencari kondisi yang dilarang oleh spesifikasi, tanpa menyimpulkan cacat hanya dari foto atau nama dokumen. Material yang identitasnya belum cocok masuk status hold.
3. **Pengambilan contoh dan pengujian.** Rencana menetapkan populasi/lot, cara memilih contoh, identitas contoh, laboratorium, metode, dan aturan keputusan. ISO 2859-1 dan ISO 28590 menyediakan kerangka sampling atribut, tetapi AQL, ukuran sampel, aturan switching, dan extent uji harus berasal dari standar produk serta persetujuan proyek ([ISO 2859-1:2026](https://www.iso.org/standard/85464.html), [ISO 28590:2017](https://www.iso.org/standard/64622.html)). Tandai `[NEEDS GATE-04: lot, frekuensi, ukuran sampel, dan decision rule]` bila belum ditetapkan.
4. **Penyimpanan dan fabrikasi.** Operator menjaga pemisahan heat/lot dan label yang dapat ditelusuri. QC memeriksa dimensi, panjang, bentuk, dan kesesuaian proses terhadap gambar/prosedur yang disetujui. Perubahan atau pencampuran identitas memerlukan persetujuan tertulis, bukan koreksi label sepihak.
5. **Pra-pelepasan.** QA menutup checklist, merekonsiliasi hasil dengan item material, memeriksa NCR terbuka, dan memastikan paket dossier lengkap. Pelepasan hanya dilakukan oleh pihak berwenang yang ditetapkan dalam ITP.

Bedakan **hold point** dan **witness point**. Hold berarti aktivitas berikutnya tidak boleh berjalan sebelum pihak yang ditentukan memberi release. Witness memberi kesempatan hadir atau menyaksikan; bila pihak itu tidak hadir, aturan kontrak harus menjelaskan apakah pekerjaan boleh berlanjut dan bukti apa yang wajib disimpan. Jangan mengubah witness menjadi hold, atau sebaliknya, hanya untuk mempercepat tanda tangan.

Untuk laboratorium, periksa kompetensi dan ruang lingkup akreditasi yang relevan dengan metode dan laporan. ISO/IEC 17025 membantu menilai kompetensi laboratorium, tetapi akreditasi itu sendiri bukan bukti bahwa satu batang tertentu memenuhi spesifikasi ([ISO/IEC 17025:2017](https://www.iso.org/standard/66912.html)). Rekonsiliasi dokumen inspeksi dengan pesanan, produsen, produk, heat/batch, dimensi, pengujian, dan marking mengikuti prinsip peninjauan dokumen inspeksi ([ISO 10474:2013](https://www.iso.org/standard/53736.html)).

## Faktor yang mengubah hasil

Beberapa kondisi dapat mengubah isi atau frekuensi ITP:

- **Sumber kriteria.** Grade, toleransi, dan karakteristik wajib mengikuti spesifikasi produk/kontrak yang disetujui. Status “berlaku” pada katalog standar tidak cukup untuk memilih edisi atau membuktikan kewajiban.
- **Identitas dan segregasi.** Batang dengan heat berbeda, pemasok berbeda, atau status berbeda tidak boleh diperlakukan sebagai satu lot tanpa aturan yang terdokumentasi. Jika ada klaim asal atau keberlanjutan, tetapkan dulu model chain of custody—segregasi fisik, mass balance, atau administratif—beserta batas sistem dan catatan transfer. ISO 22095 adalah kerangka umum, bukan bukti klaim baja tertentu ([ISO 22095:2020](https://www.iso.org/standard/72532.html)).
- **Perubahan proses.** Pemotongan, pembengkokan, pemanasan, atau perbaikan dapat mengubah titik inspeksi dan memicu pemeriksaan ulang. Prosedur yang disetujui harus menjawab kapan material harus ditahan.
- **Kondisi bukti.** Sertifikat tanpa rantai identitas, laporan tanpa metode yang jelas, atau hasil dari luar ruang lingkup laboratorium tidak boleh diberi bobot sama dengan bukti lengkap. Minta klarifikasi dan catat statusnya.
- **Kapasitas pengawasan.** Ketersediaan inspector, saksi, dan laboratorium memengaruhi jadwal, tetapi tidak boleh menjadi alasan menghapus karakteristik kritis. Bila metode atau keputusan belum dapat dijalankan, eskalasi ke `[NEEDS GATE-08: competent technical review dan disposition]`.

Jika Anda masih menyusun daftar pemasok, gunakan halaman [penyedia besi batangan mutu S45C di Yogyakarta](/jual-as-s45c-yogyakarta) hanya sebagai titik kontak komersial; verifikasi teknis dan dokumen tetap mengikuti ITP proyek. Untuk pilihan material lain, [penyedia besi batangan ST42 di Yogyakarta](/jual-as-st42-yogyakarta) juga bukan pengganti pemeriksaan penerimaan.

## Contoh keputusan praktis

Gunakan tabel berikut sebagai kerangka pengisian, bukan sebagai nilai penerimaan siap pakai.

| Aktivitas | Karakteristik/bukti | Metode & frekuensi | Tanggung jawab | Titik keputusan & rekaman |
|---|---|---|---|---|
| Review pesanan | Grade, ukuran, dokumen yang dipersyaratkan | Review dokumen sebelum order | Procurement, QA | Hold sebelum order; approved submittal |
| Penerimaan lot | Marking, heat/batch, dimensi, jumlah, kondisi | Pemeriksaan tiap lot sesuai spesifikasi | QC penerima | Hold bila identitas tidak cocok; receiving report |
| Uji material | Properti yang diwajibkan spesifikasi | Metode standar yang dirujuk; sampling proyek | Laboratorium & QA | Witness/hold sesuai ITP; laporan tertaut ke lot |
| Fabrikasi | Bentuk, panjang, toleransi, traceability | Inspeksi proses dan akhir sesuai prosedur | Supervisor & QC | NCR bila menyimpang; checklist fabrikasi |
| Release | Kelengkapan dossier dan NCR | Review paket sebelum serah terima | QA/engineer berwenang | Release tertulis; material status log |

Misalnya sertifikat menyebut heat 123, tetapi marking fisik pada bundel tidak terbaca. Keputusan yang dapat dipertanggungjawabkan adalah menahan bundel, mencari bukti penghubung yang sah, lalu meminta persetujuan teknis bila identitas tidak dapat dipulihkan. Jangan mengganti heat dengan asumsi bahwa ukuran dan tampilan sama. Sebaliknya, bila semua identitas cocok tetapi hasil uji berada di luar kriteria, buka NCR dan ikuti disposition yang disetujui; jangan mengedit angka laporan.

## Kesalahan umum dan cara memeriksanya

**“Satu sertifikat untuk semua.”** Periksa apakah dokumen memuat identitas produk, heat/batch, dimensi, pengujian, dan hubungan ke lot yang datang. ISO 10474 menekankan perlunya rekonsiliasi informasi tersebut; detail jenis dokumen dan tanda tangan tetap mengikuti pesanan serta edisi standar yang disetujui.

**“Sampling berarti ambil satu batang.”** Tanyakan definisi lot, dasar pemilihan, jumlah, karakteristik, dan decision rule. Tanpa itu, satu hasil hanya menggambarkan satu contoh, bukan keputusan seluruh populasi.

**“Laboratorium terakreditasi pasti membuat material lulus.”** Verifikasi scope, metode, otorisasi laporan, dan chain of identity. Kompetensi laboratorium meningkatkan keandalan proses ukur, bukan mengubah kriteria proyek.

**“NCR ditutup dengan tanda tangan.”** Pastikan ada deskripsi penyimpangan, material terdampak, containment, akar masalah bila diminta, tindakan koreksi, bukti verifikasi, dan persetujuan disposition. Status release harus mengikuti penutupan yang disyaratkan, bukan sekadar tanggal.

**“Witness boleh dihapus karena jadwal.”** Cek matriks ITP dan kontrak: siapa yang harus diberi notifikasi, tenggat, bukti ketidakhadiran, serta kewenangan melanjutkan. Perubahan ITP harus dikendalikan revisinya.

## Jalan pintas yang sering dipilih

Jalan pintas yang tampak efisien adalah menyalin template ITP lama lalu mengganti nama proyek. Cara ini gagal ketika grade, edisi standar, model sampling, atau batas tanggung jawab berbeda. Template boleh menjadi kerangka kolom, tetapi setiap baris harus ditautkan ulang ke spesifikasi dan aliran material proyek ini. Sobat Besi.co.id, luangkan satu rapat singkat untuk mengunci criterion source, lot, hold/witness, dan pemilik release sebelum material tiba; biaya koordinasinya lebih kecil daripada menelusuri stok yang sudah tercampur.

## Kesimpulan dan langkah berikutnya

ITP material dan proses besi batangan yang baik memetakan perjalanan setiap lot: aktivitas, karakteristik, sumber kriteria, metode, frekuensi, penanggung jawab, hold/witness, rekaman, NCR, dan release. Metode ISO membantu cara mengukur; spesifikasi produk dan persetujuan proyek tetap menentukan apa yang diterima.

Langkah berikutnya adalah minta tim proyek mengesahkan empat hal yang belum boleh diasumsikan: sumber kriteria, aturan identitas/lot, rencana sampling dan decision rule, serta kewenangan disposition (`[NEEDS GATE-01/GATE-04/GATE-08]`). Setelah itu, tautkan setiap laporan dan marking ke material status log, tutup NCR dengan bukti verifikasi, lalu minta technical review sebelum release akhir. Aturan operasionalnya sederhana: jika identitas, kriteria, atau kewenangan keputusan belum jelas, tahan material dan eskalasikan—jangan menebak.
