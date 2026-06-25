# Bank Marketing Classification using Random Forest

Implementasi algoritma **Random Forest** untuk melakukan klasifikasi pada **Bank Marketing Dataset** menggunakan **Scikit-Learn**.

## 📌 Deskripsi

Project ini merupakan implementasi praktikum Machine Learning yang membahas proses klasifikasi menggunakan algoritma **Random Forest**. Notebook mencakup seluruh tahapan mulai dari Data Understanding hingga evaluasi model.

Tahapan yang dilakukan meliputi:

- Data Understanding
- Feature Selection
- Data Preprocessing
- Train-Test Split
- Pipeline
- Random Forest Classification
- Model Evaluation
- Out-of-Bag (OOB) Evaluation
- Hyperparameter Analysis
- Feature Importance
- Save & Load Model
- Prediction on New Data

---

## 📂 Dataset

Dataset yang digunakan adalah **Bank Marketing Dataset**.

Target klasifikasi:

- **yes** → Nasabah berlangganan deposito.
- **no** → Nasabah tidak berlangganan deposito.

---

## 🛠️ Library

- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Joblib

---

## 📈 Algoritma

Model yang digunakan:

- Random Forest Classifier

Tahapan preprocessing:

- SimpleImputer
- OneHotEncoder
- ColumnTransformer
- Pipeline

---

## 📊 Evaluasi Model

Model dievaluasi menggunakan:

- Accuracy
- Confusion Matrix
- Classification Report
- Out-of-Bag (OOB) Score

Selain itu dilakukan analisis pengaruh hyperparameter:

- `n_estimators`
- `max_depth`

---

## 📁 Struktur Project

```
bank-marketing-random-forest/
│
├── bank.csv
├── RandomForest_BankMarketing.ipynb
├── random_forest_bank.pkl
└── README.md
```

---

## 👤 Author

**Gumelar Akhirul Ramadhan**  
NIM: 0920240027  
Program Studi Teknologi Rekayasa Perangkat Lunak  
Politeknik Astra
