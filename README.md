# 🪐 STELLA ORBIT
**Inclusive Tele-Robotics & Enterprise Sign Language Translator**
*Submission for Google Developer Indonesia: #JuaraVibeCoding 2026*

## 🚨 Latar Belakang Masalah (The Problem)
Sektor logistik dan industri importir alat berat memiliki dua tantangan besar saat ini:
1. **Minimnya Aksesibilitas:** Pekerja lapangan yang merupakan teman-teman difabel (Tuli/Bisu) sering kali kesulitan memberikan aba-aba yang cepat dan akurat kepada operator alat berat, yang mana berpotensi mengucilkan mereka dari ekosistem kerja industri berat.
2. **Risiko Keselamatan Kerja:** Kesalahan komunikasi sekecil apa pun dalam mengendalikan alat berat (seperti *forklift* atau *crane*) dapat berakibat fatal bagi keselamatan fisik pekerja di sekitarnya.

## 💡 Solusi: STELLA ORBIT
**STELLA (Spatial Tele-Robotics Logical & Linguistic Architecture)** hadir sebagai sistem AI penengah yang memecahkan kedua masalah tersebut sekaligus melalui pendekatan **Orbit**:

* **Core 1: Kinetic Translator (Inklusivitas).** Stella membaca matriks koordinat kerangka tangan secara *real-time* dan menerjemahkan bahasa isyarat pekerja menjadi teks instruksi natural yang mudah dibaca oleh siapa saja.
* **Core 2: Saturn Nodes Evaluator (Keselamatan).** Saat Stella mendeteksi bahwa isyarat tersebut adalah perintah mesin (misal: "Maju", "Angkat"), sistem tidak langsung mengeksekusinya. Stella akan memicu simulasi Node keamanan satelit (seperti Node TITAN) untuk memvalidasi risiko manuver sebelum memberikan status `APPROVED` atau `REJECTED`.

## ⚙️ Cara Kerja & Teknologi (Tech Stack)
Aplikasi ini dirancang ringan dan aman. Alih-alih mengirimkan video berat ke *server*, sistem ini merender video di *browser* dan hanya mengirimkan titik matriks JSON ke AI.
* **AI Brain:** Google Gemini 3.1 Pro (Menganalisis matriks menjadi keputusan spasial).
* **Vision Sensor:** Google MediaPipe Hands (Client-side rendering).
* **Backend Engine:** Python, FastAPI, Uvicorn.
* **Frontend UI:** HTML5, JS, Tailwind CSS (LUMEN UI System).

## 🚀 Instalasi Lokal
Jika Anda ingin mengevaluasi mesin ini secara lokal:
1. *Clone* repositori ini: `git clone https://github.com/USERNAME-GITHUB-KAMU/NAMA-REPOSITORI-KAMU.git`
2. Instal dependensi: `pip install -r requirements.txt`
3. Masukkan kunci rahasia Anda ke dalam *Environment Variables* dengan nama `GEMINI_API_KEY`.
4. Jalankan *server*: `python -m uvicorn main:app --reload`
5. Buka `index.html` pada browser Anda.

---
**Kevin Gunawan**
*S1 Teknik Informatika - Universitas Dian Nusantara (UNDIRA)*
