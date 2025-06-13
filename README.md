# 🌿 Model LeafCheck

**LeafCheck** adalah model deteksi penyakit pada daun jagung menggunakan CNN (Convolutional Neural Network) berbasis TensorFlow. Proyek ini bertujuan untuk membantu identifikasi penyakit daun jagung secara otomatis melalui gambar, dengan pendekatan machine learning.

## 🗂️ Dataset

Dataset yang digunakan berasal dari Kaggle:

🔗 [Corn Leaf Disease Dataset – by ndisan](https://www.kaggle.com/datasets/ndisan/corn-leaf-disease)

Dataset terdiri dari beberapa kategori daun jagung, termasuk:
- Bercak Daun
- Daun Sehat
- Hawar Daun
- Karat Daun

## 🧠 Model

Model dibangun menggunakan TensorFlow dan arsitektur CNN sederhana dengan beberapa lapisan konvolusi, max pooling, dan fully connected. Input gambar dire-size ke `(224, 224)` dengan 3 channel warna (RGB).

Output model berupa prediksi kelas dan confidence score.

## ⚙️ Arsitektur CNN

- `Rescaling` dan `Data Augmentation`
- `Conv2D` + `MaxPooling2D`
- `Flatten` dan `Dense`
- `Dropout`
- `Softmax` untuk klasifikasi

