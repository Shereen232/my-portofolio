# Portfolio Dicky Ilmansyah - JavaScript Version

Portfolio profesional yang telah dikonversi dari Laravel menjadi aplikasi web murni dengan JavaScript untuk deployment di Vercel.

## Deskripsi

Aplikasi portfolio ini menampilkan:
- Profil dan pengalaman kerja
- Keterampilan teknis
- Proyek yang telah dikerjakan
- Riwayat pendidikan dan sertifikasi
- Informasi kontak

## Teknologi yang Digunakan

- **HTML5** - Struktur halaman
- **CSS3** - Styling dengan Tailwind CSS
- **JavaScript** - Interaktivitas dan animasi
- **AOS (Animate On Scroll)** - Library animasi scroll
- **Vercel** - Platform deployment

## Struktur File

```
portfolio/
├── index.html          # Halaman utama portfolio
├── assets/             # Assets yang diperlukan
│   ├── app-Bb1cchPk.css    # CSS yang di-build
│   ├── app-CAiCLEjY.js     # JavaScript yang di-build
│   └── images/
│       └── profile.png     # Gambar profil
├── vercel.json         # Konfigurasi Vercel
└── README.md          # Dokumentasi ini
```

## Cara Menjalankan Lokal

1. **Clone atau download** repository ini
2. **Buka file index.html** di browser web modern
3. Portfolio akan langsung berjalan tanpa perlu server

### Atau menggunakan server lokal:

```bash
# Menggunakan Python
python -m http.server 8000

# Atau menggunakan Node.js
npx serve .

# Kemudian buka http://localhost:8000 di browser
```

## Deployment ke Vercel

1. **Push ke GitHub** repository ini
2. **Connect ke Vercel** dan import repository
3. **Deploy** - Vercel akan otomatis mendeteksi `vercel.json` dan deploy sebagai static site
4. **Akses** portfolio di URL Vercel yang diberikan

## Fitur

- **Responsive Design** - Tampil optimal di desktop dan mobile
- **Smooth Scrolling** - Navigasi halus antar section
- **Animations** - Animasi scroll dan hover effects
- **Interactive Elements** - Counter animations, mobile menu
- **Modern UI** - Menggunakan Tailwind CSS untuk styling

## Pengembangan

Jika ingin mengubah styling atau JavaScript, Anda perlu:
1. Setup ulang Laravel project dengan Vite
2. Edit file di `resources/css/app.css` dan `resources/js/app.js`
3. Build assets: `npm run build`
4. Copy file CSS/JS hasil build ke folder `assets/`
5. Update nama file di `index.html` jika berubah

## Optimisasi untuk Vercel

- **Static Assets**: Semua file CSS, JS, dan gambar disimpan di folder `assets/`
- **No Backend**: Tidak ada server-side processing
- **Fast Loading**: Assets dioptimasi dan di-cache oleh Vercel
- **CDN**: Assets didistribusikan melalui CDN global Vercel

## Kontak

- **Email**: dickyilmanyah504@gmail.com
- **WhatsApp**: +6289653797645
- **GitHub**: https://github.com/Shereen232
- **Instagram**: https://instagram.com/d_ilmansyah7

---

© 2025 Dicky Ilmansyah. All rights reserved.