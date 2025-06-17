# **Synapsis AI - Sistem Penyaringan CV Cerdas**
**Synapsis AI** adalah aplikasi web modern yang dirancang untuk membantu tim HR merevolusi proses rekrutmen. Dengan memanfaatkan kekuatan AI, aplikasi ini dapat menganalisis deskripsi pekerjaan dan puluhan CV secara bersamaan, lalu memberikan skor kecocokan dan ringkasan analisis mendalam untuk setiap kandidat.

Proyek ini dibangun menggunakan **Flask** untuk backend dan **Alpine.js** untuk frontend yang interaktif, serta terhubung dengan **DeepSeek-V3-0324** sebagai otaknya.

**Demo:**

<video src="media/2025-06-17 07-16-37_1.mp4" controls width="600">
  Your browser does not support the video tag.
</video>

## **Fitur Utama**
- **Analisis Berbasis AI:** Membandingkan konten CV dengan deskripsi pekerjaan untuk menghasilkan skor kecocokan yang objektif.
- **Unggahan Massal:** Mendukung unggahan beberapa CV kandidat sekaligus untuk efisiensi maksimal.
- **Analisis Mendalam:** Memberikan ringkasan positif, poin kunci yang cocok, dan poin perhatian untuk setiap kandidat.
- **Dukungan Multi-bahasa:** Mampu mendeteksi dan memberikan analisis dalam bahasa yang sama dengan CV (Indonesia atau Inggris).
- **Laporan Profesional:** Mengunduh hasil analisis dalam format file Excel (.xlsx) yang rapi, lengkap dengan styling untuk kemudahan membaca.

## **Tech Stack**
### **Backend:**
- Python 3 dengan Flask
- Gunicorn sebagai WSGI Server
- Pandas & Openpyxl untuk pembuatan laporan Excel
- PyMuPDF untuk ekstraksi teks dari PDF

### **Frontend:**
- HTML5
- Tailwind CSS untuk styling
- Alpine.js untuk reaktivitas antarmuka

### **Layanan AI:**
- DeepSeek-V3-0324

### **Deployment:**
- Railway

### Akses Aplikasi
Aplikasi ini telah di-deploy dan dapat diakses secara publik melalui tautan berikut:

[Buka Synapsis AI](https://synapsis-ai-production.up.railway.app/)