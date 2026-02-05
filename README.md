# ISPnet - Website Template

Website profil perusahaan penyedia jasa internet (ISP) dengan desain modern dan premium.

## Fitur

- **Desain Premium** - Tampilan modern dengan typography yang elegan
- **Single Page Design** - Semua konten dalam satu halaman dengan smooth scroll
- **Responsif** - Optimal di desktop, tablet, dan mobile
- **Tailwind CSS** - Styling dengan framework utility-first
- **Alpine.js** - Interaktivitas ringan untuk navigation
- **Font Awesome** - Ikon lengkap untuk UI elements
- **Google Fonts** - Inter & Plus Jakarta Sans untuk typography premium

## Struktur Proyek

```
ispnet/
├── index.html              # Halaman utama (single page)
└── images/
    ├── hero.jpg            # Gambar hero section
    ├── about.jpg           # Gambar tentang kami
    ├── office.jpg          # Gambar kantor
    ├── team1-4.jpg         # Foto tim
    └── testimonial1-3.jpg  # Foto testimoni
```

## Halaman/Section

1. **Hero Section** - Pengenalan dengan CTA dan stats
2. **Features** - Keunggulan layanan ISPnet
3. **About** - Profil perusahaan
4. **Stats** - Statistik pencapaian
5. **Services - Paket Rumah** - 4 paket: Starter, Home Basic, Home Premium, Home Ultimate
6. **Services - Paket Bisnis** - 3 paket: Business Basic, Business Pro, Enterprise
7. **Testimonials** - Ulasan dari pelanggan
8. **CTA** - Call to action untuk menghubungi sales
9. **Footer** - Informasi kontak, social media, dan link

## Social Media
- Facebook
- Instagram
- LinkedIn
- YouTube

## Kustomisasi

### Mengganti Kontak
Edit file `index.html` dan cari:
- `0812-3456-7890` - Nomor WhatsApp
- `info@example.com` - Email
- `(021) 1234-5678` - Telepon
- Alamat di footer

### Mengganti Gambar
Ganti file di folder `images/` dengan gambar sesuai kebutuhan.

### Mengganti Warna
Edit `tailwind.config` di bagian `<script>` di `index.html`:
```
colors: {
    primary: {
        500: '#0ea5e9', // warna utama
        // ...
    }
}
```

## Credit

Design by [Bitnesia](https://www.bitnesia.com)

## Lisensi

Template ini gratis untuk digunakan. Silakan modifikasi sesuai kebutuhan.