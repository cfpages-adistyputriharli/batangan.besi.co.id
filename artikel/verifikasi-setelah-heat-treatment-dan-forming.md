---
article_id: BESB-09-A06
title: "Verifikasi setelah Heat Treatment dan Forming"
slug: "verifikasi-setelah-heat-treatment-dan-forming"
description: "Panduan QA menautkan identitas, rekaman proses, ukuran, uji sifat, permukaan, retak, dan ketertelusuran sebelum dinyatakan boleh keluar"
writing_contract_version: "native-id-v2"
status: draft
publication_date: "2026-04-02"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BESB-09
primary_intent: "Plan release tests"
reader_community: "Besi.co.id"
reader_address: "Teman Besi.co.id"
final_route: "/artikel/verifikasi-setelah-heat-treatment-dan-forming.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/78322.html"
  - "https://www.iso.org/standard/72529.html"
  - "https://www.iso.org/standard/89449.html"
  - "https://www.iso.org/standard/60321.html"
  - "https://www.iso.org/standard/87851.html"
  - "https://www.iso.org/standard/86032.html"
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

# Verifikasi setelah Heat Treatment dan Forming

Halo, Teman Besi.co.id! Batangan yang baru keluar dari heat treatment dan forming belum otomatis siap dirilis hanya karena bentuknya rapi atau satu angka hardness terlihat sesuai. Keputusan release harus menghubungkan identitas material, rekaman proses, ukuran akhir, hasil uji, kondisi permukaan, dan ketertelusuran ke spesifikasi yang disetujui BESB-12-A02.

Jawaban singkatnya: tahan material bila salah satu mata rantai bukti itu putus. Cocokkan heat/lot dan nomor batch, verifikasi bahwa siklus treatment serta forming tercatat, lalu lakukan pemeriksaan dimensi, kekerasan atau mekanik sesuai rencana sampling dan spesifikasi. Periksa juga permukaan, dekarburisasi (decarburization), scale, dan retak. Nilai penerimaan, kelas toleransi, metode ukur, serta keputusan rework tetap harus ditetapkan oleh dokumen proyek dan peninjau kompeten. **[NEEDS GATE-01: spesifikasi BESB-12-A02, sampling plan, dan kriteria release harus dikonfirmasi.]**

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

Gambar ini adalah ilustrasi umum dari aset lokal dan bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

Verifikasi pascaproses adalah pemeriksaan terhadap batangan pada kondisi setelah perlakuan panas dan pembentukan, bukan penilaian umum atas seluruh kemampuan material. Heat treatment mengubah kondisi metalurgi melalui siklus pemanasan dan pendinginan; forming mengubah geometri dan dapat meninggalkan tegangan sisa atau cacat lokal. Karena itu, sertifikat bahan awal saja tidak menutup kebutuhan pemeriksaan akhir.

Batas artikel ini adalah kriteria release dalam spesifikasi BESB-12-A02. Ia tidak menetapkan komposisi baru, menggantikan drawing, atau menyatakan batangan aman untuk struktur tertentu. Standar uji seperti ISO 6892-1 menjelaskan cara pengujian tarik pada temperatur ruang, sedangkan ISO 377 dan amendemennya membahas pemilihan serta penyiapan sampel. Keduanya membantu menghasilkan data yang dapat dibandingkan, tetapi nilai lulus/gagal tetap berasal dari spesifikasi produk dan rencana inspeksi yang disetujui ([ISO 6892-1](https://www.iso.org/standard/78322.html), [ISO 377](https://www.iso.org/standard/72529.html), [amendemen ISO 377](https://www.iso.org/standard/89449.html)).

## Cara kerjanya

Mulailah dari identitas. Salin nomor heat, ukuran awal, lot, dan nomor batch ke lembar penelusuran (traveler) atau catatan inspeksi. Pastikan label fisik, sertifikat bahan, rekaman tungku (furnace), dan catatan forming menunjuk ke material yang sama. Bila satu bundel tercampur, hentikan pelepasan dan pisahkan berdasarkan identitas yang dapat dibuktikan.

Berikutnya, cocokkan rekaman proses: prosedur treatment yang disetujui, waktu dan temperatur aktual, media pendingin, urutan forming, serta setiap straightening atau koreksi. Rekaman ini bukan bukti bahwa hasil pasti memenuhi syarat, tetapi menjadi dasar untuk menentukan lokasi pemeriksaan dan menelusuri penyimpangan.

Lakukan pemeriksaan dimensi setelah material berada pada kondisi ukur yang ditetapkan. Ukur diameter atau sisi, panjang, kelurusan, ovalitas, dan fitur forming yang dipersyaratkan pada drawing. Gunakan alat terkalibrasi dan catat lokasi serta orientasi pengukuran. ISO 9013 dan amendemennya dapat menjadi rujukan untuk kualitas thermal cut, sementara ISO 13920 membahas toleransi umum konstruksi las; keduanya tidak otomatis menjadi toleransi universal untuk setiap bar atau bend ([ISO 9013](https://www.iso.org/standard/60321.html), [amendemen ISO 9013](https://www.iso.org/standard/87851.html), [ISO 13920](https://www.iso.org/standard/86032.html)).

Setelah dimensi, ambil sampel untuk hardness dan/atau uji mekanik sesuai sampling plan. Catat posisi sampel, orientasi, kondisi permukaan, metode, satuan, dan identitas heat. Laporan yang hanya memuat angka tanpa asal spesimen tidak cukup untuk menyimpulkan kesesuaian seluruh lot. **[NEEDS GATE-02: laboratorium, metode, lokasi spesimen, dan rencana sampling harus disetujui sebelum hasil dipakai untuk release.]**

Terakhir, lakukan inspeksi visual dan pemeriksaan tak merusak (NDE) bila diwajibkan: cari lipatan, laps, gouge, bekas overheating, kerak oksida (scale) yang tidak terangkat, area dekarburisasi, dan indikasi retak. Bila indikasi tidak dapat diputuskan secara visual, tahan lot untuk metode pemeriksaan yang ditentukan prosedur. Jangan menghapus indikasi dengan grinding sebelum evaluator menyetujui disposisinya.

## Faktor yang mengubah hasil

Ketebalan dan ukuran penampang memengaruhi respons pendinginan; lokasi di dalam furnace atau bundel dapat menghasilkan kondisi berbeda. Urutan forming, radius, gaya, pelumasan, dan koreksi setelah treatment juga memengaruhi dimensi dan kemungkinan retak.

Kondisi permukaan harus dibaca bersama proses. Scale atau oksida dapat menutupi retak dangkal; dekarburisasi mengubah lapisan permukaan sehingga hasil hardness dekat permukaan mungkin tidak mewakili inti. Metode pembersihan, kedalaman pengukuran, dan kriteria indikasi harus mengikuti prosedur yang disetujui, bukan kebiasaan operator.

Faktor bukti sama pentingnya dengan faktor fisik. Alat ukur tanpa status kalibrasi, data logger furnace tanpa time stamp, atau formulir yang tidak menautkan sampel ke heat membuat hasil sulit dipertahankan saat audit. Kawan Besi.co.id, anggap setiap kolom identitas sebagai pengaman keputusan, bukan administrasi belaka.

## Contoh keputusan praktis

Gunakan matriks ini sebagai pemicu keputusan, bukan pengganti BESB-12-A02:

| Temuan | Tindakan sementara | Bukti yang harus dilengkapi |
|---|---|---|
| Identitas heat dan rekaman proses lengkap; dimensi sesuai drawing | Lanjutkan uji akhir dan review QA | Laporan ukur, status alat, tanda tangan pemeriksa |
| Hardness memenuhi target internal, tetapi asal spesimen tidak jelas | Tahan lot | Heat map, lokasi/orientasi sampel, metode dan sampling plan |
| Ada indikasi retak atau lipatan | Isolasi dan hentikan release | Marking, NDE sesuai prosedur, keputusan engineering |
| Ukuran melewati drawing setelah forming | Jangan mengandalkan straightening informal | Prosedur koreksi dan pemeriksaan ulang |
| Scale berat menutupi permukaan | Bersihkan sesuai prosedur lalu inspeksi ulang | Metode pembersihan dan catatan hasil |

Misalnya, satu hasil tarik berada di atas nilai minimum, tetapi nomor heat pada kupon berbeda dari bundel. Angka itu tidak mewakili bundel tersebut; statusnya tetap hold sampai identitas dipulihkan atau pengujian ulang disetujui. Teman Besi.co.id, keputusan konservatif ini melindungi ketertelusuran tanpa menyimpulkan cacat material yang belum terbukti.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah melepas berdasarkan tampilan. Permukaan mengilap tidak membuktikan tidak adanya retak bawah permukaan atau dekarburisasi. Tambahkan pemeriksaan terarah dan catat area yang diperiksa.

Kesalahan kedua adalah memakai satu angka hardness sebagai pengganti semua verifikasi. Tanyakan: dari heat mana sampel berasal, di mana lokasinya, bagaimana preparasinya, dan apakah metode serta alatnya sesuai prosedur? Untuk uji mekanik, pastikan laporan menyebut kondisi spesimen dan satuan, sebagaimana prinsip identitas sampel dalam ISO 377 dan metode ISO 6892-1.

Kesalahan ketiga adalah menerapkan toleransi umum tanpa melihat drawing. Toleransi harus ditautkan ke fungsi, ukuran, proses, dan cara ukur. Jika drawing atau prosedur belum menetapkan kelasnya, jangan mengisi kekosongan dengan angka kebiasaan bengkel.

Kesalahan keempat adalah mencampur lot saat rework. Pertahankan label, buat catatan perpindahan, dan ulangi pemeriksaan yang terdampak. **[NEEDS GATE-04: disposisi nonconforming, rework, dan kebutuhan uji ulang memerlukan persetujuan engineering/QA proyek.]**

## Jalan pintas yang sering dipilih

Jalan pintas yang paling menggoda adalah “uji satu batang, lalu lepas semua”. Cara itu gagal ketika variasi furnace, posisi bundel, ukuran penampang, atau forming membuat satu sampel tidak mewakili lot. Alternatif yang lebih andal adalah menerapkan sampling plan BESB-12-A02, menyimpan peta sampel, dan menaikkan cakupan bila ada hasil meragukan atau perubahan proses.

## Penutup

Verifikasi setelah heat treatment dan forming berarti mengikat identitas, rekaman proses, dimensi, sifat mekanik, kondisi permukaan, dan keputusan ketidaksesuaian dalam satu jejak bukti. Jangan nyatakan release hanya dari bentuk atau satu nilai pengujian. Sebelum menandatangani, minta spesifikasi BESB-12-A02, drawing, rekaman proses, status kalibrasi, laporan laboratorium, serta disposisi untuk setiap indikasi.

Langkah berikutnya: QA menyusun checklist lot, menahan material yang identitas atau kriterianya belum lengkap, lalu meminta review teknis kompeten untuk setiap gate terbuka. Jika perlu menyiapkan material sesuai spesifikasi yang telah disetujui, Anda dapat melihat [baja S45C di Yogyakarta](/jual-as-s45c-yogyakarta) atau [baja ST42 di Yogyakarta](/jual-as-st42-yogyakarta) sebagai rujukan pilihan material.

Aturan operasionalnya sederhana: bila bukti tidak dapat ditautkan ke heat dan persyaratan yang berlaku, status tetap ditahan—bukan lulus dengan asumsi.
