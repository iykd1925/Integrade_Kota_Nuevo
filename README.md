# Integrade Kota Nuevo

[![Unity Version](https://shields.io)](https://unity.com)
[![Platform](https://shields.io)](#)
[![Genre](https://shields.io)](#)
[![Theme](https://shields.io)](#)

**Integrade Kota Nuevo** adalah game *casual-simulation arcade* 2D bertema keberlanjutan kota (*Sustainable Cities and Communities*). Dalam game ini, pemain berperan sebagai seorang **BuzzNova** (kondektur/pramujasa halte bus kota) yang bertugas mengelola rute penumpang demi menjaga keseimbangan ekonomi, sosial, dan pertahanan Kota Nuevo.

Game ini dikembangkan menggunakan **Unity Engine** dan dioptimalkan agar dapat dimainkan secara fleksibel melalui platform **PC** maupun langsung di browser (**Web/WebGL**).

---

## 📑 Ringkasan Dokumen Desain Game (GDD)

### 1. Unique Selling Point (USP)
* **Top-Down 2D Management View:** Sudut pandang dari atas memudahkan pemain melihat seluruh area halte, antrian warga, dan pergerakan bus secara taktis.
* **Impactful Management:** Setiap keputusan rute penumpang berpengaruh langsung pada indikator keberlanjutan kota.
* **Empathetic Learning:** Pemain belajar memahami isu aksesibilitas, keselamatan, dan kualitas transportasi publik melalui cerita dan dilema para NPC.
* **Story & Arcade Fusion:** Kombinasi antara perkembangan narasi yang emosional dengan *gameplay arcade* yang cekatan.

### 2. Mekanik Utama (Core Gameplay)
* **Sistem Inspeksi:** Pemain menekan karakter penumpang di area halte, membaca dialog singkat, melakukan inspeksi, dan mencocokkan kebutuhan mereka dengan rute bus.
* **Top-Down Drag-and-Drop:** Mekanik utama memilah dan menarik grafis penumpang dari antrian halte menuju kompartemen bus yang tepat.
* **Time & Patience Limit:** Setiap penumpang memiliki batas kesabaran 30 detik. Pemain dituntut teliti dan cekatan agar tingkat kepuasan warga tidak turun di bawah 80%.
* **Progression System:** Menyelesaikan sesi permainan menghasilkan EXP untuk menaikkan level, membuka rute/bangunan baru, serta melanjutkan alur cerita.

---

## 🎨 Spesifikasi Visual & Audio

### Karakter & Dunia Game
* **Dunia Game (Lore):** Kota Nuevo sedang berkembang dari kota kecil di pinggir Pulau Wemdalain. Dipimpin oleh lembaga teknologi **Tarapoza**, kota ini mengoperasikan sistem bus bernama **Buzz**.
* **Daftar NPC:** Penumpang terdiri dari berbagai golongan masyarakat dengan kebutuhan unik: Lansia (Kakek Oda, Nenek Bella), Pelajar (Parama, Viano), Pekerja, Ibu & Anak, hingga Penyandang Disabilitas (Noma, Noku, Nomu).
* **Resolusi & Perspektif Aset:** 
  * Perspektif: **Top-Down 2D** (Tampak Atas)
  * Sprite Karakter: `32x32 px`
  * Bus: `64x64 px`
  * Background Halte & Lingkungan: `1280x720 px`

### Musik & Sound Effect
* **BGM Kota:** Musik klasik *Vivaldi – The Four Seasons "Spring"* (Remix Version).
* **BGM Gameplay:** *Vivaldi – The Four Seasons "Autumn"* (Remix Version).
* **SFX:** Bunyi ketikan balon dialog, bel penanda sesi, bunyi pintu bus ditutup, dan efek suara umpan balik *right/wrong answer*.

---

## 🛠️ Arsitektur Teknis & Kebutuhan Sistem

### Spesifikasi Sistem Minimum (Target 30 FPS):
* **OS:** Windows 10
* **Processor:** Intel Centrino / AMD Athlon
* **Memory:** RAM 4 GB
* **Storage:** 128 GB
* **Graphics:** Intel HD Graphics / AMD Radeon

### Skema Kontrol Input:
* **Mouse (Click & Drag):** Untuk interaksi lingkungan *top-down*, UI, inspeksi, dan memindahkan penumpang dari halte ke bus.
* **[Enter]:** Mengunci jawaban/keputusan rute.
* **[ESC]:** Jeda permainan (*Pause Game*).

---

## 🚀 Rencana Pengembangan (Roadmap)
- [x] **Oktober (Minggu ke-4):** Finalisasi Dokumen GDD & Produksi Aset Visual/Audio.
- [ ] **November:** Pengembangan Purwarupa Core Mechanics (*Core Loop Top-Down*).
- [ ] **Desember:** Perilisan Versi Alpha 1 (Playable, Stable & Bug-Free).

---

## 🤝 Lisensi & Kontribusi
Proyek ini dikembangkan sebagai bagian dari mata kuliah **Pemrograman Permainan 2D & Teknologi Permainan** di **Politeknik Negeri Media Kreatif Jakarta**.

* **Dosen Pengampu:** Yeni Nurhasanah, S.Pd., M.T
* **Pengembang Utama:** Dea Anda Lusia (GJ25A / 25913459021) — *Holix Paradox*

*Copyright © 2026 Holix Paradox. All rights reserved.*
