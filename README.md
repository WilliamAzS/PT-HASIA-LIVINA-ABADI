# PT Hasia Livina Abadi Website

Website company profile modern untuk **PT HASIA LIVINA ABADI** dengan positioning utama sebagai penyedia solusi alat berat industri, forklift rental, sparepart, ban solid, service, overhaul, dan restorasi.

## Fitur versi terbaru

- Tampilan lebih eye-catching dengan gaya industrial premium.
- Default bahasa Indonesia dengan pilihan bahasa Indonesia, English, Japanese, dan Chinese (Simplified).
- Toggle tema Dark / Light dengan preferensi tersimpan di browser.
- Hero section interaktif dengan CTA quotation.
- Quick WhatsApp quote builder.
- Service tabs interaktif untuk Rental, Sales, Sparepart, Ban Solid, dan Service.
- Animated counters, reveal animation, hover/tilt card effect.
- Galeri foto dengan modal preview.
- FAQ accordion.
- Form quotation yang otomatis membuka WhatsApp.
- Google Maps embed dan kontak lengkap.
- Responsive untuk desktop, tablet, dan mobile.

## Struktur file

```text
index.html
styles.css
script.js
assets/
  favicon.svg
  logo.svg
  whatsapp.svg
  og-preview.svg
  social-cover.jpg
  social-fleet.jpg
  social-gallery.jpg
  social-rental.jpg
  social-restoration.jpg
research-notes.md
```

## Cara menjalankan lokal

Cukup buka file `index.html` di browser.

Untuk development lokal yang lebih aman, jalankan server sederhana:

```bash
python -m http.server 8000
```

Lalu buka:

```text
http://localhost:8000
```

## Cara upload ke GitHub

```cmd
cd "D:\PT HASIA LIVINA ABADI WEBSITE\pt-hasia-livina-abadi-website"
git add .
git commit -m "Add Japanese and Chinese translations with improved branding"
git push
```

Jika repository belum pernah dibuat / belum ada remote:

```cmd
git init
git add .
git commit -m "Initial website for PT Hasia Livina Abadi"
git branch -M main
git remote add origin https://github.com/WilliamAzS/PT-HASIA-LIVINA-ABADI.git
git push -u origin main
```

## Catatan edit konten

- Nomor WhatsApp ada di `index.html` dan `script.js`: `6281585267190`.
- Email ada di `index.html`: `hasialivina.abadi@gmail.com`.
- Gambar bisa diganti di folder `assets/` dengan nama file yang sama agar tidak perlu mengubah kode.
- Terjemahan Indonesia/English/Japanese/Chinese ada di object `translations` pada file `script.js`.
- `assets/logo.svg` adalah logo HLA custom yang lebih premium; ganti dengan logo resmi perusahaan jika sudah tersedia.
- `assets/whatsapp.svg` dipakai untuk tombol WhatsApp dan floating contact button.


## Latest update

- Replaced the placeholder/site logo with the user-provided PT HLA Forklift Specialist logo and prepared a transparent PNG asset for web use.

- Fixed visibility of the dark PT HLA logo on dark sections by placing it inside a bright rounded logo container.

- PT HLA Maps address updated to: PT. Hasia Livina Abadi, Blk. AB, Ruko Palazzo, Jl. Villa Mutiara Cikarang No.65, Ciantra, Cikarang Selatan, Bekasi, Jawa Barat 17530.
