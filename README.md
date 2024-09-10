# AttendanceFaceRecognition

Repository ini berisi tugas mata kuliah Computer Vision yang fokus pada implementasi pengenalan wajah menggunakan OpenCV dan library face_recognition dalam Python.

## Deskripsi Proyek
#### 1. Pengenalan Wajah antara Dua Gambar
Script Basics.py digunakan untuk melakukan deteksi dan perbandingan wajah antara dua gambar:
- Gambar Referensi: Elon Musk.jpg
- Gambar Uji: Elon Test.jpg

Langkah-langkah yang dilakukan:
- Memuat dan mengonversi gambar ke format RGB.
- Mendeteksi lokasi wajah dan melakukan encoding pada wajah di kedua gambar.
- Membandingkan wajah dari kedua gambar dan menghitung jarak wajah (face distance).
- Menampilkan hasil perbandingan dan jarak wajah pada gambar uji.
#### 2. Sistem Absensi dengan Pengenalan Wajah Real-time
Script AttendanceProject.py digunakan untuk pengaplikasian pengenalan wajah real-time yang dapat digunakan sebagai sistem absensi:
- Menggunakan webcam untuk menangkap video secara real-time.
- Mendeteksi dan mengenali wajah berdasarkan dataset gambar yang ada di folder ImagesAttendance.
- Mencatat kehadiran dengan menulis nama dan waktu ke dalam file Attendance.csv.

Fitur yang diimplementasikan:
- Deteksi Wajah: Menggunakan face_recognition untuk mendeteksi lokasi wajah dalam frame video.
- Encoding Wajah: Membuat encoding wajah dari gambar referensi untuk digunakan dalam proses pengenalan.
- Perbandingan Wajah: Membandingkan wajah yang terdeteksi dengan dataset wajah yang dikenal.
- Pencatatan Kehadiran: Menyimpan nama dan timestamp saat wajah dikenali ke dalam file CSV.
