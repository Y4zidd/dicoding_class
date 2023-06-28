# Rangkuman
- Salah satu modul yang digunakan oleh aplikasi dalam melakukan akses ke data adalah database. Database ini adalah yang mengatur bagaimana data itu disimpan, diakses, diubah, dan dihapus.

Mekanisme dasar yang mencerminkan fungsi apa saja dalam mengakses data salah satunya adalah CRUD. Dimana CRUD itu sendiri adalah sebuah singkatan. Berikut adalah kepanjangan dari CRUD:

- Create, proses aplikasi dalam membuat data dalam database.
- Read, proses aplikasi dalam mengakses suatu data dalam database.
- Update, proses aplikasi dalam mengubah data yang sudah ada.
- Delete, proses aplikasi dalam menghapus data.

Ada beberapa istilah lain dalam menyebut struktur tabel pada database, yaitu:
- Field, merupakan kumpulan karakter dengan memiliki arti tertentu. Sebutan lain untuk masing    masing kepala tabel (table header).

- Record, sebutan lain untuk setiap baris yang memiliki data.

- SQL adalah bahasa kueri standar yang digunakan untuk melakukan operasi dalam mengakses database. SQL ini hanya bahasanya, dan diimplementasi oleh layanan database yang lain seperti MySQL.

- Tipe data adalah sebuah ketentuan untuk mengatur jenis data. Adapun berikut adalah beberapa tipe data yang digunakan di SQL.

|   Tipe Data  | Deskripsi |   values    |
| ------------ | --------- | ----------  |
| Integer      | Tipe data yang merepresentasikan bilangan desimal.      |     210     | 
| Real         | Tipe data yang merepresentasikan bilangan pecahan       |    44.6     |
| Text         | Tipe data yang merepresentasikan kalimat atau kumpulan huruf, namun tidak ditentukan batas limitnya      |      A journey      |
|  VARCHAR     | Sama dengan tipe data TEXT, namun ditentukan panjang karakternya.      |     A journey       |

- MySQL adalah layanan database yang umum dipakai. Adapun berikut adalah beberapa perintah dasar yang digunakan untuk mengakses data, maupun memodifikasi data pada database dengan mengambil contoh pada eksperimen sebelumnya dengan menggunakan tools paiza.io: 
 - Membuat Table
    ```
    create table keluarga ( 
      no int primary key, 
      nama text, 
      umur int, 
      posisi text
    );

 - Menyisipkan data pada tabel
   ```
   insert into keluarga (no, nama, umur, posisi) values (1, "Adi", 40, "Suami");

 - Membaca keseluruhan data pada tabel
   ```
   select * from keluarga;

 - Memperbarui data pada Tabel
   ```
   update keluarga set nama = 'Nisa' where no=2;

 - Menghapus data pada tabel 
   ```
   delete from keluarga where no = 2;
   
# Daftar Referensi

[7] Thomas N. “Databases”. (https://learning.oreilly.com/learning-paths/learning-path-sql/9781492058076/9781491938607-/ch02.html?snippet_id=snippet03) diakses pada 15 Februari 2021.

[8] Oracle. “Chapter 11 Data Types”. (https://dev.mysql.com/doc/refman/8.0/en/data-types.html) diakses pada 15 Februari 2021.
