# Deteksi dan Penghitungan Kerusakan Jalan Menggunakan YOLOv8
---------
Proyek ini membangun model *object detection* menggunakan YOLOv8 untuk mendeteksi dan menghitung jumlah kerusakan jalan (*potholes*). Model ini dilatih menggunakan dataset khusus kerusakan jalan, dan diuji menggunakan data video nyata untuk mengevaluasi performa di situasi lapangan.

## 📌 Tujuan Proyek
- Mengimplementasikan model YOLOv8 untuk mendeteksi kerusakan jalan secara otomatis.
- Menghitung jumlah kerusakan jalan dalam sebuah video atau gambar.
- Menguji kemampuan model pada data video asli (*real-world testing*).

## 🧠 Teknologi dan Framework
- Python 3.10+
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV
- NumPy

## 🗂️ Struktur Dataset

### Dataset untuk Training dan Validation
Dataset ini digunakan untuk melatih dan memvalidasi model deteksi kerusakan jalan:

🔗 [Download Dataset Train & Validation](https://www.dropbox.com/s/qvglw8pqo16769f/pothole_dataset_v8.zip?dl=1)

### Dataset untuk Pengujian (Testing)
Dataset ini berupa video nyata jalanan untuk menguji performa model terhadap kondisi sesungguhnya:

🔗 [Download Video Uji dan Hasil Deteksi](https://drive.google.com/drive/folders/1uwUJXK6_N83O_g8tXIsdUdZYIVd-RNZ4?usp=sharing)

## 🚀 Cara Menjalankan Proyek
---------
Proyek ini bertujuan untuk mendeteksi lubang di jalan raya dan menghitung jumlah lubang secara otomatis pada setiap gambar.
Model yang digunakan adalah YOLOv8 (You Only Look Once versi 8) untuk deteksi objek.

JALANKAN :
1. Upload file notebook (*.ipynb*) di Google Colab.
2. Jalankan semua cell berurutan
