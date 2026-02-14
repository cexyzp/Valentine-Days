
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=200&color=FF69B4&text=Happy%20Valentine&animation=fadeIn&fontAlignY=50" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/DzarelDeveloper/Valentine-Days?style=for-the-badge&color=FF69B4" alt="last commit">
  <img src="https://img.shields.io/github/repo-size/DzarelDeveloper/Valentine-Days?style=for-the-badge&color=white" alt="repo size">
  <img src="https://img.shields.io/github/languages/top/DzarelDeveloper/Valentine-Days?style=for-the-badge&color=FF1493" alt="top language">
</p>

<p align="center">
  <a href="#-tech-stack--languages">
    <img src="https://img.shields.io/badge/Documentation-Explore-FF69B4?style=flat-square" />
  </a>
  <a href="https://github.com/DzarelDeveloper/Valentine-Days/issues">
    <img src="https://img.shields.io/badge/Issues-Report-red?style=flat-square" />
  </a>
</p>

---

## About The Project
Sebuah pengalaman web interaktif dan romantis yang dirancang khusus sebagai hadiah Valentine. Proyek ini memiliki alur interaktif multi-step yang membawa pengguna menuju 3D Dome Gallery berisi koleksi memori digital.

---

## Features

* **Love Mode Toggle**: Switch glassmorphic untuk transisi suasana UI.
* **Interactive Tic-Tac-Toe**: Modifikasi logika permainan untuk memunculkan elemen kejutan.
* **Love Meter**: Visualisasi progres menggunakan SVG gauge hingga 100%.
* **Typewriter Message**: Animasi teks dinamis untuk pesan personal.
* **3D Dome Gallery**: Galeri bola 3D interaktif untuk menampilkan aset foto.
* **Background Music**: Sistem pemutaran audio otomatis untuk file musik eksternal.
* **Premium UI**: Implementasi Tailwind CSS dan Framer Motion untuk transisi halus.

---

## Tech Stack & Languages

| Komponen | Teknologi |
| :--- | :--- |
| **Framework** | ![Next.js](https://img.shields.io/badge/Next.js%2015-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black) |
| **Language** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **Styling** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) |
| **Animation** | ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) |
| **Icons** | ![Lucide](https://img.shields.io/badge/Lucide_React-F75C03?style=flat-square&logo=lucide&logoColor=white) |

---

## Getting Started

### Prerequisites
* Node.js (v18 atau lebih tinggi)
* npm atau yarn

### Installation
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/DzarelDeveloper/Valentine-Days.git](https://github.com/DzarelDeveloper/Valentine-Days.git)
   cd Valentine-Days
   ```
 * Install dependencies:
   ```bash
   npm install
   ```
 * Run the development server:
   ```bash
   npm run dev
   ```

 * Open in browser:
   ```bash
   http://localhost:3000
   ```
Customization
Changing Photos
Simpan aset gambar di folder public/ dengan format penamaan 1.jpg hingga 15.jpg. Sesuaikan array userImages pada file app/page.tsx jika terdapat perubahan jumlah aset.
Changing Music
Ganti file public/pretty.mp3 dengan file audio pilihan. Pastikan ekstensi file sesuai atau perbarui referensi file pada kode sumber.
Changing the Message
Modifikasi teks pada file components/InteractionFlow.tsx di dalam komponen TypewriterStep.
Hosting & Deployment
Proyek ini dioptimalkan untuk dideploy menggunakan platform Vercel:
 * Sinkronisasi kode ke repository GitHub.
 * Hubungkan repository ke dashboard Vercel.
 * Jalankan proses deployment otomatis.

