# 📘 PRAKTIKUM 4 – LIST  
### Bahasa Pemograman

---

</div>

## 📌 LATIHAN
### 🎯 Hasil Akhir
<img width="1651" height="372" alt="hasil latihan" src="https://github.com/user-attachments/assets/c6cd00bb-bf36-4922-8499-44c994536506" />

## 📘 TUGAS PRAKTIKUM  
Program sederhana untuk menambahkan data ke dalam sebuah list.

---

## 🧩 Flowchart Program
![flowchart](https://github.com/user-attachments/assets/149da486-b0b4-4036-a065-c43cee31ce8b)
## Penjelasan Flowchart

Program dimulai dengan membuat sebuah list kosong untuk menyimpan data.
Setelah itu, program meminta pengguna untuk memasukkan satu data.
Data yang dimasukkan kemudian disimpan ke dalam list.

Setelah menyimpan data, program menanyakan kepada pengguna apakah ingin menambahkan data lagi.
Jika pengguna menjawab “y”, maka program kembali meminta input data baru dan menyimpannya ke list.
Proses ini akan terus berulang selama pengguna menjawab “y”.

Jika pengguna menjawab “t”, program berhenti meminta input dan langsung menampilkan seluruh data yang sudah terkumpul di dalam list.
Setelah data ditampilkan, program menghitung nilai akhir berdasarkan tiga komponen:

- nilai tugas (30%),
- nilai UTS (35%),
- nilai UAS (35%).

Setelah perhitungan selesai, program menampilkan hasil akhir dan kemudian proses berakhir.

---
## 💻 Penjelasan Code
- ```data_mahasiswa = []``` List utama diinisialisasi untuk menampung semua data.
- ```while True:```	Memulai perulangan tak terbatas yang akan meminta input data mahasiswa baru.
- ```nilai_tugas = int(input(...))```	Meminta input nilai dan menyimpannya sebagai bilangan bulat (int).
- ```nilai_akhir = (...)```	Menghitung Nilai Akhir menggunakan rumus rata-rata tertimbang dan menyimpannya.
- ```data_mahasiswa.append([...])```	Menambahkan data mahasiswa (berupa List lain) ke List utama (data_mahasiswa).
- ```if tambah_lagi == 't': break``` 	Menghentikan perulangan jika pengguna memasukkan 't'.
- ```for mhs in data_mahasiswa:```	Memulai perulangan untuk mencetak setiap data yang sudah tersimpan.
- ```{mhs[0]:<15}```	Mencetak nilai dari List (mhs[0], yaitu Nama) dan mengaturnya rata kiri (<) dengan lebar 15 karakter (15) agar tabel lurus.

Program ini punya resep khusus untuk menentukan Nilai Akhir:
1. Nilai Tugas dianggap paling ringan, hanya menyumbang 30% (atau 0.30) dari total nilai.
2. Nilai UTS (Ujian Tengah Semester) dianggap lebih penting, menyumbang 35% (atau 0.35).
3. Nilai UAS (Ujian Akhir Semester) juga menyumbang 35% (atau 0.35).

Proses Perhitungannya di KodeDi dalam kode, yang terjadi adalah: 
1. Program mengambil nilai Tugas, UTS, dan UAS yang Anda masukkan.
2. Setiap nilai dikalikan dengan bobotnya. Misalnya, jika Nilai Tugas Anda 70, maka kontribusinya adalah $70 \times 0.30 = 21$.
3. Ketiga hasil perkalian itu dijumlahkan.
4. Hasil penjumlahan tersebut adalah Nilai Akhir mentah (misalnya, 71.75).
5. Terakhir, program menggunakan perintah round(..., 2) untuk memastikan nilai tersebut dibulatkan rapi menjadi dua angka di belakang koma (misalnya, tetap 71.75), sebelum disimpan ke dalam daftar data.

Jadi, Hasil Akhir adalah hasil terpenting dari seluruh proses input, karena merupakan nilai yang ditaruh di kolom terakhir daftar nilai mahasiswa.

Saat program mencetak tabel, ia menggunakan kode format khusus: {mhs[5]:<7.2f}.
- mhs[5] adalah cara program mengambil Nilai Akhir dari daftar data

- <7.2f adalah aturannya:
    - <7 memastikan ada ruang 7 karakter di layar (lebar kolom).
    - .2f adalah perintah untuk memastikan nilai ini selalu terlihat dengan dua angka desimal (seperti 71.75 atau 80.00).
---
## 🖥️ Hasil Running Program
<img width="1851" height="825" alt="hasil tugas praktikum" src="https://github.com/user-attachments/assets/d0d3113e-69b9-41a9-add8-a00357f782a9" />


<div align="center">
  
### 🎉 *Selesai — Terima kasih!*

</div>
