# Awesome AI Indonesia [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Kecerdasan artifisial untuk bahasa Indonesia, data Indonesia, dan usaha di Indonesia.

Daftar kurasi sumber daya AI untuk developer dan UMKM Indonesia: model yang paham bahasa Indonesia dan bahasa daerah, dataset dan benchmark, pustaka NLP, suara (ASR dan TTS), data publik, komunitas, tempat belajar, regulasi, cara membayar API AI dengan metode pembayaran lokal, server MCP, dan otomasi. Setiap tautan dicek manual dan oleh skrip mingguan; tanggal pengecekan terakhir ada di bagian Footnotes.

**English summary:** A curated list of AI resources for Indonesian developers and small businesses (UMKM): open models that understand Indonesian and regional languages (Javanese, Sundanese, Balinese and more), Indonesian NLP datasets and benchmarks, libraries, speech models, public data APIs, communities, Indonesian-language courses, AI policy and regulation in Indonesia, AI API access that accepts local payment methods such as QRIS, MCP servers for Indonesian data, and n8n automation. Descriptions are in Indonesian; every link was checked by hand and is re-checked weekly by a script.

## Contents

- [Model Bahasa Besar (LLM)](#model-bahasa-besar-llm)
- [Model Encoder dan Embedding](#model-encoder-dan-embedding)
- [Dataset dan Benchmark](#dataset-dan-benchmark)
- [Pustaka dan Alat NLP](#pustaka-dan-alat-nlp)
- [Suara: ASR dan TTS](#suara-asr-dan-tts)
- [Data Publik dan API Pemerintah](#data-publik-dan-api-pemerintah)
- [Layanan AI Lokal](#layanan-ai-lokal)
- [Komunitas](#komunitas)
- [Belajar AI](#belajar-ai)
- [Regulasi dan Kebijakan](#regulasi-dan-kebijakan)
- [Akses API AI dengan Pembayaran Lokal](#akses-api-ai-dengan-pembayaran-lokal)
- [MCP dan Agen AI](#mcp-dan-agen-ai)
- [Otomasi](#otomasi)
- [Daftar Terkait](#daftar-terkait)
- [FAQ](#faq)

## Model Bahasa Besar (LLM)

- [GoTo-AI Gemma 3 27B IT](https://huggingface.co/GoToCompany/gemma3-27b-cpt-gotoai-v3-instruct) - Model 27B dari GoTo bersama AI Singapore (Oktober 2026) untuk bahasa Indonesia, Jawa, Sunda, Batak Toba, dan Bali, konteks 128 ribu token, lisensi Gemma.
- [Sahabat-AI 70B](https://huggingface.co/GoToCompany/Llama-Sahabat-AI-v2-70B-IT) - Model 70B Sahabat-AI dari GoTo dan Indosat berbasis Llama 3.1, dilatih lanjut untuk bahasa Indonesia dan bahasa daerah.
- [Sahabat-AI 9B](https://huggingface.co/GoToCompany/gemma2-9b-cpt-sahabatai-v1-instruct) - Versi 9B berbasis Gemma 2 yang muat di satu GPU, juga tersedia versi Llama 3 8B dari pembuat yang sama.
- [SEA-LION](https://sea-lion.ai) - Keluarga model terbuka AI Singapore untuk bahasa Asia Tenggara termasuk Indonesia, generasi v4 tersedia dalam beberapa ukuran termasuk varian visi.
- [Sailor2](https://huggingface.co/sail/Sailor2-8B-Chat) - Model chat Sea AI Lab (1B, 8B, 20B) untuk bahasa Asia Tenggara termasuk Indonesia dan Jawa, lisensi Apache-2.0.
- [SeaLLMs v3](https://huggingface.co/SeaLLMs/SeaLLMs-v3-7B-Chat) - Model chat 1,5B dan 7B dari DAMO Academy untuk bahasa Asia Tenggara termasuk Indonesia.
- [Komodo-7B](https://huggingface.co/Yellow-AI-NLP/komodo-7b-base) - Model dasar 7B dari Yellow.ai untuk bahasa Indonesia, Inggris, dan bahasa daerah, perlu menyetujui syarat di Hugging Face.
- [Cendol](https://github.com/IndoNLP/cendol) - Koleksi model instruksi IndoNLP berbasis mT5 dan Llama 2 untuk bahasa Indonesia dan bahasa daerah.
- [Merak-7B](https://huggingface.co/Ichsan2895/Merak-7B-v4) - Model chat 7B buatan komunitas untuk bahasa Indonesia, lisensi CC BY-NC-SA 4.0 (non-komersial), pembaruan terakhir 2023.

## Model Encoder dan Embedding

- [IndoBERT (IndoNLU)](https://huggingface.co/indobenchmark/indobert-base-p1) - BERT bahasa Indonesia dari tim IndoNLU yang dilatih pada korpus Indo4B, dasar banyak model klasifikasi lokal.
- [IndoBERT (IndoLEM)](https://huggingface.co/indolem/indobert-base-uncased) - BERT bahasa Indonesia dari tim IndoLEM, lisensi MIT.
- [IndoBERTweet](https://huggingface.co/indolem/indobertweet-base-uncased) - BERT untuk teks media sosial berbahasa Indonesia.
- [IndoBART](https://huggingface.co/indobenchmark/indobart-v2) - Model sequence-to-sequence dari IndoNLG untuk ringkasan dan terjemahan Indonesia, Jawa, dan Sunda.
- [NusaBERT](https://github.com/LazarusNLP/NusaBERT) - IndoBERT yang diperluas ke belasan bahasa daerah Indonesia.
- [Indonesian Sentence Embeddings](https://github.com/LazarusNLP/indonesian-sentence-embeddings) - Model dan benchmark embedding kalimat bahasa Indonesia untuk pencarian semantik dan RAG.

## Dataset dan Benchmark

- [IndoNLU](https://github.com/IndoNLP/indonlu) - Benchmark pemahaman bahasa Indonesia (12 tugas) beserta korpus pralatih Indo4B.
- [IndoNLG](https://github.com/IndoNLP/indonlg) - Benchmark pembangkitan teks untuk bahasa Indonesia, Jawa, dan Sunda.
- [IndoLEM](https://github.com/indolem/indolem) - Benchmark NLU bahasa Indonesia untuk morfosintaksis, semantik, dan wacana.
- [NusaX](https://github.com/IndoNLP/nusax) - Data paralel sentimen dan terjemahan untuk 10 bahasa daerah, bahasa Indonesia, dan Inggris.
- [NusaCrowd](https://github.com/IndoNLP/nusa-crowd) - Katalog dan pemuat terpadu ratusan dataset bahasa-bahasa di Indonesia.
- [NusaWrites](https://github.com/IndoNLP/nusa-writes) - Korpus dan benchmark pemodelan bahasa untuk bahasa daerah yang minim data.
- [SEACrowd](https://github.com/SEACrowd/seacrowd-datahub) - Hub dataset bahasa dan budaya Asia Tenggara, penerus NusaCrowd.
- [IndoMMLU](https://github.com/fajri91/IndoMMLU) - Soal ujian sekolah Indonesia untuk mengukur pengetahuan LLM tentang pelajaran dan budaya lokal.
- [SEA-HELM](https://github.com/aisingapore/SEA-HELM) - Kerangka evaluasi LLM untuk bahasa Asia Tenggara, dengan [papan peringkat](https://leaderboard.sea-lion.ai) publik.
- [COPAL-ID](https://github.com/haryoa/COPAL-ID) - Benchmark penalaran sebab-akibat dengan nuansa budaya Indonesia, lisensi CC BY-SA 4.0.
- [IndoNLI](https://github.com/ir-nlp-csui/indonli) - Dataset inferensi bahasa alami (NLI) bahasa Indonesia dari Universitas Indonesia.
- [Liputan6 Summarization](https://github.com/fajri91/sum_liputan6) - Korpus ringkasan berita bahasa Indonesia berskala besar (AACL 2020).
- [IndoSum](https://github.com/kata-ai/indosum) - Benchmark ringkasan teks bahasa Indonesia dari Kata.ai.
- [UD Indonesian-GSD](https://github.com/UniversalDependencies/UD_Indonesian-GSD) - Treebank Universal Dependencies untuk POS tagging dan parsing bahasa Indonesia.
- [Indonesian Hate Speech Multi-label](https://github.com/okkyibrohim/id-multi-label-hate-speech-and-abusive-language-detection) - Dataset ujaran kebencian dan bahasa kasar dari Twitter berbahasa Indonesia.

## Pustaka dan Alat NLP

- [PySastrawi](https://github.com/har07/PySastrawi) - Stemmer bahasa Indonesia untuk Python, port dari Sastrawi.
- [Sastrawi](https://github.com/sastrawi/sastrawi) - Stemmer bahasa Indonesia untuk PHP, kini tidak aktif dikembangkan tetapi masih banyak dipakai.
- [nlp-id](https://github.com/kumparan/nlp-id) - Tokenizer, lemmatizer, POS tagger, dan stopword bahasa Indonesia dari kumparan.
- [Aksara](https://github.com/ir-nlp-csui/aksara) - Alat analisis morfologi dan sintaksis bahasa Indonesia sesuai Universal Dependencies v2, lisensi AGPL-3.0.
- [kbbi-python](https://github.com/laymonage/kbbi-python) - Modul Python untuk mengambil entri KBBI Daring.
- [stopwords-id](https://github.com/stopwords-iso/stopwords-id) - Daftar stopword bahasa Indonesia.
- [InSet](https://github.com/fajri91/InSet) - Leksikon sentimen bahasa Indonesia.
- [Kamus Alay](https://github.com/nasalsabila/kamus-alay) - Kamus normalisasi kata tidak baku dan slang ke bahasa Indonesia baku.

## Suara: ASR dan TTS

- [Whisper](https://github.com/openai/whisper) - Model pengenalan ucapan multibahasa yang mendukung bahasa Indonesia, lisensi MIT.
- [Whisper Medium Indonesia](https://huggingface.co/cahya/whisper-medium-id) - Whisper yang di-fine-tune untuk transkripsi bahasa Indonesia.
- [wav2vec2 Indonesia-Jawa-Sunda](https://huggingface.co/indonesian-nlp/wav2vec2-indonesian-javanese-sundanese) - Model ASR untuk bahasa Indonesia, Jawa, dan Sunda, lisensi Apache-2.0.
- [SeaLLMs-Audio](https://huggingface.co/SeaLLMs/SeaLLMs-Audio-7B) - Model audio-bahasa 7B yang memahami ucapan dalam bahasa Asia Tenggara termasuk Indonesia.
- [MMS-TTS Indonesia](https://huggingface.co/facebook/mms-tts-ind) - Model TTS bahasa Indonesia dari proyek MMS Meta, lisensi CC BY-NC 4.0 (non-komersial).
- [Indonesian TTS](https://github.com/Wikidepia/indonesian-tts) - Model TTS bahasa Indonesia berbasis Coqui TTS, lisensi tidak dicantumkan di repo.
- [Common Voice](https://commonvoice.mozilla.org/id/datasets) - Dataset suara terbuka Mozilla yang memuat rekaman bahasa Indonesia.
- [FLEURS](https://huggingface.co/datasets/google/fleurs) - Benchmark ucapan multibahasa dari Google yang memuat bahasa Indonesia dan Jawa, lisensi CC BY 4.0.

## Data Publik dan API Pemerintah

- [Portal Satu Data Indonesia](https://data.go.id) - Katalog data terbuka pemerintah pusat dan daerah.
- [Web API BPS](https://webapi.bps.go.id/documentation/) - API statistik Badan Pusat Statistik, perlu mendaftar untuk mendapatkan kunci.
- [Data Terbuka BMKG](https://data.bmkg.go.id) - Prakiraan cuaca tingkat desa, data gempa, dan peringatan dini cuaca.
- [Indonesia Government APIs](https://github.com/suryast/indonesia-gov-apis) - Katalog sumber data dan API pemerintah Indonesia beserta catatan akses dan bukti pengecekan.
- [API Indonesia](https://apiindonesia.id) - REST API berbayar per kredit untuk wilayah, kode pos, hari libur, jadwal salat, KBBI, dan gempa BMKG, dengan bonus kredit awal.

## Layanan AI Lokal

- [GLAIR](https://glair.ai) - Platform AI dan konsultasi AI untuk perusahaan.
- [Kata.ai](https://kata.ai) - Platform AI percakapan untuk perusahaan.
- [Nodeflux](https://www.nodeflux.ai) - Analitik video on-premise, agen AI, dan AI citra satelit.

## Komunitas

- [IndoNLP](https://indonlp.github.io) - Kolektif riset terbuka di balik IndoNLU, NusaX, NusaCrowd, dan Cendol.
- [SEACrowd](https://seacrowd.org) - Komunitas riset terbuka untuk data dan model bahasa Asia Tenggara.
- [INDONESIA-AI di Hugging Face](https://huggingface.co/INDONESIA-AI) - Organisasi komunitas untuk berbagi model dan dataset AI Indonesia.
- [Python Indonesia](https://www.python.or.id) - Komunitas pengguna Python di Indonesia.
- [PythonID di Telegram](https://t.me/pythonid) - Grup diskusi publik komunitas Python Indonesia.
- [Data Science Indonesia](https://datascience.or.id) - Komunitas praktisi dan pelajar sains data.
- [KORIKA](https://korika.id) - Kolaborasi riset dan inovasi industri kecerdasan artifisial di Indonesia.
- [Global AI Yogyakarta](https://globalai.community/chapters/yogyakarta) - Chapter Global AI Community di Yogyakarta.

## Belajar AI

- [Google Bangkit Bersama AI](https://grow.google/intl/id_id/ai-skills/) - Program pelatihan AI dari Google dalam bahasa Indonesia, sebagian gratis.
- [Microsoft Elevate Indonesia](https://dicoding.elevaite.id) - Program pelatihan AI Microsoft bersama Dicoding untuk profesional dan akademisi.
- [Digital Talent Scholarship](https://digitalent.komdigi.go.id) - Program pelatihan digital Komdigi, termasuk tema AI.
- [Dicoding Belajar Dasar AI](https://www.dicoding.com/academies/653) - Kelas dasar AI berbahasa Indonesia tanpa prasyarat, berbayar langganan.
- [Dicoding Belajar Penggunaan Generative AI](https://www.dicoding.com/academies/867) - Kelas pemakaian AI generatif untuk pekerjaan sehari-hari.
- [Kursus LLM Hugging Face](https://huggingface.co/learn/llm-course/id/chapter1/1) - Kursus gratis NLP dan LLM dengan terjemahan bahasa Indonesia untuk bab awal.
- [Tips AI Indonesia](https://github.com/EzkielynaGroup/tips-ai-indonesia) - Panduan praktis berbahasa Indonesia tentang memilih model, menghemat token, prompt, agen coding, dan keamanan API key.

## Regulasi dan Kebijakan

- [Strategi Nasional Kecerdasan Artifisial 2020-2045](https://karya.brin.go.id/id/eprint/13918/) - Dokumen Stranas KA yang disusun BPPT (kini BRIN), acuan arah pengembangan AI nasional.
- [SE Menkominfo No. 9 Tahun 2023](https://jdih.komdigi.go.id/produk_hukum/view/id/883/t/surat+edaran+menteri+komunikasi+dan+informatika+nomor+9+tahun+2023) - Surat edaran tentang Etika Kecerdasan Artifisial untuk pelaku usaha dan PSE, berstatus berlaku di JDIH Komdigi.
- [UU No. 27 Tahun 2022](https://peraturan.bpk.go.id/Details/229798/uu-no-27-tahun-2022) - Undang-Undang Pelindungan Data Pribadi yang berlaku untuk aplikasi AI yang mengolah data pribadi.
- [Panduan Kode Etik AI Fintech OJK](https://ojk.go.id/id/Publikasi/Roadmap-dan-Pedoman/ITSK/Pages/Panduan-Kode-Etik-Kecerdasan-Buatan-%28AI%29-yang-Bertanggung-Jawab-dan-Terpercaya-di-Industri-Teknologi-Finansial.aspx) - Panduan AI yang bertanggung jawab di industri teknologi finansial (Desember 2023).
- [Pendaftaran PSE Komdigi](https://pse.komdigi.go.id) - Portal pendaftaran Penyelenggara Sistem Elektronik, termasuk layanan AI yang beroperasi di Indonesia.
- [Status Rancangan Perpres AI](https://nasional.kontan.co.id/news/dua-perpres-ai-tinggal-tunggu-tanda-tangan-prabowo) - Laporan Kontan (September 2026) bahwa dua rancangan Perpres AI, peta jalan dan etika, menunggu tanda tangan Presiden.

## Akses API AI dengan Pembayaran Lokal

Entri disusun menurut abjad. Harga dan metode pembayaran dapat berubah, cek halaman penyedia. Pengelola daftar ini juga mengelola Ezkielyna, lihat pengungkapan di bagian Footnotes.

- [Ezkielyna](https://ezkielyna.store/?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-indonesia) - Gateway API AI independen berformat OpenAI dan Anthropic, saldo mulai $0,5 lewat QRIS, DANA, GoPay, atau USDT.
- [Flaz Cloud AI Gateway](https://flaz.id/en/ai-services) - Gateway API berformat OpenAI, isi saldo mulai Rp10.000 lewat QRIS, virtual account, atau Flaz Wallet.
- [Google AI Studio](https://aistudio.google.com) - Akses Gemini API dengan kuota gratis, Indonesia termasuk [wilayah yang didukung](https://ai.google.dev/gemini-api/docs/available-regions).
- [Kiosapi.id](https://kiosapi.id) - Gateway API berformat OpenAI dan Anthropic, isi saldo mulai Rp10.000 lewat QRIS, e-wallet, virtual account, atau kartu.
- [Nexotao](https://www.nexotao.com) - Gateway API berformat OpenAI dan Anthropic dengan saldo Rupiah, isi saldo lewat QRIS mulai Rp10.000.
- [OpenRouter](https://openrouter.ai) - Gateway global ratusan model, bayar dengan kartu kredit atau kripto (USDC), ada model gratis dengan batas harian.

## MCP dan Agen AI

- [Awesome MCP Indonesia](https://github.com/EzkielynaGroup/awesome-mcp-indonesia#readme) - Daftar lengkap server MCP untuk Indonesia dan panduan pemasangan berbahasa Indonesia.
- [bmkg-api](https://github.com/dhanyyudi/bmkg-api) - REST API dan server MCP buatan komunitas untuk prakiraan cuaca, gempa, dan peringatan dini BMKG.
- [BPS MCP Server](https://github.com/setiapam/bps-mcp-server) - Server MCP untuk data statistik BPS, perlu kunci Web API BPS.
- [DOKU MCP Server](https://developers.doku.com/accept-payments/doku-mcp-server) - Server MCP dari DOKU untuk membuat tautan pembayaran, QRIS, virtual account, dan cek transaksi.
- [Ezkielyna Image MCP](https://github.com/EzkielynaGroup/ezkielyna-image-mcp) - Server MCP untuk membuat dan mengedit gambar dari file lokal di Claude Desktop, Claude Code, Cursor, dan OpenCode.
- [indonesia-civic-stack](https://github.com/suryast/indonesia-civic-stack) - SDK Python dan server MCP untuk belasan portal data publik Indonesia seperti BPOM, BPJPH, OJK, dan BMKG.
- [kbbi-mcp](https://github.com/gaato/kbbi-mcp) - Server MCP buatan komunitas untuk mencari kata di KBBI.
- [mcp-bmkg](https://github.com/EzkielynaGroup/mcp-bmkg) - Server MCP tanpa API key untuk gempa terkini dan prakiraan cuaca tingkat desa dari data terbuka BMKG.
- [mcp-hari-libur-indonesia](https://github.com/EzkielynaGroup/mcp-hari-libur-indonesia) - Server MCP offline untuk hari libur nasional dan cuti bersama sesuai SKB 3 Menteri, plus hitung hari kerja.
- [mcp-qris](https://github.com/EzkielynaGroup/mcp-qris) - Server MCP offline untuk membaca, memvalidasi, menambah nominal, dan merender payload QRIS.
- [mcp-rupiah](https://github.com/EzkielynaGroup/mcp-rupiah) - Server MCP offline untuk terbilang, format dan baca nominal Rupiah, serta kalkulator PPN sesuai aturan 2025+.
- [mcp-wilayah-indonesia](https://github.com/EzkielynaGroup/mcp-wilayah-indonesia) - Server MCP offline untuk kode wilayah Kemendagri dari provinsi sampai desa.
- [xendit-mcp](https://github.com/mrslbt/xendit-mcp) - Server MCP buatan komunitas untuk API pembayaran Xendit, tidak berafiliasi dengan Xendit.

## Otomasi

- [n8n](https://github.com/n8n-io/n8n) - Platform otomasi alur kerja dengan node AI yang bisa di-host sendiri, lisensi fair-code.
- [n8n Workflow Templates](https://n8n.io/workflows/) - Ribuan templat alur kerja n8n dari komunitas, termasuk agen AI dan chatbot.
- [n8n Workflows Indonesia](https://github.com/EzkielynaGroup/n8n-workflows-indonesia) - Workflow n8n siap impor untuk UMKM: CS toko di Telegram, ringkas PDF ke Google Sheets, draf balasan Gmail, dan API terjemahan.

## Daftar Terkait

- [id-nlp-resource](https://github.com/kmkurn/id-nlp-resource) - Daftar sumber daya NLP bahasa Indonesia.
- [indonesian-nlp](https://github.com/gentaiscool/indonesian-nlp) - Kumpulan makalah riset dan sumber daya untuk bahasa-bahasa di Indonesia.
- [Awesome Indonesian LLM Dataset](https://github.com/irfanfadhullah/awesome-indonesian-llm-dataset) - Kumpulan dataset bahasa Indonesia untuk melatih LLM dan model visi-bahasa.
- [Awesome Indonesia Repo](https://github.com/GitIndonesia/awesome-indonesia-repo) - Repositori open source buatan developer Indonesia.
- [Awesome Indonesia](https://github.com/fransallen/awesome-indonesia) - Produk, proyek, dan acara buatan developer dan founder Indonesia.

## FAQ

**Model AI terbuka apa yang paham bahasa Indonesia?** Untuk chat, mulai dari GoTo-AI 27B, Sahabat-AI, SEA-LION v4, atau Sailor2: semuanya dilatih lanjut pada teks bahasa Indonesia dan bobotnya ada di Hugging Face. Untuk klasifikasi atau pencarian, model encoder seperti IndoBERT dan embedding kalimat dari LazarusNLP lebih ringan dan murah dijalankan.

**Bagaimana cara memakai API AI tanpa kartu kredit di Indonesia?** Beberapa gateway lokal menerima QRIS, e-wallet, atau virtual account dan memakai format API OpenAI, sehingga cukup mengganti base URL dan API key di kode. Daftarnya ada di bagian Akses API AI dengan Pembayaran Lokal. Google AI Studio juga memberi kuota gratis Gemini API yang bisa dipakai dari Indonesia.

**Apakah sudah ada undang-undang AI di Indonesia?** Belum ada undang-undang khusus AI per November 2026. Yang berlaku adalah SE Menkominfo No. 9 Tahun 2023 tentang Etika Kecerdasan Artifisial, UU Pelindungan Data Pribadi, dan panduan sektoral seperti kode etik AI fintech dari OJK. Dua rancangan Perpres AI dilaporkan menunggu tanda tangan Presiden pada September 2026.

**Di mana mencari dataset bahasa Indonesia dan bahasa daerah?** Mulai dari NusaCrowd dan SEACrowd yang mengumpulkan ratusan dataset dalam satu pemuat, lalu IndoNLU, NusaX, dan IndoMMLU untuk benchmark. Selalu cek lisensi tiap dataset sebelum dipakai untuk produk komersial.

**Apa itu MCP dan apakah ada server MCP untuk data Indonesia?** MCP (Model Context Protocol) adalah standar terbuka yang membuat asisten AI seperti Claude, Cursor, atau OpenCode bisa memanggil alat dan data dari luar. Sudah ada server MCP untuk BPS, BMKG, KBBI, portal data pemerintah, dan pembayaran seperti DOKU, lihat bagian MCP dan Agen AI.

**Is there an English version of this list?** The descriptions are in Indonesian because the audience is Indonesian, but the names and links work for everyone. The English summary at the top explains every section.

## Contributing

Kontribusi sangat diterima. Baca [panduan kontribusi](CONTRIBUTING.md) untuk kriteria entri, format, dan cara mengusulkan.

## Footnotes

- Semua tautan dicek pada 11 November 2026 dan dicek ulang tiap minggu oleh [skrip pengecek tautan](scripts/check_links.py).
- Pengungkapan: pengelola daftar ini, Ezekiel Lieberhart, juga mengelola Ezkielyna, gateway API AI independen. Entri Ezkielyna dan repo EzkielynaGroup mengikuti kriteria yang sama dengan entri lain, seperti dijelaskan di panduan kontribusi.
- Merek dan nama produk milik pemiliknya masing-masing. Daftar ini tidak berafiliasi dengan penyedia yang dicantumkan.
