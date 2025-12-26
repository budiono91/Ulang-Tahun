# Ulang-Tahun
# 🎉 Special Day: Nazwa - Interactive Birthday Website

Sebuah website ucapan ulang tahun interaktif yang dirancang khusus untuk memberikan kejutan digital yang berkesan. Proyek ini menggabungkan elemen *gamification* sederhana, desain modern (*Glassmorphism*), dan galeri foto interaktif.


## ✨ Fitur Utama

Website ini terdiri dari 4 tahapan (slide) interaktif:

1.  **Intro Challenge:** Halaman pembuka dengan tantangan untuk pengguna.
2.  **Mini Game "Catch Me":** Tombol yang akan menghindar ("lari") saat didekati kursor. Tombol hanya bisa diklik setelah percobaan ke-15 atau saat pengguna "menyerah".
3.  **Success Message:** Pesan transisi setelah berhasil menekan tombol.
4.  **Main Celebration:** Halaman utama yang berisi:
    * Efek **Confetti** (hujan kertas warna-warni) otomatis.
    * **Music Player** latar belakang (`lagu selamat ulang tahun.MP3`).
    * **3D Photo Gallery** menggunakan Swiper.js.
    * Surat ucapan personal dan tombol balas via **WhatsApp**.

## 🛠️ Teknologi yang Digunakan

Project ini dibangun menggunakan *Vanilla JavaScript* dengan bantuan beberapa library modern via CDN (tidak perlu instalasi Node.js):

* **HTML5 & CSS3**
* **[Tailwind CSS](https://tailwindcss.com/):** Framework CSS untuk styling cepat dan responsif.
* **[AOS (Animate On Scroll)](https://michalsnik.github.io/aos/):** Untuk animasi elemen saat di-scroll.
* **[Swiper.js](https://swiperjs.com/):** Untuk slider foto dengan efek 3D Coverflow.
* **[Canvas Confetti](https://www.kirilv.com/canvas-confetti/):** Untuk efek ledakan kertas saat halaman utama terbuka.
* **Glassmorphism Style:** Desain kartu transparan dengan efek *blur*.

## 📂 Struktur Folder

Agar website berjalan dengan baik (termasuk gambar dan lagu), pastikan struktur foldermu seperti ini:

```text
/birthday-nazwa
│
├── index.html                  # File utama (kode yang kamu buat)
├── README.md                   # Dokumentasi ini
│
├── /audio
│   └── lagu selamat ulang tahun.MP3
│
└── /image
    ├── foto-roblox.jpeg
    ├── foto awa 1.jpeg
    ├── foto awa 2.jpeg
    ├── foto awa 3.jpeg
    └── foto awa 4.jpeg
