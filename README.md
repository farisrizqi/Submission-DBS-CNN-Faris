# Klasifikasi Gambar Menggunakan Convolutional Neural Network (CNN)

Proyek ini bertujuan untuk membangun model klasifikasi gambar menggunakan **Convolutional Neural Network (CNN)** dengan dataset gambar yang telah dibagi menjadi data pelatihan (training), pengujian (testing), dan validasi. Model ini diharapkan dapat mengenali dan mengklasifikasikan gambar dengan akurasi yang baik.

## Deskripsi Proyek

### Dataset
Dataset yang digunakan dalam proyek ini berisi gambar-gambar yang telah dipilih dan dibagi menjadi tiga subset:
- **Train Set**: Data yang digunakan untuk melatih model.
- **Test Set**: Data yang digunakan untuk menguji performa model.
- **Validation Set**: Data yang digunakan untuk validasi model.

### Arsitektur Model
Model yang dibangun menggunakan **Convolutional Neural Network (CNN)** dengan beberapa layer Conv2D dan pooling. 

### Proses Penyimpanan Model
Model yang dilatih disimpan dalam beberapa format, termasuk:
- **SavedModel**: Format standar TensorFlow yang disimpan dalam folder `saved_model/`.
- **TensorFlow Lite (TF-Lite)**: Model yang dioptimalkan untuk perangkat mobile, disimpan di folder `tflite/`.
- **TensorFlow.js (TFJS)**: Model untuk digunakan dalam aplikasi berbasis JavaScript, disimpan di folder `tfjs_model/`.


### Cara Menjalankan Proyek

1. **Clone Repositori**

2. **Instalasi Dependensi**
Pastikan semua dependensi sudah terinstall dengan menjalankan perintah berikut:
`pip install -r requrements.txt`

3. **Menjalankan Notebook**
Buka notebook `notebook.ipynb` untuk melihat detail implementasi dan eksperimen yang dilakukan.

4. **Penyimpanan Model**
Model disimpan dalam format `SavedModel`, `TF-Lite`, dan `TFJS`. Model dapat digunakan di platform lain seperti aplikasi mobile dan berbasis JavaScript.

## Teknologi yang Digunakan
- **TensorFlow**: Untuk membangun dan melatih model CNN.
- **Keras**: Untuk implementasi model dan layer.
- **Matplotlib/Seaborn**: Untuk visualisasi akurasi dan loss selama pelatihan.
- **Python**: Bahasa pemrograman yang digunakan untuk pengembangan model.
