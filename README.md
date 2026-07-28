# Laporan Analisis Inovasi RSUD Sekarwangi 2026

Isi folder ini:
- `index.html` — halaman pembuka, menautkan ke kedua laporan
- `infografis.html` — Infografis Peringkat Inovasi (berdasarkan kelengkapan 20 indikator)
- `dashboard.html` — Dashboard Rekapitulasi Nilai (skor berbobot mengacu pada Bobot Penilaian Profil Inovasi)

File-file ini adalah HTML statis (tidak butuh server/database), sehingga bisa langsung di-deploy ke layanan hosting statis gratis mana pun. Berikut beberapa opsi termudah:

## Opsi 1 — Netlify Drop (paling cepat, tanpa akun wajib)
1. Buka https://app.netlify.com/drop
2. Drag & drop **seluruh isi folder ini** (bukan file zip-nya) ke halaman tersebut
3. Netlify akan langsung memberi URL publik (contoh: `nama-acak.netlify.app`)
4. Opsional: daftar akun gratis untuk mengatur nama domain custom

## Opsi 2 — Vercel
1. Buat akun di https://vercel.com
2. Pilih "Add New Project" → "Upload" atau hubungkan ke repo GitHub berisi folder ini
3. Deploy — Vercel otomatis mendeteksi ini sebagai situs statis

## Opsi 3 — GitHub Pages (gratis, cocok untuk dokumentasi resmi)
1. Buat repository baru di GitHub, upload semua file di folder ini ke root repo
2. Buka Settings → Pages → pilih branch `main` dan folder `/root`
3. Situs akan aktif di `https://<username>.github.io/<nama-repo>/`

## Catatan
- Semua data (termasuk logo) sudah tertanam langsung di dalam file HTML (base64), jadi tidak ada file terpisah yang perlu diupload lagi.
- Karena berisi data kinerja/penilaian internal rumah sakit, pertimbangkan untuk **membatasi akses** (misalnya lewat password protection di Netlify, atau membuat repo GitHub bersifat private) jika laporan ini belum untuk konsumsi publik sepenuhnya.
