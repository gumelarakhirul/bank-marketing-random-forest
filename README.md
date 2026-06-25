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

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Joblib

---

## 📈 Algoritma

Model yang digunakan:

- Random Forest Classifier

Preprocessing:

- SimpleImputer
- OneHotEncoder
- ColumnTransformer
- Pipeline

---

## 📊 Evaluasi Model

Evaluasi dilakukan menggunakan:

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
├── README.md
└── requirements.txt
```

---

## ▶️ Menjalankan Project

Clone repository:

```bash
git clone https://github.com/gumelarakhirul/bank-marketing-random-forest.git
```

Masuk ke folder project:

```bash
cd bank-marketing-random-forest
```

Install dependency:

```bash
pip install -r requirements.txt
```

Jalankan notebook:

```bash
jupyter notebook
```

---

## 👤 Author

**Gumelar Akhirul Ramadhan**

Politeknik Astra

TRPL
