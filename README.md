# 📊 HR Analytics Dashboard (Employee Attrition Analysis)

## 📌 Deskripsi Proyek
Proyek ini berfokus pada analisis data Sumber Daya Manusia (HR) untuk mengidentifikasi pola, tren, dan faktor-faktor utama yang mendorong perputaran karyawan (*employee attrition*). Dengan menggunakan **Power BI**, data mentah diolah menjadi *dashboard* interaktif yang dapat membantu tim HR dan manajemen mengambil keputusan berbasis data (*data-driven decisions*) untuk meningkatkan retensi karyawan.

---

## 📊 Tampilan Dashboard
<img width="1159" height="653" alt="image" src="https://github.com/user-attachments/assets/95e9da58-2729-43e1-bec9-0a3a6011d96c" />

---

## 🛠️ Langkah-Langkah Pengerjaan (Data Pipeline)
1. **Data Cleaning & Transformation (Power Query):** 
   * Menghapus duplikasi data dan menangani nilai yang hilang (*missing values*).
   * Membuat pengelompokan baru (*conditional columns*) seperti kelompok umur (`Age Group`) dan rentang gaji (`Salary Slab`).
     
2. **Data Modeling:**
   * Membangun skema relasi antar tabel (jika menggunakan lebih dari satu tabel).
   * Membuat kolom kalkulasi (*Calculated Columns*) dan *Measures* menggunakan **DAX**.
     
3. **Data Visualization:**
   * Mendesain tata letak visual (*layout design*) dengan prinsip hirarki visual agar metrik penting mudah dibaca.

---

## 💡 Metrik Utama (Key Performance Indicators)
Berdasarkan data yang dianalisis pada dashboard:
* **Total Employees:** 1,417 Karyawan
* **Active Employees:** 1,186 Karyawan
* **Attrition Count:** 231 Karyawan telah keluar
* **Attrition Rate:** 16.30%
* **Average Age:** 36.94 Tahun
* **Average Experience:** 7.04 Tahun

---

## 🔍 Temuan & Analisis Utama (Key Insights)
* **Atrisi Berdasarkan Rentang Gaji:** Tingkat atrisi tertinggi secara masif terjadi pada karyawan dengan pendapatan rendah hingga menengah, khususnya pada rentang **6-10 LPA (399 total karyawan, 73 keluar)** dan **0-3 LPA (299 total karyawan, 61 keluar)**.
* **Faktor Usaha & Pengalaman:** Mayoritas karyawan yang keluar berada pada kelompok usia produktif **26-35 tahun** (588 karyawan), dengan masa kerja awal (*Total Experience* di bawah 5 tahun) menjadi titik paling rawan.
* **Distribusi Departemen:** Departemen **Operations** dan **Sales** menyumbang jumlah karyawan sekaligus volume atrisi terbesar dibandingkan departemen lainnya seperti IT atau Finance.

---

## 🚀 Rekomendasi Bisnis untuk Manajemen HR
1. **Evaluasi Struktur Kompensasi:** Melakukan *benchmarking* gaji pada rentang di bawah 10 LPA karena area ini memiliki risiko perputaran karyawan paling tinggi.
2. **Program Onboarding & Mentorship:** Mengingat tingginya atrisi pada karyawan muda (usia 26-35) dan mereka yang bermasa kerja pendek, program *mentorship* intensif di 1-2 tahun pertama sangat disarankan.
3. **Fokus pada Kepuasan Kerja Departemen Kritikal:** Melakukan survei internal berkala khusus untuk departemen *Operations* dan *Sales* guna memahami beban kerja atau tekanan spesifik di divisi tersebut.

---
