## Implementasi Object Detection by Segmentation menggunakan Python tanpa library eksternal.
implementasi murni algoritma deteksi objek dari awal (from scratch) menggunakan bahasa Python, tanpa bergantung pada library eksternal seperti OpenCV atau TensorFlow. Metode yang digunakan adalah Background Subtraction, teknik untuk melakukan segmentasi dan mendeteksi objek bergerak pada latar belakang yang statis.

## Requirements
Python: Versi 3.x (direkomendasikan 3.9 atau 3.11 untuk kompatibilitas terbaik).

Format Dataset:

  - Gambar harus dalam format PPM (P3 - ASCII). Jika dataset Anda dalam format lain (JPG, PNG), Anda harus mengonversinya terlebih dahulu.

  - File anotasi ground truth harus dalam format XML PASCAL VOC (seperti yang dihasilkan oleh alat anotasi LabelImg atau CVAT).
