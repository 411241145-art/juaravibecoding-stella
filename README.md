# juaravibecoding-stella
Juaravibecoding - Google dev Indoenesia
# 🌟 STELLA Dual-Core AI
**Inclusive Tele-Robotics & Enterprise Sign Language Translator**

Submission for **Google Developer Indonesia: #JuaraVibeCoding 2026**

![Gemini 3.1 Pro](https://img.shields.io/badge/Gemini%203.1%20Pro-AI%20Engine-4285F4?style=for-the-badge&logo=google)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Vision-EA4335?style=for-the-badge)

## 📖 Latar Belakang Proyek
Di sektor logistik dan importir alat berat, komunikasi yang cepat dan keselamatan kerja adalah harga mati. Namun, bagaimana jika operator atau pekerja di lapangan adalah teman-teman difabel (Tuli/Bisu)? 

**STELLA (Spatial Tele-Robotics Logical & Linguistic Architecture)** hadir sebagai solusi *Enterprise* yang menggabungkan Inklusivitas dan Keamanan Mesin. Menggunakan ketajaman **Gemini 3.1 Pro** dan pelacakan spasial **MediaPipe**, Stella membaca pergerakan gestur tangan secara *real-time* dan memprosesnya melalui dua "Core" (inti) secara bersamaan.

## ⚙️ Arsitektur Dual-Core
1. **Core 1: Kinetic Translator (Aksesibilitas)** Stella bertindak sebagai ahli linguistik, menerjemahkan bahasa isyarat dinamis (ayunan dan koordinat 3D) menjadi teks *subtitle* bahasa Indonesia yang natural agar mudah dipahami oleh pekerja awam.
2. **Core 2: Saturn Nodes Evaluator (Keselamatan Tele-Robotik)**
   Jika gestur yang terdeteksi adalah sebuah "Komando Alat Berat" (misal: Maju, Angkat Beban, Berhenti Darurat), Stella seketika memicu simulasi 7 Node Satelit Saturnus. Node **TITAN** akan mengevaluasi risiko benturan fisik, sementara Node **TETHYS** memastikan kelancaran gerak mesin sebelum perintah dikirim ke *database* (Status: APPROVED / REJECTED).

## 🛠️ Tech Stack
* **AI Brain:** Google Gemini 3.1 Pro (via `google-genai` SDK)
* **Computer Vision:** Google MediaPipe Hands (Client-side rendering)
* **Backend:** Python, FastAPI, Uvicorn (RESTful API)
* **Frontend:** HTML5, JavaScript, Tailwind CSS (LUMEN UI Design System)

## 🚀 Cara Menjalankan Aplikasi Secara Lokal

### 1. Kloning Repositori & Instalasi
Pastikan Python sudah terinstal di sistem Anda.
```bash
git clone [https://github.com/USERNAME-GITHUB-KAMU/stella-dualcore-ai.git](https://github.com/USERNAME-GITHUB-KAMU/stella-dualcore-ai.git)
cd stella-dualcore-ai
pip install -r requirements.txt
