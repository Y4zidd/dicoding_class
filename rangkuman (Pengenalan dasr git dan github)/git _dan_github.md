# Rangkuman Git dan Github

Bagaimana, apakah pembelajaran yang kami jabarkan dapat dipahami dengan baik? Pada modul ini kita telah mempelajari bagaimana sejarah serta penggunaan Git dan GitHub. Oleh karena itu, mari kita ulas secara singkat apa yang telah kita pelajari.

Pada materi Git kita mempelajari sejarah berdirinya platform Git, bagaimana Linus Torvalds bersama tim membangun platform tersebut pada tahun 2005. Git dibangun dengan tujuan agar dapat melakukan kolaborasi antar tim serta bagaimana proyek dapat dikontrol dengan baik. Untuk bisa berkolaborasi, bisa dengan membangun proyek menjadi open source atau pilihan lainnya menyetel kolaborasi dengan orang lain.

Kemudian, kita juga telah belajar bagaimana dapat memahami perintah dan istilah yang ada pada Git, seperti Git Repository, Git Branch, Git Fork, Git Clone, Git Commit, dan Git Push. 
## Perintah Fungsi
- Git Repository	Media penyimpanan file proyek di dalam Git server.
- Git Branch	Percabangan untuk versi baru dari proyek repository.
- Git Fork	Penyalinan dari repository orang/organisasi lain, lalu menyimpannya di dalam repository Git sendiri.
- Git Clone	Mengambil sebuah repository dan menyimpannya pada direktori lokal.
- Git Commit	Cuplikan perubahan (snapshot) dari repository Anda pada waktu tertentu.
- Git Push	Mengirim hasil dari perubahan file yang dilakukan ke dalam repository server.
- Git Pull	Menarik atau mengambil source code dari repository server ke lokal..

Selanjutnya, pada materi GitHub kita telah mempelajari bagaimana menggunakan Platform Website GitHub. 

- GitHub merupakan sebuah perusahaan layanan hosting repository Git berbasis Cloud. Dengan menggunakan GitHub, berkolaborasi antar anggota tim menjadi lebih mudah. GitHub adalah tools yang sangat populer karena mudah digunakan.

- Terdapat menu utama pada saat mengakses halaman GitHub yaitu, Explore Repository, Sign up, dan Sign in. Selain itu, ada juga fitur-fitur pendukung pada GitHub seperti:

- New Repository, digunakan membuat repository baru dengan jenis public & private.
- Import Repository, digunakan untuk mengambil/menyalin file proyek dari vendor lain seperti Subversion atau Mercurial ke dalam repository baru pada GitHub. Proses impor dilakukan dengan menggunakan link URL.
- Gist, digunakan untuk berbagi potongan kode, catatan, melakukan daftar, dan lainnya. Seperti halnya repositori, Anda dapat menyetel dan menyimpan Intisari Anda sebagai rahasia atau publik.
- GitHub Organization, digunakan untuk berkolaborasi bersama pada suatu organisasi misalnya untuk bisnis dengan sejumlah kelebihan misalnya banyak proyek sekaligus. Pemilik dan administrator dapat mengelola hak akses anggota ke suatu data atau proyek dengan fitur keamanan dan administratif yang canggih.
- GitHub Project, digunakan untuk mengatur dan memprioritaskan pekerjaan. Anda dapat membuat papan proyek (project board) untuk mengerjakan fitur tertentu, peta alur yang komprehensif (comprehensive roadmaps), atau bahkan merilis daftar periksa (release checklists). Dengan papan proyek, Anda memiliki fleksibilitas untuk membuat alur kerja khusus yang sesuai dengan kebutuhan Anda.

Selain itu, terdapat beberapa latihan yang telah kita lakukan dalam materi Git dan GitHub. Berikut di antaranya:

## Latihan Membuat Akun GitHub
Berikut beberapa tahapan yang bisa Anda lakukan untuk membuat akun GitHub:
Mengakses alamat https://github.com/signup. 
Melengkapi data-data yang diperlukan. 
Melakukan verifikasi pendaftaran menggunakan kode unik yang dikirimkan GitHub melalui email. 
Menambahkan dan memverifikasi email cadangan untuk mengelola akun GitHub (opsional).

Latihan Mengeksplorasi Proyek GitHub
Berikut beberapa tahapan yang bisa Anda lakukan untuk mengeksplorasi proyek GitHub:

- Melakukan pencarian proyek GitHub dengan menggunakan fitur Search. Pencarian proyek GitHub bertujuan untuk mendapatkan referensi repository saat mengerjakan proyek sendiri. 

- Menganalisis hasil pencarian tersebut seperti, jumlah pengunjung yang memonitor (watch), memberikan bintang (star), dan menyalin proyek repository ke repository pribadi (fork).

- Memberikan bintang hasil pencarian proyek repository agar dapat mengikuti perkembangannya. GitHub memiliki fitur stars (bintang) yang memudahkan Anda untuk menemukan repository atau topik yang Anda cari sebelumnya.

- Melihat kontributor dan kolaborator dari sebuah proyek repository. Setiap proyek repository memiliki kolaborator dan kontributor. 

## Latihan Mengenal GitHub Dashboard
Berikut beberapa tahapan yang bisa Anda lakukan untuk mengenal GitHub Dashboard:
- Melihat semua aktifitas yang dilakukan pada halaman GitHub dashboard, seperti mengikuti proyek repository, melakukan perubahan pada proyek GitHub, atau memberikan komentar/tanggapan di dalam repository. 
- Melihat bagian toolbar pada halaman GitHub dashboard. Dalam toolbar terdapat beberapa menu seperti:
  - Pull request untuk melihat semua aktivitas mengenai pekerjaan yang telah selesai dan tersimpan di dalam GitHub. 
  - Issues untuk melihat semua tanggapan atau komentar mengenai permasalahan yang kita dapat saat menggunakan repository milik orang lain. 
  - Marketplace untuk mencari dan memasang fitur tools pendukung yang disediakan oleh GitHub. Tools dalam marketplace akan membantu Anda dalam mengoptimalkan penggunaan GitHub di dalam proyek. 
  - Explore untuk melihat berbagai informasi atau berita terkini mengenai repository, topik, dan  trending di GitHub. 
  - Settings untuk melakukan perubahan profil seperti username, foto, serta informasi lainnya.

- Setiap proyek repository memiliki kolaborator dan kontributor. Seorang kolaborator merupakan anggota tim yang memiliki akses dalam sebuah repositori proyek (project repository). Akses ini tentunya bermacam-macam ya, ada yang dibatasi pada pekerjaan-pekerjaan tertentu, ada pula yang dapat melakukan semua pekerjaan dalam sebuah repository.

- Ketika Anda membuat sebuah repository menggunakan akun personal, maka secara otomatis akan menjadi seseorang owner repository dan memiliki akses penuh terhadap repository tersebut. Di sisi lain, ketika Anda mengundang orang lain menjadi kolaborator dalam repository tersebut, maka mereka akan dapat melakukan pull (read) dan push (write) pada repository tersebut.

- Namun, jika Anda menggunakan akun organisasi, GitHub menyediakan 5 tingkatan level (role) yang berbeda untuk seorang kolaborator, yakni read, triage, write, maintain, dan admin.
  - Seorang kolaborator dengan tingkatan read, biasanya hanya memiliki akses untuk membuka repository. Level ini direkomendasikan untuk orang non-coding (tim lain) yang ingin melihat atau berdiskusi mengenai proyek repository.
  - Seorang kolaborator dengan tingkatan write, biasanya digunakan oleh seorang developer atau pengembang untuk membuka, melakukan clone, dan melakukan push pada repository tersebut. Ia juga dapat mengelola issues dan pull request yang masuk.
  - Seorang kolabolator dengan tingkatan triage, biasanya digunakan oleh maintainer yang hanya dapat mengeloa issues dan pull request yang ada masuk ke dalam repository.
  - Seorang kolaborator dengan tingkatan maintain, biasanya digunakan oleh seorang project manager yang dapat mengelola beberapa pengaturan dalam repository. Ia juga dapat melakukan berbagai hal seseorang dengan tingkatan read.
  - Seorang kolaborator dengan tingkatan admin, biasanya digunakan oleh seseorang yang butuh mengakses secara penuh kepada repository. Ia dapat melakukan berbagai hal, termasuk mengundang kolaborator lain untuk bergabung dalam repository.

- Seorang kolaborator juga dapat berperan sebagai kontributor. Apa itu kontributor? Kontributor adalah siapa saja yang dapat melakukan commit atau menyimpan cuplikan perubahan ke dalam repository (git push). Akan tetapi, tidak semua kontributor dapat melakukan commit secara langsung. Ini disebabkan karena mereka tidak memiliki akses untuk melakukan push ke dalam repository tersebut (atau tidak berperan sebagai kolaborator). Sehingga mereka perlu melakukan pull request untuk melakukan commit pada repository orang lain.

- Di dalam GitHub terdapat sistem notifikasi untuk memberikan pembaruan informasi kepada Anda. Secara umum, Anda akan otomatis berlangganan pemberitahuan bila Anda memiliki:
 - Fitur Watch pada repository atau tim yang Anda ikuti dalam keadaan aktif
 - Menerima tanggapan Pull request atau membuat issues.
 - Melakukan Pull request, issue, atau membuat percakapan diskusi bersama tim.
 - Berlangganan secara manual dengan mengeklik Watch atau Subscribe.
 - Saat teman atau orang lain melakukan @mentioned terhadap nama GitHub Anda.
 Mengubah status, seperti dengan menutup masalah (issues) atau melakukan penggabungan pull request.
  - Anda menjadi anggota tim dan mendapatkan @mentioned oleh satu tim Anda.

- Setiap notifikasi yang masuk akan terlihat pada Inbox Notifications. Anda dapat menghentikan notifikasi dengan cara melakukan Unsubscribe pada menu Manage Notification.

- Selain mendapatkan notifikasi masuk langsung di dalam GitHub Dashboard, Anda juga akan mendapatkan notifikasi melalui email yang Anda gunakan sebagai akun GitHub. Pengaturan notifikasi email dapat dilakukan pada menu Setting Notifications. 
Dengan mengikuti pembelajaran Git dan GitHub ini, Anda diharapkan dapat mencoba mengimplementasikan semua materi ke dalam proyek yang sesungguhnya, serta dapat berkolaborasi bersama tim dengan menggunakan GitHub. Semangat!

