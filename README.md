## Praktikum 2 : CSS Dasar
~~~
Subkhan Fadilah
311910410
TI.19.A.2
~~~
# LANGKAH 1
Membuat Dokumen HTML seperti berikut
![1](https://user-images.githubusercontent.com/56526583/115675746-14301d80-a379-11eb-9e18-bbceb00159fa.png)
# LANGKAH 2
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian ```head``` dokumen
![2](https://user-images.githubusercontent.com/56526583/115676454-d089e380-a379-11eb-9f87-5ef70916f210.png)
# LANGKAH 3
Kemudian tambahkan deklarasi inline CSS pada tag ```<p>``` seperti berikut
  ![3](https://user-images.githubusercontent.com/56526583/115676606-f3b49300-a379-11eb-8ab8-423ef2dd7545.png)
# LANGKAH 4
  Membuat CSS eksternal dan Kemudian tambahkan tag ```<link>``` untuk merujuk file css yang sudah dibuat pada bagian ```<head>```
  ![4](https://user-images.githubusercontent.com/56526583/115677170-6de51780-a37a-11eb-8b91-b7313e9a7a9d.png)
# LANGKAH 5
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector, Pada file style_eksternal.css
![5](https://user-images.githubusercontent.com/56526583/115677414-a684f100-a37a-11eb-8dd5-8fba07e9d900.png)
# Pertanyaan dan Tugas
# 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
Saya melakukan beberapa eksperimen seperti mengubah nilai yang hasilnya mengubah ukuran ataupun warna dan mengganti background
![tugas ss 1](https://user-images.githubusercontent.com/56526583/115677615-da601680-a37a-11eb-8a9d-da271c7b9a18.png)
# 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
Pendeklarasian CSS elemen h1 mengubah tampilan seluruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki id #intro.
# 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?Berikan penjelasan dan contohnya!
Setelah saya mencoba, jika mendeklarasikan CSS pada elemen yang sama namun dengan isi deklarasi yang berbeda, maka semua deklarasi CSS tersebut akan ditampilkan. Contohnya:
![ss tugas ss 2](https://user-images.githubusercontent.com/56526583/115677900-257a2980-a37b-11eb-92b3-0b8b2ce2f990.png)
Namun jika isi dari ketiga deklarasi CSSnya sama semua, maka browser hanya akan menampilkan salah satunya, dengan urutan Inline CSS, Eksternal CSS, dan yang terakhir Internal CSS.
![tugas ss 3](https://user-images.githubusercontent.com/56526583/115678021-4478bb80-a37b-11eb-8850-bc08bf437102.png)
# 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
Kedua deklarasi tersebut akan tampil, namun selector ID yang akan tampil jika deklarasinya ada yang sama antara ID dan Class.
![ss tugas ss 4](https://user-images.githubusercontent.com/56526583/115678208-7853e100-a37b-11eb-8de1-931e0b851a22.png)



