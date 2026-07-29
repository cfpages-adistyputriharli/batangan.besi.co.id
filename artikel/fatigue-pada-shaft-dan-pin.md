---
article_id: BESB-07-A04
title: "Fatigue dan Stress Concentration pada Shaft dan Pin"
slug: "fatigue-pada-shaft-dan-pin"
description: "Memahami siklus, takik, bahu, keyway, permukaan, tegangan sisa, korosi, inspeksi, dan riwayat pada shaft serta pin"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-02-02"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BESB-07
primary_intent: "Understand cyclic failure"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/fatigue-pada-shaft-dan-pin.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/78322.html"
  - "https://www.iso.org/standard/72529.html"
  - "https://www.iso.org/standard/89449.html"
  - "https://www.iso.org/standard/64834.html"
  - "https://www.iso.org/standard/77795.html"
  - "https://content.ampp.org/books/book/12/Corrosion-Basics-An-Introduction"
  - "https://www.iso.org/standard/46556.html"
  - "https://www.fhwa.dot.gov/bridge/steel/pubs/nhi16016.pdf"
  - "https://www.fhwa.dot.gov/bridge/inspection/"
  - "https://www.fhwa.dot.gov/publications/ndec/ndecnews.cfm"
---

# Fatigue dan Stress Concentration pada Shaft dan Pin

Halo, Kawan Besi.co.id! Shaft dan pin dapat patah setelah berulang kali menerima beban, meskipun tegangan pada satu kejadian belum tampak melebihi kekuatan materialnya. Penyebab yang sering terlewat bukan sekadar “besinya kurang kuat”, melainkan kombinasi jumlah siklus, perubahan geometri yang menajamkan tegangan, kondisi permukaan, korosi, dan riwayat beban yang tidak terdokumentasi.

Jawaban singkatnya: perlakukan fatigue (kelelahan) sebagai akumulasi kerusakan pada setiap siklus. Periksa dari mana retak dapat mulai—bahu diameter, alur pasak, ulir, lubang pin, atau goresan—lalu telusuri bagaimana retak bisa tumbuh pada beban aktual. Nilai material dari satu kupon tidak cukup untuk menyatakan shaft aman; identitas material, cara pengambilan spesimen, orientasi, metode uji, dan identitas heat (nomor peleburan) atau produk harus tetap tersambung pada laporan uji ([ISO 6892-1](https://www.iso.org/standard/78322.html), [ISO 377](https://www.iso.org/standard/72529.html), dan [Amandemen ISO 377](https://www.iso.org/standard/89449.html)).

Jika riwayat putaran, kejutan beban, detail manufaktur, dan kondisi korosi belum tersedia, kesimpulan umur tidak boleh ditebak. **[NEEDS GATE-01: riwayat beban/siklus dan penilaian fatigue oleh tenaga kompeten untuk komponen ini.]**

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

Gambar ini bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

Fatigue adalah kerusakan yang berkembang karena tegangan berulang. “Berulang” tidak selalu berarti putaran konstan: siklus nyala-mati, pembalikan arah, getaran, benturan, dan perubahan muatan juga membentuk siklus. Shaft biasanya memikul torsi dan lentur yang berubah terhadap waktu, sedangkan pin dapat menerima geser, lentur lokal, dan tekanan kontak pada bidang lubang. Kombinasi tersebut menghasilkan rentang tegangan, bukan satu angka tegangan statis.

Stress concentration (konsentrasi tegangan) terjadi ketika aliran gaya dipaksa melewati perubahan bentuk: transisi diameter, alur pasak (keyway), lubang melintang, ulir, sudut tajam, atau kontak yang tidak merata. Radius transisi yang kecil, bekas alat, burr, dan ketidakselarasan dapat membuat lokasi awal retak lebih mudah. Ini tidak berarti setiap takik pasti gagal; artinya detail itu harus masuk ke penilaian detail fatigue, bukan dihapus dari gambar kerja sebagai “hal kecil”.

Artikel ini membantu Anda menyusun pertanyaan inspeksi dan data awal. Artikel ini tidak menghitung umur, memilih ukuran akhir, menetapkan interval inspeksi, atau menggantikan persetujuan desain. **[NEEDS GATE-02: verifikasi geometri, material, detail manufaktur, dan konsekuensi kegagalan oleh perancang/penilai yang berwenang.]**

## Cara kerjanya

Urutannya dapat dibayangkan sebagai rantai. Beban operasi menciptakan siklus; geometri memperbesar respons lokal; permukaan dan lingkungan menyediakan titik lemah; retak mikro kemudian dapat memanjang jika siklus berikutnya terus datang. Pada shaft, perubahan torsi dan lentur sering berinteraksi. Pada pin, celah, distribusi tekanan di lubang, dan gerak bolak-balik dapat menambah gesekan atau fretting (keausan akibat gesekan berulang) di dekat tepi lubang.

Retak tidak selalu terlihat pada awalnya. Karena itu, riwayat kapan komponen mulai berputar, perubahan kecepatan atau muatan, kejadian macet, benturan, pelumasan, penggantian bantalan (bearing), dan perbaikan las perlu dicatat sebagai bagian dari identitas komponen. Rujukan fatigue/fracture FHWA menempatkan identitas detail, konteks tegangan, riwayat beban dan perubahan penggunaan, riwayat material/fabrikasi, korosi, kerusakan, temuan sebelumnya, serta perbaikan sebagai data evaluasi—namun panduan tersebut ditujukan untuk jembatan dan bukan persyaratan bangunan Indonesia ([manual fatigue/fracture FHWA](https://www.fhwa.dot.gov/bridge/steel/pubs/nhi16016.pdf)).

Inspeksi dan pengujian harus mengikuti dugaan lokasi retak. Pemeriksaan visual memetakan perubahan warna, karat lokal, garis retak, deformasi, atau kelonggaran. Bila akses dan indikasinya memadai, metode nondestructive examination (NDE, pemeriksaan tak merusak) dipilih oleh pemeriksa kompeten sesuai material, bentuk, dan jenis cacat yang dicari. Pusat sumber inspeksi FHWA dan program NDE mereka dapat menjadi bacaan metodologis, bukan dasar untuk menyatakan komponen Anda lulus ([hub inspeksi FHWA](https://www.fhwa.dot.gov/bridge/inspection/) dan [program fatigue-crack NDE](https://www.fhwa.dot.gov/publications/ndec/ndecnews.cfm)).

## Faktor yang mengubah hasil

**Geometri dan permukaan.** Bahu diameter sebaiknya diperiksa bersama radius aktual, bukan hanya ukuran nominal. Pada keyway atau ulir, perhatikan ujung alur, kualitas dasar, burr, dan bekas pemesinan. Goresan aksial, pitting, atau bekas penjepitan dapat menjadi pemicu lokal. Pin juga perlu diperiksa terhadap keausan oval pada lubang dan kontak satu sisi; kelonggaran mengubah distribusi beban pada siklus berikutnya.

**Tegangan sisa dan proses.** Pemesinan, pelurusan, penggerindaan, perlakuan panas, pengelasan perbaikan, atau penembakan permukaan dapat mengubah tegangan sisa dan kondisi lapisan permukaan. Jangan menyimpulkan proses tertentu “menambah umur” tanpa spesifikasi proses, rekaman pelaksanaan, dan verifikasi yang sesuai.

**Lingkungan.** Air tertahan, garam, bahan kimia, celah sambungan, kontak dua logam, suhu, serta lapisan pelindung yang rusak dapat mempercepat kerusakan. Klasifikasi lingkungan dan pemilihan sistem cat harus dimulai dari paparan nyata—kebasahan, kondensasi, polutan, perendaman atau tanah, drainase, akses, dan rencana pemeliharaan—bukan hanya label kategori ([ISO 12944-2](https://www.iso.org/standard/64834.html), [ISO 12944-5](https://www.iso.org/standard/77795.html), dan [Corrosion Basics AMPP](https://content.ampp.org/books/book/12/Corrosion-Basics-An-Introduction)). Kedua bagian ISO tersebut tercatat dalam proses revisi pada halaman katalognya, sehingga sistem, persiapan permukaan, ketebalan, inspeksi, dan perbaikan harus dikonfirmasi dari dokumen yang berlaku untuk proyek.

**Material dan bukti.** Sertifikat material, heat number, jejak lot, serta orientasi spesimen harus cocok dengan komponen. ISO 6892-1 menjelaskan metode uji tarik pada temperatur ruang; itu tidak otomatis menjadi persyaratan penerimaan produk. Jika identitas bar atau pin putus, hasil uji terpisah tidak boleh dipakai untuk “mengisi” identitas yang hilang. **[NEEDS GATE-04: kecocokan material/heat, laporan uji, dan dasar penerimaan yang ditinjau kompeten.]**

**Perubahan penggunaan.** Kenaikan jam operasi, percepatan, beban kejut, atau perubahan attachment dapat mengubah spektrum siklus. Penilaian kondisi struktur yang sudah ada secara umum memerlukan tujuan penilaian, dokumen, survei, identitas material, geometri, riwayat penggunaan dan perubahan, kerusakan, pemantauan atau pengujian, analisis, kontrol sementara, serta disposisi yang ditinjau ([ISO 13822](https://www.iso.org/standard/46556.html)).

## Contoh keputusan praktis

Gunakan skenario berikut sebagai cara mengumpulkan bukti, bukan sebagai izin operasi.

| Temuan awal | Pertanyaan berikutnya | Keputusan sementara |
|---|---|---|
| Retak garis di ujung keyway | Apakah panjang, arah, dan kedalamannya sudah dipetakan? Adakah perubahan beban terakhir? | Hentikan operasi yang dapat memperbesar risiko dan minta pemeriksaan kompeten; jangan menggerinda lalu mengembalikan komponen tanpa evaluasi. |
| Pin aus dan lubang menjadi oval | Apakah kelonggaran diukur pada beberapa posisi dan beban aktual tercatat? | Amankan gerakan, dokumentasikan ukuran, lalu nilai pin, lubang, dan pasangan kontak sebagai satu sistem. |
| Karat lokal di bawah lapisan pelindung (coating) | Apakah ada air tertahan, garam, celah, atau logam berbeda yang bersentuhan? | Kendalikan paparan dan akses inspeksi; pilih perbaikan lapisan berdasarkan survei lingkungan, bukan warna cat semata. |
| Tidak ada retak terlihat, tetapi terjadi pemutus berulang (trip) | Apakah kejadian trip mengubah siklus dan kejutan torsi? | Perbarui riwayat operasi dan minta penilaian fatigue; “belum terlihat” bukan bukti umur tersisa. |

Kawan Besi.co.id, catat tanggal, jam operasi, kondisi muatan, lokasi indikasi, foto berorientasi, alat ukur, dan siapa yang memeriksa. Catatan berurutan membantu membedakan indikasi baru, pertumbuhan, dan perubahan akibat pembersihan.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah memakai kekuatan tarik atau kekerasan (hardness) dari satu kupon untuk menjawab umur fatigue. Periksa kembali identitas spesimen, lokasi, orientasi, metode, kondisi uji, unit, dan spesifikasi produk sebelum mengaitkan angka apa pun dengan shaft atau pin.

Kedua, menghaluskan takik tanpa mengukur geometri dan tanpa mencari retak di bawah permukaan. Tindakan itu dapat menghapus bukti, mengurangi diameter efektif, atau memindahkan lokasi kritis. Alternatif yang lebih aman adalah dokumentasikan kondisi awal, batasi operasi bila perlu, lalu minta rencana pemeriksaan dan perbaikan tertulis.

Ketiga, menganggap lapisan pelindung baru menyelesaikan fatigue. Lapisan itu mengelola paparan korosi; ia tidak menghapus rentang tegangan, konsentrasi tegangan, atau retak yang sudah ada. Pastikan sumber air, drainase, celah, persiapan permukaan, dan akses pemeliharaan ikut diperiksa.

Keempat, menyalin interval inspeksi dari aset lain. Frekuensi harus mengikuti konsekuensi kegagalan, spektrum siklus, akses, temuan terdahulu, dan perubahan penggunaan yang ditinjau untuk aset ini. Teman Besi.co.id, bila data itu belum tersedia, tulis “belum ditetapkan” dan eskalasikan—jangan menggantinya dengan angka kebiasaan.

## Jalan pintas penggantian langsung

Jalan pintas yang sering dipilih adalah mengganti shaft atau pin dengan stok berdiameter sama lalu menganggap masalah selesai. Penggantian dapat menghilangkan retak pada komponen lama, tetapi tidak otomatis menghilangkan penyebabnya: alur pasak tetap bertakik, keselarasan (alignment) tetap buruk, siklus kejut tetap terjadi, dan lingkungan korosif tetap ada. Cocokkan material dan jejak produknya, periksa pasangan lubang/bantalan, verifikasi geometri serta proses, dan dokumentasikan perubahan penggunaan sebelum melepas kontrol sementara.

Jika spesifikasi pengganti sudah disetujui, halaman [besi as S45C di Yogyakarta](/jual-as-s45c-yogyakarta) dan [besi as ST42 di Yogyakarta](/jual-as-st42-yogyakarta) dapat menjadi titik awal pengadaan. Keduanya bukan bukti bahwa salah satu mutu (grade) cocok untuk komponen Anda: minta perancang mengonfirmasi mutu, ukuran, jejak heat, dan dasar penerimaannya sebelum membeli atau memasang.

## Kesimpulan

Fatigue pada shaft dan pin ditentukan oleh siklus yang benar-benar dialami dan bagaimana detail—bahu, keyway, ulir, lubang, permukaan, tegangan sisa, korosi, dan kelonggaran—mengubah tegangan lokal. Mulailah dengan menghentikan asumsi, bukan langsung menghitung umur: kumpulkan gambar dan ukuran aktual, sertifikat serta laporan uji yang dapat ditelusuri, riwayat beban dan perbaikan, peta korosi/keausan, dan hasil inspeksi.

Minta perancang atau penilai kompeten menetapkan pemeriksaan lanjutan, kontrol operasi, dan disposisi berdasarkan data tersebut. Untuk orientasi langkah awal, Anda dapat mulai dari [beranda Besi.co.id](/) bersama rekaman inspeksi aset. **Aturan operasinya: tanpa riwayat siklus, kondisi detail, dan tinjauan teknis yang dapat dipertanggungjawabkan, umur tersisa tidak boleh dinyatakan.**
