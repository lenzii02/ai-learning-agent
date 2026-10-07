# AI Learning Agent Framework 🧠⚡

> **Project-Based Learning by Building with 80/20 Rule, 3D CAD Visualization, and Immediate Tangible Tasks**  
> Framework pembelajaran berbasis AI yang mengubah tumpukan materi teoritis, silabus kuliah, paper riset, atau kode repositori menjadi misi belajar praktis terarah.

Cocok dipasang di:
- **NotebookLM** (sebagai Source Note / Panduan Notebook)
- **ChatGPT / Claude / Hermes Agent / Cursor Rules / Antigravity IDE**

---

## 🚀 Mengapa Menggunakan Framework Ini?

Pembelajaran teknis konvensional sering kali gagal karena:
1. **Tutorial Hell / Teori Berlebihan**: Belajar berbulan-bulan dari bab 1 tanpa pernah menyelesaikan satu proyek nyata.
2. **Cognitive Overload (Kelelahan Mental / ADHD)**: AI memberikan penjelasan panjang setebal buku ensiklopedia yang sulit dicerna memori kerja.
3. **Tanpa Aksi Nyata**: Selesai membaca penjelasan AI, pengguna tidak tahu harus mengetik apa di editor.

**Solusi AI Learning Agent:**
- **Inspeksi Proyek Duluan**: Menyesuaikan materi belajar dengan kode atau tugas nyata yang sedang dikerjakan.
- **Prinsip 80/20 Agresif**: Hanya mengajarkan 20% konsep inti yang dibutuhkan untuk membuka blocker saat ini.
- **Visualisasi 3D & Hardware Wiring**: Menyediakan visualisasi 3D (OpenSCAD / Three.js) dan panduan pinout kabel saat berhadapan dengan robotika / mikrokontroler.
- **Wajib Ada Tugas Nyata (Tangible Task)**: Setiap sesi belajar diakhiri dengan tugas mini 15-30 menit yang menghasilkan artefak nyata.

---

## 📂 Struktur Repositori

```text
ai-learning-agent/
├── SKILL.md                          # Definisi skill untuk AI Agent (Hermes, Claude, OpenCode)
├── README.md                         # Dokumentasi utama framework
├── system-prompt-notebooklm.md       # Teks siap copy-paste ke NotebookLM / Custom Instructions
├── prompts/
│   └── prompt-cookbook.md            # Kumpulan prompt siap pakai (3D visual, wiring, 80/20, dsb)
├── modules/
│   ├── 01-inspect-and-learning-map.md  # SOP inspeksi repo & peta MUST KNOW / SKIP
│   ├── 02-80-20-deadline-mode.md       # Protokol kompresi materi saat deadline ketat
│   ├── 03-adhd-and-task-loop.md        # Loop belajar ramah ADHD (LEARN ➔ SEE ➔ DO ➔ CHECK)
│   └── 04-visualization-cad-robotics.md# Panduan visualisasi 3D, OpenSCAD, & pinout STM32
└── templates/
    └── task-template.md                # Template output tugas nyata berbatas waktu
```

---

## 🛠️ Cara Pasang di Google NotebookLM

1. Buat Notebook baru di [NotebookLM](https://notebooklm.google.com/).
2. Tambahkan berkas atau teks:
   - Salin isi dari `system-prompt-notebooklm.md` lalu tempel sebagai **Copied Text Source** atau buat sebagai Note utama.
   - Unggah materi belajar Anda (silabus, paper PDF, atau rangkuman repositori GitHub).
3. Gunakan prompt dari `prompts/prompt-cookbook.md` di kolom chat NotebookLM.

---

## 🎯 6 Skenario Penggunaan Utama (Prompt Showcase)

1. **Konsep ke Model 3D / Robotika**:  
   Minta 3 ide proyek robotika, pilih yang terbaik, dan buatkan visualisasi 3D (OpenSCAD/HTML).
2. **Wiring Hardware & Pinout**:  
   Kirim foto atau tipe board (misal: STM32 ke ST-LINK), dapatkan panduan sambungan pin kabel kabel step-by-step.
3. **Penyaring Silabus & Buku (80/20)**:  
   Masukkan silabus kuliah dan daftar buku tebal. Agen akan memotong 80% materi pelengkap dan menunjukkan bab mana yang benar-benar diujikan.
4. **Kurasi Paper Riset**:  
   Masukkan 5 paper akademis. Agen akan menyaring mana paper paling kredibel dan intisarinya.
5. **Mode Deadline Darurat (7 Hari)**:  
   Tanyakan pemahaman minimum mutlak untuk menyelesaikan tugas tanpa terjebak teori sejarah.
6. **Pencari Sumber Daya Gratis (Sub-Agent Web Search)**:  
   Mencari model 3D, dataset, dan tutorial gratis beserta lisensi penggunaannya.

---

## 📄 Lisensi & Kontributor
- **Author:** [lenzii02](https://github.com/lenzii02)
- **Lisensi:** MIT License
