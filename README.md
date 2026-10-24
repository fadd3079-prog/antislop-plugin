# antislop — Adaptive Natural Writing

Skill penulisan adaptif untuk ChatGPT yang membantu membuat,
menyunting, dan mengevaluasi tulisan agar natural, jelas,
koheren, serta sesuai konteks tanpa kehilangan substansi.

**Natural bukan berarti santai. Formal bukan berarti kaku.
Ringkas bukan berarti dangkal.**

## Fitur

- WRITE: membuat tulisan baru sesuai tujuan dan audiens.
- REWRITE: memperbaiki tulisan dengan perubahan seperlunya.
- REVIEW: menganalisis pola bahasa generik dan AI-slop.
- Adaptasi otomatis terhadap konteks dan gaya bahasa.
- Perlindungan fakta, angka, istilah teknis, dan sitasi.
- Mendukung bahasa Indonesia dan bahasa lain sesuai instruksi.
- Tidak membutuhkan API key, MCP server, atau dependency tambahan.

## Penggunaan

Cocok untuk:

- Tugas kuliah, esai, dan laporan praktikum.
- Paper ilmiah dan laporan penelitian.
- Email dan pesan WhatsApp.
- Portofolio, caption, dan konten kreatif.
- Proposal dan komunikasi organisasi.
- Komunikasi freelance dan bisnis.
- Penyuntingan tulisan umum.

## Instalasi di ChatGPT

1. Buka halaman **Releases** repository ini.
2. Unduh `antislop-v2.0.0.zip` dari bagian Assets.
3. Buka menu Plugins di ChatGPT.
4. Gunakan fitur unggah plugin jika tersedia pada akunmu.
5. Pilih ZIP yang telah diunduh.
6. Selesaikan proses instalasi.
7. Pilih `@antislop` dari pemilih plugin untuk menggunakannya.

Catatan: Ketersediaan fitur instalasi bergantung pada akses
akun dan platform. Mengunduh ZIP tidak otomatis menginstal skill.

## Contoh penggunaan

### Memperbaiki tulisan

Perbaiki paragraf berikut agar lebih natural. Pertahankan
makna, informasi penting, sitasi, dan gaya penulis.
Lakukan perubahan minimal.

### Menulis pesan

Buat pesan WhatsApp kepada dosen untuk mengonfirmasi
pengumpulan tugas. Gunakan bahasa sopan, singkat,
dan tidak terlalu kaku.

### Memeriksa AI-slop

Analisis tulisan berikut. Tunjukkan bagian yang generik,
repetitif, atau kurang sesuai konteks. Jangan revisi dahulu.

## Struktur

- `plugin.json` — metadata plugin.
- `skills/antislop/SKILL.md` — instruksi utama.
- `skills/antislop/references/context-guidelines.md` —
  panduan adaptasi konteks.
- `skills/antislop/references/regression-cases.md` —
  spesifikasi pengujian.
- `assets/` — ikon plugin.

## Batasan

antislop bukan alat pendeteksi asal-usul tulisan.

Skill tidak menjamin teks lolos AI detector dan tidak
menggantikan verifikasi fakta, pemeriksaan sumber,
atau ketentuan integritas akademik.

Hasilnya tetap perlu diperiksa sebelum digunakan,
terutama untuk tulisan akademik dan dokumen penting.

Kasus regresi dalam repository merupakan spesifikasi
pengujian, bukan klaim bahwa seluruh kasus telah lulus
pengujian runtime.

## Lisensi

Lihat file LICENSE.
