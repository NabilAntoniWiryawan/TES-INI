# 📚 Perencanaan & Dokumentasi Pembuatan Landing Page "Nabil Book"
**Mata Kuliah:** Pemrograman Web (PW)  
**Teknologi:** Murni HTML5 & CSS3 (100% Offline Compatible)

---

## 1. Identitas Mahasiswa Pengembang
- **Nama Lengkap:** NABIL ANTONI
- **NIM:** SI22250011
- **Program Studi:** Sistem Informasi
- **Mata Kuliah:** Pemrograman Web (PW)
- **Topik Landing Page:** Bookstore (Toko Buku Online - **"Nabil Book"**)

---

## 2. Struktur File & Direktori Proyek
```text
PW/
│
├── index.html              # Berkas utama landing page semantik
├── planning.md             # Dokumen perencanaan & spesifikasi tugas
│
└── css/
    └── style.css           # Berkas styling pure CSS3 (Modern Minimalist)
```

---

## 3. Spesifikasi & Komponen Halaman (`index.html`)

1. **Header & Navigasi Semantik (`<header>`, `<nav>`)**
   - Logo bertema toko buku (*Nabil Book*) dengan ikon SVG murni.
   - Menu navigasi cepat: Beranda, Identitas Mahasiswa, Koleksi Buku, Kategori, Keunggulan, Kontak.
   - Tombol CTA *"Jelajahi Toko"*.

2. **Hero Section (`<section class="hero-section">`)**
   - Headline utama: *"Eksplorasi Dunia & Cerita Terbaik di Nabil Book"*.
   - Deskripsi singkat toko buku dengan fokus novel dan sastra berkualitas.
   - Tombol CTA ganda: *"Lihat Koleksi Bestseller"* & *"Info Pengembang Web"*.
   - Statistik ringkas: 500+ Judul, 100% Original, Rating 4.9/5.
   - Mockup visual buku 3D flat menggunakan CSS murni (menampilkan buku unggulan *Laut Bercerita*).

3. **Section Identitas Mahasiswa (`<section class="student-section">`)** *(Syarat Wajib Dosen)*
   - Terletak strategis tepat setelah Hero Banner agar dosen penilai langsung melihat keaslian tugas.
   - Memuat Avatar Mahasiswa (SVG terintegrasi), Nama Lengkap (**NABIL ANTONI**), NIM (**SI22250011**), Program Studi (**Sistem Informasi**), dan catatan orisinalitas proyek.

4. **Koleksi Novel & Fiksi Populer (`<section class="books-section">`)**
   - Grid 6 kartu buku dengan cover visual warna-warni murni CSS tanpa ketergantungan gambar luar:
     1. *Laut Bercerita* - Leila S. Chudori (Fiksi Sejarah)
     2. *Bumi Manusia* - Pramoedya Ananta Toer (Sastra Klasik)
     3. *Cantik Itu Luka* - Eka Kurniawan (Realisme Magis)
     4. *Hujan* - Tere Liye (Fiksi Ilmiah)
     5. *Gadis Kretek* - Ratih Kumala (Drama Sejarah)
     6. *Pulang* - Leila S. Chudori (Sastra Populer)
   - Setiap kartu buku dilengkapi: Label genre, judul, penulis, rating bintang, harga normal & diskon, serta tombol direct **Pesan via WhatsApp** (`https://api.whatsapp.com/send?...`).

5. **Kategori Genre Buku (`<section class="categories-section">`)**
   - 4 kartu kategori utama: *Fiksi & Sastra*, *Misteri & Thriller*, *Sci-Fi & Fantasi*, dan *Pengembangan Diri*.

6. **Keunggulan Toko (`<section class="features-section">`)**
   - 4 pilar layanan: *100% Asli & Bergaransi*, *Kemasan Aman Rapi*, *Harga Sahabat Mahasiswa*, dan *Proses Cepat & Responsif*.

7. **Testimoni Pembaca (`<section class="testimonials-section">`)**
   - Ulasan dari pembaca setia dan kalangan mahasiswa.

8. **Section Kontak & WhatsApp (`<section class="contact-section">`)**
   - Callout interaktif pemesanan dan konsultasi judul buku via WhatsApp.

9. **Footer Semantik (`<footer>`)**
   - Ringkasan toko, navigasi tautan, kolom identitas mahasiswa, dan *copyright notice* 2026.

---

## 4. Keunggulan Teknis CSS (`css/style.css`)
- **100% Offline-Ready:** Memakai *system font stack* modern (`-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto...`) sehingga halaman tampil cepat, elegan, dan sempurna meski komputer dosen tidak terhubung ke internet.
- **Pure CSS Book Cover Generator:** Sampul buku didesain dengan gradien CSS dan garis punggung buku (*book spine effect*), sehingga tidak akan terjadi masalah *broken image* / gambar tidak muncul saat file dipindah.
- **Fully Responsive:** Menggunakan CSS Flexbox, CSS Grid, dan Media Queries untuk kenyamanan tampilan di laptop, tablet, dan smartphone.
- **Desain Modern Minimalist:** Nuansa Slate Navy (`#0f172a`), Clean White Canvas (`#f8fafc`), dan Royal Blue Accent (`#2563eb`).

---

## 5. Status Pengerjaan
- [x] Perencanaan proyek & struktur berkas (`planning.md`)
- [x] Pengumpulan identitas mahasiswa & penentuan nama toko ("Nabil Book")
- [x] Pembuatan kode semantik HTML5 (`index.html`)
- [x] Pembuatan styling CSS3 responsif & offline-ready (`css/style.css`)
- [x] Verifikasi kelengkapan identitas mahasiswa (Nama, NIM, Prodi)
