# Dashboard Penjualan KDMP Pungpungan — Vercel

Website statis yang siap di-deploy ke Vercel.

## Deploy
1. Buat repository baru di GitHub.
2. Upload file `index.html`, `impor_pdf.html`, dan `vercel.json` di root repository (bukan di dalam subfolder).
3. Buka https://vercel.com/new, login dengan GitHub, pilih repository tersebut.
4. Pilih Framework Preset: **Other**. Biarkan Build Command kosong dan Output Directory kosong/default.
5. Klik Deploy. Vercel memberikan alamat `*.vercel.app`.

## Catatan
- Data dashboard masih disimpan pada localStorage browser. Tidak otomatis sinkron antarperangkat dan dapat hilang jika data browser dihapus.
- Halaman impor PDF menggunakan OCR di browser. Akurasi pembacaan foto struk belum dijamin; periksa semua hasil sebelum menyimpan.
- Halaman ini tidak memiliki login. Jangan masukkan data pribadi/sensitif sebelum menambahkan autentikasi dan database.
