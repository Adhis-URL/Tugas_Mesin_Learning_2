# Tugas Mesin Learning 2
## CNN dan Transfer Learning

### Identitas Mahasiswa
- **Nama:** Adhi Sukmo Manunggal
- **NIM:** 452024611004
- **Mata Kuliah:** Machine Learning 2


## Deskripsi Tugas

Repository ini berisi implementasi:

1. Convolutional Neural Network (CNN) untuk klasifikasi citra menggunakan dataset CIFAR-10.
2. Transfer Learning menggunakan model MobileNetV2 yang telah dilatih sebelumnya (pre-trained model).
3. Evaluasi performa model menggunakan metrik Accuracy dan Loss.
4. Visualisasi hasil pelatihan berupa grafik Accuracy dan Loss.


## Dataset

### CIFAR-10
Dataset CIFAR-10 terdiri dari:
- 50.000 data training
- 10.000 data testing
- 10 kelas objek

Contoh kelas:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Arsitektur CNN

Model CNN yang digunakan terdiri dari:

- Conv2D (32 Filter)
- MaxPooling2D
- Conv2D (64 Filter)
- MaxPooling2D
- Flatten
- Dense (128 Neuron)
- Dense (10 Output Class)


## Transfer Learning

Transfer Learning menggunakan:

- MobileNetV2
- Pre-trained Weights: ImageNet
- GlobalAveragePooling2D
- Dense Layer
- Softmax Classification


## Hasil Pengujian

### CNN

- Training Accuracy ≈ 82%
- Validation Accuracy ≈ 70%
- Test Accuracy ≈ 69%

### Transfer Learning

- Accuracy ≈ 81%
- Loss ≈ 0.58


## Visualisasi

Repository ini juga menampilkan:

- Grafik Training Accuracy vs Validation Accuracy
- Grafik Training Loss vs Validation Loss


## Tools yang Digunakan

- Python
- TensorFlow
- NumPy
- Matplotlib
- Google Colab


## Cara Menjalankan

1. Buka file notebook `.ipynb` menggunakan Google Colab.
2. Jalankan seluruh cell secara berurutan.
3. Tunggu proses training selesai.
4. Lihat hasil evaluasi dan grafik performa model.


## Repository

Dibuat untuk memenuhi tugas Mata Kuliah Machine Learning 2.

**Adhi Sukmo Manunggal**  
**452024611004**
