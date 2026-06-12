# Eksperimen_SML_Nama-siswa

Repository eksperimen preprocessing dataset Iris untuk submission Membangun Sistem Machine Learning (SMSML).

## Struktur Folder

```
Eksperimen_SML_Nama-siswa
├── iris_raw/
│   └── iris_raw.csv               ← Dataset mentah
├── preprocessing/
│   └── Eksperimen_Nama-siswa.ipynb ← Notebook eksperimen
│   └── iris_preprocessing/        ← Dataset hasil preprocessing
│       └── iris_preprocessing.csv
```

## Langkah Eksperimen

1. **Data Loading** — memuat dataset Iris (150 baris, 5 kolom)
2. **EDA** — analisis distribusi kelas, missing values, statistik deskriptif
3. **Preprocessing** — encoding label, StandardScaler normalization, train-test split 80/20
4. **Simpan** — dataset preprocessed disimpan ke `iris_preprocessing/`

## Cara Menjalankan

```bash
pip install pandas scikit-learn numpy jupyter
jupyter notebook preprocessing/Eksperimen_Nama-siswa.ipynb
```
