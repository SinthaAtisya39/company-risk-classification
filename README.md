# Corporate ESG & Financial Risk Predictor 🚀

Proyek ini berisi alur kerja komprehensif untuk AI Fundamentals Coding Challenge, yang dirancang untuk menganalisis metrik perusahaan global. 

Proyek ini bertujuan untuk menganalisis hubungan antara metrik *Environmental, Social, and Governance* (ESG) dengan stabilitas finansial perusahaan (Altman Z-Score), serta memprediksi risiko kebangkrutan menggunakan *Machine Learning*. 

Proyek ini dikembangkan sebagai bagian dari **AI Fundamentals Coding Challenge - Perempuan Inovasi 2026**.

## 📊 Dataset
Dataset yang digunakan berisi 7.610 perusahaan dan berasal dari Kaggle: [Business Companies Dataset](https://www.kaggle.com/datasets/tonylm00/business-companies-dataset).

## Struktur Challenge

Pengerjaan proyek ini terbagi ke dalam lima modul utama:
*Challenge 1* - Data Exploration: Memuat dataset, mengevaluasi kualitas data (missing values dan duplikasi), serta membangun visualisasi data menggunakan Pandas, Matplotlib, dan Seaborn.   
*Challenge 2* - Machine Learning: Merumuskan rekayasa variabel target dan melatih model klasifikasi (Scikit-learn) untuk mendeteksi risiko kebangkrutan perusahaan.   
*Challenge 3* - Prediction: Menguji keandalan model final untuk melakukan prediksi pada data uji.   
*Challenge 4* - Integrasi Gemini API: Memanfaatkan model bahasa besar (LLM) untuk memperkaya analisis dan otomatisasi ekstraksi wawasan.   
*Challenge 5* - Responsible AI Reflection: Mengevaluasi implikasi etis, keadilan model, dan transparansi dari hasil Machine Learning. 

## 🛠️ Fitur & Model Machine Learning
Pendekatan yang digunakan adalah *Binary Classification* untuk memprediksi target variabel `is_safe`, yaitu apakah suatu perusahaan tergolong "Aman" (1) atau "Berisiko" (0). Fitur utama yang dianalisis meliputi:
- Skor ESG (`esg`)
- Jumlah Karyawan (`employees`)

Beberapa algoritma klasifikasi yang dievaluasi dalam proyek ini meliputi:
- Logistic Regression (Baseline)
- Random Forest
- Decision Tree
- K-Nearest Neighbors (KNN)
- Gradient Boosting & HistGradientBoosting
- XGBoost (Advanced)
- Support Vector Machine (SVM)
- Naive Bayes

## 🚀 Cara Menjalankan
1. *Clone repository* ini ke komputer lokal.
2. Pastikan *library* Python seperti `pandas`, `scikit-learn`, `matplotlib`, dan `seaborn` sudah terinstal.
3. Buka dan jalankan sel di dalam file Jupyter Notebook yang tersedia untuk melihat alur eksplorasi data hingga prediksi.