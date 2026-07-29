---
article_id: BESB-08-A03
title: "Drilling, Threading, dan Keyway pada Bar"
slug: "drilling-threading-dan-keyway-bar"
description: "Panduan menyiapkan lubang, ulir, dan alur pasak pada bar dengan datum, allowance, inspeksi, dan ketertelusuran yang jelas"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-02-24"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BESB-08
primary_intent: "Plan features"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/drilling-threading-dan-keyway-bar.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/78322.html"
  - "https://www.iso.org/standard/72529.html"
  - "https://www.iso.org/standard/89449.html"
  - "https://www.iso.org/standard/53736.html"
  - "https://www.iso.org/standard/66912.html"
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

# Drilling, Threading, dan Keyway pada Bar

Halo, Kawan Besi.co.id! Pada bar, tiga fitur ini bukan sekadar lubang, ulir, dan alur yang dikerjakan berurutan. Keputusan yang paling aman adalah membekukan identitas material, datum, ukuran dasar, allowance, dan cara inspeksi terlebih dahulu; parameter potong serta detail geometri tetap milik gambar dan route kerja yang disetujui. Tanpa itu, fitur mungkin tampak selesai tetapi tidak lagi satu sumbu, tidak cukup menyisakan material, atau menjadi titik konsentrasi tegangan.

Jawaban singkatnya: baca drawing dari datum dan fungsi, tandai setiap fitur dengan referensi yang sama, kerjakan dengan urutan yang menjaga penjajaran, lalu verifikasi dimensi, bentuk, burr, permukaan, dan traceability sebelum perlindungan akhir. Kondisi material, toleransi, jenis pasangan ulir atau pasak, dan persyaratan inspeksi dapat mengubah urutan tersebut. Jika salah satu belum jelas, tahan pekerjaan pada `[NEEDS GATE-01: konfirmasi drawing, toleransi, dan kriteria penerimaan oleh penanggung jawab proyek]`.

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

*Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu. Ini hanya ilustrasi umum, bukan dokumentasi proyek.*

## Definisi dan batas objek

“Drilling” di sini berarti membuat lubang pada bar; “threading” membentuk ulir internal atau eksternal; “keyway” membuat alur untuk elemen pasak. Ketiganya dapat berada pada satu sumbu, tetapi tidak otomatis memiliki datum, yaitu permukaan atau sumbu acuan ukur, atau toleransi yang sama. Lubang bisa menjadi acuan ulir, sedangkan keyway mungkin harus sejajar dengan fitur ujung atau tanda orientasi. Gambar harus menyatakan hubungan itu—bukan operator yang menebaknya.

Artikel ini membantu menyiapkan pekerjaan dan pemeriksaan. Ia tidak memilih diameter bor, pitch ulir, kedalaman alur, radius sudut, allowance, cutting speed, feed, atau material pahat. Semua parameter tersebut berasal dari drawing, route, material specification, dan persetujuan teknis. Jangan mengubahnya hanya karena ukuran “umum” terasa cocok.

Identitas bar juga bagian dari objek kerja: heat atau batch, ukuran awal, kondisi permukaan, dan tanda fisik harus tetap dapat ditelusuri. Hasil uji tarik hanya bermakna bersama sumber spesimen, orientasi, lokasi, persiapan, metode, kondisi, satuan, dan identitas produk/heat; metode uji sendiri bukan bukti bahwa seluruh bar memenuhi grade ([ISO 6892-1:2019](https://www.iso.org/standard/78322.html), [ISO 377:2017](https://www.iso.org/standard/72529.html), [amendemen ISO 377:2025](https://www.iso.org/standard/89449.html)).

## Cara kerjanya

Mulai dari paket kerja yang sama: drawing revisi berlaku, route operasi, material certificate, alat ukur yang tersedia, dan titik hold. Tandai datum primer pada bar, lalu tentukan bagaimana benda dijepit dan dibalik tanpa kehilangan referensi. Untuk bar bulat, runout dan konsentrisitas terhadap sumbu menjadi pertanyaan awal; untuk bar dengan sisi referensi, pastikan orientasi keyway tidak tertukar saat setup kedua.

Urutan praktisnya biasanya berupa penyiapan muka dan datum, pembuatan lubang pilot atau lubang sesuai route, pembentukan ulir, lalu keyway ketika akses dan kekakuan memungkinkan. Itu bukan resep universal. Jika keyway mengurangi penampang sebelum pengeboran, atau ulir harus konsentris terhadap lubang, route dapat memerintahkan urutan berbeda. Catat siapa yang menetapkan urutan dan mengapa.

Setiap perpindahan setup menambah peluang error. Gunakan witness mark atau metode identifikasi yang tidak merusak area fungsi. Setelah roughing, sisakan allowance yang dinyatakan route untuk finishing; jangan menganggap material tersisa sebagai toleransi cadangan. Deburr di antara operasi secukupnya agar serpihan tidak mengganjal datum, tetapi jangan menghilangkan radius atau chamfer yang dipersyaratkan.

Threading memerlukan verifikasi pasangan: jenis ulir, kelas atau fit yang tertulis, panjang engagement, dan bentuk awal-akhir ulir. Keyway memerlukan pemeriksaan lebar, kedalaman, posisi angular, panjang, dan kondisi dasar/sudut sesuai drawing. Drilling memerlukan diameter, kedalaman, posisi, dan kondisi mulut serta dasar lubang. Parameter numeriknya tetap `[NEEDS GATE-02: drawing dan route menyebutkan ukuran serta metode ukur yang disetujui]`.

## Faktor yang mengubah hasil

Datum yang tidak stabil membuat fitur benar secara lokal tetapi salah terhadap sumbu komponen. Chuck, soft jaw, mandrel, atau fixture harus dipilih dari geometri dan kekakuan yang benar-benar tersedia. Bar yang memiliki tegangan sisa, stok tidak lurus, atau permukaan kasar dapat berubah bentuk ketika allowance dilepas. Karena itu, periksa kondisi sebelum dan sesudah roughing; jangan menyimpulkan stabilitas dari satu pembacaan.

Titik yang memperbesar konsentrasi tegangan (stress raiser) sering muncul di ujung keyway, dasar ulir, lubang melintang, atau pertemuan chamfer yang terlalu tajam. Artikel ini tidak menetapkan radius aman. Tugas operator adalah memastikan radius, relief, dan pemecah tepi (edge break) yang diminta drawing benar-benar dikerjakan dan tidak tertutup burr. Bila gambar tidak menjelaskan detail yang memengaruhi fungsi atau kekuatan, hentikan interpretasi dan minta keputusan desain.

Permukaan juga bukan sekadar kosmetik. Burr pada mulut lubang dapat mengganggu seating; burr di sisi keyway dapat mengganjal pasak; serpihan pada ulir dapat memberi pembacaan gauge yang menipu. Lindungi permukaan setelah inspeksi—misalnya dengan penutup atau pelindung yang disetujui—dan pastikan perlindungan tidak menyembunyikan cacat atau menghapus marking.

Inspection document harus direkonsiliasi dengan order, produsen, produk, heat/batch, dimensi, pengujian, dan marking fisik. Kompetensi laboratorium membantu menilai keandalan hasil, tetapi akreditasi tidak dengan sendirinya membuktikan item tertentu conform ([ISO 10474:2013](https://www.iso.org/standard/53736.html), [ISO/IEC 17025:2017](https://www.iso.org/standard/66912.html)). Untuk acceptance, minta review teknis atas dokumen dan rantai identitas melalui `[NEEDS GATE-04: verifikasi sertifikat, scope laboratorium, dan kriteria penerimaan proyek]`.

## Contoh keputusan praktis

Bayangkan drawing memuat lubang aksial, ulir pada lubang itu, dan satu keyway yang harus berorientasi terhadap tanda ujung. Sebelum menyalakan mesin, tulis tiga pertanyaan di traveler: “datum mana yang mengontrol sumbu?”, “kapan allowance terakhir dilepas?”, dan “alat ukur apa yang membuktikan posisi angular?”. Jika jawabannya tidak ada, masalahnya bukan kecepatan mesin; paket kerja belum siap.

| Situasi yang terlihat | Keputusan kerja yang aman |
|---|---|
| Material dan heat mark cocok, tetapi revisi drawing berbeda | Karantina pekerjaan sampai revisi yang berlaku dikonfirmasi. |
| Diameter lubang lolos, namun posisi terhadap datum belum diukur | Jangan nyatakan lulus; lakukan pengukuran posisi dengan metode yang disetujui. |
| Ulir terasa masuk dengan baut contoh, tetapi gauge atau fit tidak ditetapkan | Hentikan penerimaan berdasarkan “rasa”; minta kelas/fit dan alat ukur dari drawing. |
| Keyway bersih dilihat mata, tetapi ujungnya menyisakan sudut tajam | Periksa radius/relief yang dipersyaratkan; jangan mengikir bebas. |
| Sertifikat tersedia, marking pada bar hilang setelah pemotongan | Pulihkan identitas dengan prosedur traceability sebelum komponen berpindah. |

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menganggap semua bar memiliki pusat dan ujung yang dapat dijadikan datum. Ukur kondisi awal dan dokumentasikan datum yang benar-benar dipakai. Kedua, membuat keyway atau lubang sampai ukuran akhir sebelum memastikan allowance dan urutan finishing; akibatnya koreksi tidak lagi tersedia. Ketiga, memakai baut atau pasak contoh sebagai satu-satunya inspeksi. Contoh dapat menunjukkan interaksi kasar, bukan seluruh dimensi dan posisi.

Gunakan checklist singkat berikut pada tiap hold point:

- identitas heat/batch dan revisi drawing cocok;
- datum, setup, dan orientasi sudah ditandai;
- allowance tersisa sesuai route;
- ukuran dan posisi drilling, threading, serta keyway diukur dengan alat yang ditentukan;
- burr, edge break, radius, dan permukaan diperiksa setelah pembersihan;
- hasil ukur, alat, operator, waktu, dan disposition tercatat;
- marking dan perlindungan tidak menghalangi pemeriksaan berikutnya.

Jika hasil tidak sesuai, pisahkan komponen dan catat nonconformance sebelum melakukan rework. Jangan “memperbaiki” dengan memperbesar lubang, memperdalam keyway, atau mengikir ulir tanpa keputusan tertulis; perubahan itu dapat memindahkan masalah ke fit atau kekuatan.

## Jalan pintas yang perlu dihindari

Shortcut yang sering menggoda adalah mengerjakan semua fitur dalam satu setup memakai angka dari tabel lama, lalu memeriksa di akhir. Cara ini memang tampak cepat, tetapi menyembunyikan perubahan datum, allowance yang habis, dan burr yang muncul sebelum fitur berikutnya. Alternatif yang lebih dapat dipertanggungjawabkan adalah membagi operasi pada hold point: konfirmasi identitas dan datum, verifikasi roughing, inspeksi fitur, lalu perlindungan dan serah-terima dokumen. Angka proses hanya boleh berasal dari drawing dan route yang berlaku.

## Kesimpulan

Drilling, threading, dan keyway pada bar harus diperlakukan sebagai satu rantai referensi: identitas material, datum, allowance, urutan setup, kondisi tepi, inspeksi, perlindungan, dan traceability. Besar kecilnya fitur bukan alasan untuk menghapus salah satu mata rantai.

Teman Besi.co.id, sebelum pekerjaan berjalan, minta drawing revisi dan route kerja serta kriteria penerimaan dan metode ukur yang disetujui. Jika identitas grade masih perlu ditindaklanjuti, gunakan [halaman AS S45C Yogyakarta](/jual-as-s45c-yogyakarta) atau [halaman AS ST42 Yogyakarta](/jual-as-st42-yogyakarta) sebagai rujukan informasi produk, lalu cocokkan semuanya dengan sertifikat dan marking fisik. Dokumentasikan setiap hold point. Bila parameter atau detail radius belum jelas, berhenti pada batas aman dan minta keputusan engineer/inspector. Aturan operasinya sederhana: tidak ada fitur yang dinyatakan selesai sebelum hubungan terhadap datum dan bukti pemeriksaannya jelas. Sobat Besi.co.id, pastikan catatan itu diserahkan bersama komponen kepada tim inspeksi.
