<!-- Watermark: NIM: 103122400018 | Nama: Muhammad Rasyid Ridho -->

# Curriculum Vitae — Muhammad Rasyid Ridho (103122400018)

Website CV pribadi sederhana untuk tugas Praktikum Web. Fokusnya pada penerapan elemen semantik dasar, penggunaan tabel untuk data terstruktur, pembuatan form, dan styling tata letak menggunakan Flexbox tanpa mengandalkan framework eksternal.

## 🎯 Poin Utama

- Menggunakan **HTML5 semantik**, dengan struktur yang memanfaatkan elemen seperti `<aside>`, `<nav>`, `<main>`, dan `<section>`.
- CSS **native eksternal** murni, tidak menggunakan framework, dan pemisahan yang jelas antara struktur (HTML) dan desain (CSS).
- Layout navigasi dan beberapa elemen konten utama (seperti profil dan kontak) diatur menggunakan **CSS Flexbox**.
- Menggunakan elemen `<table>` yang telah di-styling (termasuk efek hover) untuk menampilkan riwayat pendidikan, pengalaman kerja, dan sertifikasi secara rapi.
- Memiliki bagian **Form Registrasi** fungsional di bagian bawah dengan berbagai tipe input HTML5 (`text`, `email`, `date`, `radio`, dll).

## 📂 Struktur File

    .
    ├── index.html   # Halaman utama struktur CV
    ├── style.css    # Stylesheet eksternal untuk index.html
    └── me.jpeg      # Aset gambar profil

Hanya menggunakan file inti yang sangat mudah dipelajari dan dimodifikasi tanpa perlu setup yang rumit.

## 🌐 Cara Pakai

Buka file `index.html` langsung lewat browser pilihanmu, atau gunakan server lokal untuk melihat perubahan secara real-time saat mengedit. Atau bisa gunakan extension live server.

## 🧱 Struktur Halaman

Halaman ini dibagi menjadi beberapa bagian utama:
- **Sidebar (Kiri):** Berisi menu navigasi (`<nav>`) yang diatur fixed agar selalu terlihat saat di-scroll.
- **Konten Utama (Kanan):** 
  - **Profile:** Foto, nama, peran, dan deskripsi singkat.
  - **Education:** Tabel riwayat pendidikan.
  - **Work Experience:** Tabel pengalaman kerja dan freelance.
  - **Certificate and Training:** Tabel daftar sertifikasi.
  - **Contact & Social Media:** Daftar email, telepon, dan tautan sosial media.
  - **Register:** Form interaktif untuk pendaftaran dengan validasi required.

## 🎨 Desain

### Tema & Warna
- Tema desain menggunakan mode gelap (Dark Mode) dengan warna latar belakang dominan biru sangat gelap (`#000011`).
- Warna teks utama putih (`#fff`) dengan warna aksen keabu-abuan (`#b5bfcc`) untuk tautan dan elemen sekunder, memberikan kontras yang nyaman di mata.

### Layout & Tipografi
- Menggunakan **CSS Flexbox** untuk menata navigasi sidebar dan membagi kolom di bagian kontak (kiri kontak, kanan sosial media).
- Tabel memiliki desain modern dengan border-collapse, outline halus (`#474747`), dan efek hover interaktif (`#262926`) pada setiap baris.
- Form dibuat rapi dengan input yang mengisi lebar penuh container dan tombol submit bergaya interaktif.
- Mendukung `scroll-behavior: smooth` untuk transisi navigasi halaman yang mulus.

## 🛠 Teknologi

| Kategori | Teknologi yang dipakai |
|----------|------------------------|
| Markup | HTML5 |
| Style | CSS3 native (eksternal) |
| Layout | CSS Flexbox |
| OS / environment | Local browser / http server |

Sengaja tidak menggunakan framework CSS seperti Bootstrap atau Tailwind agar fokus pada pemahaman dasar CSS murni (Vanilla CSS).

## ✅ Validasi Pokok

- Implementasi form HTML lengkap dengan atribut `<label>` yang dihubungkan dengan id input, dan validasi form dasar menggunakan atribut `required`.
- Tautan navigasi sidebar menggunakan anchor link (`href="#id"`) yang terhubung langsung dengan ID pada tiap `<section>`.
- Tabel data terstruktur dengan elemen `<th>` dan `<td>` yang semantik.

## 🔮 Pengembangan Selanjutnya

Ruang untuk perbaikan dan pengembangan di masa depan:
- **Responsivitas Layar (Mobile Friendly):** Menambahkan CSS Media Queries (`@media`) agar sidebar navigasi dapat berubah menjadi menu hamburger atau pindah ke atas/bawah pada layar berukuran kecil (HP).
- **Variabel CSS:** Mengganti warna hardcoded menjadi variabel CSS (`:root`) untuk mempermudah perubahan tema.
- **CSS Grid:** Menggunakan CSS Grid untuk layout utama halaman guna pemosisian aside dan main yang lebih kokoh.

## 📝 Penjelasan Singkat Per Elemen

- `<aside>`: Digunakan sebagai kontainer sidebar untuk navigasi.
- `<nav>`: Menu daftar tautan anchor yang mengarah ke bagian-bagian dalam halaman.
- `<main>`: Kontainer pusat untuk seluruh konten spesifik CV.
- `<section>`: Membagi konten utama secara logis berdasarkan topik (Profil, Pendidikan, dll).
- `<table>`: Menyajikan data terstruktur dengan pembagian header (`<th>`) dan data (`<td>`).
- `<form>`: Wadah pengumpulan input data pengguna di bagian registrasi.