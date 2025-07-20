# IBM-Granite-Capstone-Environment-News-Analysis
Capstone Project: Klasifikasi dan Peringkasan Berita Lingkungan dengan IBM Granite AI

# **Proyek Capstone: Analisis Isu Lingkungan Global melalui Berita**
## **Klasifikasi dan Peringkasan Otomatis dengan IBM Granite AI**

---

### **Tentang Proyek Ini**
Proyek Capstone ini adalah bagian dari program sertifikasi **IBM Data Classification and Summarization Using IBM Granite**. Tujuannya adalah untuk mendemonstrasikan kemampuan dalam mengekstrak wawasan dari data teks skala besar menggunakan model Bahasa Besar (LLM). Kami fokus pada analisis berita lingkungan, mengklasifikasikannya berdasarkan isu dan meringkas isinya, untuk membantu pemahaman informasi yang cepat dan efisien.

---

### **Tujuan Proyek**
* **Klasifikasi Otomatis:** Mengidentifikasi dan mengkategorikan isu lingkungan utama dari artikel berita (misalnya, Perubahan Iklim, Polusi, Energi Terbarukan).
* **Peringkasan Cepat:** Mereduksi artikel panjang menjadi intisari informatif yang ringkas (sekitar 3-4 kalimat).

---

### **Dataset**
Dataset yang digunakan adalah **"Guardian Environment News Dataset"** dari Kaggle, berisi ribuan artikel berita lingkungan. Untuk proyek ini, kami memproses **10 artikel teratas** untuk mendemonstrasikan kapabilitas model secara efektif.
* [Link ke Dataset Kaggle](https://www.kaggle.com/datasets/beridzeg45/guardian-environment-related-news/data)

---

### **Teknologi yang Digunakan**
* **Model AI:** IBM Granite 3.3-8B-Instruct (diakses melalui Replicate API)
* **Lingkungan Pengembangan:** Google Colab
* **Pustaka Python:** `langchain_community`, `replicate`, `pandas`, `matplotlib`, `seaborn`

---

### **Bagaimana Proyek Ini Bekerja**
1.  **Akuisisi Data:** Mengunduh dan memuat 10 artikel berita lingkungan dari dataset The Guardian.
2.  **Inisialisasi Model AI:** Mengatur koneksi ke model IBM Granite melalui Replicate API dengan parameter yang telah disesuaikan.
3.  **Klasifikasi Artikel:** Model AI mengidentifikasi kategori isu lingkungan untuk setiap artikel (misalnya, 'Perubahan Iklim', 'Polusi Air').
4.  **Peringkasan Artikel:** Model AI membuat ringkasan singkat dari setiap artikel, menangkap poin-poin utamanya.
5.  **Analisis & Visualisasi:** Hasil klasifikasi dianalisis untuk melihat distribusi topik, kemudian divisualisasikan menggunakan grafik untuk insight cepat.

---

### **Insight & Temuan Utama (Contoh)**
Dari 10 artikel yang dianalisis, kami mendapatkan gambaran awal mengenai distribusi topik isu lingkungan yang paling sering diberitakan. [**Sebutkan 1-2 insight singkat dari visualisasi Anda di sini, misalnya: "Terlihat bahwa isu 'Perubahan Iklim' merupakan topik yang dominan dalam berita yang dianalisis."**]

---

### **Rekomendasi & Penerapan di Dunia Nyata**
Sistem klasifikasi dan peringkasan otomatis ini memiliki potensi besar untuk:
* **Pemantauan Berita Otomatis:** Membantu tim ESG/HSE memonitor isu lingkungan terbaru secara efisien.
* **Identifikasi Risiko & Peluang:** Cepat mengidentifikasi tren dan potensi risiko/peluang dari volume data teks yang besar.
* **Dukungan Pelaporan:** Mempercepat penyusunan laporan keberlanjutan atau komunikasi terkait isu lingkungan.

---

### **Struktur Repositori**
* `IBM-Granite-Environment-News-Analysis.ipynb`: Notebook Google Colab utama yang berisi seluruh kode, analisis, dan laporan proyek.
* `README.md`: File ini, berisi gambaran umum proyek.
* `archive.zip`: File dataset asli yang diunggah.

---

### **Cara Menjalankan Proyek**
1.  Buka file `IBM-Granite-Environment-News-Analysis.ipynb` di Google Colab.
2.  Pastikan Anda telah mengunggah `archive.zip` ke lingkungan Colab Anda.
3.  Setel `REPLICATE_API_TOKEN` Anda di Google Colab Secrets.
4.  Jalankan semua sel dari atas ke bawah.

---

### **Kontributor**
* **Hendy Suka Muliawan** - [LinkedIn](https://www.linkedin.com/in/hendy-suka-muliawan)

---
