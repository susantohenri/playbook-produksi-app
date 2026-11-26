PLAYBOOK

# ASO-FIRST
ANDROID APP GROWTH

Workflow operasional dari kepala kosong sampai aplikasi tumbuh lewat Google Play

Fokus: organic discovery Google Play • listing conversion • localization • user quality • continuous optimization

Versi 1.0  |  26 November 2026
Asumsi kerja: aplikasi Android non-game, developer indie, biaya riset dan optimasi serendah mungkin, monetisasi utama AdMob, paid acquisition dan social promotion bukan mesin utama.

Dokumen ini adalah SOP kerja, bukan klaim formula ranking Google. Faktor resmi, fitur Play Console, dan kebijakan dirujuk ke dokumentasi Google. Skor, ambang keputusan, serta urutan eksperimen adalah aturan operasional yang disarankan dan harus dievaluasi dengan data aplikasi sendiri.

# Cara memakai playbook

Ikuti urutan tahap. Setiap tahap punya checklist, output, dan gate. Jangan lompat ke coding sebelum gate validasi lolos. Setelah aplikasi live, jalankan siklus data → diagnosis → perubahan → evaluasi.

| Prinsip | Aturan kerja |

| --- | --- |

| Checklist wajib | Centang setelah benar-benar dilakukan. Simpan bukti/link/screenshot bila keputusan penting. |

| Gate | Lanjut hanya bila output minimum tersedia. Jika belum, revisi atau hentikan kandidat. |

| Skip dengan alasan | Aktivitas opsional boleh dilewati hanya jika kriteria skip terpenuhi dan alasannya dicatat. |

| Satu eksperimen = satu hipotesis | Jangan mengubah title, icon, screenshots, negara, dan fitur sekaligus lalu mengklaim tahu penyebab hasil. |

| Data Play Console mengalahkan tebakan | Riset eksternal dipakai untuk memulai; query, negara, bahasa, konversi, dan kualitas aktual menentukan iterasi. |

| No ranking guarantee | Google tidak menerbitkan bobot formula ranking Search yang bisa dioptimalkan secara pasti. Jangan perlakukan skor tool sebagai faktor ranking resmi. |

## Peta perjalanan

| Tahap | Pekerjaan | Output wajib |

| --- | --- | --- |

| 0. Brief | Tetapkan tujuan, audience, batasan | App opportunity brief |

| 1. Discovery | Cari kebutuhan dan kandidat masalah | Backlog 10–20 masalah/ide |

| 2. Keyword | Petakan search intent dan frasa | Keyword map per intent |

| 3. SERP & kompetitor | Audit hasil Play Store dan kompetitor | SERP/competitor matrix |

| 4. Decision | Nilai peluang dan pilih kandidat | GO / HOLD / KILL |

| 5. Product plan | Turunkan intent menjadi MVP | PRD + feature-to-intent map |

| 6. Build & quality | Bangun produk yang memenuhi intent | Build siap uji |

| 7. Listing | Siapkan metadata dan aset | Listing pack lengkap |

| 8. Market setup | Negara, bahasa, kategori, tags | Market/language matrix |

| 9. Release | Policy, testing, rollout | Production release |

| 10. Learn | Baca akuisisi, search terms, behavior | Baseline + diagnosis |

| 11. Optimize | CSL, experiments, product iteration | Experiment log + backlog |

| Penting:  ASO bukan keyword stuffing. Ini sistem menyelaraskan query pengguna, listing, fungsi aplikasi, dan pengalaman setelah install. |

| --- |

# Tahap 0 — Tetapkan operating brief

Isi sebelum mencari ide. Tujuannya supaya riset tidak melebar ke pasar, fitur, atau model bisnis yang tidak akan dieksekusi.

☐  Pilih satu tujuan utama per aplikasi: install organik relevan, bukan sekadar jumlah download.

☐  Tetapkan model monetisasi: AdMob saja, AdMob + IAP, atau lainnya. Tandai fitur berbayar yang memang akan dibangun.

☐  Tentukan audience awal: siapa, masalahnya apa, dan konteks penggunaan kapan/di mana.

☐  Tetapkan satu negara/bahasa awal berdasarkan bukti demand, kemampuan lokalisasi, dan ketersediaan konten/dukungan.

☐  Tetapkan batas development: waktu MVP, kemampuan backend, biaya API/data, kebutuhan maintenance, dan risiko policy.

☐  Tetapkan definisi keberhasilan awal: ada query relevan, ada listing visitors, CTR dapat diukur, dan pengguna benar-benar menyelesaikan core task.

## Template brief

| Field | Isi yang harus diputuskan |

| --- | --- |

| Audience | [Segmen + situasi penggunaan] |

| Problem/job | [Tugas spesifik yang ingin diselesaikan] |

| Primary market | [Negara + bahasa] |

| Monetization | [AdMob / hybrid / lainnya] |

| MVP timebox | [Estimasi jam/hari development] |

| Hard constraints | [Offline/backend/API/content/policy] |

| Success condition | [Sinyal demand + kualitas + konversi yang ingin dibuktikan] |

| GATE: BRIEF | JIKA BELUM LOLOS |

| --- | --- |

| Ada audience, job-to-be-done, pasar awal, monetisasi, dan batasan yang jelas. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 1 — Discovery dari kepala kosong

Jangan brainstorming nama aplikasi dulu. Cari kebutuhan, task, dan ketidakpuasan yang sudah terlihat di ekosistem Play Store.

## Urutan discovery

→  Buka Google Play di kategori yang relevan dengan jenis kebutuhan: Tools, Productivity, Education, Lifestyle, Finance, Health & Fitness, Books & Reference, dan kategori lain sesuai konteks.

→  Jelajahi Top charts, Top free, kategori, hasil Search, aplikasi baru, dan rekomendasi yang terlihat pada akun/perangkat target.

→  Catat aplikasi yang sederhana, punya use case jelas, dan review terbaru yang menyebut masalah berulang.

→  Baca review bintang 1–3 dan review bintang 4–5. Cari pekerjaan yang gagal dilakukan, fitur yang diminta berulang, hambatan onboarding, iklan mengganggu, dan kebutuhan offline.

→  Cari pola di luar Play Store: Google Trends untuk arah tren/seasonality; komunitas dan forum untuk bahasa problem; Keyword Planner hanya sebagai sinyal pencarian Google, bukan volume Play Store.

→  Buat backlog masalah, bukan backlog fitur. Satu masalah boleh menghasilkan beberapa pendekatan aplikasi.

## Sumber discovery gratis

| Sumber | Gunakan untuk | Jangan disimpulkan |

| --- | --- | --- |

| Google Play Search/autocomplete | Bahasa/query yang dikenali Play dan alternatif yang disarankan | Bukan angka volume bulanan |

| Google Play kategori/Top charts | Peta aplikasi yang sedang terlihat pada kategori/pasar | Bukan bukti otomatis ada celah |

| Review Play Store | Pain points, requested features, ekspektasi pengguna | Satu review bukan pola pasar |

| Google Trends | Tren relatif dan seasonality di Google Search | Bukan volume pencarian Play Store |

| Keyword Planner | Ide keyword dan perkiraan pencarian Google Search | Bukan volume Play Search |

| AppBrain/ASO tools freemium | Estimasi install/ranking/metadata kompetitor jika tersedia | Angka install pihak ketiga bukan angka pasti |

## Checklist discovery

☐  Kumpulkan minimal 10 masalah/ide sebelum memilih satu.

☐  Untuk setiap kandidat, tulis siapa pengguna dan tugas spesifik yang ingin diselesaikan.

☐  Kumpulkan minimal 5 review relevan dari beberapa kompetitor bila tersedia.

☐  Catat bukti tanggal, negara, bahasa, query, dan URL aplikasi; hasil Play bisa berbeda antar pasar/perangkat.

☐  Buang ide yang hanya menarik bagi developer tetapi tidak punya bukti problem atau search intent.

| GATE: DISCOVERY | JIKA BELUM LOLOS |

| --- | --- |

| Backlog berisi masalah nyata, audience, contoh aplikasi pembanding, dan bukti awal. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 2 — Keyword research dan intent map

Keyword research dilakukan per masalah/intent, bukan mengumpulkan ratusan frasa tanpa struktur. Satu aplikasi sebaiknya punya satu primary intent yang kuat dan beberapa secondary intents yang masih satu pekerjaan.

## 2.1 Bentuk seed keywords

| Jenis seed | Pertanyaan | Contoh generik |

| --- | --- | --- |

| Task/action | Pengguna ingin melakukan apa? | hitung, cari, hafal, konversi, jadwalkan |

| Outcome | Hasil apa yang dicari? | harga jual, jadwal, nilai, terjemahan |

| Problem | Masalah apa yang ingin diatasi? | susah mengingat, salah hitung, lupa jadwal |

| Object/content | Apa objek yang dipakai? | resep, doa, peta, dokumen, satuan |

| Audience/context | Untuk siapa/dalam situasi apa? | pemula, siswa, UMKM, perjalanan |

| Synonym/local wording | Apa istilah sehari-hari/istilah lokal? | sinonim, ejaan alternatif, bahasa lokal |

## 2.2 Kumpulkan keyword

→  Masukkan seed satu per satu ke Google Play Search dan catat autocomplete yang muncul.

→  Periksa related phrases, spelling variations, istilah lokal, singular/plural, dan variasi kata kerja.

→  Buka listing kompetitor dan ambil istilah yang berulang pada title, short description, screenshot, serta review.

→  Kelompokkan frasa berdasarkan intent. Jangan gabungkan query yang mengharapkan produk atau hasil berbeda.

→  Periksa Google Trends untuk tren naik/turun dan musim. Jangan mengubah trend index menjadi volume Play.

→  Simpan keyword yang tidak relevan ke daftar negatif agar tidak masuk metadata, screenshot, atau CSL.

## 2.3 Skema keyword map

| Cluster / intent | Primary query | Related phrases | Fitur yang memenuhi intent | Prioritas |

| --- | --- | --- | --- | --- |

| [Cluster A] | [1 frasa utama] | [3–10 variasi] | [Fitur inti] | P1/P2/P3 |

| [Cluster B] | [1 frasa utama] | [3–10 variasi] | [Fitur pendukung] | P1/P2/P3 |

| [Cluster C] | [1 frasa utama] | [3–10 variasi] | [Fitur pendukung] | P1/P2/P3 |

## 2.4 Prioritaskan keyword

Nilai internal 0–5, bukan metrik resmi Google: kejelasan intent, bukti autocomplete/kompetitor, relevansi dengan fungsi aplikasi, dan kemungkinan bersaing dengan hasil yang ada. Prioritaskan intent yang jelas dan dapat dipenuhi aplikasi; jangan hanya mengejar frasa populer.

☐  Pilih 1 primary query/cluster untuk positioning utama aplikasi.

☐  Pilih 2–5 secondary intents yang berdekatan dengan fungsi inti.

☐  Tandai query brand/navigation (orang mencari aplikasi tertentu) agar tidak disalahartikan sebagai demand generik.

☐  Catat kata yang ambigu, berisiko trademark, atau tidak bisa dipenuhi app; keluarkan dari target.

| Batas data:  Google Play tidak menyediakan angka monthly search volume publik untuk semua keyword. Autocomplete, ranking, dan estimasi tool adalah proxy; setelah rilis, search terms yang terlihat di Play Console menjadi sumber bukti langsung yang lebih relevan. |

| --- |

| GATE: KEYWORD | JIKA BELUM LOLOS |

| --- | --- |

| Ada primary intent, cluster turunannya, pemetaan fitur, dan daftar query yang sengaja tidak ditargetkan. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 3 — Audit SERP dan kompetitor Play Store

Lakukan pencarian langsung di Google Play. Ini memeriksa kompetisi pada tempat pengguna benar-benar mencari, bukan hanya hasil Google Web.

## Prosedur audit

→  Cari primary query dan setiap cluster utama di Play Store.

→  Catat negara, bahasa, tanggal, perangkat, dan konteks akun saat melakukan observasi. Hasil dapat dipersonalisasi dan berubah.

→  Audit 10 hasil teratas yang relevan; pisahkan aplikasi yang benar-benar menjawab intent dari hasil yang sekadar memiliki kata mirip.

→  Buka 5 kompetitor paling dekat. Catat rating, jumlah rating/review, estimasi install jika tersedia, update terakhir, monetisasi, dan fitur inti.

→  Periksa 10–20 review terbaru dan review negatif yang berulang. Tandai keluhan yang belum dijawab update terbaru.

→  Bandingkan title, short description, urutan screenshot, preview video, category/tags, dukungan bahasa, dan negara distribusi.

→  Catat celah yang bisa dibuktikan: fitur absen, onboarding sulit, iklan berlebihan, offline tidak tersedia, hasil tidak akurat, UX buruk, atau konten tidak lengkap.

## Competitor matrix

| Keyword | App / package | Posisi observasi | Rating & reviews | Install estimate | Gap / bukti |

| --- | --- | --- | --- | --- | --- |

| [query] | [app A] | [posisi/tanggal/market] | [data] | [jika tersedia] | [review/fitur] |

| [query] | [app B] | [posisi/tanggal/market] | [data] | [jika tersedia] | [review/fitur] |

| [query] | [app C] | [posisi/tanggal/market] | [data] | [jika tersedia] | [review/fitur] |

## Checklist celah

☐  Apakah top results menjawab intent secara langsung?

☐  Apakah ada keluhan berulang yang bisa diselesaikan dengan scope MVP?

☐  Apakah hasil teratas didominasi brand mapan dengan review/ratings jauh lebih kuat?

☐  Apakah diferensiasi bisa terlihat jelas dalam 1–3 screenshot?

☐  Apakah aplikasi dapat memberi pengalaman yang setidaknya sebanding dengan ekspektasi pengguna dari listing kompetitor?

| GATE: SERP | JIKA BELUM LOLOS |

| --- | --- |

| Celah pasar teridentifikasi dan dibuktikan oleh fitur/review/UX, bukan asumsi. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 4 — Pilih ide: GO / HOLD / KILL

Gunakan scoring berikut untuk membandingkan kandidat. Ini rubric internal; bukan standar Google dan bukan prediksi ranking.

| Dimensi | Bobot | Skor 0–5 | Cara memberi nilai |

| --- | --- | --- | --- |

| Bukti demand / query | 25% | [ ] | Autocomplete, hasil Play yang relevan, tren stabil/naik, search terms kompetitor sebagai proxy. |

| Kejelasan intent | 20% | [ ] | Pengguna jelas mencari satu tugas/hasil, bukan query kabur. |

| Celah kompetitor | 20% | [ ] | Ada keluhan/fitur/kekurangan yang berulang dan dapat diperbaiki. |

| Kemampuan diferensiasi | 15% | [ ] | Perbedaan nyata dapat dibangun dan ditunjukkan pada listing. |

| Feasibility & maintenance | 10% | [ ] | MVP dapat dibangun tanpa data/API/beban maintenance yang tidak sanggup dipenuhi. |

| Fit AdMob/usage | 10% | [ ] | Ada usage yang masuk akal tanpa memaksa pengguna atau merusak core task. |

Hitung total = jumlah (skor/5 × bobot).

| Keputusan | Aturan operasional |

| --- | --- |

| GO: 70–100 | Lanjut PRD jika tidak ada risiko fatal dan primary intent bisa dipenuhi. |

| HOLD: 55–69 | Riset tambahan: cari query lebih spesifik, gap kompetitor, atau diferensiasi yang lebih jelas. |

| KILL: di bawah 55 | Simpan catatan dan hentikan. Jangan menghabiskan waktu development. |

| Veto regardless of score | Tidak feasible, melanggar policy, tidak punya hak atas konten/data, atau tidak bisa memberikan fungsi yang dijanjikan. |

| Kill cepat:  Tidak ada bukti problem + intent lemah + top results sudah sangat memadai + tidak ada diferensiasi yang realistis = stop. Jangan menyelamatkan ide hanya karena sudah telanjur membuat desain. |

| --- |

| GATE: IDEA | JIKA BELUM LOLOS |

| --- | --- |

| Satu kandidat GO, skor dan bukti disimpan, serta alasan kandidat lain di-HOLD/KILL terdokumentasi. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 5 — Turunkan keyword menjadi produk / MVP

Produk harus memenuhi intent yang dipakai untuk menarik pengguna. Jangan membuat listing menjanjikan fungsi yang baru berupa rencana.

## Feature-to-intent map

| Search intent | Ekspektasi setelah install | Fungsi minimum | Bukti di listing |

| --- | --- | --- | --- |

| [primary query] | [hasil yang pengguna harapkan] | [fitur inti yang benar-benar bekerja] | [screenshot 1/2] |

| [secondary query] | [hasil sekunder] | [fitur pendukung] | [screenshot 3/4] |

## Checklist product readiness

☐  Tentukan satu core action yang harus berhasil pada sesi pertama.

☐  Usahakan pengguna mendapat hasil utama tanpa login jika akun tidak dibutuhkan untuk fungsi inti.

☐  Minta permission hanya saat fitur terkait dipakai; jelaskan alasan dalam konteks.

☐  Pastikan empty state, offline/error state, dan hasil tidak tersedia ditangani dengan baik.

☐  Bila offline adalah diferensiasi, pastikan fungsi offline benar-benar lengkap dan dijelaskan akurat.

☐  Rancang repeat-use loop hanya jika kebutuhan memang berulang; jangan memaksakan streak/notifikasi pada tool satu kali pakai.

☐  Tempatkan iklan setelah core value jelas. Hindari interstitial yang memotong tugas utama atau memicu accidental click.

☐  Buat event analytics minimal untuk first_open, core_action_started, core_action_completed, error, ad_impression (jika perlu), dan key return event.

☐  Buat backlog dari review kompetitor dan kelompokkan menjadi must-have, nice-to-have, dan bukan scope MVP.

## PRD minimum

☐  Problem statement + target user

☐  Primary/secondary search intent

☐  Core user flow dan acceptance criteria

☐  Maksimal 3–5 fitur MVP yang memenuhi intent

☐  Non-goals / fitur yang sengaja tidak dibuat

☐  Ad placement map dan UX guardrails

☐  Data/event yang perlu diukur

☐  Release risks dan maintenance owner

| GATE: MVP | JIKA BELUM LOLOS |

| --- | --- |

| Fitur inti bekerja, value proposition terbukti di produk, dan semua klaim listing dapat didemokan. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 6 — Build, kompatibilitas, dan technical quality

Quality adalah bagian dari acquisition strategy. Google menyatakan metrik Android Vitals tertentu memengaruhi discoverability; masalah pada model perangkat tertentu dapat mengarahkan pengguna model tersebut ke aplikasi lain.

## Checklist build

☐  Gunakan Android App Bundle (.aab) untuk release Play baru.

☐  Target API level sesuai kebijakan yang berlaku pada tanggal submit. Pada 26 Nov 2026: app baru dan update wajib target Android 16 / API 36 atau lebih tinggi; aplikasi existing perlu API 35 atau lebih tinggi agar tersedia untuk pengguna baru di perangkat OS lebih baru.

☐  Tetapkan minSdk berdasarkan kebutuhan fitur dan data target devices, bukan sekadar mengejar angka kompatibilitas tertinggi.

☐  Jangan menambah hardware feature/permission declaration yang tidak diperlukan karena dapat mempersempit kompatibilitas.

☐  Tes release build, bukan hanya debug build. Uji cold start, first task, back navigation, rotation/responsive layouts bila didukung, low-memory, no-network, dan permission denied.

☐  Periksa crash, ANR, app startup, battery/network, ukuran app, dan accessibility.

☐  Upload mapping/debug symbols bila memakai obfuscation/native code agar stack trace dapat dibaca.

☐  Tinjau Device Catalog setelah bundle tersedia; pastikan model penting tidak ter-exclude tanpa alasan.

| Target API 2026:  Kebijakan yang berlaku sejak 31 Agustus 2026 mensyaratkan API 36 untuk aplikasi baru dan update. API 35 adalah batas untuk aplikasi existing agar tetap tersedia bagi pengguna baru di perangkat Android yang lebih baru. Verifikasi ulang halaman kebijakan sebelum setiap submission. |

| --- |

## Android Vitals watchlist

| Metric | Ambang bad behavior keseluruhan | Tindakan |

| --- | --- | --- |

| User-perceived ANR rate | ≥ 0.47% DAU | Buka cluster ANR; prioritaskan cluster dengan banyak user terdampak. |

| User-perceived crash rate | ≥ 1.09% daily users | Buka crash clusters dan lakukan perbaikan berurutan. |

| Device-level bad behavior | ≥ 8% DAU untuk satu model | Analisis model, Android version, RAM/SoC, dan versi app. |

| Battery / wake locks | Periksa sesuai jenis app dan status metrik | Untuk app biasa, jangan menambah background work tanpa alasan. |

Google umumnya melihat 28 hari terakhir untuk evaluasi kualitas, tetapi dapat bertindak lebih cepat bila terjadi lonjakan. Baca breakdown artifact, Android version, form factor, dan device model.

| GATE: TECH | JIKA BELUM LOLOS |

| --- | --- |

| Build sesuai API policy, release build lulus tes, deklarasi/permission tepat, dan tidak ada masalah kritis yang diketahui. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 7 — Siapkan listing pack sebelum publish

Jangan menulis listing dari nol pada hari rilis. Siapkan copy dan aset berdasarkan primary intent serta diferensiasi yang sudah lolos audit.

## 7.1 Metadata

| Elemen | Batas / aturan | Checklist |

| --- | --- | --- |

| App name / title | Maks. 30 karakter | Nama jelas, unik, mengandung konteks utama secara natural, tidak misleading. |

| Short description | Maks. 80 karakter | Satu kalimat manfaat terpenting; jangan menjejalkan keyword. |

| Full description | Maks. 4.000 karakter | Paragraf awal menjelaskan fungsi; lanjutkan fitur, use case, cara pakai, batasan. |

| Category | Satu kategori paling tepat | Pilih berdasar tujuan utama aplikasi. |

| Tags | Maks. 5 | Pilih hanya tags yang jelas relevan dari listing atau pengalaman awal. |

| Developer contact | Email dan detail yang valid | Support channel dipantau; privacy policy aktif. |

## 7.2 Susunan full description yang bisa dipakai

→  Pembuka: apa aplikasi ini dan masalah utama yang diselesaikan.

→  Benefit: apa yang pengguna bisa lakukan/hasilkan.

→  Fitur inti: daftar pendek fitur yang benar-benar tersedia.

→  Use case: variasi penggunaan yang masih satu intent.

→  Offline/data/privacy: jelaskan secara akurat bila relevan.

→  Batasan penting: kompatibilitas, kebutuhan internet, atau fitur yang memang tidak ada.

## 7.3 Screenshot sequence

| Slot | Tujuan | Isi |

| --- | --- | --- |

| 1 | Jawab “ini aplikasi apa dan apa hasilnya?” | Core value + layar hasil terbaik. |

| 2 | Buktikan core flow | Langkah utama atau input → hasil. |

| 3 | Diferensiasi | Fitur yang kompetitor kurang punya. |

| 4 | Trust / depth | Offline, data, variasi, akurasi, atau fitur pendukung yang relevan. |

| 5–8 | Objection handling | Use case tambahan yang sering muncul pada query/review. |

Persyaratan aset utama saat ini: icon 512×512 PNG; feature graphic 1024×500; phone listing 2–8 screenshots. Untuk kelayakan beberapa format rekomendasi, Google merekomendasikan setidaknya empat screenshot 1080 px atau lebih (portrait 1080×1920, landscape 1920×1080). Ikuti ukuran/format yang ditampilkan Console karena persyaratan perangkat berbeda.

☐  Gunakan capture UI aplikasi nyata; jangan menampilkan fitur yang belum ada.

☐  Pastikan urutan screenshot bisa dipahami tanpa membaca full description.

☐  Jangan membuat seluruh screenshot menjadi poster teks; tampilkan interface dan hasil.

☐  Lokalkan teks overlay untuk setiap bahasa yang ditargetkan.

☐  Isi alt text yang menjelaskan konteks screenshot.

☐  Video preview YouTube bersifat opsional: buat hanya jika demonstrasi video benar-benar menjelaskan nilai produk lebih baik daripada screenshot.

## 7.4 Policy check untuk aset

☐  Tidak ada klaim ranking, #1, award, promo price, “free”, atau “no ads” yang dilarang pada metadata/visual.

☐  Tidak ada keyword block, pengulangan tidak wajar, atau referensi misleading ke app/brand lain.

☐  Tidak ada testimonial anonim/tidak teratribusi.

☐  Tidak ada logo, karakter, atau materi pihak ketiga tanpa hak.

☐  Aset menunjukkan fungsi yang benar dan aman untuk general audience.

| GATE: LISTING | JIKA BELUM LOLOS |

| --- | --- |

| Title, short/full description, category/tags, icon, feature graphic, screenshots, translations awal, dan policy review siap. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 8 — Negara, bahasa, dan distribusi

Jangan menerjemahkan semua bahasa sekaligus. Pilih pasar yang didukung bukti keyword, competitor demand, bahasa produk, dan kemampuan support.

## Urutan ekspansi pasar

→  Tentukan primary country + language dari riset awal.

→  Tentukan country availability di Play Console. Pastikan produk, konten, legal, support, dan monetization tersedia di sana.

→  Tambahkan listing translation untuk bahasa yang punya peluang. Terjemahkan title, short, full, screenshot overlays, dan app strings yang benar-benar terlihat.

→  Periksa local wording, decimal/currency/date formats, measurement units, examples, and cultural references.

→  Bandingkan visitors, clicks/CTR, acquisitions, ratings, and retention per country/language setelah data muncul.

→  Ekspansi ke bahasa/negara berikutnya bila ada evidence atau biaya lokalisasinya kecil dibanding potential reach.

## Market-language matrix

| Market | Language / locale | Evidence | Listing + screenshots | In-app localized? | Decision |

| --- | --- | --- | --- | --- | --- |

| [Country A] | [locale] | [query/competitors] | Yes/No | Yes/No | Launch/Test/Skip |

| [Country B] | [locale] | [query/competitors] | Yes/No | Yes/No | Launch/Test/Skip |

| [Country C] | [locale] | [query/competitors] | Yes/No | Yes/No | Launch/Test/Skip |

| Waspada CSL vs translation:  Custom Store Listings tidak otomatis mendapat automated translation. Jika CSL ditargetkan ke pengguna dengan bahasa lain, tambahkan terjemahan CSL yang sesuai; jika tidak, listing dapat tampil dalam bahasa default CSL. |

| --- |

| GATE: MARKET | JIKA BELUM LOLOS |

| --- | --- |

| Negara distribusi, default language, prioritas terjemahan, dan batasan support diputuskan. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 9 — Play Console setup, policy, dan release

## 9.1 App setup

☐  Buat app, pilih app/game, free/paid, default language, dan package name yang final.

☐  Isi Store listing dan Store settings: category, tags, contact, target distribution, external marketing preference.

☐  Pastikan preview assets ter-upload pada Main store listing.

☐  Isi App content: privacy policy, ads declaration, app access/login instructions, target audience, content rating, Data safety, dan permission declarations sesuai kebutuhan app.

☐  Jika audience mencakup anak, periksa Families Policy dan persyaratan SDK iklan yang berlaku.

☐  Pastikan kebijakan privasi tersedia di URL publik yang valid, bukan file PDF atau halaman yang butuh login.

## 9.2 Testing

☐  Internal testing untuk smoke test build dan alur dasar.

☐  Closed/open testing bila perlu feedback pengguna atau ada syarat akun developer yang berlaku.

☐  Periksa pre-launch report: stability, compatibility, performance, accessibility, screenshots.

☐  Berikan test credentials/instructions jika crawler perlu melewati login.

☐  Uji pada perangkat Android yang mewakili target audience dan ukuran layar yang didukung.

☐  Pastikan listing menjanjikan hanya hal yang lolos uji.

## 9.3 Production checklist

☐  Upload AAB dan review release warnings.

☐  Pilih negara distribusi dengan sadar; jangan sekadar memilih semua negara bila belum siap support.

☐  Isi release notes singkat dan faktual.

☐  Pilih staged rollout untuk update yang berisiko; untuk launch awal, tentukan rollout scope secara sengaja.

☐  Periksa Publishing overview dan kirim seluruh perubahan yang masih menunggu review.

☐  Setelah live, buka listing dari Play Store target market untuk memeriksa bahasa, aset, dan tombol install.

| GATE: RELEASE | JIKA BELUM LOLOS |

| --- | --- |

| App live dan dapat diinstall pada negara/perangkat target; listing tampil benar; tidak ada policy blocker. | Jangan lanjut. Revisi tahap ini atau hentikan kandidat. |

# Tahap 10 — Baseline dan sumber data Play Console

Begitu app live, berhenti menebak. Buat snapshot baseline. Simpan export atau screenshot dengan rentang tanggal dan filter yang sama agar bisa dibandingkan.

## Menu utama yang harus dikenal

| Area Console | Fungsi dalam workflow | Kapan dibuka |

| --- | --- | --- |

| Grow users overview | Akuisisi pengguna/perangkat dan sumber traffic Play | Weekly |

| Store performance → Conversion analysis | Visitors, unique clicks, CTR; filter source, listing, country, language, UTM, acquisition state | Weekly |

| Search terms / search term breakdown | Query yang membawa visitor dan kandidat CSL | Weekly / saat data muncul |

| Store listings | Default listing, translations, custom listings, experiments | Saat build/optimasi |

| Ratings and reviews | Rating trend, review themes, reply | Weekly |

| Android vitals | Crash, ANR, battery, compatibility, device breakdown | Weekly; segera jika alert |

| Reach and devices → Device catalog | Supported/excluded device coverage | Saat launch dan saat ada issue |

| Pre-launch report | Stability, compatibility, performance, accessibility test | Setiap bundle yang diuji |

## Perubahan metrik listing 2026 — wajib dipahami

| Mulai Juni/Juli 2026:  Store listing performance berfokus pada unique clicks (intent) seperti klik Install, Open, atau Pre-register. Successful user acquisitions tetap dilihat di Grow users overview, Statistics, dan downloadable reports. Jangan menyamakan unique install clicks dengan completed installs. |

| --- |

| Metrik | Artinya | Gunakan untuk |

| --- | --- | --- |

| Store listing visitors | Pengguna yang melihat listing sesuai definisi report | Ukuran kesempatan listing |

| Unique user clicks | Pengguna unik yang klik Install/Open/Pre-register | Intent terhadap listing |

| CTR | Clicks ÷ visitors (sesuai metric/report filter) | Mengevaluasi listing assets/copy |

| User acquisitions | Pengguna baru yang acquired | Hasil acquisition |

| Device acquisitions | Jumlah device install; bisa termasuk device tambahan | Jangan disamakan dengan jumlah orang |

| Traffic source | Explore, Paid and direct, Pre-installs, Not attributed, dll. | Pisahkan organic Play dari sumber lain |

| Search terms | Query Play yang terlapor membawa traffic | Keyword mining + CSL candidates |

## Baseline snapshot

| Tanggal/range | Source | Country / language | Visitors | Clicks / CTR | Acquisitions | Notes |

| --- | --- | --- | --- | --- | --- | --- |

| [date range] | Google Play Search | [market/locale] | [ ] | [ ] | [ ] | [ ] |

| [date range] | Google Play Explore | [market/locale] | [ ] | [ ] | [ ] | [ ] |

| [date range] | Paid/direct/referral | [market/locale] | [ ] | [ ] | [ ] | [ ] |

Catat juga: rating/rating count, installs/uninstalls, active users, core-action completion, retention, crash/ANR, dan top negative review themes. Pakai satu rentang waktu konsisten, misalnya 7/28 hari.

# Tahap 11 — Post-launch diagnosis dan action rules

Tentukan bottleneck sebelum mengedit apa pun. Gunakan pohon keputusan berikut sebagai urutan diagnosis.

| Gejala | Periksa dahulu | Tindakan pertama |

| --- | --- | --- |

| Search visitors sangat rendah | Primary query, country/language, availability, category, indexing/listing state, competition | Periksa relevansi title/short description, apakah query benar-benar ada di Play search; jangan langsung mengubah semua metadata. |

| Search visitors ada, CTR rendah | CTR vs peer median/percentile, icon, title, short description, first screenshots, locale fit | Jalankan eksperimen listing yang paling mungkin memperjelas value. |

| CTR sehat, acquisitions tidak sejalan | Bedakan clicks vs acquisitions; compatibility, install failure, returning users, report definition | Periksa Grow overview, Statistics, device compatibility, dan funnel. |

| Install ada, uninstall cepat | Review, crash/ANR, permissions, onboarding, ad interruption, expectation mismatch | Perbaiki core experience dan listing honesty. |

| Install ada, core action rendah | First session, tutorial, login, unclear CTA, empty state, performance | Perbaiki activation dan ukur lagi. |

| Negara A bagus, negara B buruk | Language, query intent, country-level CTR, device reach, support/product fit | Localized listing/CSL jika cukup bukti; jangan terjemahkan membabi buta. |

| Satu device model punya issue | Android Vitals breakdown + Device Catalog | Perbaiki kompatibilitas atau batasi hanya jika ada alasan teknis yang valid. |

## Jadwal pemeriksaan

| Waktu | Pemeriksaan | Keputusan yang boleh dibuat |

| --- | --- | --- |

| Hari 0–3 | Live status, installability, policy, listing, crashes, major errors | Fix blocker saja; jangan buru-buru menyimpulkan ranking. |

| Hari 4–7 | Traffic source, first search terms jika tersedia, review awal, vitals | Temukan error/intent mismatch; jangan membuat A/B test tanpa traffic cukup. |

| Hari 8–14 | Visitors, clicks/CTR, country/language, competitor changes | Pilih satu bottleneck dan satu hipotesis. |

| Hari 15–28 | Search terms, acquisition, activation/retention, reviews, vitals | Buat CSL/experiment hanya jika sample cukup. |

| Setiap 28 hari | Bandingkan periode, peer benchmark, trend negara, review clusters | Keep / iterate / rollback / stop investing. |

| Low-volume rule:  Kalau traffic belum cukup untuk membaca pola atau calculator eksperimen memproyeksikan durasi terlalu panjang, jangan memaksa A/B test. Pakai data kualitatif (SERP, review, usability), lakukan satu perubahan terkontrol, lalu tunggu data yang memadai. |

| --- |

# Tahap 12 — Custom Store Listings (CSL) playbook

CSL bukan halaman SEO tambahan dan tidak otomatis menaikkan ranking query. Fungsinya menyesuaikan listing bagi segmen pengguna yang ditargetkan. Google saat ini mengizinkan hingga 50 CSL per aplikasi.

## Prioritas penggunaan CSL

| Urutan | Target | Gunakan saat | Skip saat |

| --- | --- | --- | --- |

| 1 | Search keywords | Search terms / traffic memberi bukti cluster query; setiap cluster punya pesan/screenshot berbeda. | Belum ada traffic atau semua query punya intent yang sama. |

| 2 | Country/region | Negara berbeda membutuhkan value proposition, konten, atau visual lokal. | Perbedaan hanya bendera/terjemahan literal; belum ada data market. |

| 3 | Custom URL | Ada sumber traffic milik sendiri yang memang butuh landing message khusus. | Tidak ada channel/link destination yang relevan. |

| 4 | Lapsed/churned users | Ada fitur/update baru yang nyata untuk mengajak kembali. | App tidak punya update/reason-to-return. |

| 5 | Custom audiences / buyers | App punya audience signals dan use case bisnis/purchase yang nyata. | App sederhana, tidak ada segmentasi atau data cukup. |

| 6 | Pre-registration / ads traffic | Ada preregistration atau kampanye aktif dan memang perlu message berbeda. | Tidak menggunakan pre-reg/Google Ads. |

## Prosedur CSL berdasarkan Search Keywords

→  Buka Grow users → Store presence → Custom store listings → Create custom store listing.

→  Pilih target audience = Search keywords.

→  Pilih query yang Play Console tandai/kenali membawa traffic; Console juga memungkinkan pencarian keyword baru.

→  Periksa View variations: spelling corrections dan translations; keluarkan variasi yang salah intent.

→  Kelompokkan beberapa keyword yang punya satu intent menjadi satu listing. Hindari satu CSL per keyword kecuali ada alasan kuat dan volume cukup.

→  Buat title, descriptions, icon/screenshots yang menonjolkan fungsi yang menjawab cluster tersebut.

→  Preview listing pada bahasa dan perangkat terkait; pastikan custom listing memiliki terjemahan sendiri bila perlu.

→  Publish, catat tanggal, keyword bundle, assets, dan baseline. Ukur clicks/CTR dan acquisitions secara terpisah.

## Checklist CSL

☐  Cluster query punya bukti traffic atau alasan riset yang kuat.

☐  User intent dalam satu cluster konsisten.

☐  Pesan utama atau screenshot benar-benar berbeda dari default listing.

☐  Tidak ada overlap country targeting yang melanggar aturan (satu negara hanya dapat ditarget oleh satu CSL country listing pada satu waktu).

☐  Nama/icon/deskripsi tetap akurat terhadap aplikasi.

☐  Bahasa CSL dipastikan; jangan mengandalkan automated translation untuk CSL.

| Start small:  Mulai dari 1–3 CSL yang paling kuat, bukan membuat puluhan listing sekaligus. Gunakan 50-slot limit sebagai kapasitas, bukan target yang harus dihabiskan. |

| --- |

# Tahap 13 — Store Listing Experiments

Gunakan eksperimen saat ada traffic yang memadai. Play Console punya satu default graphics experiment per app dan hingga lima localized experiments bersamaan. Default graphics menguji icon, feature graphic, dan screenshots; localized experiments juga dapat menguji teks/deskripsi pada bahasa terkait.

## Urutan eksperimen yang disarankan

| Urutan | Asset | Hipotesis contoh | Metric/segment |

| --- | --- | --- | --- |

| 1 | Icon | Icon lebih mudah dikenali di hasil search/category | Unique install clicks; listing default |

| 2 | Screenshot pertama | Benefit utama lebih jelas sebelum scroll | Unique install clicks; query/country |

| 3 | Screenshot 2–4 | Use case utama lebih meyakinkan | Unique install clicks |

| 4 | Short description / localized copy | Pesan lebih sesuai intent/bahasa | Localized experiment |

| 5 | Feature graphic / video | Visual lebih cepat menjelaskan fungsi | Default/localized sesuai availability |

## Prosedur

→  Tulis hipotesis dan metrik utama sebelum membuat variant.

→  Pilih satu asset/elemen untuk menghindari confounding.

→  Gunakan experiment calculator Play Console untuk estimasi traffic dan durasi/statistical significance.

→  Ikuti rekomendasi periode; praktik Google menyarankan setidaknya satu minggu untuk memperhitungkan weekday/weekend.

→  Jangan mengubah listing lain, targeting, atau app functionality bersamaan tanpa dicatat.

→  Catat variant, tanggal mulai/selesai, result, segment, confidence/significance bila tersedia, dan keputusan.

→  Implement winner bila hasil kuat; jika inconclusive, pertahankan control dan perbaiki hipotesis.

## Experiment log

| ID / date | Hypothesis | Control vs variant | Audience / language | Result | Decision / next test |

| --- | --- | --- | --- | --- | --- |

| [E-01] | [why variant should win] | [asset A vs B] | [segment] | [result] | Keep / revert / retest |

| [E-02] | [hypothesis] | [A vs B] | [segment] | [result] | [decision] |

# Tahap 14 — Review, retention, vitals, dan device coverage

## Ratings & reviews

☐  Pantau rating trend, recent reviews, rating distribution, dan top issue themes.

☐  Kelompokkan review menjadi bug, UX, missing feature, content accuracy, ads, device compatibility, support, dan expectation mismatch.

☐  Balas review yang memerlukan bantuan dengan informasi relevan; jangan meminta perubahan rating sebagai syarat bantuan.

☐  Gunakan In-App Review API setelah pengguna menyelesaikan pengalaman bermakna; jangan menjanjikan hadiah atau memaksa rating.

☐  Jangan membeli, mengotomasi, menukar, atau menginsentifkan rating/review/install.

## Retention dan core value

Google menyebut DAU/MAU sebagai salah satu metrik yang digunakan untuk menilai core value; MAU dihitung sebagai orang yang membuka aplikasi setidaknya sekali dalam 28 hari. Jangan menganggap satu target DAU/MAU universal cocok untuk semua kategori. Aplikasi utilitas episodik bisa punya pola penggunaan berbeda dari social app.

☐  Ukurlah apakah pengguna berhasil menyelesaikan tugas utama, bukan hanya berapa lama app terbuka.

☐  Cari titik drop-off sebelum core action selesai.

☐  Perbaiki crash, onboarding, permission friction, latency, dan iklan interruptive sebelum menambah gimmick retention.

☐  Buat notifikasi hanya jika berguna, diharapkan, dan dapat dikontrol pengguna.

## Vitals dan device catalog

☐  Periksa Android Vitals sekurangnya mingguan dan lebih cepat jika ada alert/anomali.

☐  Gunakan breakdown versi app, Android version, form factor, dan device model untuk menemukan konsentrasi masalah.

☐  Buat custom peer groups untuk membandingkan vitals/ratings bila berguna; Vitals custom group memerlukan 8–12 aplikasi.

☐  Buka Device Catalog untuk memeriksa supported, partially supported, unsupported, dan excluded devices.

☐  Jangan mengecualikan model hanya karena murah/lambat. Lakukan hanya jika ada alasan teknis teruji dan hitung konsekuensi reach.

# Tahap 15 — Fitur Google Play: pakai / skip dengan sengaja

Tidak semua fitur harus digunakan pada semua aplikasi. Tabel ini mencegah waktu habis untuk fitur yang tidak tersedia atau tidak relevan.

| Fitur | Status / manfaat | Keputusan default |

| --- | --- | --- |

| Search terms + conversion analysis | Core; keyword/market/listing performance | WAJIB dipakai setelah data tersedia |

| Store Listing Experiments | Gratis A/B test listing; perlu sample cukup | PAKAI saat traffic memadai |

| Custom Store Listings | Hingga 50; keyword, country, URL, audience | PAKAI bertahap berdasarkan data |

| Translations/localized assets | Menjangkau bahasa yang dipilih pengguna | PAKAI pada market tervalidasi |

| Category + tags | Kategori + maksimal 5 tags relevan | WAJIB konfigurasi sekali; review bila produk berubah |

| External marketing | Google dapat memakai aset untuk properti Google; ada setting opt-out | Review setting; bukan jaminan ranking |

| Promotional Content | Untuk semua game dan app yang memenuhi eligibility Premium growth tools | SKIP kecuali akses tersedia dan ada event baru yang nyata |

| Play Shorts | Program terbatas pada partner terpilih; dokumentasi menyebut ketersediaan awal US | SKIP kecuali menu/eligibility tersedia di Console |

| Pre-registration | Membangun minat sebelum app tersedia | SKIP untuk MVP kecil tanpa alasan demand prelaunch |

| Device-specific screenshots | Tablet/foldable/TV/Wear/Automotive/XR | PAKAI hanya jika UX benar-benar mendukung form factor |

| Peer benchmarks | Membandingkan CTR/vitals/ratings dengan peer group bila data cukup | PAKAI saat benchmark muncul |

| Pre-launch report | Automated crawl stabilitas/kompatibilitas/performa/aksesibilitas | PAKAI setiap bundle; review hasil |

| Google Ads | Paid acquisition | DI LUAR scope ASO organik; hanya uji bila budget dan unit economics siap |

| Backlinks/social/PR | External referrals | SEKUNDER; jangan jadi fokus utama workflow ini |

## Promotional Content — syarat keputusan

☐  Periksa apakah akun/app memiliki akses Premium growth tools.

☐  Gunakan hanya untuk event baru, noteworthy, user-facing, dan berjalan di dalam app pada periode yang sama.

☐  Jika meminta featuring, cek deadline dan kuota pada Console; broad-target app event dan specific-audience event memiliki allotment berbeda.

☐  Jika tidak ada event/akses, jangan memaksakan evergreen content sebagai event.

## Play Shorts — status akses

Dokumentasi Play Console yang tersedia per 26 November 2026 menyebut akses program terbatas pada partner terpilih dan availability awal hanya di Amerika Serikat. Jangan menyusun workflow produksi konten Shorts untuk aplikasi sebelum menu dan eligibility benar-benar tersedia pada akunmu.

# Tahap 16 — Skip rules: yang boleh sengaja tidak dikerjakan

| Aktivitas | Skip jika… | Jangan skip jika… |

| --- | --- | --- |

| Backlink campaign | Tidak ada bukti referral berkualitas atau waktu lebih bernilai untuk listing/product | Referral menjadi sumber acquisition terukur atau ada partnership relevan |

| Social media content rutin | Tidak ada kapasitas dan tidak menghasilkan traffic berkualitas | Dipakai untuk validasi audience atau mengirim traffic yang bisa diukur |

| Translate ke banyak bahasa sekaligus | Belum ada evidence market, produk belum dilokalkan, tidak bisa support | Ada search terms/visitor dari bahasa itu dan mampu memenuhi ekspektasi |

| CSL per keyword | Query masih sepi atau intent-nya sama | Cluster terpisah punya traffic dan butuh message/visual berbeda |

| A/B testing | Traffic terlalu rendah untuk hasil yang berguna | Calculator menunjukkan sample/durasi masuk akal |

| Promo Content | Tidak memenuhi Premium growth eligibility atau tidak ada event baru | Console memberi akses dan ada event/update sungguhan |

| Play Shorts | Tidak terpilih sebagai partner / market belum tersedia | Console menunjukkan akses dan target market didukung |

| Video listing | Screenshot + UI demo sudah menjelaskan fungsi dan video tak memberi info tambahan | Produk kompleks, interaksi sulit terlihat dari screenshot |

| Tablet/foldable/TV/Wear assets | App tidak mendukung UX form factor itu | Ada layout khusus dan pengguna target di perangkat tersebut |

| Push notification/retention gimmick | Use case tidak berulang atau tidak ada manfaat bagi pengguna | Notifikasi menyelesaikan kebutuhan yang sah dan dapat dikontrol |

| Pre-registration | MVP bisa dirilis cepat dan belum ada audience prelaunch | Produk butuh lead time, demand, atau kampanye peluncuran |

| Paid traffic | Budget/monetization/retention belum tervalidasi | Ada budget eksperimen terpisah dan tracking yang benar |

| Catat setiap skip:  Tulis fitur/aktivitas yang di-skip, alasan, tanggal, dan kondisi yang akan memicu evaluasi ulang. Dengan begitu “tidak relevan” menjadi keputusan yang dapat diaudit, bukan kelupaan. |

| --- |

# Tahap 17 — Operating cadence

| Cadence | Routine | Artefak yang disimpan |

| --- | --- | --- |

| Setiap hari (5–10 menit) | Check policy/release alerts dan vitals anomali jika sedang rollout | Issue log |

| Mingguan | Grow overview, conversion analysis, search terms, reviews, vitals, country/language | Weekly ASO snapshot |

| Dua mingguan | Pilih satu bottleneck, satu hipotesis, satu perubahan/experiment | Experiment backlog |

| Bulanan / 28 hari | Bandingkan acquisition, CTR, country/language, reviews, quality, retention | Monthly decision memo |

| Saat rilis fitur | Update listing only if user-facing value materially changed; re-evaluate tags if function/content significantly changed | Release + listing changelog |

| Per market expansion | Re-check keywords, language, competitors, translation quality, support, distribution | Market launch checklist |

## Aturan urutan prioritas backlog

→  Policy / technical blocker yang membatasi distribusi.

→  Crash / ANR / compatibility yang berdampak pada pengguna.

→  High-intent search traffic rendah atau listing CTR jauh di bawah peer benchmark.

→  Expectation mismatch: install terjadi tetapi core task tidak berhasil.

→  Country/language dengan traffic berarti dan konversi tertinggal.

→  Fitur tambahan hanya setelah masalah utama di atas terkendali.

# Template kerja yang bisa disalin

## A. Opportunity card

| Field | Isi |

| --- | --- |

| Opportunity ID / date | [ ] |

| Problem / audience | [ ] |

| Primary job-to-be-done | [ ] |

| Primary keyword / intent | [ ] |

| Related keyword clusters | [ ] |

| Demand evidence | [Play autocomplete / SERP / Trends / review] |

| Competitor gap evidence | [App + review + feature gap] |

| MVP differentiation | [ ] |

| Monetization fit | [ ] |

| Risks / policy / data rights | [ ] |

| Score / decision | [ ] GO / HOLD / KILL |

## B. Keyword cluster worksheet

| Cluster | Query | Market/locale | Evidence | Intent | Feature match | Priority |

| --- | --- | --- | --- | --- | --- | --- |

| [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |

| [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |

| [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |

## C. Weekly ASO review

☐  Periode dan filters sama dengan snapshot sebelumnya.

☐  Acquisitions dan traffic source: perubahan apa yang paling besar?

☐  Search terms baru: intent mana yang relevan/tidak relevan?

☐  Country/language: pasar mana yang punya traffic tetapi CTR/quality lemah?

☐  CTR: bandingkan peer benchmark bila tersedia.

☐  Reviews: apa 3 issue yang paling berulang?

☐  Vitals: issue mana yang paling banyak user terdampak?

☐  Keputusan: keep / test / fix / rollback / kill. Satu owner dan due date.

## D. Change log

| Date | Area | Before | Change | Reason / hypothesis | Result | Decision |

| --- | --- | --- | --- | --- | --- | --- |

| [ ] | [listing/product/market] | [ ] | [ ] | [ ] | [ ] | [ ] |

| [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |

# Sumber resmi dan referensi

Dokumentasi Google Play berubah dari waktu ke waktu. Gunakan halaman berikut sebagai rujukan saat mengerjakan tahap terkait; periksa lagi sebelum mengirim app/update, terutama bagian policy, target API, CSL, dan fitur program.

R01  Understand and grow your app’s user base (reports, unique clicks, traffic source, search terms) — https://support.google.com/googleplay/android-developer/answer/9859173

R02  Run A/B tests on your store listing — https://support.google.com/googleplay/android-developer/answer/12053285

R03  Store listing experiments best practices — https://google.play/business/store-listing-experiments/

R04  Create custom store listings (targeting, keywords, limits, audiences) — https://support.google.com/googleplay/android-developer/answer/9867158

R05  Translate and localize your app — https://support.google.com/googleplay/android-developer/answer/9844778

R06  Choose a category and tags — https://support.google.com/googleplay/android-developer/answer/9859673

R07  Best practices for your store listing — https://support.google.com/googleplay/android-developer/answer/13393723

R08  Metadata policy — https://support.google.com/googleplay/android-developer/answer/9898842

R09  Add preview assets to showcase your app (icon, feature graphic, screenshots) — https://support.google.com/googleplay/android-developer/answer/9866151

R10  Monitor technical quality with Android vitals — https://support.google.com/googleplay/android-developer/answer/9844486

R11  Target API level requirements for Google Play apps (updated 2026) — https://support.google.com/googleplay/android-developer/answer/11926878

R12  Prepare your app for review (App content, privacy, ads, audience, data safety) — https://support.google.com/googleplay/android-developer/answer/9859455

R13  Prepare and roll out a release — https://support.google.com/googleplay/android-developer/answer/9859348

R14  Use a pre-launch report to identify issues — https://support.google.com/googleplay/android-developer/answer/9842757

R15  View and restrict compatible devices / Device Catalog — https://support.google.com/googleplay/android-developer/answer/7353455

R16  Ratings, reviews, and installs policy — https://support.google.com/googleplay/android-developer/answer/9898684

R17  Promotional content eligibility and setup — https://support.google.com/googleplay/android-developer/answer/12932541

R18  Manage Play Shorts in Play Console (eligibility and availability) — https://support.google.com/googleplay/android-developer/answer/17165227

R19  Compare Android vitals and ratings with custom peer groups — https://support.google.com/googleplay/android-developer/answer/9842755

---

End of playbook. Perubahan menu/eligibility dapat terjadi; untuk keputusan yang bergantung pada tanggal, cek dokumen Google terbaru dan nilai yang tampil pada Play Console akun aplikasi.
