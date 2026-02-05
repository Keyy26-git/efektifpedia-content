# 📚 Efektifpedia Content Storage (The Brain)

<p align="center">
  <img src="https://img.shields.io/badge/Status-Automated-success?style=for-the-badge&logo=github-actions" alt="Status Automated">
  <img src="https://img.shields.io/badge/Architecture-Decoupled-blue?style=for-the-badge" alt="Architecture Decoupled">
  <img src="https://img.shields.io/badge/Powered%20By-AI-orange?style=for-the-badge" alt="AI Powered">
</p>

---

## 📜 Sejarah & Evolusi
Efektifpedia lahir dari visi untuk menyajikan konten berkualitas yang menjembatani antara kebutuhan bisnis dan pembaca. Perjalanan kami dibagi menjadi tiga fase utama:

| Fase | Deskripsi | Status |
| :--- | :--- | :--- |
| **1. Manual Era** | Jasa penulisan artikel kreatif melalui landing page Bootstrap. | ✅ Done |
| **2. Hybrid Era** | Penggunaan AI Bot untuk membantu riset & penulisan konten. | ✅ Done |
| **3. Decoupled Era** | Pemisahan Kode Utama (Repo A) dengan Gudang Konten (Repo B). | 🚀 Current |

---

## 🏗️ Arsitektur Sistem "The Decoupled"
Sistem ini menggunakan arsitektur modern yang memisahkan **Tampilan** dan **Isi**:

* **[Repo A (Main)](https://github.com/chipper26/efektifpedia):** Rumah bagi kode utama, desain Bootstrap, dan logika robot AI.
* **[Repo B (Content)](https://github.com/Keyy26-git/efektifpedia-content):** (Gudang ini) Tempat penyimpanan file artikel `.md` dan aset gambar.
* **Sveltia CMS:** Antarmuka manajemen konten yang memudahkan admin mengelola isi gudang tanpa menyentuh terminal.

---

## 🤖 Pasukan Robot Penulis
Repository ini diperbarui secara otomatis oleh **Trinitas AI Bot** yang bekerja di balik layar GitHub Actions:

| Bot Spesialis | Jadwal Update (WIB) | Kategori Konten |
| :--- | :--- | :--- |
| **News Bot** | 07:10, 13:10, 19:10 | Viral Technology & AI News |
| **Education Bot** | 09:40 & 21:40 | Edukasi & Lifestyle Tips |
| **Innovation Bot** | 05:15 | Deep Dive Tutorial & Digital Future |

---

## 🛠️ Development Log: Solving The "Gatekeeper"
Selama pembangunan, kami berhasil memecahkan tantangan teknis krusial untuk memastikan sinkronisasi antar-akun berjalan mulus:

> **Issue 403 Forbidden & Unpack Failed**
> Kami mengimplementasikan metode **"Clone & Inject"**. Alih-alih melakukan *push* standar, robot melakukan kloning segar ke dalam mesin virtual, menyisipkan konten baru, dan melakukan otentikasi menggunakan *Personal Access Token* (PAT) milik `Keyy26-git`.

---

## 📂 Struktur Data
```text
efektifpedia-content/
├── blog/             # Arsip seluruh artikel (.md)
├── img/
│   └── uploads/      # Aset visual pendukung artikel
└── README.md         # Dokumentasi sistem
