# Panduan Kontribusi

Terima kasih sudah mau membantu. Daftar ini dikurasi: tujuannya memuat sumber daya yang berguna dan masih hidup, bukan semua yang pernah ada.

*English: contributions are welcome. Open a pull request that adds one entry in the format below and explain in the PR why it is useful for Indonesian developers or small businesses. Descriptions are written in Indonesian; if you cannot write Indonesian, write English and a maintainer will translate it.*

## Kriteria entri

Sebuah entri diterima jika:

1. **Relevan untuk Indonesia.** Mendukung bahasa Indonesia atau bahasa daerah, memakai data Indonesia, melayani pengguna di Indonesia (misalnya pembayaran lokal), atau merupakan sumber belajar/regulasi Indonesia.
2. **Masih hidup dan bisa dicek.** Tautan bisa dibuka; repo tidak diarsipkan; ada README atau dokumentasi yang menjelaskan cara pakai. Repo yang lama tidak diperbarui tetap boleh jika masih berguna (misalnya dataset riset), tetapi tuliskan tahunnya bila relevan.
3. **Lisensi jelas.** Kode dan model mencantumkan lisensi. Jika lisensinya non-komersial atau tidak dicantumkan, tulis hal itu di deskripsi.
4. **Deskripsi jujur dan netral.** Satu kalimat, faktual, bisa dicek dari halaman sumber. Tanpa klaim pemasaran seperti "terbaik", "termurah", "tanpa batas", atau "resmi" (kecuali menyebut sumber pemerintah apa adanya).
5. **Layanan berbayar boleh**, asal model harganya disebut terus terang (gratis, kuota gratis, berbayar per kredit, berlangganan).
6. **Satu entri per proyek.** Jangan menambahkan beberapa tautan untuk proyek yang sama.

Tidak diterima: tautan afiliasi atau referral, konten yang melanggar hukum atau hak cipta, model atau layanan yang dipasarkan untuk konten tanpa pengaman keamanan, dan alat yang mengambil data pribadi tanpa dasar hukum.

## Format

```markdown
- [Nama](https://tautan) - Deskripsi singkat yang diawali huruf kapital dan diakhiri titik.
```

- Tambahkan entri di bagian yang paling cocok. Di bagian **Akses API AI dengan Pembayaran Lokal** urutannya menurut abjad; di bagian lain tambahkan di bawah entri yang mirip.
- Tautan GitHub mengarah ke halaman repo, bukan ke file atau rilis tertentu.
- Satu baris per entri, tanpa hard-wrap.
- Jalankan pengecek tautan sebelum membuka PR:

```bash
python3 scripts/check_links.py README.md CONTRIBUTING.md
```

## Pengungkapan kepentingan

Pengelola daftar ini, Ezekiel Lieberhart, juga mengelola **Ezkielyna**, gateway API AI independen untuk developer Indonesia, dan organisasi GitHub **EzkielynaGroup**. Agar adil:

- Ezkielyna hanya muncul sebagai **satu entri netral** di bagian Akses API AI, diurutkan menurut abjad bersama penyedia lain, dengan deskripsi faktual yang sama formatnya.
- Repo EzkielynaGroup hanya dimasukkan jika memenuhi kriteria yang sama seperti entri lain (berfungsi, berlisensi, terdokumentasi). Repo yang belum publik disimpan sebagai komentar HTML di README dan baru diaktifkan setelah publik.
- Usulan untuk menambah penyedia lain, termasuk pesaing Ezkielyna, diperlakukan sama. Jika menurut Anda ada entri yang tidak netral, buka issue.

## Pemeriksaan tautan otomatis

Workflow `.github/workflows/link-check.yml` menjalankan `scripts/check_links.py` setiap Senin dan pada setiap PR yang mengubah file Markdown. Skrip hanya memakai pustaka standar Python dan token bawaan GitHub Actions (tanpa secret tambahan). Status `WARN` berarti situs memblokir bot atau perlu login, jadi dicek manual; status `FAIL` berarti tautan mati dan entri perlu diperbaiki atau dihapus.

## Lisensi

Dengan berkontribusi, Anda setuju kontribusi Anda pada daftar dirilis di bawah [CC0 1.0](LICENSE). Skrip di folder `scripts/` berlisensi MIT (teks lisensi ada di kepala berkas skrip).
