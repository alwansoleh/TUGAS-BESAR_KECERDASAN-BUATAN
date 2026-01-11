SISTEM FUZZY PENENTUAN KELAYAKAN KOST

Deskripsi:
Program ini merupakan implementasi Sistem Fuzzy Mamdani
untuk menentukan tingkat kelayakan kost mahasiswa berdasarkan:
1. Harga
2. Jarak ke kampus
3. Fasilitas

Proses yang dilakukan:
1. Membaca data dari file CSV
2. Fuzzifikasi
3. Inferensi menggunakan aturan fuzzy
4. Defuzzifikasi menggunakan metode centroid
5. Menyimpan hasil ke file CSV

Struktur File:
- main.py
- DATASET.csv
- DATASET_ranked.csv
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

PERAN ANGGOTA KELOMPOK
 
Anggota 1
Nama : Nur Tsalits Alwan Mubarok
NIM  : 103132400039

Peran:
- Merancang konsep Sistem Fuzzy Mamdani untuk penentuan kelayakan kost
- Menentukan atribut input dan output sistem fuzzy
- Mendesain fungsi keanggotaan (harga, jarak ke kampus, dan fasilitas)
- Menyusun aturan inferensi fuzzy
- Melakukan analisis hasil dan evaluasi sistem


Anggota 2
Nama : Andi Muhammad Abid Jaya
NIM  : 103132400014

Peran:
- Mengimplementasikan sistem fuzzy ke dalam program Python
- Membuat fungsi fuzzifikasi, inferensi, dan defuzzifikasi
- Mengelola pembacaan dataset dan penyimpanan hasil ke file CSV
- Melakukan pengujian program dan perankingan kost terbaik
- Menyusun dokumentasi program dan README.txt

