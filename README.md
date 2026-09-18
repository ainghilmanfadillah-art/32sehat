# 32SEHAT!

Aplikasi pencatatan kebugaran jasmani siswa berbasis web untuk mengelola data tes, menghitung BMI, menilai kategori TKJI, serta mengekspor data ke CSV atau backup JSON.

## Fitur utama
- Input data siswa dan hasil tes kebugaran
- Perhitungan BMI otomatis
- Kategori TKJI otomatis
- Dashboard statistik
- Daftar siswa dan filter pencarian
- Export ke CSV dan backup JSON
- Penyimpanan lokal di browser via localStorage

## Jalankan lokal
Buka file HTML langsung di browser, atau jalankan server lokal:

```bash
cd /workspaces/32sehat
python3 -m http.server 8000
```

Lalu buka: http://localhost:8000

## Deploy ke GitHub Pages
Repo ini sudah dikonfigurasi untuk deploy otomatis menggunakan GitHub Actions.

Langkah yang perlu dilakukan di GitHub:
1. Push project ke repository GitHub Anda
2. Buka repository -> Settings -> Pages
3. Pilih source: "GitHub Actions"
4. Setelah workflow selesai, situs akan tersedia di:
   `https://<username>.github.io/32sehat/`

## Struktur utama
- `index.html` : aplikasi utama
- `.github/workflows/deploy-pages.yml` : workflow deploy otomatis ke GitHub Pages
- `README.md` : dokumentasi proyek
