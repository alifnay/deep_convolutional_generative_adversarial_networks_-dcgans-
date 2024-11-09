<h1 align="center">Creating Anime Characters using Deep Convolutional Generative Adversarial Networks (DCGANs) and Keras</h1>
<p align="center">Berisi tentang model pembuatan karakter anime yang dibuat menggunakan Deep Convolutional Generative Adversarial Networks (DCGANs) dan Keras.</p>
<div align="center">
  <img src="https://github.com/user-attachments/assets/8abe0666-c4c7-46a8-84a4-2bc48c8965ae">
</div>

<div align="center">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
    <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white">
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">
    <img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white">
    <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white">
    <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">

</div>

## Overview
Repository ini berisi implementasi dari Deep Convolutional Generative Adversarial Networks (DCGANs) menggunakan Python dan framework deep learning. DCGANs adalah arsitektur jaringan saraf generatif yang digunakan untuk menghasilkan gambar realistis dari data acak. DCGAN ini dibangun dengan kombinasi jaringan konvolusi (CNN) dan jaringan adversarial untuk melatih model sehingga mampu menghasilkan gambar berkualitas tinggi.

## Prerequisites

Untuk menjalankan proyek ini, digunakan beberapa library diantaranya:

- **pandas** 
- **numpy** 
- **sklearn**
- **seaborn**
- **matplotlib**
- **keras**
- **tensorflow**

## Struktur Notebook
Notebook ini terdiri dari beberapa bagian utama:
1. Inisialisasi Lingkungan dan Import Library - Mengimpor pustaka yang diperlukan dan mengatur konfigurasi dasar.
2. Persiapan Dataset - Memuat dataset dan melakukan pra-pemrosesan data untuk memastikan data sesuai untuk pelatihan DCGAN.
3. Arsitektur DCGAN - Membangun arsitektur generator dan discriminator menggunakan lapisan konvolusi.
4. Proses Pelatihan - Mengatur loop pelatihan dan memperlihatkan hasil pelatihan secara berkala.
5. Visualisasi Hasil - Menyimpan dan menampilkan gambar-gambar yang dihasilkan oleh generator setelah pelatihan selesai.

## Analisis
Dalam notebook yang telah dijalankan, terdapat beberapa point penting yaitu:

**1. Evaluasi Kualitas Gambar -**
Melalui visualisasi gambar yang dihasilkan selama pelatihan, dapat dievaluasi mengenai kualitas dan realistisnya gambar dari waktu ke waktu. Notebook ini memungkinkan pemantauan kualitas gambar secara bertahap, sehingga pengguna bisa memahami stabilitas dan performa DCGAN.

**2. Loss Generator dan Discriminator -**
DCGAN mengandalkan dua jaringan yang saling bersaing yaitu generator dan discriminator. Analisis tren loss dari kedua jaringan ini memberikan wawasan tentang konvergensi model dan apakah training berjalan dengan stabil. Idealnya, loss dari kedua jaringan harus mendekati keseimbangan tanpa ada satu jaringan yang terlalu mendominasi.

***3. Parameter Hyperparameter dan Pengaruhnya -**
Notebook ini memungkinkan eksperimen dengan berbagai hyperparameter seperti learning rate, ukuran batch, dan jumlah epoch. Analisis terhadap perubahan hyperparameter membantu pengguna memahami pengaruh masing-masing parameter terhadap kualitas hasil akhir, serta memberikan panduan dalam memilih pengaturan yang optimal untuk hasil terbaik.

## Getting Started

**1. Clone Repository**
```bash
git clone https://github.com/alifnay/deep_convolutional_generative_adversarial_networks_-dcgans-.git
```
