[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7901054&assignment_repo_type=AssignmentRepo)
# Live Code 1

## Instruction

Live Code ini dikerjakan dalam format ***notebook*** isi *notebook* harus mengikuti *outline* di bawah ini:
1. Perkenalan\
   Bab pengenalan harus diisi dengan identitas
2. **Judul/Penanda Soal**\
    Sediakan *Cell* Markdown sebelum cell import pustaka yang berisi nomor soal dan judul problem yang dikerjakan di tiap soalnya. Tiap soal mengikuti format nomor 2-6.
3. *Import* pustaka yang dibutuhkan\
   *Cell* pertama pada *notebook* **harus berisi dan hanya berisi** semua *library* yang digunakan dalam *project*.
4. *Data Loading*\
   Bagian ini berisi proses *data loading* yang kemudian dilanjutkan dengan *explorasi data* secara sederhana.
5. *Answer*\
   Bagian ini berisi proses dalam menjawab soal.
6. Hasil\
   Pada bab terakhir ini berisi jawaban pertanyaan soal.

---

## Problems

Kamu ada seorang data scientist di salah satu penyedia jasa makananan diet & healthy catering. Tim Perencanaan meminta kamu untuk mengecek kebutuhan energi dasar (BMR) harian dari customer. Informasi ini selanjutnya akan digunakan sebagai pertimbangan dalam penyusunan menu diet.

Kamu dapat menghitung kebutuhan energi dasar (BMR) harian dengan rumus berikut:
- BMR Laki-laki

<p align="center"><img src="https://latex.codecogs.com/svg.image?BMR&space;=&space;66&space;&plus;&space;(13.7&space;*&space;BB)&space;&plus;&space;(5&space;*&space;TB)&space;-&space;(6.8&space;*&space;U)" title="bmr_male" /></p>

- BMR Perempuan

<p align="center"><img src="https://latex.codecogs.com/svg.image?BMR&space;=&space;655&space;&plus;&space;(9.6&space;*&space;BB)&space;&plus;&space;(1.8&space;*&space;TB)&space;-&space;(4.7&space;*&space;U)" title="bmr_female" class="center" /></p>

- BB adalah Berat Badan dalam satuan Kilogram
- TB adalah Tinggi Badan dalam satuan sentimeter
- U adalah Usia dalam satuan tahun

a. Buatlah dua fungsi eksplisit masing-masing memuat perhitungan BMR laki-laki dan BMR Perempuan yang nantinya akan digunakan untuk perhitungan

b. Buat kolom baru dengan nama kolom **BMR** berisikan hasil perhitungan kebutuhan energi dasar (BMR) harian sesuai dengan jenis kelamin masing-masing pelanggan. (**Hint:** Gunakan for loop dan if statement untuk mengerjakan perintah nomor b, kamu bisa menggunakan list untuk menyimpan perhitungan sementara, setelahnya dapat dimasukkan ke kolom **BMR**).

c. Hitunglah rata-rata berat badan untuk Jenis kelamin laki-laki dengan umur lebih dari sama dengan 24 tahun hingga kurang dari sama dengan 35 tahun.


## Dataset
Dataset dapat diakses pada link berikut: https://raw.githubusercontent.com/rafifaditio/Dataset/main/BMR.csv

**Keterangan kolom:**
- Age: Usia
- Gender: Jenis Kelamin
- Height (cm): Tinggi Badan
- Weight (kg): Berat badan
- Index: Pengelompokkan berdasarkan BMI

---

## Assignment Rubrics

### Code Review

|Criteria|Meet Expectations|Points|
|--- |--- |--- |
|Data Loading|Mampu memuat data dengan Pandas| 2 pts |
|Looping Implementation|Mampu menerapkan looping for dalam suatu kasus| 10 pts |
|Conditional If Implementation|Mampu menerapkan konsep conditional if dalam suatu kasus| 10 pts |
|Function Implementation|Mampu menerapkan function pada sebuah kasus| 10 pts |
|Pandas Query Implementation|Mampu mengimplementasikan pandas query dalam pengolahan data| 10 pts |

### Readability

|Criteria|Meet Expectations|Points|
|--- |--- |--- |
|Tertata Dengan Baik|Semua Cell Di Notebook Terdokumentasi Dengan Baik Dengan Markdown Pada Tiap Cell Untuk Penjelasan Kode.| 8 pts |


---

```{admonition} Total Points
**50**
```
