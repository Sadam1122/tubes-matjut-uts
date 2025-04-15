# Tugas Besar Matematika Teknik Lanjut
**Program S2 Teknik Elektro** – Dosen: MKT

---

## Anggota Kelompok
- SADAM AL RASYID
- MUHAMMAD ABYAN HARITS
- RR MEIDITA THIFAL LELYTA
- KARINA NURLITA SALSABILA

---

## Deskripsi Proyek
Implementasi regresi linier dengan regularisasi L1 (Lasso) dan L2 (Ridge) menggunakan Gradient Descent (GD) dan Stochastic Gradient Descent (SGD). Proyek ini mencakup:

- Studi literatur metode GD & SGD
- Preprocessing data (standardisasi & encoding)
- Implementasi GD & SGD manual dari nol
- Eksperimen hyperparameter: learning rate, epochs, batch size, λ
- Evaluasi: MSE & R² untuk setiap kombinasi
- Visualisasi konvergensi loss dan perbandingan metode
- Analisis dampak hyperparameter dan tipe regularisasi

---

---

## Data Source
- **Medical Cost Personal Dataset** dari Kaggle
- **Link**: https://www.kaggle.com/datasets/mirichoi0218/insurance?resource=download

---

## Prosedur Pengerjaan
1. Tugas dikerjakan secara berkelompok (3–4 mahasiswa).
2. Deadline pengumpulan: 15 April 2025; presentasi sesuai jadwal.
3. Platform: Python (Google Colab).
4. Ketelitian: Gunakan 3 digit di belakang koma.
5. Laporan: Word, memuat deskripsi metode, solusi eksak (jika ada), hasil eksekusi, analisis, dan plot konvergensi loss. Sertakan listing program.
6. Pengumpulan:
   - Source code (`main.ipynb`) siap dijalankan.
   - Laporan Word.
   - Kompres materi ke ZIP/RAR dengan nama `S2TE3901_KelompokXX`.

---

## Struktur Repository
```
├── README.md          # Dokumentasi ini
├── main.ipynb         # Notebook utama implementasi
├── Gambar.zip         # Kumpulan Gambar hasil runing
```

---

## Cara Menjalankan
1. **Clone repository**:
   ```bash
   git clone https://github.com/username/S2TE3901_Kelompok01.git
   cd S2TE3901_Kelompok01
   ```
2. **Buka `main.ipynb`** di Google Colab atau Jupyter Notebook.
3. **Jalankan semua sel** secara berurutan.

---

## Ringkasan Metode
1. **Gradient Descent (GD)** dan **Stochastic Gradient Descent (SGD)** untuk optimisasi.
2. **Regularisasi L1 (Lasso)** untuk sparsity; **L2 (Ridge)** untuk shrinkage.
3. **Hyperparameter Tuning**: Eksperimen nilai α, epochs, batch size, λ.
4. **Evaluasi**: MSE, R², waktu training, dan analisis konvergensi.

---

## Hasil & Visualisasi
- Tabel MSE & R² untuk setiap kombinasi hyperparameter.
- Plot konvergensi loss per metode (GD vs SGD).
- Perbandingan efek regularisasi pada koefisien.
- Scatter plot aktual vs prediksi dan residual plot.

---

## Referensi
1. Lasso Regression from Scratch – Medium
2. A Simple Practical Guide to Linear Regression – Kaggle Notebook
3. Paper dan jurnal terkini tentang GD & SGD (3–5 tahun terakhir)

---

*README ini disusun untuk Tugas Besar Matematika Teknik Lanjut (S2 Teknik Elektro).*

