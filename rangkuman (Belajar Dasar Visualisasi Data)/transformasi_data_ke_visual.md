# Rangkuman dari Sub-modul Transformasi Data ke Visual

Diagram adalah sebuah representatif visual terhadap informasi. Diagram digunakan untuk mempermudah kita memahami informasi dari data yang kita miliki.


## Beberapa bentuk grafik dalam visualisasi data:

- Bar/Column Chart: Jenis grafik di mana setiap kategori diwakili oleh persegi panjang, dengan panjang perseginya yang sebanding dengan nilai agregasi data.

- Line Chart: Jenis grafik yang menampilkan informasi sebagai serangkaian titik data yang disebut 'penanda' yang dihubungkan oleh segmen garis lurus.

- Area Chart: Mirip dengan jenis grafik Line Chart. Namun, area di bawah garis yang menghubungkan titik data akan terisi dengan warna atau bayangan.

- Pie Chart: Jenis grafik yang menampilkan data dalam grafik lingkaran. Seluruh "kue pai" mewakili 100% dari keseluruhan, sedangkan pai "irisan" mewakili bagian dari keseluruhan.

- Scatter Chart: Menggunakan titik untuk merepresentasikan nilai numerik pada kategori yang berbeda. Posisi setiap titik pada sumbu horizontal dan vertikal menunjukkan nilai untuk titik data individual.

- Map Chart: Memungkinkan kita untuk memvisualisasikan hubungan spasial dalam data dengan menunjukkan data pada peta geografis. Umumnya pada peta seperti ini, semakin tebal warnanya, semakin intens pula kepadatan datanya.

## Kesalahan umum dalam membuat visualisasi data:

- Nilai persentase tidak sesuai (tidak sepenuhnya sampai 100%) pada grafik pai.

- Terlalu banyak data yang ingin ditunjukkan.

- Tidak mengikuti standar penulisan grafik seperti menaruh nilai minimum di sumbu Y paling atas sehingga grafik terbalik.

- Terdapat sumbu yang terpotong seperti ketika sumbu Y tidak dimulai dari 0%.

- Penggunaan grafik 3D yang kurang sesuai sehingga dapat terjadi bias pada audiens. Sebagai contoh sebuah irisan pai dapat terlihat lebih besar dari seharusnya dan sebuah batang terlihat lebih tinggi dari seharusnya.

- Grafik susah dibandingkan karena tidak jelas tujuan dan informasi yang ingin disampaikan.
Data provenance (dokumentasi data) adalah sebuah langkah untuk melihat sumber data yang kita peroleh. 

Dokumentasi data dibutuhkan untuk tahu segala proses dalam pembuatan, perubahan, penanganan, mau pun hal lainnya yang berpengaruh kepada data. 
Dokumentasi data penting untuk mengetahui keabsahan data dan memungkinkan kita menggunakannya kembali di waktu yang lain.
Dokumentasi data penting untuk dapat menilai keaslian dan menumbuhkan kepercayaan kepada data, sekaligus untuk mereproduksi data tersebut.
Contoh dari dokumentasi data dapat berupa metadata atau version history,
Pendekatan yang dapat dilakukan dalam melakukan dokumentasi data sebagai berikut:

Dicatat dalam bentuk teks, bisa menggunakan skema penulisan umum atau bisa juga dengan skema khusus dalam data provenance.
Dicatat dan disimpan secara internal menggunakan program perangkat lunak atau dalam sistem eksternal lainnya.
Dituliskan dalam bentuk yang dapat dibaca oleh mesin atau yang bisa dibaca oleh manusia.

Contoh bentuk penulisan dokumentasi data:

- Berkas README
- Data Dictionaries (kamus data)
- Data Paper
- Tips dalam menjalankan dokumentasi data:

Gunakan Alur Ilmiah yang Terstruktur: Gunakan alur terstruktur yang terdiri dari pencatatan, eksekusi, pemrosesan, dan urutan secara ilmiah, supaya pembaca paham sumber asal dan teori yang mendukung dokumentasi data tersebut.
Informasi Harus Jelas dan Sedetail Mungkin: Tautan ke data sumber asli harus jelas dan sebutkan dari mana mendapatkannya.
Exploratory analysis adalah proses penyampaian di mana Anda membimbing dan memandu audiens dalam melihat (menjelajahi) data yang telah dikumpulkan.


Explanatory analysis adalah proses penyampaian di mana Anda tidak meminta audiens untuk menjelajahi data namun langsung ke poin-poin utama dan implikasi dari data tersebut.


## poin penting dalam melakukan explanatory analysis:

- Kepada siapa kita berkomunikasi: Berkomunikasi dengan terlalu banyak orang pada saat sama sekaligus, cenderung tidak tepat sasaran karena kebutuhan masing-masing orang dapat berbeda. Jika Anda sebelumnya tidak pernah bertemu dengan audiens, berarti Anda terlebih dahulu harus membangun reputasi bahwa Anda itu benar-benar mengerti topik yang akan diberikan. Biasanya hal ini dilakukan dengan cara perkenalan diri.

- Bagaimana kita berkomunikasi dengan audiens: Pada proses presentasi secara langsung dan tatap muka, kita dapat menanggapi audiens jika terdapat hal yang kurang jelas, sehingga tidak semua yang kita sampaikan harus ditulis secara detail pada dokumen presentasi dan visualisasi data. Jika dalam bentuk dokumen yang dibaca sendiri-sendiri maka tingkat detail yang diperlukan pada penulisan dokumen biasanya lebih tinggi. Jika kita adalah orang yang menganalisis dan mengomunikasikan data, maka kita harus percaya diri.

- Bagaimana kita bisa menggunakan data untuk membantu menegaskan maksud kita: Salah satu cara yang dapat dilakukan adalah menggunakan metode 5W (What, Who, When, Why, Where) untuk menegaskan informasi penting yang ingin kita sampaikan.

## Contoh visualisasi data yang efektif

- Berbentuk Teks: Ketika kita hanya ingin menampilkan satu atau dua angka saja, gunakan teks sederhana.

- Tabel: Tabel sangat baik untuk ketika audiens Anda beragam karena mereka dapat membaca baris tertentu sesuai kepentingan masing-masing. Jika kita berhadapan dengan banyak unit pengukuran, tabel lebih memudahkan saat dibaca.

- Heatmap: Heatmap menggabungkan detail angka pada tabel dengan visual agar membantu audiens untuk lebih cepat fokus pada informasi yang penting pada tabel.

- Grafik: Grafik lebih cepat diproses dan mudah dipahami dalam mendapatkan informasi. 

  - Grafik scatterplot berguna untuk menunjukkan hubungan antara dua hal yang terdapat di sumbu x dan y karena grafik ini membuat kita memproses data serentak untuk melihat hubungan apa yang muncul.

  - Grafik garis biasanya digunakan untuk melihat data yang bersifat kontinu (berkelanjutan). Karena titik dihubungkan melalui garis, grafik ini memperlihatkan perubahan (pertumbuhan atau pengurangan) yang terjadi antar titik, sehingga tidak sesuai untuk data yang bersifat kategoris seperti data yang membandingkan jenis kelamin (berapa banyak yang laki-laki dan perempuan).

Slopegraph merupakan grafik berkategori garis yang hanya memperlihatkan perubahan antara dua titik saja agar audiens fokus pada perubahan kenaikan atau penurunan yang terjadi.

- Grafik batang (vertikal dan horizontal) dapat membandingkan beberapa data yang digambarkan dalam bentuk batang secara cepat sehingga audiens bisa dengan cepat tahu data yang terbesar, terkecil, dan perbandingan antara kategori data.

- Grafik batang bertumpuk (vertikal dan horizontal) memungkinkan untuk membandingkan antar kategori utama dan juga antar sub komponen dalam tiap kategori.

- Grafik air terjun (waterfall chart) dapat digunakan untuk menampilkan bagian tertentu dari grafik batang bertumpuk sehingga lebih fokus menunjukkan data awal, kenaikan atau penurunan yang terjadi, serta data akhir.

- Grafik area memungkinkan untuk menampilkan data secara lebih ringkas dari grafik lainnya namun tidak cocok memvisualisasikan data yang besaran perbedaan angkanya tidak tinggi.

Contoh prinsip Gestalt dalam persepsi visual

- 1. Proximity (Kedekatan): Objek yang jaraknya berdekatan merupakan kelompok atau golongan yang sama.

- 2. Similarity (Kesamaan): Objek yang memiliki warna, bentuk, ukuran, dan arah yang sama dianggap terkait atau termasuk bagian dari kelompok yang sama.

- 3. Enclosure (Pembeda): Objek yang memiliki batas fisik atau border yang sama merupakan satu golongan sama.

- 4. Closure (Penutupan Bentuk): Manusia cenderung memandang sekumpulan objek yang terpecah-pecah sebagai bagian dari satu objek yang lengkap, daripada memandang kumpulan objek tersebut sebagai sesuatu yang benar-benar terpisah satu sama lain

- 5. Continuity (Kesinambungan Pola): Manusia cenderung secara alami membentuk garis pola walaupun tidak terlihat secara eksplisit.

- 5. Connection (Koneksi): Objek yang secara fisik terhubung adalah bagian dari satu golongan atau kesatuan.

- 6. Cognitive load (beban kognitif) adalah usaha mental yang harus dilakukan untuk dapat memproses dan mempelajari informasi.

Salah satu penyebab utama yang menimbulkan cognitive load yang berlebihan adalah sebuah kerumitan atau disebut juga dengan clutter. Clutter merupakan elemen visual yang tidak menambah pemahaman.

Agar audiens dapat dengan efektif mengerti visual yang diberikan, maka Anda perlu mengurangi cognitive load. Secara umum, identifikasilah dan hapuslah elemen yang kurang efektif.

Preattentive attributes adalah komponen atau atribut visual yang langsung tertangkap perhatian kita secara tanpa sadar.

Preattentive attributes dapat dimanfaatkan untuk membantu mengarahkan perhatian pada fokus utama yang ingin disampaikan.

Atribut ini dapat digunakan untuk membuat hierarki elemen visual yang mengarahkan perhatian pada informasi yang hendak diinformasikan sesuai dengan proses yang diharapkan.

Contoh preattentive attributes adalah penggunaan warna yang berbeda, ukuran font yang lebih besar, menggunakan font cetak tebal, dan memilih posisi yang lebih umum dilihat.

3 contoh konsep desain dalam berkomunikasi dengan data

- 1. Affordances: Dalam istilah desain, semua benda memiliki fungsinya masing-masing. Karakteristik ini menunjukkan bagaimana sebuah objek seharusnya berinteraksi. Cara penerapan:

  - Gunakan warna yang umum

  - Gunakan warna yang konsisten

  - Gunakan posisi yang konsisten

- 2. Accessibility: Visual dan desain seharusnya bisa dimengerti dan digunakan oleh orang dari berbagai latar belakang atau kemampuan. Cara penerapan:

  - Gunakan bahasa yang sederhana

  - Visual harus dapat menjelaskan dirinya sendiri

  - Aesthetics: Kebiasaan manusia untuk mendapatkan kesan negatif apabila melihat sesuatu yang kurang menarik atau tidak indah. Membuat pilihan warna, bentuk, dan posisi menjadi satu kesatuan yang menarik