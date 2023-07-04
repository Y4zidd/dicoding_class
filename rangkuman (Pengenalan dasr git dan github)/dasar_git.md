# Rangkuman Dasar Git

- Sejauh ini kita sudah banyak belajar mengenai dasar – dasar Git dan melakukan latihan, mulai dari membuat repository baru di GitHub hingga membuat release file atau versi rilis untuk sebuah berkas tertentu dan mengirimkan iterasi proyek kepada pengguna. Berikut beberapa poin yang telah kita pelajari sebelumnya:

- Dengan Git, pekerjaan menjadi lebih praktis. Kita dapat melacak perubahan pada berkas yang ada di dalam repository atau direktori kerja. Selain itu, kita juga dapat mengelola versi rilis dari sebuah proyek dalam repository.

- Penggunaan Git memerlukan adanya repository, yaitu wadah atau tempat penyimpanan proyek di mana setiap berkas yang ada di dalamnya dapat dilacak jika terjadi perubahan. Berdasarkan jenisnya, repository terbagi menjadi 2, yaitu local repository dan remote repository.

 - Local repository merupakan tempat penyimpanan lokal yang berada di komputer kita. Local repository dapat kita ubah-ubah (hapus, modifikasi, dan tambah) sesuai dengan keinginan kita, sebelum akhirnya nanti di-push/diimplementasikan ke remote repository.

 - Remote Repository merupakan tempat penyimpanan berkas-berkas pekerjaan atau kenangan yang kita miliki di dalam server. Anda bisa menggunakan berbagai layanan penyimpanan berbasis cloud yang sangat populer seperti GitHub, Gitlab, dan BitBucket. Selain itu, jika Anda memiliki server sendiri, Anda juga dapat menginstal Git ke dalam server. Dengan menggunakan Remote Repository, orang lain dapat mengakses repository yang kita simpan dengan mudah.

- Pada latihan belajar dasar Git kita belajar menggunakan remote repository dari salah satu penyedia layanan cloud yaitu GitHub. Dalam belajar dan memahami semua konsep dasar dari Git, kita juga telah melakukan latihan dengan mempraktikkan bagaimana membuat repository di GitHub, di mana saat membuat repository terdapat pengaturan visibilitas yang terdiri dari 2 yaitu private dan public.

 - Private repository merupakan repository yang bersifat tertutup/pribadi dan hanya akun–akun yang telah diberikan akses saja yang bisa melihatnya.
 - Public repository merupakan repository yang bersifat terbuka dan semua orang dapat melihat dan menggunakan projek yang ada di repository tersebut.

- Ketika membuat repository ada beberapa inisialisasi yang bisa kita lakukan, yaitu:

 - Add a README file atau penambahan README File pada repository baru. Ketika repository telah dibuat, GitHub secara otomatis membuatkan file Readme ke dalam repository. 
 - Add .gitignore atau penambahan berkas .gitignore pada repository. Ketika repository telah terbuat, file .gitignore akan tercipta sesuai dengan pilihan template .gitignore yang dipilih.
 - Choose a license atau penambahan berkas license pada repository. Ketika membuat repository, Anda bisa memilih lisensi untuk repository tersebut sehingga proyek yang ada di dalamnya dapat digunakan secara bebas oleh orang lain.

- Selain itu, kita juga telah belajar tentang bagaimana alur kerja dari Git demi menyelesaikan pekerjaan secara konsisten dan produktif. Kita juga telah belajar tentang bagaimana memanfaatkan Git secara efektif di mana menggunakan Git memungkinkan kita untuk bekerja dengan tim secara paralel. Memahami alur kerja Git juga dapat mempermudah dalam proses pengerjaan proyek yang melibatkan tim, terlebih lagi jika skala proyek yang dikerjakan itu besar.

Lalu, kita juga telah belajar dan memahami konsep perintah dasar dari Git seperti Commit, Checkout, Reset, dan Revert beserta fungsinya yang bisa di lihat pada tabel berikut.

#### Perintah dan Fungsi

###### - Git Commit

Menyimpan hasil perubahan setiap file yang ada di dalam direktori kerja, baik itu file yang baru saja ditambahkan maupun perubahan pada file. Kemudian kita dapat menyisipkan pesan commit agar memudahkan dalam memahami riwayat perubahan. [Baca lebih lengkap tentang perintah Git Commit]

###### - Git Checkout

Melakukan perpindahan dari commit satu ke commit yang dituju. Namun hanya bersifat sementara. Git Checkout juga dapat digunakan untuk berpindah dari satu cabang kerja (branch) ke cabang kerja lainnya. 

###### - Git Reset

Mengembalikan keadaan suatu commit ke dalam keadaan sebelum terjadi perubahan sesuai dengan commit yang dituju. Namun, git reset akan menghapus beberapa riwayat commit sesudahnya. 

###### - Git Revert

Mengembalikan keadaan suatu berkas sebelum terjadi suatu perubahan sesuai dengan tujuan commit yang dituju. Git Revert tidak akan menghilangkan riwayat commit sesudahnya. 


- Kemudian kita juga membuat file readme yang berekstensi Markdown(md) untuk memberikan informasi tentang tujuan atau isi dalam repository. Biasanya berkas readme berupa file pertama yang akan dilihat oleh pengunjung repository Anda.

- Ketika membuat berkas readme ada beberapa format penulisan markdown yang dirangkum pada tabel berikut.
Format	dan Simbol

 - Heading = # atau ==
 - Subheading = --
 - Italic (Cetak miring) = *
 - List = -

- Lalu kita juga telah belajar mempraktekkan bagaimana cara membuat release file atau versi rilis untuk sebuah berkas tertentu di mana kita belajar dengan cara menggunakan fitur manajemen versi yang ada di web GitHub. Dari hasil versi rilis yang kita telah buat juga dapat diubah sewaktu waktu ataupun dihapus jika diperlukan.

- Kita belajar menuliskan tag version yang baik dan benar yaitu diawali dengan menggunakan huruf v kecil untuk singkatan versi lalu diikuti tanda titik(.) dan angka versi. Jika memiliki versi yang lebih dari satu angka dapat dipisah menggunakan tanda titik(.) atau jika ada penggunaan versi nama seperti beta atau alpha bisa dipisahkan dengan tanda hubung(-). [Dapat dipelajari lebih lanjut di sini]. Berikut contoh – contoh penulisan tagversionyang baik dan benar.
  - v.1.0
  - v.1.0.0
  - v.3.1-alpha
  - v.4.2-beta
Sejauh ini bagaimana? Mudah bukan untuk menggunakan Git? Mari kita pelajari berbagai hal lain seputar Git pada modul–modul berikutnya. Selamat belajar! 