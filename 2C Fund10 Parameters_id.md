# **Parameter Dana10**

Parameter Operasional Fund10 adalah parameter operasional aktual yang membentuk protokol pemungutan suara Catalyst yang diterapkan untuk memungkinkan komunitas memutuskan proposal mana yang akan menerima pendanaan dari Cardano Treasury.

### **Tabel 1**

Tabel ini merangkum parameter utama yang akan digunakan.

NOMOR | PARAMETER | NILAI | KETERANGAN
:-: | :-- | :-- | :--
 | Parameter Produk/Bisnis/Informatif |  |
A1 | Status privasi pemungutan suara langsung | Ya | Apakah suara bersifat pribadi?
A2 | Nama dana | Dana10 |
Ukuran A3 | Dana terkendali | 50.000.000 ada | Dana akan mengendalikan 50 juta ADA
Ukuran A4 | Judul dan anggaran tantangan | [Pengembangan &amp; Infrastruktur](https://cardano.ideascale.com/a/dtd/414308-48088) - ₳8.685.600<p></p> [Startup &amp; Onboarding untuk Mahasiswa](https://cardano.ideascale.com/a/dtd/422445-48088) - ₳394.800<p></p> [Produk &amp; Integrasi](https://cardano.ideascale.com/a/dtd/414299-48088) - ₳9.080.400<p></p> [OSDE: Ekosistem Pengembangan Sumber Terbuka](https://cardano.ideascale.com/a/dtd/421335-48088) - ₳3.158.400<p></p> [Alat SPO &amp; Proyek Komunitas](https://cardano.ideascale.com/a/dtd/414105-48088) - ₳4.737.600<p></p> [Ekosistem Pengembang - Evolusi](https://cardano.ideascale.com/a/dtd/422540-48088) - ₳6.316.800<p></p> [DAO &lt;3 Cardano](https://cardano.ideascale.com/a/dtd/420431-48088) - ₳3.158.400<p></p> Atala PRISM: Luncurkan Ekosistem🚀 - ₳3.158.400<p></p> [Peningkatan dan orientasi dRep](https://cardano.ideascale.com/a/dtd/418533-48088) - ₳394.800<p></p> [Membangun di NMKR](https://cardano.ideascale.com/a/dtd/419498-48088) - ₳394.800<p></p> [Catalyst Terbuka](https://cardano.ideascale.com/c/campaigns/379/about) - ₳1.400.000<p></p> [Operasional Dana Katalis](https://cardano.ideascale.com/c/campaigns/380/about) - ₳2.140.000<p></p> [Peningkatan Sistem Katalis](https://cardano.ideascale.com/c/campaigns/381/about) - ₳3.570.000 |
Ukuran A5 | Permintaan anggaran minimum per proposal | Rp 15.000 | Jumlah minimum untuk setiap proposal
A6 | Permintaan anggaran maksimum per proposal (hanya berlaku untuk kategori Catalyst Open) | Rp 75.000 | Jumlah maksimum untuk setiap proposal dalam kategori Catalyst Open
A7 | Biaya Pengajuan Proposal | Bebas | Pengusul dapat mengajukan sejumlah proposal untuk didiskusikan di Ideascale. Tim Catalyst akan menghapus proposal 'pengganti' saat batas waktu pengajuan berakhir. Proposal pengganti mencakup proposal yang salah satu kolom formulirnya tidak dijawab atau jelas tidak lengkap hingga batas waktu.
A8 | Target tanggal Dana Pindah Imbalan Instan (MIR) | 18 September 2023 | Anggaran Fund10 harus dipindahkan dari kas negara ke rekening awal sebelum hasil pemungutan suara diumumkan
A9 | Tanggal target penyaluran hadiah dan dana | 16 Oktober 2023 - 20 Oktober 2023 | Ketika hadiah komunitas dan pendanaan F10 untuk tahapan awal milestone 1 dibayarkan setelah verifikasi transaksi uji coba
A10 | Jumlah usulan maksimum yang dapat dimasukkan dalam pemungutan suara | Tidak ada batas |
A11 | Pendaftaran Peninjau Komunitas | Melalui Ideascale | Siapa pun dapat mendaftar sebagai Peninjau Komunitas<p></p> Peninjau Komunitas akan dibedakan menjadi peninjau Lv0, Lv1, Lv2 berdasarkan kontribusinya selama tahap Peninjauan Komunitas
A12 | Pendaftaran proposal di blockchain | 30 Agustus 2023 | Tanggal ketika proposal dimuat ke dalam rencana pemungutan suara dan didaftarkan ke Block0
A13 | Ambang batas kekuatan pemungutan suara | Minimal 450.000.000 lovelace (450 ada)<p></p> Direkomendasikan 500.000.000 lovelace (500 ada) | 450 ada adalah ambang batas taruhan minimum untuk menjadi pemilih, berdasarkan tolok ukur efisiensi protokol pemungutan suara<p></p> Nilai spesifik dari ambang batas kepemilikan suara akan ditentukan oleh tolok ukur protokol.<p></p> Harap dicatat bahwa karena berbagai penyedia dompet pihak ketiga yang terintegrasi dengan Catalyst dan biaya pendaftaran pemilih terkait, ambang batas yang disarankan untuk berkomunikasi adalah 500 ADA yang diperlukan untuk berpartisipasi dalam pemungutan suara Catalyst sebagai penyangga untuk memperhitungkan hadiah staking yang tidak diklaim.
A14 | Tanggal snapshot pendaftaran | 18 Agustus 2023 21:00 UTC |
A15 | Waktu mulai periode pemungutan suara | 31 Agustus 2023, 11:00 UTC | Tanggal dan waktu UTC saat pemilih dapat mulai memberikan suara pada proposal
A16 | Waktu berakhirnya periode pemungutan suara | 14 September 2023, 11:00 UTC |
A17 | Awal penghitungan | 14 September 2023 |
A18 | Akhir penghitungan | 18 September 2023 | Tanggal UTC saat penghitungan yang didekripsi dipublikasikan
A19 | id_dana | 10 | Fund_id seperti yang dijelaskan dalam rencana pemungutan suara
A20 | Pengoptimalan penghitungan | 1 ADA = 1 token pemungutan suara (yaitu jumlah taruhan di lovelace dibagi dengan 1000000) | Bagaimana hak suara dikurangi secara proporsional untuk mengoptimalkan kinerja penghitungan suara
 | Parameter Hadiah |  |
B1 | Logika Pendanaan Proposal (aturan pemilihan pemenang) | Pemungutan suara ambang batas fuzzy, proposal diberi peringkat berdasarkan perbedaan suara Ya dan Tidak dan didanai satu per satu hingga anggaran tantangan habis | Proposal diurutkan berdasarkan jumlah suara dan didanai secara berurutan. Jika jumlah yang diminta oleh proposal lebih besar dari jumlah tantangan yang tersisa, proposal tersebut akan dilewati.
B2 | Ambang batas penerimaan proposal | 1% dari total hak suara<p></p> 15% lebih banyak yang menjawab 'Ya' daripada yang menjawab 'Tidak' | Setidaknya 1% dari total saham terdaftar harus memberikan suara pada proposal tersebut<p></p> Misalnya, ada 1 miliar ADA sebagai total saham terdaftar. Agar dapat diterima (menjadi 'proposal yang disetujui' sekaligus memenuhi syarat untuk pendanaan), proposal harus mendapat suara minimal 0,01 * (1 * 10^9) = 10 juta ADA<p></p> Perbedaan 'Ya'-'Tidak' pada suara yang diberikan pada proposal harus setidaknya 15%.<p></p> Rumus: (YA-TIDAK)/(YA+TIDAK) &gt; 0,15<p></p> (misalnya, 90% 'Ya' dan 10% 'Tidak', atau 57,6% 'Ya' dan 42,4% 'Tidak', atau 100% 'Ya' dan 0% 'Tidak', dll.; diasumsikan bahwa pemegang saham yang abstain tidak memberikan suara pada proposal dalam arsitektur saat ini
B3 | Opsi pemungutan suara dan logika pendanaan dalam kategori Operasi Catalyst | Ya/Abstain<br> Opsi 'Tidak'<p></p> Tidak ada ambang batas | Pemenangnya ditentukan oleh suara 'Ya' tertinggi saja
B4 | Totalitas | 2,50%<br> Rp 1.250.000 | Hadiah Pemilih<p></p> Hadiah diterima dengan memberikan suara
B5 | Seni total | 2,50%<br> Rp 1.250.000 | Hadiah Ulasan Komunitas<br> LV0 (20% saham)<br> LV1 (80% saham)
B6 | AArtotal | 0,40%<br> Rp 200.000 | Hadiah Moderator Komunitas<p></p> LV2 (hingga ₳5 ada untuk setiap pemeriksaan ulasan)
B7 | Jumlah total | 0,22%<br> Rp 110.000<p></p> ₳10.000 per CT<p></p> 30% (₳3.000) Hasil yang dapat dicapai 1<br> 70% (₳7.000) Hasil 2 | Hadiah Tim Tantangan yang dibayarkan untuk:<p></p> 1. Hasil akhir 1: Memperkenalkan tantangan selama peluncuran F10<p></p> 2. Hasil akhir 2: Mengintegrasikan FP dan melakukan verifikasi PoL
B8 | Pam | 1,20%<br> Rp 600.000<p></p> Perincian:<br> 0,40% ₳200.000 untuk<br> Proyek &lt; ₳150,000<br> - ₳200 per Milestone PoA<p></p> 0,80% ₳400.000 untuk<br> Proyek &gt; ₳150,000<br> - ₳300 per Milestone PoA | Penghargaan Manajemen Akuntabilitas Proyek<p></p> Pengulas Komunitas yang Bermanfaat membantu memverifikasi:<br> 1. Pernyataan Tonggak Sejarah (SoM)<br> 2. Bukti Pencapaian yang Menandai<p></p> [1] Proyek yang didanai akan menyerahkan Pernyataan Tonggak Sejarah kepada Catalyst<p></p> SoM diverifikasi oleh minimal 2 peninjau komunitas dan diberi penghargaan atas pekerjaan mereka.<p></p> [2] PoA dilakukan oleh perwakilan reviewer. Insentif PoA dibayarkan kepada reviewer.<p></p> Jika proposal bernilai lebih dari ₳200.000, tinjauan harus dilakukan oleh 2 peninjau terpisah.<p></p> Hadiah maksimum adalah ₳200/₳300 masing-masing untuk 2 peninjau yang melaksanakan PoA.
B9 | Formula Penghargaan Pemilih | Vrj=jumlah sahamJjumlah sahamVrtotal | Hadiah pemilih akan diberikan untuk partisipan aktif hanya secara proporsional dengan kekuatan suara yang dimiliki pemilih.<p></p> stakej - saham pemilih;<br> staketotal - jumlah total saham yang 'aktif'.
B10 | Ulasan Komunitas Formula Hadiah LV0 | 0,5%<br> Rp 250.000<p></p> % Bagian hadiah diambil dari 20% anggaran yang dialokasikan<p></p> Maksimum ₳17 per ulasan |
B11 | Rumus hadiah Ulasan Komunitas LV1 / $ harga per hadiah pengulas Komunitas LV1 | 2%<br> Rp 1.000.000<p></p> ₳33 per ulasan diambil dari 80% anggaran yang dialokasikan | Harga sederhana yang dibayarkan per ulasan 2% dari total anggaran
B12 | Rumus hadiah Ulasan Komunitas LV2 (Moderator Komunitas) / $ per hadiah Lv2 | 0,4% dari<br> Rp 200.000<p></p> Maksimum ₳5 per pemeriksaan ulasan yang ditandai LV2 |
B13 | # ulasan LV1 yang akan diberi hadiah dalam satu putaran | 10-80 Ulasan per Pengulas Komunitas LV1 diberi penghargaan berdasarkan parameter ini | Batasan berapa banyak LV1 individu dapat diberi imbalan atas alokasi mereka dalam satu putaran pendanaan.<p></p> Ambang batas hadiah minimum adalah ₳330 dalam ADA untuk 10 ulasan. Ulasan dengan jumlah di bawah jumlah ini tidak akan diberi hadiah.<p></p> Ulasan apa pun di atas jumlah alokasi ambang batas (80) akan dimasukkan ke dalam pot LV0
 | Parameter Back-End |  |
C1 | Status privasi pemungutan suara langsung | Ya | Apakah suara bersifat pribadi?
C2 | Dana terkendali | 50.000.000 ada | Dana akan mengendalikan 50 juta ada
C3 | Ambang batas kekuatan pemungutan suara | 450.000.000 tali cinta.<br> (450 ada)<p></p> Komunikasikan ambang batas sebesar 500 untuk memperhitungkan biaya tx | Ambang batas minimal kepemilikan saham untuk menjadi pemilih, berdasarkan pada tolok ukur efisiensi protokol pemungutan suara.<p></p> Nilai spesifik dari ambang batas kepemilikan hak suara akan ditentukan oleh tolok ukur protokol.<p></p> Perhatikan bahwa ambang batas harus diturunkan sebesar 50 ada dari jumlah yang dinyatakan kepada komunitas untuk mengatasi biaya pendaftaran.
Bahasa Indonesia: C4 | nama_dana_saat_ini | Dana10 |
C5 | berbagi_wawasan_saat_ini_mulai | 22 Juni 2023 |
C6 | pengajuan_proposal_saat_ini_mulai | 22 Juni 2023 |
C7 | current_refine_proposals_mulai | 22 Juni 2023 |
C8 | proposal_finalisasi_saat_ini_mulai | 13 Juli 2023 |
C9 | penilaian_proposal_saat_ini | 20 Juli 2023 |
C10 | penilaian_qa_saat_ini_mulai | 10 Agustus 2023 |
Bab 11 | snapshot_saat_ini_mulai | 18 Agustus 2023 |
C12 | mulai_pemungutan_suara_saat_ini | 31 Agustus 2023 |
C13 | pemungutan suara_saat_ini_berakhir | 14 September 2023 |
C14 | penghitungan_saat_ini_akhir | 18 September 2023 | 
