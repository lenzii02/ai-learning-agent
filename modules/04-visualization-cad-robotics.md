# Module 4: 3D Visualization, CAD, & Robotics

## 1. Konsep Visualisasi Cepat
Jika konsep bersifat mekanik, 3D, atau perangkat keras, teks saja tidak cukup. Agen harus menyediakan representasi visual interaktif:

1. **OpenSCAD Script**: Untuk visualisasi komponen 3D CAD parametrik (bracket motor, sasis robot, enclosure sensor).
2. **Three.js / WebGL HTML**: Halaman HTML mandiri yang merender objek 3D interaktif yang bisa diputar (orbit control) di browser.
3. **Diagram Pinout Sirkuit (Mermaid / Markdown Table)**: Pemetaan sambungan pin mikrokontroler (STM32, ESP32, Arduino) ke sensor atau programmer (ST-LINK).

---

## 2. Robotics & Hardware 3-Step Pitch Framework

Jika user ingin membuat proyek robotika:

### Step 1: Brainstorm 3 Ide Terukur
- **Opsi A (Aman & Cepat)**: Memanfaatkan sensor dan modul yang sudah dimiliki user.
- **Opsi B (Menengah & Aplikatif)**: Menyeimbangkan tantangan mekanik dan algoritma kontrol (misal: PID line follower, self-balancing).
- **Opsi C (Ambisius tapi Terarah)**: Menggunakan computer vision atau inverse kinematics terisolasi.

### Step 2: Pitch & Rekomendasi
- Bandingkan estimasi biaya komponen, waktu pengerjaan, dan tingkat kesulitan software.
- Rekomendasikan 1 ide terbaik beserta alasan rasionalnya.

### Step 3: Desain 3D & Panduan Wiring Step-by-Step
- Berikan skrip OpenSCAD untuk struktur mekanik.
- Berikan tabel sambungan pin:
  | Board Pin | Target Module | Wire Color | Deskripsi Fungsi |
  |---|---|---|---|
  | SWDIO (PA13) | ST-LINK SWDIO | Kuning | Jalur data debug serial wire |
  | SWCLK (PA14) | ST-LINK SWCLK | Hijau | Jalur clock debug serial wire |
  | GND | ST-LINK GND | Hitam | Ground referensi bersama |
  | 3.3V | ST-LINK VAPP | Merah | Tegangan daya logika |
