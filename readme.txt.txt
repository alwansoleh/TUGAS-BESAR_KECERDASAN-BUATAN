SISTEM FUZZY PENENTUAN KELAYAKAN KOST

Kelompok:Harimau
Anggota Kelompok: 
-Nur Tsalits Alwan Mubarok | 103132400039
-Andi Muhammad Abid Jaya | 103132400014

Deskripsi:
Program ini merupakan implementasi Sistem Fuzzy Mamdani
untuk menentukan tingkat kelayakan kost mahasiswa berdasarkan:
1. Harga
2. Jarak ke kampus
3. Fasilitas

Proses yang dilakukan:
1. Membaca data kost dari file CSV
2. Fuzzifikasi data input
3. Inferensi menggunakan aturan fuzzy
4. Defuzzifikasi menggunakan metode centroid
5. Menyimpan hasil perankingan ke file CSV

Struktur File:
- main.py
- DATASET.csv
- README.txt

Format DATASET.csv:
id_kost,harga,jarak_kampus,fasilitas

Cara Menjalankan Program:
1. Pastikan Python sudah terinstall
2. Letakkan file DATASET.csv di folder yang sama
3. Jalankan perintah:
   python main.py
4. Hasil ranking akan tersimpan di DATASET_ranked.csv

Catatan:
Program dibuat tanpa menggunakan library fuzzy
sesuai ketentuan tugas Mata Kuliah Kecerdasan Buatan.
