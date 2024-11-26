# Tugas Besar IF4070 Representasi Pengetahuan dan Penalaran 2024/2025: Ripple Down Rules untuk Membantu Seseorang Menentukan Jenis Gangguan Mental yang Diderita

Program ini dibuat untuk memenuhi capaian kurikulum Tugas Besar IF4070 Representasi Pengetahuan dan Penalaran 2024/2025, yaitu pengembangan aplikasi intelijen berbasis pada penalaran dengan perkecualian seperti *Ripple Down Rule* (RDR). Adapun tema yang diambil pada tugas ini berkaitan dengan gangguan mental. 

## *Table of Contents*
- [Deskripsi Singkat](#deskripsi)
- [*Requirement* Program](#req)
- [Cara Menjalankan Program](#penggunaan)
- [Lampiran](#lampiran)
- [*Authors*](#author)

## Deskripsi Singkat <a name="deskripsi"></a>
Program RDR ini dibuat menggunakan bahasa Python. Program dibuat agar user(expert) dapat memasukkan gejala (symptoms) yang berkaitan dengan kesehatan mental. Program kemudian akan menampilkan hasil inferensi atau kesimpulan (conclusion). Jika user(expert) tidak setuju dengan hasil tersebut, maka dapat dimasukan penyakit baru (illness), yang akan membentuk aturan (rule) baru. Aturan baru ini akan memperbarui pohon biner RDR (Ripple Down Rules). Setelah pembaruan, aturan baru tersebut akan disimpan dalam bentuk file .rules dan divisualisasikan juga yang dapat dilihat melalui file PDF. 

## *Requirement* Program <a name="req"></a>
Beberapa hal yang harus dimiliki pengguna supaya program dapat dijalankan:
- <a href=https://jupyter.org/install>Jupyter Notebook</a>
- <a href=https://github.com/munzayanahusn/IF4070-Ripple-Down-Rules>*Repository* GitHub "IF4070-Ripple Down Rules"</a>
- colorama
- Graphviz
- Ipywidgets

## Cara Run Program <a name="penggunaan"></a>
- Melalui Google Colab : https://colab.research.google.com/drive/1FEBj3dvj08GJektpmDcAr9lNoL-TXlA7?usp=sharing. <br>Tutorial menjalankan program dapat dilihat pada tautan video <a href=https://youtu.be/jOW0ZNBB5PE>berikut</a>
- Melalui Jupyter Notebook : `src\IF4070_Ripple_Down_Rules.ipynb` <br>Adapun tutorial menjalankan program dapat dilihat pada tautan video <a href=https://youtu.be/FoQSLsS5Gxk>berikut</a>
- Melalui Visual Studio Code : `src\IF4070_Ripple_Down_Rules.ipynb` <br>Adapun tutorial menjalankan program dapat dilihat pada tautan video berikut <a href=https://youtu.be/AJqcVDQ99CM>berikut</a>
<br><br>
> [!TIP]
> Langkah menjalankan program juga dapat dilihat pada file dokumentasi pada `docs\IF4070-Tugas Ripple Down Rule-13521076 13521077 13521115.pdf` <br>
> Daftar rules tersimpan dapat dilihat pada `rules\mental-illness.rules.txt`<br>
> Hasil visualisasi graf dapat dilihat pada `rules\final_rules.pdf`

## Lampiran <a name="lampiran"></a>
- Repository GitHub : https://github.com/munzayanahusn/IF4070-Ripple-Down-Rules
- Dataset yang digunakan untuk pembangunan rule : https://drive.google.com/file/d/1Qh6IybiYPQuWL0lFuD71_Js9fc3xL6QO/view?usp=sharing
- Bentuk rules lengkap yang telah dibangun dalam bentuk pdf : https://drive.google.com/file/d/1-1d6iZqpviNFsMe3vxz1C2LzIgxwfYBx/view?usp=sharing
  
## *Authors* <a name="author"></a>
<table>
  <tr>
    <td align="center" colspan="3">No. Kelompok : 3</td>
  </tr>   
    <td align="center">NIM</td>
    <td align="center">Nama</td>
    <td align="center">Username</td>
  </tr>
    <td align="center">13521076</td>
    <td align="center">Moh. Aghna Maysan Abyan</td>
    <td align="center"><a href=https://github.com/AghnaAbyan>AghnaAbyan</a></td>
  </tr>
    <td align="center">13521077</td>
    <td align="center">Husnia Munzayana</td>
    <td align="center"><a href=https://github.com/munzayanahusn>munzayanahusn</a></td>
  </tr>
    <td align="center">13521115</td>
    <td align="center">Shelma Salsabila</td>
    <td align="center"><a href=https://github.com/shelmasalsa17>shelmasalsa17</a></td>
</table>
