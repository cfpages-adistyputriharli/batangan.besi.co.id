---
article_id: BESB-03-A02
title: "Menghitung Berat Teoretis Besi Batangan"
slug: "menghitung-berat-besi-batangan"
description: "Cara menghitung massa teoritis besi batangan dari geometri, panjang, asumsi massa jenis, satuan, dan pembulatan"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-14"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BESB-03
primary_intent: "Calculate theoretical mass"
reader_community: "Besi.co.id"
reader_address: "Sobat Besi.co.id"
final_route: "/artikel/menghitung-berat-besi-batangan.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/9985.html"
  - "https://www.asme.org/codes-standards/find-codes-standards/welded-and-seamless-wrought-steel-pipe"
---

# Menghitung Berat Teoretis Besi Batangan
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

Halo, Sobat Besi.co.id! Jika Anda perlu memperkirakan massa besi batangan untuk quantity take-off, jawabannya berasal dari volume, panjang, dan asumsi massa jenis—bukan dari nama nominal saja. Rumus dasarnya adalah:

`massa teoritis = luas penampang × panjang × massa jenis`.

Samakan satuan terlebih dahulu, lalu bulatkan hanya pada tahap akhir. Hasil ini adalah angka perhitungan berdasarkan geometri yang dirujuk; ISO 4200 dan ASME B36.10 sama-sama menempatkan dimensi serta massa teoritis dalam konteks tabel produk, sehingga label nominal, ukuran terukur, dan dasar tagihan tidak boleh dicampur ([ISO 4200](https://www.iso.org/standard/9985.html); [ASME B36.10](https://www.asme.org/codes-standards/find-codes-standards/welded-and-seamless-wrought-steel-pipe)).

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

Aset lokal ini hanya ilustrasi umum, bukan dokumentasi proyek tertentu.

## Jawaban singkat dan salah paham utama

Untuk batang bulat, luas penampangnya `π × d² / 4`. Untuk batang persegi, gunakan `s²`; untuk persegi panjang, `lebar × tebal`. Kalikan luas itu dengan panjang batang dan massa jenis yang disetujui pada lembar perhitungan. Konversi milimeter ke meter sebelum menghitung volume dalam meter kubik. Bila diameter masih berupa label nominal, tandai hasilnya sebagai teoritis, bukan hasil timbang.

Kesalahan paling mahal biasanya terjadi saat estimator memakai diameter dalam milimeter bersama panjang dalam meter tanpa konversi, atau membulatkan diameter dan massa jenis terlalu dini. Kesalahan lain adalah menganggap angka teoritis otomatis sama dengan berat pada invoice. Kawan Besi.co.id, perlakukan tiga angka berbeda: geometri acuan, massa teoritis, dan massa aktual yang kelak diverifikasi saat penerimaan. Ruang lingkup artikel ini berhenti pada perhitungan teoritis; penimbangan dan rekonsiliasi invoice memerlukan pemeriksaan terpisah.

## Definisi dan batas objek

“Berat” dalam percakapan sehari-hari sering berarti massa. Di lembar estimator, gunakan istilah massa dan satuan yang konsisten, misalnya kilogram. Massa teoritis adalah hasil model: penampang dianggap sesuai dimensi acuan, panjang dianggap sesuai potongan, dan massa jenis dianggap konstan sesuai dokumen material atau asumsi proyek.

Model ini tidak menetapkan toleransi, kelas schedule, kelayakan struktur, atau hak pembayaran. Tabel produk dapat menyajikan massa nominal, tetapi edisi standar yang berlaku dan syarat pasokan harus diperiksa sebelum angka dipakai sebagai dasar kontrak. Jika angka ini akan memengaruhi pengangkatan, kapasitas rak, atau keputusan pelepasan material, minta tinjauan kompeten dan bukti proyek yang mutakhir: `[NEEDS GATE-01/GATE-02/GATE-04: verifikasi dimensi, asumsi massa jenis, dan tujuan penggunaan sebelum keputusan keselamatan atau komersial]`.

## Cara kerjanya

Mulai dengan identifikasi penampang dari gambar, datasheet, atau dokumen pembelian. Catat apakah batang bulat, persegi, persegi panjang, atau profil berongga. Untuk penampang berongga, hitung luas luar dikurangi luas dalam; jangan mengganti dinding aktual dengan diameter luar saja.

Berikut urutan yang dapat dipakai di spreadsheet:

1. **Tetapkan geometri.** Masukkan ukuran yang dirujuk dan sumbernya. Jika yang tersedia hanya label nominal, simpan label itu di kolom terpisah dari ukuran terukur.
2. **Konversi satuan.** Ubah semua panjang menjadi meter. Diameter 25 mm, misalnya, ditulis 0,025 m sebelum dikuadratkan.
3. **Hitung luas penampang.** Pilih rumus sesuai bentuk. Jangan memakai rumus batang bulat untuk batang persegi.
4. **Hitung volume.** Kalikan luas dalam m² dengan panjang dalam m sehingga volume menjadi m³.
5. **Terapkan massa jenis.** Isi `ρ` dari dokumen material atau asumsi yang disetujui. Hindari mengunci satu angka universal jika material atau basis pengadaan berbeda.
6. **Bulatkan dan dokumentasikan.** Simpan nilai mentah, aturan pembulatan, tanggal, serta siapa yang menyetujui asumsi.

Rumus umum dapat ditulis `m = A × L × ρ`. Jika Anda menghitung banyak batang dengan ukuran sama, kalikan massa satu batang dengan jumlahnya; jika panjang berbeda, hitung tiap kelompok agar pembulatan tidak menumpuk. Tabel dimensi dan massa seperti yang dibahas ISO 4200/ASME B36.10 membantu menetapkan geometri rujukan, tetapi tidak menggantikan pengukuran penerimaan atau syarat pasokan.

## Faktor yang mengubah hasil

**Dimensi.** Karena diameter batang bulat dikuadratkan, perubahan kecil pada diameter memberi pengaruh lebih besar daripada perubahan panjang yang sama secara relatif. Ovalitas, chamfer, radius sudut, atau rongga juga mengubah luas efektif. Gunakan dimensi pada dokumen yang sama; jangan menggabungkan diameter dari satu sumber dengan panjang dari sumber lain tanpa catatan.

**Panjang.** Panjang teoritis adalah panjang yang benar-benar dimodelkan: satu batang penuh, potongan bersih, atau total akumulasi. Kerf pemotongan dan sisa ujung hanya masuk bila memang termasuk kuantitas yang dihitung. Untuk kebutuhan pemesanan, bedakan panjang bersih dari allowance fabrikasi.

**Massa jenis.** Simbol `ρ` adalah asumsi input, bukan keluaran rumus. Ambil dari spesifikasi material yang disetujui atau nyatakan jelas bahwa itu asumsi estimasi. Jika revisi dokumen mengubah nilai tersebut, hitung ulang seluruh baris terkait.

**Pembulatan.** Bulatkan pada hasil akhir per batang atau pada total—pilih satu aturan dan terapkan konsisten. Menjumlahkan angka yang sudah dibulatkan per potong dapat berbeda dari membulatkan total mentah. Untuk lifting atau desain penyangga, jangan mengandalkan angka pembulatan yang mengurangi margin tanpa tinjauan kompeten.

## Contoh keputusan praktis

Misalkan estimator menerima satu batang bulat dengan diameter acuan 25 mm dan panjang 6 m. Ia memilih massa jenis asumsi `ρ = 7.800 kg/m³` hanya untuk contoh perhitungan internal, bukan klaim nilai standar atau jaminan material.

Konversi diameter menjadi 0,025 m. Luas penampangnya `π × (0,025²) / 4 ≈ 0,0004909 m²`. Volume satu batang `0,0004909 × 6 ≈ 0,002945 m³`. Massa teoritisnya `0,002945 × 7.800 ≈ 22,97 kg`, lalu dibulatkan sesuai aturan lembar kerja.

Keputusan berikutnya bergantung pada tujuan:

| Tujuan | Angka yang dipakai | Pemeriksaan sebelum diputuskan |
|---|---|---|
| Estimasi kuantitas awal | Massa teoritis dari asumsi tertulis | Cocokkan bentuk, ukuran, dan panjang pada gambar |
| Input pengangkatan/rak | Massa teoritis konservatif | Tinjauan kapasitas, tumpuan, dan kondisi aktual; jangan memakai angka contoh |
| Penerimaan atau invoice | Bukan massa teoritis saja | Ikuti prosedur timbang, dokumen pasokan, dan rekonsiliasi yang disetujui |

Teman Besi.co.id, bila salah satu input belum pasti, tampilkan rentang atau marker tinjauan daripada menyamarkan ketidakpastian dengan dua angka desimal.

## Kesalahan umum dan cara memeriksanya

- **Campur mm dan m.** Tulis unit di setiap kolom dan buat pemeriksaan otomatis bahwa semua panjang untuk volume sudah dalam meter.
- **Mengkuadratkan angka yang salah.** Pastikan diameter dikonversi sebelum `d²`; jangan mengonversi luas setelah pembulatan.
- **Menganggap nominal = aktual.** Simpan kolom “acuan” dan “terukur” terpisah. Jika belum ada pengukuran, sebut hasilnya teoritis.
- **Mengabaikan bentuk berongga.** Kurangi luas dalam dari luas luar dan dokumentasikan tebal dinding yang dipakai.
- **Membulatkan tiap langkah.** Pertahankan beberapa digit pada luas dan volume, bulatkan sekali di keluaran.
- **Menjadikan hasil sebagai bukti timbang.** Massa teoritis tidak membuktikan massa aktual, kadar air, pelapis, atau dasar invoice. Tandai kebutuhan verifikasi penerimaan.

Checklist singkat sebelum mengirim quantity take-off: apakah sumber dimensi tercatat, unit seragam, massa jenis memiliki dasar, panjang dan jumlah batang benar, aturan pembulatan tertulis, serta tujuan penggunaan sudah ditetapkan? Jika jawabannya belum, perhitungan belum siap menjadi keputusan.

## Jalan pintas yang sebaiknya dihindari

Shortcut yang sering dipilih adalah menyalin “kg per meter” dari tabel lama karena terlihat cepat. Cara itu hanya aman jika tabel tersebut benar-benar merujuk pada bentuk, dimensi, edisi dokumen, massa jenis, dan aturan pembulatan yang sama. ISO 4200 dan ASME B36.10 menunjukkan mengapa dimensi serta massa teoritis terikat pada produk dan tabel tertentu; keduanya tidak memberi hak untuk memindahkan angka ke semua batang.

Alternatif yang lebih dapat diaudit: bangun satu baris rumus dari geometri, panjang, dan `ρ`, lalu simpan tautan atau nomor dokumen sumber. Untuk kebutuhan lanjutan, Anda dapat melihat [besi AS S45C di Yogyakarta](/jual-as-s45c-yogyakarta) atau [besi AS ST42 di Yogyakarta](/jual-as-st42-yogyakarta) setelah spesifikasi dan jumlahnya jelas. Minta pemeriksaan kedua untuk baris yang akan dipakai pada lifting, kapasitas penyimpanan, atau komitmen komersial. Jika bukti proyek belum tersedia, pertahankan marker kebutuhan review dan jangan mengisinya dengan tebakan.

## Kesimpulan

Berat teoretis besi batangan dihitung dengan `m = A × L × ρ`: tentukan luas penampang yang benar, samakan satuan, gunakan massa jenis yang dinyatakan, dan bulatkan di akhir. Angka tersebut berguna untuk estimasi kuantitas, tetapi tidak menggantikan timbang aktual, dokumen pasokan, atau persetujuan profesional.

Langkah Anda sekarang adalah menyimpan dimensi acuan, sumbernya, panjang, jumlah batang, asumsi `ρ`, dan aturan pembulatan dalam satu lembar yang dapat ditinjau. Sobat Besi.co.id, pakai hasil teoritis sebagai input terjelas untuk keputusan berikutnya—dan hentikan penggunaannya sebagai angka keselamatan atau invoice sampai pemeriksaan kompeten menyelesaikan `[NEEDS GATE-01/GATE-02/GATE-04]`.
