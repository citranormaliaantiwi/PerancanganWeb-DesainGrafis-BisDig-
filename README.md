# PerancanganWeb-DesainGrafis-BisDig-

file:///C:/xampp/htdocs/xampp/citra%203.html

# PerancanganWeb-DesainGrafis-BisDig

Repositori ini berisi berbagai proyek terkait perancangan web dan desain grafis.

---

## Proyek 1: Halaman Profil Fotografer Profesional

**Deskripsi:**
Proyek ini mendemonstrasikan pembuatan halaman profil web yang sederhana namun fungsional untuk seorang fotografer profesional.

**File Terkait:** `index.html`, `style.css` (untuk bagian ini)

---

## Proyek 2: Blog Post dengan Fitur Komentar Dinamis

**Deskripsi:**
Proyek ini menunjukkan bagaimana JavaScript dapat digunakan untuk menambahkan interaktivitas sederhana pada halaman web, khususnya fitur "Tampilkan Komentar".

**File Terkait:** `index.html` (bagian JavaScript inline)

---

## Proyek 3: Landing Page Promosi - Komponen "PromoCard"

### Deskripsi Proyek

Proyek ini mendemonstrasikan implementasi dasar sebuah landing page promosi yang menampilkan komponen "PromoCard" dengan layout grid responsif.

**File Terkait:** `index.html`, `style.css` (untuk bagian ini)

---

## Proyek 4: Portofolio Mahasiswa dengan Desain Responsif

### Deskripsi Proyek

Proyek ini mengatasi masalah umum di mana situs web tidak terlihat rapi di perangkat seluler. Ini mendemonstrasikan penerapan **Desain Responsif** menggunakan **Media Queries** untuk memastikan tampilan situs portofolio yang optimal di berbagai ukuran layar, dari desktop hingga smartphone.

### Konsep Utama yang Diterapkan:

* **Responsive Design**: Pendekatan desain web di mana satu basis kode menyesuaikan layout dan elemen visual secara otomatis dengan ukuran layar perangkat.
* **Flexible Images**: Gambar diatur agar ukurannya otomatis menyesuaikan lebar kontainer tanpa meluber atau merusak rasio aspek.
* **Flexible Grid Layouts**: Menggunakan CSS Grid untuk membuat tata letak yang fleksibel, di mana item-item portofolio akan menyesuaikan jumlah kolomnya berdasarkan lebar layar.
* **Media Queries**: Aturan CSS yang memungkinkan penerapan gaya berbeda berdasarkan karakteristik perangkat (misalnya, lebar viewport). Ini digunakan untuk mengubah layout grid dari 3 kolom menjadi 2 kolom, dan akhirnya 1 kolom di layar yang sangat kecil.

### Solusi untuk Masalah Umum:

* **Gambar Terlalu Besar**: Diatasi dengan `img { max-width: 100%; height: auto; }`.
* **Teks Meluber**: Dicegah dengan penggunaan `max-width: 100%` pada kontainer teks dan penyesuaian padding/font-size via media queries. Layout grid juga memastikan kontainer item tidak meluber.

### Struktur File
