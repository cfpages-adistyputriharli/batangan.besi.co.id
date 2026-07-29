---
article_id: BESB-02-A05
title: "Rekonsiliasi PO, Marking, dan Certificate"
slug: "rekonsiliasi-identitas-bar-stock"
description: "Cara mencocokkan PO, packing list, marking fisik, heat, ukuran, jumlah, dan penerbit sertifikat"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-02"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BESB-02
primary_intent: "Check document/material match"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/rekonsiliasi-identitas-bar-stock.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/by_ics?ics_no=77.140.70&key="
  - "https://pesta.bsn.go.id/produk/by_ics/2?ics_no=77.140.50&key="
  - "https://www.iso.org/standard/53736.html"
  - "https://www.iso.org/standard/66912.html"
  - "https://www.iso.org/standard/72532.html"
  - "https://www.iso.org/standard/85464.html"
  - "https://www.iso.org/standard/64622.html"
---

# Rekonsiliasi PO, Marking, dan Certificate

Halo, Kawan Besi.co.id! Ketika bar stock tiba dan angka pada purchase order (PO), packing list, marking fisik, serta certificate tidak persis sama, jangan langsung menganggap salah satu dokumen “paling benar”. Keputusan yang aman adalah menahan identitas lot, membuat matriks pencocokan, lalu meminta bukti yang menutup setiap selisih. Certificate yang tampak rapi tidak dapat menggantikan marking atau ukuran yang tidak cocok; marking yang terbaca juga tidak membuktikan isi certificate bila heat number-nya berbeda.

Rekonsiliasi berarti mencocokkan satu unit atau satu lot melalui rantai **PO → packing list → tanda fisik → heat/batch → dimensi dan jumlah → certificate → penerbit**. Jika satu mata rantai putus, statusnya bukan “lulus dengan catatan” secara otomatis, melainkan **hold untuk klarifikasi**. Pengujian material berada di lingkup proses lain dan halaman ini tidak melepas stok. [NEEDS GATE-01: nomor PO, revisi, dan kriteria penerimaan proyek harus dikonfirmasi oleh penanggung jawab teknis.]

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

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

*Aset lokal proyek; gambar ini hanya ilustrasi umum, bukan dokumentasi proyek tertentu.*

## Definisi dan batas objek

PO adalah sumber kebutuhan: profil atau bentuk produk, grade yang diminta, ukuran, panjang, toleransi, jumlah, dokumen yang disyaratkan, serta aturan penerimaan. Packing list menjelaskan apa yang dikirim dalam kemasan tertentu. Marking adalah identitas yang terlihat pada batang, bundel, tag, atau label. Heat atau batch menghubungkan material fisik dengan riwayat produksi. Certificate adalah dokumen penerbit yang menyatakan hasil atau identitas sesuai ruang lingkupnya; ia bukan tiket bebas dari verifikasi.

Urutan ini penting karena standar produk berbeda menurut bentuk dan penggunaan. Katalog BSN memisahkan kelompok produk baja profil dan produk baja datar, sehingga satu daftar standar tidak dapat dipakai untuk semua plate, bar, tube, mesh, fastener, coating, atau rakitan terpasang ([katalog profil baja BSN](https://pesta.bsn.go.id/produk/by_ics?ics_no=77.140.70&key=), [katalog produk baja datar BSN](https://pesta.bsn.go.id/produk/by_ics/2?ics_no=77.140.50&key=)). Status “berlaku” di katalog membantu menemukan rekaman, tetapi belum menetapkan edisi yang mengikat PO, kontrak, atau regulasi proyek.

Batas artikel ini adalah identitas dan kelengkapan bukti saat penerimaan. Tidak dibahas penentuan grade lintas standar, metode uji, AQL, atau keputusan desain. Bila barang sudah dipotong, dicampur, atau dipindahkan tanpa jejak, rekonsiliasi harus berhenti pada batas bukti yang masih tersedia dan dikaji oleh pihak berwenang. Untuk menyiapkan dokumen penerimaan, Anda dapat memakai konteks layanan di [Besi.co.id](/) sebagai titik awal, bukan sebagai pengganti persetujuan proyek. Jika hasil rekonsiliasi mengharuskan pengadaan ulang, lihat [besi as S45C di Yogyakarta](/jual-as-s45c-yogyakarta) atau [besi as ST42 di Yogyakarta](/jual-as-st42-yogyakarta) sebagai konteks produk; spesifikasi dan persetujuan proyek tetap menjadi acuan.

## Cara kerjanya

Mulai dengan membuat satu baris untuk setiap bundel atau lot yang datang. Salin nomor PO dan revisinya, lalu tambahkan nomor packing list, pemasok, deskripsi produk, ukuran nominal, panjang, jumlah, heat/batch, dan lokasi fisik. Jangan merangkum beberapa heat menjadi satu baris hanya karena grade dan ukurannya sama.

Berikut urutan pemeriksaan yang dapat dipakai di area penerimaan:

1. **Kunci dokumen acuan.** Cocokkan nomor PO, tanggal/revisi, item, dan persyaratan certificate. Jika packing list mengacu pada PO lama, tandai konflik sebelum memeriksa angka lain.
2. **Hitung dan ukur secara teridentifikasi.** Catat jumlah kemasan dan unit, ukuran yang diminta, panjang, serta satuan. Tulis alat dan kondisi pengukuran sesuai prosedur proyek; jangan mengubah hasil lapangan agar tampak cocok.
3. **Baca marking tanpa menebak.** Foto atau salin persis heat, batch, grade, ukuran, dan simbol penerbit yang terlihat. Bila sebagian marking tertutup, catat bagian yang tidak terbaca dan jaga segregasi.
4. **Telusuri heat ke dokumen.** Heat pada marking harus muncul konsisten pada packing list dan certificate. Jika satu certificate mencakup beberapa heat, minta daftar cakupan yang jelas, bukan asumsi bahwa semua bundel termasuk.
5. **Periksa certificate sebagai dokumen inspeksi.** Cocokkan produsen, produk, dimensi, heat/batch, hasil yang dilaporkan, tanggal, dan otorisasi penerbit dengan PO dan benda fisik. ISO 10474 memberi kerangka untuk dokumen inspeksi; halaman standarnya tidak menggantikan persyaratan kontrak atau teks lengkap yang berlaku ([ISO 10474:2013](https://www.iso.org/standard/53736.html)).
6. **Validasi kompetensi penerbit atau laboratorium.** Nama lembaga saja tidak cukup. Periksa ruang lingkup akreditasi, metode, otorisasi laporan, dan rantai identitas. ISO/IEC 17025 relevan untuk kompetensi laboratorium, tetapi kompetensi itu sendiri tidak membuktikan item tertentu memenuhi PO ([ISO/IEC 17025:2017](https://www.iso.org/standard/66912.html)). [NEEDS GATE-02: ruang lingkup akreditasi, metode, dan otorisasi certificate harus diverifikasi dari dokumen proyek terkini.]
7. **Tetapkan status per baris.** Gunakan “cocok”, “selisih administratif”, atau “hold—identitas belum tertutup”. Sertakan bukti dan pemilik tindakan untuk setiap selisih. Stok yang berstatus hold tetap terpisah dari stok siap pakai.

## Faktor yang mengubah hasil

Edisi standar dan bentuk produk dapat mengubah kolom yang wajib diperiksa. Rekaman BSN untuk produk tertentu dapat menampilkan lebih dari satu edisi atau klasifikasi; karena itu, salin judul dan status rekaman yang benar-benar dipakai, lalu cocokkan dengan PO dan kontrak. Jangan menulis “sesuai SNI” hanya karena nomor standar muncul di certificate.

Identitas juga berubah ketika material dipotong, dibundel ulang, atau dipindahkan. Rantai custody perlu menunjukkan karakteristik yang diklaim, batas sistem, catatan input-output, pihak yang bertanggung jawab, dan aturan transfer. ISO 22095 menjelaskan bahwa model segregasi fisik, mass balance, dan klaim administratif adalah model berbeda; masing-masing membutuhkan bukti dan tidak boleh dihitung ganda ([ISO 22095:2020](https://www.iso.org/standard/72532.html)). [NEEDS GATE-04: model chain-of-custody, aturan transfer, dan catatan transaksi harus disetujui untuk klaim yang dipakai proyek.]

Kondisi kemasan, label yang hilang, tinta pudar, satuan berbeda, pembulatan panjang, atau jumlah bundel yang berubah adalah sinyal untuk memperluas pemeriksaan dokumen—bukan alasan untuk mengisi angka yang hilang. Jika penerimaan memakai sampling, rencana harus mendefinisikan lot/populasi, karakteristik, metode, pemilihan sampel, identitas sampel, ukuran/frekuensi, kriteria, aturan keputusan, penanggung jawab, dan jalur ketidaksesuaian. Jangan mengambil ukuran sampel atau AQL dari ringkasan web; ISO 2859-1 dan ISO 28590 hanya menjadi titik rujuk sampai edisi lengkap dan ITP yang disetujui tersedia ([ISO 2859-1:2026](https://www.iso.org/standard/85464.html), [ISO 28590:2017](https://www.iso.org/standard/64622.html)).

## Contoh keputusan praktis

Bayangkan satu PO meminta bar dengan ukuran tertentu dan dua heat. Packing list menyebut dua bundel, tetapi label fisik pada satu bundel hanya memuat satu heat. Certificate mencantumkan kedua heat dan dimensi yang diminta. Keputusan yang dapat dipertanggungjawabkan adalah menerima secara administratif hanya bagian yang identitasnya tertutup, menahan bundel berlabel tidak lengkap, dan meminta pemasok menghubungkan bundel itu ke heat melalui catatan pengiriman atau verifikasi yang disetujui. Jangan mengalokasikan certificate gabungan ke bundel yang tidak dapat diidentifikasi.

Gunakan tabel sederhana berikut untuk menjaga keputusan tetap terlihat:

| Pemeriksaan | Cocok bila | Jika selisih |
|---|---|---|
| PO dan revisi | Nomor item serta persyaratan sama | Hold dan klarifikasi revisi |
| Packing list | Bundel, jumlah, dan heat terpetakan | Hitung ulang; jangan gabungkan lot |
| Marking fisik | Teks terbaca dan konsisten | Foto, segregasi, minta bukti pengganti |
| Dimensi dan satuan | Nilai, satuan, dan toleransi mengacu acuan | Catat pengukuran; rujuk kriteria proyek |
| Certificate | Penerbit, heat, produk, dan hasil terotorisasi | Verifikasi issuer dan cakupan |

Ini adalah contoh bersyarat, bukan pelepasan stok. Penanggung jawab proyek tetap menentukan apakah bukti tambahan atau inspeksi profesional diperlukan.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menganggap certificate selalu mengalahkan marking. Periksa dulu apakah nomor heat pada keduanya sama dan apakah certificate menyebut semua dimensi serta jumlah yang diterima. Kesalahan kedua adalah mencocokkan hanya grade dan ukuran, lalu mengabaikan produsen atau heat. Buat kolom identitas lengkap agar dua barang yang tampak sama tidak tertukar.

Kesalahan ketiga adalah memotret label tanpa menyimpan lokasi bundel dan nomor packing list. Foto tanpa konteks sulit diaudit. Beri pengenal unik pada foto, baris rekonsiliasi, dan dokumen sumber. Kesalahan keempat adalah menyatakan “uji sudah ada” sebagai bukti kesesuaian. Hasil uji harus terkait dengan sampel dan lot yang benar, metode yang disetujui, serta aturan keputusan; halaman ini tidak menetapkan hasil uji.

Terakhir, jangan menghapus baris yang tidak cocok dari spreadsheet penerimaan. Simpan nilai yang diterima, nilai yang diminta, bukti pendukung, pemilik tindakan, dan tanggal penutupan. Dengan begitu, perubahan status dapat ditelusuri tanpa menulis ulang sejarah.

## Jalan pintas yang tampak praktis tetapi berisiko

Shortcut yang sering dipilih adalah memakai satu certificate untuk seluruh kiriman karena nama produk dan grade terlihat sama. Cara ini gagal ketika satu kiriman berisi beberapa heat, pemasok berbeda, atau bundel yang ditata ulang. Mekanismenya sederhana: dokumen menjadi tidak terikat pada objek fisik, sehingga selisih tidak lagi terlihat saat stok bergerak.

Alternatif yang lebih aman adalah membuat matriks satu baris per bundel/lot, meminta konfirmasi tertulis atas cakupan certificate, dan mempertahankan segregasi sampai identitas tertutup. Sobat Besi.co.id, bila pemasok hanya mengirim salinan tanpa rantai pengiriman yang jelas, perlakukan itu sebagai kekurangan bukti—bukan sebagai alasan untuk menebak.

## Kesimpulan dan langkah berikutnya

Rekonsiliasi PO, marking, dan certificate selesai ketika identitas setiap lot dapat ditelusuri dari kebutuhan di PO, catatan packing, tanda fisik, heat/batch, ukuran dan jumlah, sampai penerbit dokumen. Satu selisih yang memutus rantai membuat status tetap hold; certificate atau hasil laboratorium tidak otomatis menutupnya.

Kawan Besi.co.id, langkah berikutnya adalah bekukan nomor PO dan revisinya, buat matriks per bundel, lampirkan foto marking serta packing list, lalu minta penanggung jawab teknis menutup `[NEEDS GATE-01]`, `[NEEDS GATE-02]`, dan `[NEEDS GATE-04]` dengan bukti proyek yang berlaku. Jangan lepaskan atau campur stok sebelum keputusan itu terdokumentasi. Simpan matriks ini sebagai referensi kerja, bukan sebagai bukti kesesuaian. Jika identitas tetap tidak dapat dibuktikan, eskalasikan untuk review profesional sesuai kontrak dan prosedur penerimaan.
