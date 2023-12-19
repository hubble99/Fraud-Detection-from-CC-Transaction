# Fraud Detection

Proyek Fraud Detection ini bertujuan untuk mendeteksi aktivitas penipuan dalam transaksi keuangan menggunakan beberapa model machine learning, yaitu Logistic Regression, Decision Tree, dan Random Forest. Dataset yang digunakan adalah dataset transaksi.

## Latar Belakang

Peningkatan aktivitas penipuan dalam transaksi keuangan menuntut adanya solusi yang efektif untuk mendeteksinya secara otomatis. Proyek ini mencoba menggunakan teknik machine learning untuk mengidentifikasi pola-pola penipuan dalam data transaksi keuangan.

## Model Machine Learning

1. **Logistic Regression:**
   - Akurasi: 0.630322
   - Recall: 0.596840
   - Presisi: 0.027761
   - F1-Score: 0.053054
   - AUC Score: 0.656533

2. **Random Forest:**
   - Akurasi: 0.673939
   - Recall: 0.698420
   - Presisi: 0.036397
   - F1-Score: 0.069189
   - AUC Score: 0.747141

3. **Decision Tree:**
   - Akurasi: 0.634066
   - Recall: 0.673138
   - Presisi: 0.031402
   - F1-Score: 0.060005
   - AUC Score: 0.703014

## Preprocessing Data

Proses preprocessing data melibatkan langkah-langkah sebagai berikut:
- Handling missing value
- Handling outlier
- Encoding kategorikal
- Seleksi model berdasarkan korelasi
- Undersampling untuk menangani kasus imbalanced data

## Hyperparameter Tuning

Hyperparameter tuning telah dilakukan untuk meningkatkan performa model. Hasil evaluasi diperoleh setelah penyetelan hyperparameter.
