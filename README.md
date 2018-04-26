# Soal Ujian Purwadhika Back-End Dev (*Remedial*)

![Lintang_Purwadhika](https://static.wixstatic.com/media/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png/v1/fill/w_246,h_39,al_c,usm_0.66_1.00_0.01/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png)

**Materi Back End Web Dev dapat diakses di [klik sini!](https://github.com/LintangWisesa/Purwadhika-JC04-03_BackEndWeb)**

### **Soal 1 Remedial - MySQL Database**

Tuliskan langkah-langkah/urutan query MySQL untuk membuat sebuah database RDBMS (Relational Table) dengan spesifikasi sebagai berikut:
- Terdapat sebuah database dengan nama __"Plantae"__.
- Database __"Plantae"__ memiliki 2 buah tabel: __"Monocotyledon"__ dan __"Dicotyledon"__.
- Masukkan data-data berikut ke dalam tabel __"Monocotyledon"__ dan __"Dicotyledon"__:

![Plantae](https://1.bp.blogspot.com/-Z1onpZ5dY3Y/WuFyPUy396I/AAAAAAAAECA/mjeey5mTBNcGf684h-jGpTViKyR5KsYOgCLcBGAs/s640/Picture1.png)

_**Catatan:**_ _Soal ini hanya meminta Anda untuk menuliskan langkah-langkah/urutan query MySQL, sesuai spesifikasi di atas. Ketik jawaban dalam sebuah file .txt!_

### **Soal 2 Remedial - MongoDB Database**

Tuliskan langkah-langkah/urutan query MongoDB untuk membuat sebuah database Non-RDBMS (Document Store) dengan spesifikasi sebagai berikut:
- Terdapat sebuah database dengan nama __"Animalia"__.
- Database __"Animalia"__ memiliki 2 buah collection: __"Vertebrata"__ dan __"Invertebrata"__.
- Masukkan 5 buah data berikut ke collection __"Vertebrata"__:

```javascript
    {nama:"Kanguru", latin:"Macropus rufus", famili:"Macropodidae"},
    {nama:"Kambing", latin:"Ovis aries", famili:"Bovidae"},
    {nama:"Kijang", latin:"Odocoileus virginiana", famili:"Cervidae"},
    {nama:"Koala", latin:"Phascolarctos cinereus", famili:"Phascolarctidae"},
    {nama:"Kuda", latin:"Equus caballus", famili:"Equidae"},
```

- Masukkan 5 buah data berikut ke collection __"Invertebrata"__:

```javascript
    {nama:"Laba-laba", latin:"Salcitus scenicus", famili:"Araneae"},
    {nama:"Lalat", latin:"Tabanus sp", famili:"Diptera"},
    {nama:"Lebah", latin:"Polistes sp", famili:"Anthophila"},
    {nama:"Lipan", latin:"Scolopendra gigantea", famili:"Scolopendra"},
    {nama:"Lobster", latin:"Cherax quadricarinatus", famili:"Nephropidae"},
```

_**Catatan:**_ _Soal ini hanya meminta Anda untuk menuliskan langkah-langkah/urutan query MongoDB, sesuai spesifikasi di atas. Ketik jawaban dalam sebuah file .txt!_

### **Soal 3 Remedial - Express**

Buatlah sebuah aplikasi NodeJS (Express) sederhana yang mampu mengakses database __"Plantae"__ (**Soal No. 1**) dan database __"Animalia"__ (**Soal No. 2**), dengan spesifikasi sebagai berikut:

> - __GET /flora/monokotil__ &rarr; akan memberikan response: menampilkan semua data dari tabel __"Monocotyledon"__.

> - __GET /flora/dikotil__ &rarr; akan memberikan response: menampilkan semua data dari tabel __"Dicotyledon"__.

> - **GET /fauna/vertebrata** &rarr; akan memberikan response: menampilkan semua data dari collection **"Vertebrata"**.

> - **GET /fauna/invertebrata** &rarr; akan memberikan response: menampilkan semua data dari collection **"Invertebrata"**.

### *__#HappyCoding__*
