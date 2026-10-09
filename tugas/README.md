# 📐 Kalkulator Interaktif & Geometri

> **Projek IT — Pemrograman Web & JavaScript**  
> *Kelas 10 Semester 1*

Aplikasi web modern, interaktif, dan responsif yang dibangun menggunakan **HTML5**, **Vanilla CSS3**, dan **JavaScript (ES6+)**. Aplikasi ini menyediakan dua mode kalkulator utama: **Kalkulator Persegi Panjang dengan Visualisasi Dinamis** dan **Kalkulator Standar Serbaguna**, lengkap dengan fitur peralihan tema (**Dark Mode & Light Mode**).

---

## ✨ Fitur Utama

### 1. 📐 Kalkulator Persegi Panjang & Visualisasi Geometris
- **Input Ukuran**:
  - Kolom input **Panjang ($p$)** dan **Lebar ($l$)** dalam satuan centimeter ($\text{cm}$).
  - Tampilan input bersih tanpa tombol panah/spinner bawaan browser yang mengganggu.
  - Dilengkapi validasi otomatis (memastikan nilai lebih besar dari 0).
- **Tombol Aksi**:
  - **Hitung Hasil**: Menghitung luas dan keliling secara instan tanpa memuat ulang (*reload*) halaman.
  - **Reset**: Mengosongkan form, mengembalikan hasil, dan mereset visualisasi ke bentuk awal.
- **Hasil Perhitungan**:
  - **Luas ($L$)**: $L = p \times l$ (disertai rincian langkah perhitungan).
  - **Keliling ($K$)**: $K = 2 \times (p + l)$ (disertai rincian langkah perhitungan).
- **Visualisasi Proporsional Real-Time**:
  - Bentuk persegi panjang otomatis menyesuaikan rasio ukuran panjang dan lebar yang diinputkan.
  - Dilengkapi label ukuran dinamis pada sisi atas ($p$), sisi kanan ($l$), dan luas area di tengah kotak.
  - Animasi transisi halus (*smooth scaling*) saat ukuran berubah.

---

### 2. 🧮 Kalkulator Biasa (Standar)
- **Operasi Aritmatika Lengkap**:
  - Penjumlahan ($+$), Pengurangan ($-$), Perkalian ($\times$), dan Pembagian ($\div$).
  - Tombol desimal ($.$), persentase ($\%$), dan pembalik tanda ($\pm$).
  - Tombol **$\text{AC}$** (*All Clear*) untuk reset dan **$\text{⌫}$** (*Delete*) untuk menghapus digit terakhir.
- **Layar Tampilan Ganda (Dual Display)**:
  - Baris atas menampilkan riwayat operasi (misal: `12 × 5 +`).
  - Baris utama menampilkan angka yang sedang diinput atau hasil akhir.
  - Bersih dari *scrollbar* atau panah bawaan sistem.
- **Dukungan Keyboard Fisik**:
  - Angka: `0` – `9`
  - Operator: `+`, `-`, `*`, `/`
  - Eksekusi: `Enter` atau `=`
  - Hapus: `Backspace`
  - Reset: `Escape`

---

### 3. 🌓 Toggle Dark Mode & Light Mode
- **Peralihan Tema Cepat**: Tombol di navigasi atas untuk beralih antara Mode Gelap (*Dark Mode*) dan Mode Terang (*Light Mode*).
- **Penyimpanan Otomatis (`localStorage`)**: Pilihan tema pengguna otomatis tersimpan di peramban, sehingga tema tetap terjaga saat halaman dibuka kembali.

---

### 4. 🎨 Desain Modern & Responsif
- **Aksen Glassmorphism**: Efek blur kartu modern dengan pencahayaan gradien elegan.
- **Tipografi Premium**: Menggunakan Google Fonts (*Plus Jakarta Sans* untuk UI dan *JetBrains Mono* untuk angka kalkulator).
- **Responsif**: Tampilan tetap rapi dan proporsional di perangkat ponsel (*smartphone*), tablet, maupun laptop/PC.

---

## 📁 Struktur Berkas

```text
tugas/
├── index.html     # File utama (struktur HTML, styling CSS, dan logika JavaScript)
└── README.md      # Panduan dokumentasi proyek
```

---

## 🚀 Cara Menjalankan Proyek

Proyek ini dibuat menggunakan teknologi web murni (*pure client-side*), sehingga **tidak memerlukan instalasi dependensi atau web server khusus**.

### Cara 1: Buka Langsung di Browser
1. Buka File Explorer di komputer Anda.
2. Masuk ke folder:  
   `d:\School\10th grade 1st semester\Project IT\JavaScript\tugas\`
3. Klik dua kali pada file **`index.html`** (akan otomatis terbuka di Google Chrome, Microsoft Edge, atau Firefox).

### Cara 2: Menggunakan VS Code (Live Server)
1. Buka folder proyek di **Visual Studio Code**.
2. Klik kanan pada file **`index.html`**.
3. Pilih **"Open with Live Server"**.

---

## 📖 Panduan Penggunaan

### Menghitung Persegi Panjang:
1. Pastikan Anda berada pada tab **"Persegi Panjang"**.
2. Masukkan angka pada kolom **Panjang (p)** (contoh: `12`).
3. Masukkan angka pada kolom **Lebar (l)** (contoh: `6`).
4. Klik tombol **"Hitung Hasil"**.
5. Lihat kartu hasil perhitungan **Luas** dan **Keliling**, serta perhatikan perubahan bentuk kotak pada bagian visualisasi.
6. Klik tombol **"Reset"** jika ingin mengulang perhitungan dari awal.

### Menggunakan Kalkulator Biasa:
1. Klik tab **"Kalkulator Biasa"** pada bagian atas layar.
2. Klik tombol angka dan operator pada layar, atau ketik langsung melalui keyboard fisik laptop/PC.
3. Tekan tombol **$=$** atau tombol `Enter` pada keyboard untuk memperoleh hasil perhitungan.

---

## 📐 Rumus Matematika yang Digunakan

| Bangun Datar | Rumus Luas | Rumus Keliling |
| :--- | :--- | :--- |
| **Persegi Panjang** | $L = p \times l$ | $K = 2 \times (p + l)$ |

---

## 🛠️ Teknologi yang Digunakan
- **HTML5**: Semantik dokumen web (`<header>`, `<main>`, `<section>`, `<form>`, `<nav>`).
- **CSS3**: CSS Variables, CSS Grid, Flexbox, Glassmorphism (`backdrop-filter`), dan Media Queries.
- **JavaScript (Vanilla ES6)**: DOM Manipulation, Event Listeners, State Management, Validasi Form, dan Web Storage API (`localStorage`).

---

*Dibuat untuk keperluan Tugas Pemrograman IT Kelas 10 Semester 1.*
