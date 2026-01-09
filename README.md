Siap — ini versi **singkat dan tepat** sesuai arah proyek kamu (fokus ke *class weighting*, bukan SMOTE) 👇

---

## Project Overview

Proyek ini bertujuan membangun **model klasifikasi** untuk memprediksi apakah hujan akan terjadi keesokan harinya (*RainTomorrow*) menggunakan dataset cuaca harian dari **Australian Bureau of Meteorology (BOM)**. Dataset mencakup lebih dari sepuluh tahun observasi dari berbagai lokasi di Australia dengan fitur utama seperti suhu, kelembapan, kecepatan angin, dan tekanan udara.

Tantangan utama dalam proyek ini adalah **tingginya proporsi missing values** pada beberapa variabel penting serta **ketidakseimbangan kelas** antara hari hujan dan tidak hujan. Untuk itu, kami menerapkan **strategi imputasi berbasis pola waktu dan lokasi** serta menangani imbalance dengan pendekatan **class weighting**, sehingga model tetap adil tanpa menambah data sintetis.

Beberapa algoritma machine learning—termasuk **Logistic Regression, Random Forest, dan XGBoost**—dievaluasi menggunakan metrik seperti **F1-Score dan ROC-AUC** untuk memastikan performa yang stabil dan relevan dalam konteks prediksi cuaca.
