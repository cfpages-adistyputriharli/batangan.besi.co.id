---
article_id: BESB-08-A06
title: "Route Card dan Traceability Proses Bar Stock"
slug: "route-card-bar-stock"
description: "Menelusuri heat ID, blank potongan, operasi, operator, inspeksi, NCR, finishing, dan serial akhir"
status: draft
publication_date: "2026-03-07"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BESB-08
primary_intent: "Maintain process records"
reader_community: "Besi.co.id"
reader_address: "Teman Besi.co.id"
final_route: "/artikel/route-card-bar-stock.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://www.iso.org/standard/78322.html"
  - "https://www.iso.org/standard/72529.html"
  - "https://www.iso.org/standard/89449.html"
  - "https://www.iso.org/standard/53736.html"
  - "https://www.iso.org/standard/66912.html"
  - "https://www.iso.org/standard/60321.html"
  - "https://www.iso.org/standard/87851.html"
---

# Route Card dan Traceability Proses Bar Stock

Halo, Teman Besi.co.id!

Route card yang baik bukan sekadar lembar tanda tangan. Ia adalah rantai identitas: heat ID dari material masuk harus dapat ditelusuri ke blank hasil potong, operasi, operator, inspeksi, NCR, finishing, sampai serial final. Untuk QA yang mengendalikan banyak part, aturan praktisnya sederhana: jangan lepaskan part ketika satu mata rantai tidak dapat dicocokkan dengan bukti fisik dan dokumen sumber.

Mulailah dari satu ID unik per batang atau bundel, lalu buat catatan perubahan status di setiap perpindahan. Sertifikat material, hasil uji, dan marking harus direkonsiliasi dengan order, produsen, produk, heat atau batch, dimensi, dan pengujian. Kerangka inspeksi dokumen [ISO 10474](https://www.iso.org/standard/53736.html) membantu menata rekonsiliasi itu, sedangkan kompetensi laboratorium perlu ditinjau terpisah melalui [ISO/IEC 17025](https://www.iso.org/standard/66912.html). [NEEDS GATE-01: tetapkan dokumen produk, aturan sampling, dan kriteria penerimaan proyek sebelum release.]

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
![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

Gambar lokal ini hanya ilustrasi umum, bukan dokumentasi proyek tertentu.

## Hasil akhir dan prasyarat

Hasil akhirnya adalah satu paket rekaman yang memungkinkan orang lain menjawab tiga pertanyaan tanpa menebak: material apa yang dipakai, pekerjaan apa yang sudah dilakukan, dan bukti apa yang mendasari statusnya. QA mengendalikan format serta review; produksi mengisi kejadian aktual; operator mengonfirmasi pekerjaan yang dilakukan; dan inspeksi mencatat hasil ukur atau observasi. Persetujuan engineering atau klien tetap mengikuti prosedur proyek—halaman ini tidak menggantikan ITP atau release.

Sebelum route card diterbitkan, siapkan nomor order, drawing dan revisinya, daftar operasi, identitas material, metode pengukuran, formulir NCR, serta aturan penamaan serial. Tentukan pula siapa yang boleh membuka, menahan, mengoreksi, dan menutup kartu. Jika sistem digital dipakai, kunci riwayat perubahan; jika kertas dipakai, gunakan koreksi yang masih memperlihatkan catatan awal dan paraf berwenang.

## Langkah 1 — tetapkan batas

Tuliskan batas proses secara eksplisit: penerimaan bar stock, pemotongan blank, machining atau proses lain yang termasuk order, inspeksi antar-operasi, finishing, lalu serial final. Cantumkan antarmuka dengan gudang, subcontractor, laboratorium, dan area karantina. ITP dan keputusan release berada di ruang lingkup dokumen proyek lain, sehingga route card hanya merekam status dan bukti yang menjadi inputnya.

Buat matriks identitas. Kolom awal memuat heat ID, nomor bundel, ukuran awal, kuantitas, lokasi penyimpanan, dan marking fisik. Setiap blank mendapat turunan ID yang tidak menghapus heat asal. Saat satu batang dibagi menjadi beberapa blank, catat hubungan induk-anak dan sisa material. Tanpa hubungan ini, hasil ukur yang tampak rapi tetap tidak membuktikan asalnya. Jika perlu membandingkan pilihan material di Yogyakarta, Anda dapat melihat [AS S45C Yogyakarta](/jual-as-s45c-yogyakarta) atau [ST42 Yogyakarta](/jual-as-st42-yogyakarta); kecocokan akhirnya tetap mengikuti drawing dan spesifikasi order.

Tentukan toleransi dan metode ukur dari drawing atau spesifikasi yang disetujui, bukan dari kebiasaan bengkel. [ISO 9013](https://www.iso.org/standard/60321.html) dan [amendemen 2024-nya](https://www.iso.org/standard/87851.html) dapat menjadi rujukan umum untuk kualitas potongan termal, tetapi kelas, rentang, dan metode ukur harus dikonfirmasi terhadap material, ketebalan, drawing, serta prosedur proyek. [NEEDS GATE-02: verifikasi edisi dokumen dan persyaratan dimensional yang benar untuk order ini.]

## Langkah 2 — kumpulkan dan cocokkan bukti

Urutkan bukti berdasarkan titik keputusan. Pada incoming, cocokkan sertifikat dengan order, heat atau batch, dimensi, dan marking pada benda. [ISO 10474](https://www.iso.org/standard/53736.html) menempatkan inspeksi dokumen dalam konteks produk dan identitasnya; nama sertifikat saja tidak cukup. Simpan salinan yang terbaca, nomor revisi, penerbit, serta tautan ke ID material internal.

Untuk hasil uji tarik, tautkan laporan ke spesimen yang benar: sumber material, orientasi atau lokasi, persiapan, metode, kondisi, satuan, dan heat atau product identity. [ISO 6892-1](https://www.iso.org/standard/78322.html) menjelaskan metode uji pada temperatur ruang, sedangkan [ISO 377](https://www.iso.org/standard/72529.html) dan [amendemen 2025-nya](https://www.iso.org/standard/89449.html) membahas pengambilan serta penyiapan spesimen. Metode uji tidak otomatis menetapkan nilai lulus; nilai dan disposisi harus berasal dari spesifikasi produk atau kontrak yang berlaku. Satu angka tanpa chain of identity bukan dasar release.

Di setiap operasi, catat tanggal dan shift, mesin atau alat, operator, instruksi kerja yang dipakai, kuantitas masuk-keluar, dan status inspeksi. Tambahkan nomor alat ukur serta status kalibrasi bila hasilnya menjadi dasar keputusan. Bila terjadi penyimpangan, buat NCR yang merujuk langsung ke ID part, operasi, bukti ukur yang tersedia, disposition, dan otoritas yang menyetujuinya. Jangan menimpa nilai lama; buat entri koreksi yang terlacak.

## Langkah 3 — jalankan urutan kerja

Urutan konseptualnya: verifikasi material dan marking, keluarkan work order beserta route card, potong dan identifikasi blank, lakukan inspeksi awal, lanjutkan operasi berikutnya, tahan part saat hasil tidak sesuai, lalu tutup kartu setelah semua bukti dan serial final cocok. Pada handoff, penerima menghitung kuantitas dan memeriksa identitas sebelum menandatangani penerimaan.

Untuk potongan termal, rekam proses dan kondisi yang relevan bagi kualitas tepi serta fungsi downstream, lalu gunakan persyaratan drawing sebagai acuan. Jangan menjadikan satu toleransi umum sebagai izin untuk semua produk. Jika ada pekerjaan panas, tautkan nomor prosedur dan catatan K3 yang berlaku; rincian kontrol harus ditetapkan oleh penilaian kompeten dan prosedur lokasi.

Teman Besi.co.id, perlakukan route card sebagai peta status, bukan buku harian. Setiap baris harus menjawab “apa yang berubah?”, “siapa yang mengonfirmasi?”, dan “bukti mana yang bisa dibuka kembali?”.

## Titik tahan dan kondisi berhenti

Hentikan aliran part dan pindahkan ke status hold bila heat ID hilang, marking fisik tidak terbaca, kuantitas tidak cocok, sertifikat tidak terkait dengan order, revisi drawing meragukan, alat ukur tidak berstatus layak, atau hasil inspeksi menyimpang. Hold juga berlaku saat NCR belum memiliki disposition yang disetujui. Jangan mengganti ID dengan label baru tanpa menjaga relasi ke catatan asal.

Jika hasil uji berasal dari laboratorium eksternal, periksa identitas penerbit, ruang lingkup kompetensi, metode yang dipakai, otorisasi laporan, dan chain of custody. Akreditasi atau kompetensi laboratorium meningkatkan kepercayaan pada proses hasil, tetapi tidak sendirian membuktikan part tertentu memenuhi spesifikasi. [NEEDS GATE-04: review laporan aktual, ruang lingkup laboratorium, dan persetujuan disposition oleh pihak kompeten.]

## Verifikasi hasil dan serah terima

Sebelum handover, QA melakukan rekonsiliasi silang: heat ID di sertifikat = material di gudang = blank dan serial final; kuantitas masuk dikurangi scrap dan rework = kuantitas keluar; setiap operasi memiliki status dan pelaksana; setiap inspeksi memiliki metode, unit, hasil, dan alat; setiap NCR tertutup atau ditahan secara resmi; finishing dan marking akhir terbaca.

Buat indeks paket dengan tautan atau nomor halaman ke drawing revisi, sertifikat, laporan laboratorium, catatan inspeksi, NCR, dan foto identifikasi bila dipersyaratkan. Simpan daftar part yang ditahan agar tidak bercampur dengan part released. Jika rekonsiliasi gagal, kembalikan status ke hold dan buka pertanyaan spesifik—misalnya “blank B-014 berasal dari heat mana?”—bukan sekadar meminta tanda tangan tambahan.

## Kebiasaan ringkas yang sering dicoba

Jalan pintas yang menggoda adalah menyalin heat ID pada awal pekerjaan lalu menganggap semua blank dan serial otomatis mewarisinya. Ini gagal ketika satu batang dibagi, ada sisa yang kembali ke stok, atau part berpindah area tanpa marking. Alternatif yang lebih andal adalah relasi induk-anak dan verifikasi di setiap handoff. Mengarsipkan satu sertifikat tanpa mencocokkan spesimen dan laporan uji juga membuat angka terlihat resmi tetapi tidak menjawab identitas part.

## Kesimpulan

Route card dan traceability bar stock berarti menghubungkan heat ID, blank, operasi, operator, inspeksi, NCR, finishing, dan serial final dalam satu rantai yang dapat diaudit. Ambil satu order aktif, uji rekonsiliasi tiga titik—sertifikat, marking fisik, dan serial—lalu minta review QA/engineering untuk gate yang belum terjawab. Kawan Besi.co.id, jangan nyatakan release hanya karena formulir lengkap; nyatakan status berdasarkan identitas, bukti, dan persetujuan proyek yang benar-benar tersedia.
