# 🧩 KED UI — Komponen UI Reusable Pribadi

**KED UI** adalah kumpulan komponen HTML dan CSS modular yang saya buat untuk digunakan ulang dalam berbagai proyek front-end, terutama untuk portofolio dan landing page pribadi. Komponen ini dibangun dengan struktur yang terorganisir dan tanpa dependensi framework (vanilla HTML & CSS).

---

## 🚧 Tujuan

Proyek ini bertujuan untuk:

- Menyediakan **komponen UI reusable** seperti kartu, carousel, label, dsb.
- Mempercepat proses pembuatan halaman dengan elemen siap pakai.
- Menjadi **base UI kit** untuk proyek statis seperti portofolio atau dokumentasi.

---

## 📁 Struktur Folder
```
portofolio/
├── asset/
│ ├── font/ # Font Inter (custom load)
│ └── img/ # Gambar untuk artikel, avatar, sertifikat
│
├── components/
│ ├── base/ # Komponen dasar: card, label, typography
│ └── sections/ # Komponen layout per section: article, certificate, carousel
│
├── styles/
│ └── global.css # Global styling
│
├── utilities/
│ └── *.html # Elemen global: header, footer, dsb
│
├── *.html # Halaman utama (contact, project, stack, dll)
└── README.md
```

---

## 🧱 Daftar Komponen

| Kategori     | Komponen                                           | Deskripsi                              |
|--------------|----------------------------------------------------|----------------------------------------|
| Base         | `card.html`, `label.html`                          | Komponen dasar UI                      |
| Typography   | `typograpy.html`                                   | Pengaturan teks                        |
| Sections     | `article.html`, `certificate.html`, `carousel.html`| Layout untuk konten utama              |
| Utilities    | `header.html`, `footer.html`, `global-chat.html`   | Komponen global tiap halaman          |

---

## 🔗 Cara Menggunakan

1. **Include komponen secara modular** dengan teknik HTML partials (jika pakai template engine atau build tool), atau **copy langsung ke proyek**.
2. Pastikan mengimpor `styles/global.css` agar semua komponen tampil dengan benar.
3. Ganti isi konten sesuai kebutuhan proyekmu.

---

## 📌 Catatan

- Tidak menggunakan framework JS atau CSS (pure HTML + CSS).
- Kompatibel dengan semua proyek HTML statis.
- Sangat cocok untuk landing page, portofolio, dan dokumentasi UI pribadi.

---

<!-- ## 📷 Screenshot

>  -->