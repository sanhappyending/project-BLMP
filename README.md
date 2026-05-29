# Project BLMP — Clustering & Classification Machine Learning

Proyek machine learning yang menggabungkan pendekatan **Unsupervised Learning** dan **Supervised Learning** untuk membangun sistem klasifikasi berbasis hasil clustering.

## 📌 Deskripsi Project

Project ini merupakan submission akhir pada pembelajaran Machine Learning yang berfokus pada implementasi:

* **Clustering (Unsupervised Learning)**
* **Classification (Supervised Learning)**

Dataset yang digunakan berasal dari modifikasi dataset:

> Bank Transaction Dataset for Fraud Detection

Pada tahap awal, dilakukan proses clustering untuk menghasilkan label atau kelas baru dari data yang belum memiliki label. Selanjutnya, label hasil clustering digunakan sebagai target pada proses klasifikasi untuk membangun model prediksi.

Project ini bertujuan untuk mengintegrasikan dua pendekatan machine learning dalam satu workflow yang terstruktur dan relevan terhadap studi kasus nyata.

---

## 🎯 Objectives

* Melakukan eksplorasi dan preprocessing data
* Mengimplementasikan clustering untuk menghasilkan label
* Menggabungkan hasil clustering dengan dataset utama
* Membangun model klasifikasi berbasis hasil clustering
* Mengevaluasi performa model machine learning

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Project Structure

```bash
project-BLMP/
│
├── clustering.ipynb
├── klasifikasi.ipynb
├── data_clustering.csv
├── data_clustering_inverse.csv
├── decision_tree_modul.h5
├── explore_RandomForestClassifier_classification.h5
├── model_clustering.h5
├── PCA_model_clustering.h5
└── tuning_classification.h5
```

---

## 📊 Workflow Project

### 1. Data Preparation

Melakukan preprocessing dataset seperti:

* cleaning data
* handling missing values
* encoding
* scaling

### 2. Clustering (Unsupervised Learning)

Menggunakan algoritma clustering untuk:

* mengelompokkan data
* menghasilkan label/kelas baru
* menemukan pola pada dataset

### 3. Classification (Supervised Learning)

Menggunakan label hasil clustering sebagai target klasifikasi untuk:

* melatih model machine learning
* memprediksi kelas data baru
* mengevaluasi performa model

---

## 📈 Models Used

### Clustering

* K-Means
* PCA

### Classification

* Decision Tree
* Random Forest Classifier

---

## ⚙️ Installation

Clone repository:

```bash
git clone https://github.com/sanhappyending/project-BLMP.git
```

Masuk ke folder project:

```bash
cd project-BLMP
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Project

Buka notebook menggunakan Jupyter Notebook atau VS Code:

```bash
jupyter notebook
```

Jalankan:

* `clustering.ipynb`
* `klasifikasi.ipynb`

---

## 📌 Notes

* Dataset yang digunakan merupakan versi modifikasi khusus untuk kebutuhan submission.
* Notebook mengikuti struktur template submission machine learning.
* Seluruh proses analisis dilakukan secara bertahap mulai dari clustering hingga classification.
