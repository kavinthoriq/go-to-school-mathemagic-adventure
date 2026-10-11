# 🎒 GO TO SCHOOL: Mathemagic Adventure

Game edukasi bergenre **RPG petualangan** bertema matematika, dibuat dengan **RPG Maker MZ**. Ikuti perjalanan **Vynz** berangkat ke sekolah, melewati berbagai ujian karakter, belajar tentang **sifat operasi hitung**, lalu menjelajah **Dunia Bilangan** yang penuh tantangan angka.

> 🎮 **Mainkan langsung di browser:** [kavinthoriq.github.io/go-to-school-mathemagic-adventure](https://kavinthoriq.github.io/go-to-school-mathemagic-adventure/)

<!-- Tambahkan screenshot di sini, misalnya:
![Menu Utama](screenshots/menu.png)
-->

---

## 📖 Tentang Game

*Go To School* adalah contoh media pembelajaran interaktif yang menggabungkan cerita, penanaman nilai karakter, dan latihan soal matematika dalam satu permainan. Pemain tidak hanya menjawab soal, tetapi juga harus membuat pilihan yang mencerminkan sikap baik: berpamitan kepada orang tua, menolak ajakan membolos, dan bekerja sama dengan teman.

> ⚠️ Seperti yang disebutkan di dalam game: game ini adalah hiburan sebagai contoh media pembelajaran.

---

## 🗺️ Alur Cerita

| Tahap | Lokasi | Deskripsi |
| --- | --- | --- |
| **Prolog** | Rumah | Vynz harus berpamitan kepada Ibu sebelum pintu rumah bisa dibuka. |
| **Ujian Karakter** | Lingkungan | Bertemu Kakek, lalu menghadapi si Penghasut yang mengajak bolos. Pilihan yang salah berujung *Game Over*. |
| **Gerbang Pengetahuan** | Depan Sekolah | Penguji menghalangi jalan dan memberi soal hitung sederhana. |
| **Kerja Sama Tim** | Halaman Sekolah | Pintu sekolah hanya bisa dibuka jika Vynz mengajak teman-temannya (Babang, Opang, dan Arul) masuk bersama. |
| **Sesi Pembelajaran** | Kelas | Pak Guru menjelaskan materi **Sifat Operasi Hitung** beserta contoh penggunaannya. |
| **Hidden Stage** | Dunia Bilangan | Dungeon fantasi penuh angka dengan monster, perahu penyeberangan, dan boss kecil. |
| **Ending** | Rumah | Vynz pulang dan disambut Ibu yang bangga padanya. |

---

## ✨ Fitur

- **Cerita dengan nilai karakter**: hormat kepada orang tua dan guru, rajin belajar, serta kerja sama dengan teman.
- **Dialog bercabang**: pilihan jawaban memengaruhi kelanjutan cerita dan bisa menyebabkan *Game Over*.
- **Materi pembelajaran dalam game**: Sifat Operasi Hitung dan contoh penggunaannya, dipilih langsung oleh pemain di kelas.
- **Soal berbasis pertempuran**: di Dunia Bilangan, jawaban salah mengurangi EXP, dan terlalu banyak salah membuat pemain kalah.
- **Empat area permainan**: Rumah, Lingkungan, Sekolah, dan Dunia Bilangan.
- **Langsung main di browser**: tanpa instalasi, bisa dibuka lewat PC maupun HP.

---

## 🧮 Materi Matematika

- Operasi hitung campuran (penjumlahan dan pengurangan)
- Sifat-sifat operasi hitung
- Sifat distributif, contohnya `(13 × 10) + (11 × 10) = 10 × (13 + 11)`

---

## 🧑‍🤝‍🧑 Karakter

| Karakter | Peran |
| --- | --- |
| **Vynz** | Tokoh utama yang dimainkan pemain |
| **Ibu** | Orang tua Vynz yang memberi pesan sebelum berangkat |
| **Kakek** | Warga sekitar yang menasihati Vynz di jalan |
| **Penghasut** | Sosok yang mengajak Vynz membolos |
| **Penguji** | Penjaga gerbang yang menguji kemampuan hitung Vynz |
| **Security** | Penjaga sekolah |
| **Babang, Opang, Arul** | Teman-teman Vynz |
| **Pak Guru** | Guru yang menyampaikan materi di kelas |
| **Monster & NPC People** | Penghuni Dunia Bilangan |

---

## 🕹️ Cara Bermain

| Aksi | PC (Keyboard) | HP (Layar Sentuh) |
| --- | --- | --- |
| Bergerak | Tombol panah | Ketuk lokasi tujuan |
| Interaksi / Konfirmasi | `Enter` / `Z` / `Spasi` | Ketuk layar |
| Batal / Buka menu | `Esc` / `X` | Ketuk dua jari / tombol menu |

---

## 🚀 Cara Menjalankan

### 1. Main Online (paling mudah)
Buka tautan demo di atas langsung dari browser, tanpa instalasi.

### 2. Jalankan Secara Lokal
Game versi web perlu dijalankan lewat web server (tidak bisa dengan dobel-klik `index.html`).

```bash
# Clone repository
git clone https://github.com/kavinthoriq/go-to-school-mathemagic-adventure.git
cd go-to-school-mathemagic-adventure

# Pilih salah satu cara menjalankan server lokal:
npx http-server        # jika memakai Node.js
python -m http.server  # jika memakai Python
```

Lalu buka `http://localhost:8080` (http-server) atau `http://localhost:8000` (Python) di browser.

---

## 📁 Struktur Folder

```
go-to-school-mathemagic-adventure/
├── audio/            # BGM, BGS, ME, dan SE
├── css/              # Stylesheet game
├── data/             # Data game (map, event, database)
├── effects/          # Efek animasi
├── fonts/            # Font game
├── icon/             # Ikon aplikasi
├── img/              # Gambar (karakter, tileset, UI, dll.)
├── js/               # Engine & plugin RPG Maker MZ
├── movies/           # Video
├── index.html        # Titik masuk game
├── package.json
├── .nojekyll         # Agar GitHub Pages melayani semua file
├── .gitignore
└── README.md
```

---

## 🛠️ Teknologi

- [RPG Maker MZ](https://www.rpgmakerweb.com/products/rpg-maker-mz): engine pembuatan game
- JavaScript, HTML5, dan CSS3: dasar dari game versi web
- GitHub Pages: hosting versi web

---

## 🎨 Kredit & Lisensi Aset

- Game dibuat menggunakan **RPG Maker MZ**. Aset bawaan (grafis dan audio) mengikuti ketentuan lisensi RPG Maker MZ dari Gotcha Gotcha Games / KADOKAWA.
- Jika kamu memakai aset dari pihak lain, cantumkan namanya di sini:
  - _(contoh: Nama Aset, oleh Nama Kreator, tautan)_

Project ini dibuat untuk keperluan pembelajaran.

---

## 👤 Author

**Kavin Thoriq**
- GitHub: [@kavinthoriq](https://github.com/kavinthoriq)

---

⭐ Kalau kamu suka project ini, jangan lupa kasih **star** di repository ini!
