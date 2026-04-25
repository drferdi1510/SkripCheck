# SkripCheck v.0.1.0
**AI Content Detector untuk Karya Ilmiah Akademik**  
Dibuat oleh dr. WIY

---

## Cara Deploy ke GitHub Pages

### 1. Buat Repository GitHub
- Buka [github.com](https://github.com) → login
- Klik **"New repository"**
- Nama: `skripcheck`
- Pilih **Public**
- Klik **Create repository**

### 2. Upload File
Upload ketiga file berikut ke repository:
- `index.html`
- `manifest.json`
- `README.md`

Caranya: klik **"uploading an existing file"** → drag & drop → **Commit changes**

### 3. Aktifkan GitHub Pages
- Masuk **Settings** → **Pages**
- Source: pilih **Deploy from a branch**
- Branch: **main** → folder: **/ (root)**
- Klik **Save**

### 4. Akses Aplikasi
Setelah 1–2 menit, aplikasi bisa diakses di:
```
https://username.github.io/skripcheck
```

---

## Cara Mendapatkan Groq API Key
1. Buka [console.groq.com](https://console.groq.com)
2. Daftar dengan email atau Google account (gratis)
3. Masuk menu **API Keys** → **Create API Key**
4. Beri nama, lalu **salin key** (hanya tampil sekali)
5. Format: `gsk_xxxxxxxxxxxxxxxxxxxxxxxx`

---

## Fitur
- Deteksi probabilitas konten AI (0–100%)
- Highlight per kalimat: AI / Tidak Pasti / Human
- Saran parafrasa otomatis
- Upload manuskrip (.PDF, .DOC, .DOCX)
- Bilingual Bahasa Indonesia & English
- API key tersimpan aman di browser

## Engine
- **Model**: LLaMA 3.3 70B (via Groq API)
- **Batas teks**: 300 kata per analisis
- **Biaya**: Gratis (Groq free tier)
