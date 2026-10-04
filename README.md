# Tugas Praktikum Pertemuan 3 - Desain Web

**Nama:** Karel Abimanyu Ahpandi
**NIM:** 4525210031
**Kelas:** A

## Isi Tugas

Individu

1. Modifikasi Profil Pertemuan 3 dengan 10 property CSS inline dan 4 format warna berbeda.
2. Membuat Mini Style Guide: 2 opsi font, warna utama, warna aksen, ukuran heading, dan line height.
3. Readme: source code, hasil screenshot desktop/mobile, ringkasan kesimpulan 150-200 kata.

## File

| File | Keterangan |
| --- | --- |
| `index.html` | Halaman Profil Mahasiswa (sudah dimodifikasi, CSS inline, tema Omen) |
| `img` | Foto profil dan Hasil Tampilan Desktop |

## 10 Property CSS Inline yang Digunakan

| No | Property | Contoh pemakaian |
| --- | --- | --- |
| 1 | `font-family` | `Arial, sans-serif` (body), `Impact, sans-serif` (heading) |
| 2 | `color` | `#a855f7` pada judul h1, `lavender` pada teks isi |
| 3 | `background-color` | `#0d0a1a` pada body, `rgba(168, 85, 247, 0.2)` pada kotak penutup |
| 4 | `font-size` | `36px` (h1), `24px` (h2), `16px` (isi) |
| 5 | `line-height` | `1.6` body, `1.8` paragraf Tentang Saya, `2` daftar |
| 6 | `text-align` | `center` pada judul, `justify` pada paragraf |
| 7 | `padding` | `15px` pada kotak penutup |
| 8 | `margin` | `30px` pada body |
| 9 | `border-radius` | `10px` pada foto profil |
| 10 | `border` | `3px solid #a855f7` pada foto, `1px solid #a855f7` pada garis `<hr>` |

Property tambahan: `border-bottom`, `padding-bottom`, `font-weight`, `text-transform`, `letter-spacing`, `text-shadow`.

## 4 Format Warna yang Digunakan

| Format | Contoh | Dipakai untuk |
| --- | --- | --- |
| Hex | `#a855f7`, `#0d0a1a` | Warna utama: judul h1, garis `<hr>`, border foto; latar body |
| RGB | `rgb(217, 70, 239)` | Warna aksen: sub-judul (h2) dan garis bawahnya |
| RGBA | `rgba(168, 85, 247, 0.2)` | Latar kotak penutup (transparan), efek cahaya judul |
| Nama warna | `lavender` | Warna teks isi |

## Mini Style Guide

**Font**

- Opsi A (sans-serif, isi/body): `Arial, sans-serif`
- Opsi B (heading): `Impact, sans-serif`

**Warna**

- Utama: `#a855f7` (ungu)
- Aksen: `rgb(217, 70, 239)` (magenta)
- Pendukung: `#0d0a1a` (latar), `rgba(168, 85, 247, 0.2)` (latar kotak), `lavender` (teks)

**Ukuran heading dan line height**

| Elemen | Ukuran | Line height |
| --- | --- | --- |
| h1 | 36px | 1.6 |
| h2 | 24px | 1.6 |
| Paragraf | 16px | 1.6 |
| Daftar | 16px | 2 |


## Screenshot

**Tampilan Desktop**

<img width="1901" height="1091" alt="index desktop" src="https://github.com/user-attachments/assets/f690551e-8007-4499-9bd7-724fdd810b5e" />


## Ringkasan Kesimpulan

Pada tugas ini saya memodifikasi halaman Profil Mahasiswa menggunakan CSS inline, yaitu atribut style yang ditulis langsung pada tiap elemen HTML. Saya memakai lebih dari sepuluh property CSS, di antaranya font-family, color, background-color, font-size, line-height, text-align, padding, margin, border-radius, dan border. Saya juga menggunakan empat format warna, yaitu hex, rgb, rgba, dan nama warna, sehingga saya memahami bahwa satu warna bisa ditulis dengan cara berbeda dan rgba memberi kontrol transparansi. Tema halaman saya sesuaikan dengan karakter Omen dari Valorant, yaitu latar ungu gelap, judul dengan efek cahaya, dan teks terang. Saya membuat mini style guide berisi dua opsi font, warna utama, warna aksen, ukuran heading, dan line height supaya tampilan konsisten. Dari tugas ini saya belajar bahwa CSS inline mudah dipakai untuk latihan karena hasilnya langsung terlihat, tetapi kurang efisien karena gaya yang sama, seperti pada tiga subjudul, harus ditulis berulang. Karena itu, untuk proyek yang lebih besar, file CSS terpisah lebih cocok dipakai.
