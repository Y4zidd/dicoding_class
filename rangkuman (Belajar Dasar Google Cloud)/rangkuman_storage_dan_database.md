# Rangkuman
Terdapat tiga macam jenis data, yakni *structured data*, *semi-structured data*, dan *unstructured data*. 

*Structured data* merupakan data yang dikelola dan disimpan dengan format tabel yang terdiri dari baris dan kolom, seperti halnya Anda menyimpan sebuah data di Spreadsheet atau Excel.

*Unstructured data* merupakan data yang bentuknya bermacam-macam sehingga biasanya mempunyai format khusus dalam penyimpanan setiap jenis datanya. Contoh jenis data tidak terstruktur adalah data berformat gambar, video, atau suara seperti foto, film, maupun rekaman audio.

Data *semi-terstruktur* merupakan jenis data yang memiliki karakteristik campuran dari data terstruktur dan data tidak terstruktur. Data ini dapat berupa tabel, tetapi skema penyimpanan datanya mungkin berbeda: tidak menggunakan baris dan kolom, melainkan menggunakan format tertentu.

## Tipe-Tipe Data Storage
Terdapat tiga tipe data storage: *File Storage*, *Block Storage*, dan *Object Storage*.

*Block storage* adalah format penyimpanan data yang terkelola dalam sebuah volume (wadah) yang dapat diatur sesuai keinginan pengguna. Persistent disk ini layaknya hard disk yang menyimpan file sistem operasi dan juga wadah penyimpanan file yang Anda simpan pada sebuah sistem operasi.

Persistent disk dapat melakukan mekanisme Snapshot atau pencadangan disk.

*Snapshot* adalah mekanisme pencadangan disk yang akan mencadangkan data secara inkremental atau bertahap. Jadi, ketika kita melakukan pencadangan pertama kali, semua konten yang ada pada disk akan disimpan. Lalu, ketika setiap kali kita melakukan snapshot kedua ataupun seterusnya, disk yang memiliki perubahan saja yang akan disimpan pada snapshot baru. 

*Object storage* merupakan format penyimpanan data untuk data yang tidak terstruktur. Contoh layanan yang dapat Anda pakai untuk object storage adalah Google Cloud Storage (GCS).

Google Cloud Storage (GCS) adalah layanan dari Google Cloud untuk menyimpan segala data yang tidak terstruktur, seperti gambar, video, file, skrip, hingga data backup.

Pada GCS, object akan disimpan dalam sebuah wadah yang bernama bucket. Untuk bisa menyimpan berbagai macam data ke dalam bucket, Anda harus menamai bucket dengan unik secara global. 

GCS memiliki empat kelas penyimpanan, yakni Standar (untuk menyimpan data yang sering diakses), Nearline (untuk menyimpan data yang 30 hari sekali diakses), Coldline (untuk menyimpan data 90 hari sekali diakses), dan Archive (untuk menyimpan data 1 tahun sekali diakses). 

Masing-masing kelas penyimpanan tersebut juga menyediakan tiga pilihan berdasarkan jenis lokasinya seperti Multi-region, Dual-Region, Region.

GCS juga memiliki berbagai fitur canggih, salah satunya adalah Object Lifecycle Management. Pada fitur ini, Anda dapat menentukan aturan yang mengatur apa yang akan terjadi pada object yang disimpan di bucket ketika suatu kondisi terpenuhi. 

*File storage* merupakan tipe data storage yang penyimpanan datanya berbasis hierarki file. Ini berarti file disimpan sebagai satu bagian informasi di suatu hierarki atau tingkatan, seperti folder dan file. Contohnya, ketika Anda perlu mengakses data yang tersimpan di file storage, Anda hanya perlu mengetahui jalur folder (path) untuk menemukannya. Data disimpan, diatur, dan diambil menggunakan metadata yang memberi tahu komputer dengan tepat di mana file berada.

*Google Filestore* merupakan layanan yang dapat membantu Anda mengelola penyimpanan file dengan mekanisme NFS secara terkelola. Biasanya, Filestore digunakan untuk aplikasi yang membutuhkan file system interface (antarmuka file) dan shared file system (berbagi file system) yang menawarkan latensi rendah sehingga memudahkan dalam mengakses penyimpanan data. 


## Tipe-Tipe Database

Pada umumnya, terdapat dua tipe database yang sering kita pakai untuk menyimpan data pada sebuah aplikasi. Dua tipe database tersebut adalah relational database dan non-relational database.

*Relational database* merupakan database yang skema penyimpanan datanya berupa tabel yang berisi baris (mewakili entri data) dan kolom (menyimpan dan mengurutkan informasi). Database ini digunakan untuk menyimpan data yang terstruktur ke dalam tabel. Anda bisa bayangkan relational database seperti spreadsheet atau file excel yang sering kita gunakan untuk mengelola dan menyimpan data dalam bentuk tabel.

Database ini dalam pengelolaan datanya menggunakan bahasa kueri, yakni SQL (structured query language). SQL digunakan untuk mengelola relational data seperti membuat kueri, memperbarui, mengedit, atau menghapus data.

Contoh relational database adalah *MySQL*, *PostgreSQL*, *Microsoft SQL Server*, dan *MariaDB*. Google Cloud menyediakan beberapa pilihan layanan untuk mengelola relational database seperti *Cloud SQL* dan *Cloud Spanner*. 

*Non-relational* database merupakan database yang menyimpan data tanpa menggunakan skema yang kaku, ia bisa berupa key-value, dokumen, grafik, wide-column, dsb. 

Dibandingkan dengan relational database yang tata letak datanya berbasis tabel, non-relational database tidak memiliki skema data yang baku sehingga struktur penyimpanan datanya dapat bervariasi. 

Database ini dikenal sebagai NoSQL (Not Only SQL) database atau ‘Tidak Hanya SQL’ karena ia dapat menggunakan bahasa kueri lain bergantung pada tata letak datanya yang bisa saja dalam format non-standar.

Contoh non-relational database di antaranya adalah MongoDB, Cassandra, dan Redis. Nah, Google Cloud menyediakan layanan untuk tipe database ini seperti Firestore dan Bigtable

## Solusi database di GCP
## Layanan Relational Database

*Cloud SQL* adalah layanan untuk relational database yang terkelola sepenuhnya oleh Google Cloud yang kompatibel dengan berbagai macam jenis layanan relational database seperti SQL Server, MySQL, dan PostgreSQL. 

Cloud SQL memiliki berbagai fitur seperti pencadangan otomatis, replikasi data, dan pemulihan bencana (disaster recovery) untuk memastikan ketersediaan dan ketahanan yang tinggi. 

Anda dapat mengintegrasikan layanan ini dengan berbagai layanan Google Cloud lainnya seperti *Compute Engine, App Engine, BigQuery, dan Kubernetes*.

*Cloud Spanner* adalah layanan untuk relational database yang memiliki ketersediaan secara global yang terkelola sepenuhnya oleh Google Cloud. Layanan ini dapat menyediakan kapasitas hingga petabyte dan menawarkan konsistensi transaksional pada skala global, keamanan bawaan yang handal, dan replikasi sinkron otomatis untuk ketersediaan tinggi.

Cloud Spanner biasanya digunakan dalam aplikasi keuangan, inventaris, fintech, dan perbankan yang membutuhkan performa dan konsistensi tingkat global yang tinggi dalam pengelolaan dan akses database. 

Jika Anda membutuhkan lebih dari 30 TB ruang penyimpanan, lebih dari 4000 koneksi serentak ke database, atau ingin menyerahkantanggung jawab atas scaling, ketersediaan, dan manajemen lokasi kepada Google, pertimbangkanlah untuk menggunakan Cloud Spanner.

Jika Anda memiliki persyaratan tertentu seperti konfigurasi sistem operasi, basis data khusus, atau persyaratan cadangan khusus, pertimbangkan untuk meng-hosting database Anda sendiri di VM menggunakan Compute Engine. Jika tidak, sangat disarankan untuk menggunakan Cloud SQL sebagai layanan yang terkelola sepenuhnya untuk database relasional Anda.

## Layanan Non-Relational Database di GCP

*Cloud Firestore* adalah database NoSQL serverless yang terkelola sepenuhnya oleh Google Cloud yang dirancang untuk pengembangan aplikasi dalam skala global. Anda dapat menggunakannya untuk menyimpan, menyinkronkan, dan meminta data untuk aplikasi web, game, seluler, dan IoT (Internet of Things). 

Layanan ini memiliki berbagai fitur untuk dukungan offline mode, sinkronisasi secara langsung, dan keamanan. Anda dapat mengintegrasikan Firestore dengan Firebase, yakni platform pengembangan seluler GCP untuk pembuatan dan pengelolaan aplikasi yang lebih mudah.

*Cloud Bigtable* adalah layanan database NoSQL yang terkelola sepenuhnya oleh Google Cloud. Ia dirancang untuk beban kerja operasional dan analitik yang besar. Cloud Bigtable menyertakan fitur untuk ketersediaan tinggi, perubahan konfigurasi tanpa henti, dan latensi di bawah 10 ms. Anda dapat mengintegrasikannya dengan berbagai alat, termasuk Apache Hadoop, TensorFlow, dan BigQuery.

*Cloud Bigtable* adalah pilihan yang baik jika Anda menggunakan database dengan jenis non-relational database. Secara khusus, ini bagus untuk beban kerja latensi rendah dan throughput tinggi. 

Jika Anda perlu melakukan analisis di satu region, Cloud Bigtable lebih pas daripada Cloud Spanner. Namun, jika Anda memerlukan operasi multi-regional, Cloud Spanner adalah solusi yang disarankan. 

*Cloud Memorystore* adalah penyimpanan data Google Cloud dalam memori yang terkelola sepenuhnya. Ini dirancang agar aman, sangat tersedia, dan scalable. Cloud Memorystore memungkinkan Anda membuat cache aplikasi dengan latensi sub-milidetik untuk akses data. Ia kompatibel dengan *Memcached* dan *Redis*. 

Untuk kebutuhan yang lebih besar, seperti *data analitik* atau *big data*, tersedia juga layanan *data warehouse*, yakni *BigQuery*. 

*BigQuery* adalah gudang data tanpa server (serverless data warehouse) yang terkelola sepenuhnya. Ia dapat melakukan analisis data yang sangat besar menggunakan bahasa SQL dan dapat mengelola data streaming kueri. BigQuery mencakup layanan transfer data bawaan untuk membantu Anda memigrasikan data dari sumber daya lokal, termasuk Teradata. 

BigQuery memiliki berbagai fitur seperti database untuk machine learning, business intelligence, dan analisis data. Fitur-fitur ini disediakan melalui *BigQuery ML* dan *BI Engine*.

Jika Anda perlu menyimpan lebih dari 1 TB data terstruktur, membutuhkan volume tulis yang sangat tinggi, memerlukan latensi baca/tulis kurang dari 10 milidetik, atau memerlukan layanan penyimpanan yang kompatibel dengan beberapa aplikasi data processing, pertimbangkanlah untuk menggunakan *Cloud Bigtable*. 

Jika Anda tidak memerlukan semua kebutuhan di atas dan mencari layanan penyimpanan non relational database yang digunakan dengan baik untuk penggunaan mobile, game atau IoT pada skala regional, pertimbangkan untuk menggunakan *Cloud Firestore*