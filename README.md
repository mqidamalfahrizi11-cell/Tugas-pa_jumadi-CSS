# Panduan Selektor CSS

Daftar ini berisi referensi selektor yang sering digunakan dalam pengembangan web, dikategorikan berdasarkan metode penulisan CSS.

## 1. CSS Inline (Atribut Style)
*Catatan: CSS Inline tidak menggunakan selektor karena ditulis langsung di dalam tag HTML.*


| No | Tag Elemen | Fungsi Umum |
|:---:|:---:|:---|
| 1 | `h1` | Mengatur heading utama secara spesifik |
| 2 | `p` | Mengatur gaya pada paragraf tertentu |
| 3 | `div` | Mengatur gaya container/pembungkus |
| 4 | `span` | Mengatur dekorasi teks kecil dalam baris |
| 5 | `button` | Memberikan gaya instan pada tombol |
| 6 | `input` | Mengatur tampilan form input |
| 7 | `img` | Mengatur ukuran atau border gambar |
| 8 | `a` | Mengatur warna atau garis bawah link |
| 9 | `table` | Mengatur lebar atau border tabel |
| 10 | `li` | Mengatur gaya pada item list tertentu |

---

## 2. CSS Internal (Dalam Tag `<style>`)
Digunakan untuk mengatur gaya pada satu halaman HTML tertentu.


| No | Selektor | Jenis | Fungsi |
|:---:|:---|:---:|:---|
| 1 | `body` | Element | Mengatur latar belakang & font seluruh halaman |
| 2 | `h2` | Element | Mengatur semua heading level 2 |
| 3 | `.kotak` | Class | Selektor untuk elemen-elemen kelompok tertentu |
| 4 | `#judul` | ID | Selektor unik untuk satu elemen spesifik |
| 5 | `div p` | Descendant | Mengatur paragraf yang berada di dalam `div` |
| 6 | `ul li` | Descendant | Mengatur item list di dalam Unordered List |
| 7 | `input[type=text]` | Attribute | Mengatur input khusus tipe teks |
| 8 | `a:hover` | Pseudo-class | Mengubah gaya saat kursor diarahkan ke link |
| 9 | `section` | Element | Mengatur tata letak bagian (section) halaman |
| 10 | `*` | Universal | Meriset atau mengatur semua elemen sekaligus |

---

## 3. CSS External (File `.css` Terpisah)
Metode terbaik untuk proyek skala besar agar kode lebih terorganisir.


| No | Selektor | Fungsi |
|:---:|:---|:---|
| 1 | `.container` | Mengatur pembungkus utama tata letak (layout) |
| 2 | `h1` | Konsistensi gaya heading utama antar halaman |
| 3 | `.card` | Mengatur tampilan komponen kartu (box) |
| 4 | `#header` | Mengatur gaya area navigasi atas (unik) |
| 5 | `nav a` | Mengatur menu navigasi di dalam tag `nav` |
| 6 | `footer p` | Mengatur teks catatan kaki di bagian `footer` |
| 7 | `button:hover` | Memberikan efek interaktif pada tombol |
| 8 | `img` | Mengatur responsivitas semua gambar |
| 9 | `table tr` | Mengatur baris pada tabel secara keseluruhan |
| 10 | `ol li` | Mengatur urutan list pada Ordered List |

---
*Dibuat untuk dokumentasi belajar pengembangan web.*

