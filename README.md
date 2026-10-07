
# Pembelajaran Mesin

Repositori dokumentasi praktikum, tugas, dan eksperimen mata kuliah **Pembelajaran Mesin** (`RTI235004`). Materi disusun mengikuti tahapan pengembangan machine learning, dari pemahaman data sampai deployment model.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)](https://opencv.org/)
[![Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)

## Tentang

Setiap notebook berisi langkah praktikum lengkap dengan output eksekusi, sehingga dapat dibaca langsung di GitHub maupun dijalankan ulang. Struktur folder mengikuti penomoran jobsheet (`JS02` sampai `JS06`).

## Praktikum

| Jobsheet | Topik | Notebook |
| --- | --- | --- |
| JS02 | Exploratory Data Analysis dan pra-pengolahan data | [JS02](JS02) |
| JS03 | Regresi dan evaluasi model | [JS03](JS03) |
| JS04 | Klasifikasi dan pemisahan data | [JS04](JS04) |
| JS05 | Klasifikasi kNN dan Naive Bayes | [JS05](JS05) |
| JS06 | Klasifikasi SVM (linier, non-linier, citra wajah, siang-malam) | [JS06](JS06) |

Tiap folder berisi notebook praktikum (`-01`, `-02`, ...) dan notebook tugas. Notebook JS06 sudah dilengkapi output hasil eksekusi.

## Materi

**Dasar**

- Pengenalan Artificial Intelligence dan Machine Learning
- Jenis-jenis pembelajaran mesin
- Etika dan tantangan penggunaan AI

**Persiapan dan Pengolahan Data**

- Exploratory Data Analysis
- Pra-pengolahan data
- Imputasi, encoding, normalisasi, dan standardisasi
- Ekstraksi dan seleksi fitur

**Supervised Learning**

- Regresi
- Klasifikasi menggunakan kNN, Naive Bayes, dan SVM

**Unsupervised Learning**

- Klasterisasi menggunakan K-Means, DBSCAN, dan HDBSCAN
- Approximate Nearest Neighbors dengan ANNOY, FAISS, dan HNSW

**Deep Learning**

- Artificial Neural Network
- Convolutional Neural Network

**Deployment**

- Machine learning pipeline dan deployment

## Dataset

| Dataset | Digunakan pada |
| --- | --- |
| Titanic Dataset | Pra-pengolahan data |
| Wisconsin Breast Cancer Dataset | Klasifikasi |
| Iris Dataset | Klasifikasi |
| Mall Customers Dataset | Klasterisasi |
| Credit Card Customer Dataset | Klasterisasi |
| SMS Spam Dataset | Naive Bayes |
| Churn Modelling Dataset | Klasifikasi |
| MNIST dan CIFAR Dataset | Deep learning |
| Cats versus Dogs Dataset | CNN |
| Dataset citra siang dan malam | SVM berbasis fitur citra |
| Dataset musik Spotify | Klasterisasi |

## Teknologi

**Bahasa dan Lingkungan**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)

**Analisis dan Visualisasi Data**

[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)](https://seaborn.pydata.org/)

**Machine Learning**

[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)](https://opencv.org/)
[![HDBSCAN](https://img.shields.io/badge/HDBSCAN-2C3E50?style=flat)](https://hdbscan.readthedocs.io/)
[![ANNOY](https://img.shields.io/badge/ANNOY-0078D7?style=flat)](https://github.com/spotify/annoy)
[![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)](https://github.com/facebookresearch/faiss)
[![HNSW](https://img.shields.io/badge/HNSW-8E44AD?style=flat)](https://github.com/nmslib/hnswlib)

**Deep Learning**

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)

**Deployment**

[![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/spaces)

## Struktur Repositori

```
pembelajaran-mesin/
├── JS02/   Exploratory Data Analysis dan pra-pengolahan data
├── JS03/   Regresi dan evaluasi model
├── JS04/   Klasifikasi dan pemisahan data
├── JS05/   Klasifikasi kNN dan Naive Bayes
├── JS06/   Klasifikasi SVM
└── README.md
```

## Tujuan

Repositori ini menjadi dokumentasi proses pembelajaran dan implementasi konsep machine learning melalui materi teori, praktikum, eksperimen, serta tugas.
Dua catatan sebelum aku tulis ke file:
1. Label topik per jobsheet (tabel Praktikum & Struktur) adalah hasil inferensi dari isi notebook. JS03 memakai LogisticRegression dan JS04 memakai LinearRegression, jadi penomorannya bisa tertukar. Mohon konfirmasi label yang benar.
2. Semua badge pakai shields.io dan butuh koneksi internet saat dirender di GitHub. Kalau tidak mau badge, bilang saja, aku ganti jadi teks biasa.
