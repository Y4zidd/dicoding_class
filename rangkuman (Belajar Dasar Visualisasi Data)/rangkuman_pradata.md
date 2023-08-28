Spreadsheet merupakan sebuah lembaran berisi baris dan kolom yang dapat kita gunakan untuk analisis data.

## Kegunaan spreadsheet:
1. Menyimpan informasi secara detail.
2. Membuat tabel data dengan lebih mudah.
3. Membantu dalam perhitungan statistik.
4. Memvisualisasikan data ke dalam bentuk grafik.
5. Lengkap dengan rumus-rumus yang membantu dalam perhitungan data.

## Macam-macam aplikasi spreadsheet:
1. Microsoft Excel
2. LibreOffice Calc
3. Google Sheets

Spreadsheet pada dasarnya baris dan kolom. Baris dan kolom merupakan kumpulan dari sel. Data yang dapat dimasukkan dalam sel dapat berupa:

- Angka : Anda dapat memasukkan angka yang nantinya dapat dihitung secara matematis.
- Teks : Anda dapat memasukkan data atau informasi dalam bentuk teks seperti “Jumlah barang” atau “Nama lengkap”. 
- Rumus : Digunakan untuk melakukan perhitungan atau kalkulasi dari sebuah atau sekelompok sel. Misal, kita dapat menggunakan rumus untuk menjumlahkan sebuah deretan sel yang berisi data dalam bentuk angka.

## Elemen pada menu bar Google Sheets:
- Title bar: Bagian yang menunjukkan judul berkas.
- Menu bar: Terletak di bawah judul berkas. Tersedia berbagai menu yang disediakan oleh Google Sheets mulai dari File hingga Help.

## Opsi ketika melakukan import file pada Google Sheets:
- Create new spreadsheet : Menambahkan berkas pada spreadsheet baru.
- Insert new sheet(s) : Menambahkan berkas menjadi sheet baru dalam spreadsheet yang sedang aktif.
- Replace spreadsheet : Menggantikan spreadsheet yang sedang aktif dengan berkas yang ditambahkan.
- Opsi pengolahan data pada berkas spreadsheet aplikasi Google Sheets:
- Sortir data: Fitur untuk mengurutkan data supaya lebih tertata rapi.
- Penyaringan data: Cara agar hanya menampilkan data tertentu berdasarkan kondisi yang kita tentukan. Pada saat penyaringan data dilakukan, maka data yang tidak memenuhi kriteria kondisi untuk dimunculkan akan secara otomatis disembunyikan. Namun data yang disembunyikan tersebut tidak terhapus dari Google Sheets.
- Formula: Langkah atau rumus untuk melakukan perhitungan matematis sehingga mendapatkan nilai tertentu. Sebuah formula pasti merujuk pada sebuah alamat sel tertentu yang dapat disebut sebagai referensi sel.
- Pivot table: Fitur untuk mengumpulkan dan mengelompokkan data berdasarkan parameter tertentu sesuai kebutuhan, tanpa perlu menggunakan penulisan rumus. Hasil akan disajikan dalam bentuk tabel.
- Operator adalah simbol atau tanda yang memiliki fungsi tertentu dan digunakan untuk melakukan pemrosesan atau perhitungan data.
 

*Operator aritmatika*: Operator aritmatika atau matematika digunakan pada aplikasi spreadsheet untuk melakukan operasi matematika dasar, seperti penambahan, pengurangan, perkalian, atau pembagian. Selain itu dapat digunakan untuk menghitung nilai pangkat atau persen.


*Operator perbandingan*: Dalam spreadsheet biasanya kita menggunakan jenis operator perbandingan untuk fungsi-fungsi logika seperti IF, OR, AND, dan NOT. Hasilnya adalah kondisi nilai True atau False.


*Operator text*: Contoh adalah ampersand (“&”) yang berfungsi untuk menggabungkan beberapa string text menjadi satu string tunggal


## Elemen formula dalam spreadsheet aplikasi Google Sheets:
- Sama dengan (“=”): Tanda sama dengan “=” merupakan elemen yang paling awal ditulis dalam sebuah formula apa pun sebelum lanjut ke elemen lainnya.
- Fungsi: Fungsi merupakan sebuah penamaan yang telah ditentukan untuk melakukan kalkulasi data berdasarkan susunan argumen dalam aplikasi spreadsheet.
- Referensi Sel: Acuan sebuah sel atau range dalam aplikasi spreadsheet, mulai dari sheet yang sama hingga berbeda berkas atau workbook.
- Operator: Simbol atau tanda yang memiliki fungsi tertentu dan digunakan untuk melakukan pemrosesan atau perhitungan data. 
- Konstanta: Nilai masukan yang bukan berasal dari perhitungan karena nilainya selalu sama dan tidak pernah berubah. Bentuk dari konstanta bisa berupa teks atau angka.

## Beberapa fungsi pada spreadsheet aplikasi Google Sheets:
- Sum: Mendapatkan nilai total dari rentang sel yang dipilih. Cara penulisan: =SUM(data ke-1, data ke-2, … , data ke-n)
- SumIF: Menjumlahkan data yang sesuai kriteria tertentu. Hanya terbatas untuk satu kriteria. Cara  penulisan: =SUMIF(range, ”kriteria”,sum_range)
- SumIFS: Menjumlahkan data yang sesuai kriteria tertentu. Menggunakan lebih dari satu kriteria. Cara penulisan: =SUMIFS(sum_range, kriteria_range1, “kriteria1”, kriteria_range2, “kriteria2”, dan seterusnya)
- Average: Rata-rata aritmatika yang menjumlahkan semua data kemudian dibagi dengan jumlah data yang ada. Cara penulisan: =AVERAGE(data ke-1, data ke-2, … , data ke-n)
- Count: Menghitung banyaknya sel terpilih dalam rentang tertentu yang berisi nilai numerik. Cara penulisan: =COUNT(data ke-1, data ke-2, … , data ke-n)
- CountA: Menghitung banyaknya sel terpilih dalam rentang tertentu, tak peduli apa pun jenis data yang ada di dalamnya (angka, teks, tanggal, kondisi benar atau salah, hingga kesalahan perhitungan), namun tidak menghitung sel yang kosong. Cara penulisan: =COUNTA(data ke-1, data ke-2, … , data ke-n)
- CountIF: Menghitung banyaknya sel terpilih dalam rentang tertentu, yang sesuai kriteria tertentu. Hanya terbatas untuk satu kriteria. Cara penulisan: =COUNTIF(range, “kriteria”)
- CountIFS: Menghitung banyaknya sel terpilih dalam rentang tertentu, yang sesuai kriteria tertentu. Menggunakan lebih dari satu kriteria. Cara penulisan: =COUNTIFS(kriteria_range1, “kriteria1”, kriteria_range2, “kriteria2”, dan seterusnya)
- Min: Menentukan nilai terendah dalam rentang tertentu. Contoh penulisan: =MIN(data ke-1, data ke-2, … , data ke-n)
- Max: Menentukan nilai tertinggi dalam rentang tertentu. Contoh penulisan: =MAX(data ke-1, data ke-2, … , data ke-n)
- Trim: Menghilangkan ruang kosong yang tidak dibutuhkan pada sebuah teks. Fungsi ini hanya berjalan pada sel tunggal bukan pada rentang sel. Cara penulisan: =TRIM(teks)
- Replace: Mengganti string baik berupa angka maupun teks biasa. Cara penulisan: =REPLACE(text, position, length, new_text)
- Unique: Mencari data yang unik dari sebuah rentang data yang mungkin saja ada yang sama. Cara penulisan: =UNIQUE(range)
- If: Membuat perbandingan logis antara sebuah data dengan kondisi penguji yang yang diberikan. Cara penulisan untuk If sederhana: =IF(sel yang ingin diuji, [nilai jika benar]. [nilai jika salah])