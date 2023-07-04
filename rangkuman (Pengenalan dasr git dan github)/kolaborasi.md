# Rangkuman Kolaborasi dengan Tim

Pada rangkuman ini akan mengulas kembali apa saja yang telah dipelajari pada materi kolaborasi dengan tim. Berikut poin-poinnya:

- Kolaborasi adalah proses dua orang atau lebih, entitas atau organisasi yang bekerja sama untuk menyelesaikan tugas atau mencapai suatu tujuan. Sebagian besar kolaborasi membutuhkan kepemimpinan, meskipun bentuk kepemimpinan dapat bersifat sosial dalam kelompok yang terdesentralisasi dan egaliter (sederajat).
- Fitur kolaborasi ini dapat Anda temukan pada GitHub dengan menambahkan akun lainnya (kolaborator) ke dalam repository yang tersimpan.
- Di dalam GitHub sendiri terdapat dua cara kolaborasi bersama tim yang sering digunakan:
 - Repository Organisasi: Pemilik organisasi dapat menambahkan kolaborator dengan tingkat izin yang berbeda untuk berbagai repository.
 - Repository Pribadi: Pemilik repository dapat menambahkan kolaborator dengan akses read & write untuk satu repository.

- Fork adalah proses menyalin proyek repository orang lain ke repository pribadi. Fork bertindak sebagai jembatan antara repositori asli (original repository) dan repositori salinan (fork repository). Anda dapat menawarkan perubahan yang dilakukan pada repositori salinan ke repositori asli untuk membantu membuat proyek orang lain lebih baik dengan melakukan pull request.

- Squash bertujuan untuk membuat riwayat commit yang lebih ramping dalam repository. Pada dasarnya setiap commit akan membantu untuk melihat setiap perubahan yang telah dilakukan, tetapi tak semua commit  selalu menjadi hal yang penting untuk disimpan dalam riwayat Git. Contohnya ketika melakukan beberapa perubahan pada formating (perubahan spasi, titik, koma). Jika Anda menggabungkan beberapa commit ini menjadi satu commit, perubahan yang dilakukan menjadi terlihat lebih jelas terlihat, serta menjadi lebih fokus pada tujuan dari commit tersebut.

- Untuk melakukan squashing dalam GitHub, Anda dapat menggunakan Squash & Merge sewaktu melakukan pull request.
Network graph dalam GitHub digunakan untuk melihat berbagai alur dari riwayat commit sebuah repository.
Network Graph dalam GitHub hanya tersedia secara gratis untuk repository publik dengan akun pribadi dan akun organisasi. Sedangkan untuk repository private dapat digunakan secara berbayar melalui GitHub Pro, GitHub Team, GitHub Enterprise Cloud, dan GitHub Enterprise Server. Untuk informasi lebih lanjut, lihat " Tentang grafik repositori " dan " Produk GitHub ."
- Network graph semua commit yang dilakukan akan terlihat dalam bentuk jalur history. History ini terdiri dari kumpulan titik/dot yang mewakili commit dan pull request yang telah dilakukan.
- Code reviews bertujuan untuk  mengomentari perubahan, menyetujui perubahan, atau meminta perubahan lebih lanjut sebelum pull request digabungkan.
 - Berikut beberapa aspek yang dapat digunakan sebagai acuan dalam melakukan ulasan kode/code reviews:
  - Kode dirancang dengan baik.
  - Fungsionalitasnya dapat berjalan dengan baik.
  - Setiap perubahan yang dilakukan masuk akal dan terlihat bagus.
  - Kodenya tidak lebih kompleks dari yang seharusnya.
  - Developer mengimplementasikan hal-hal yang diperlukan saat ini saja. Bukan menyediakan kode untuk masa depan, tetapi tidak digunakan saat ini.
  - Kode memiliki unit test (pengujian unit) yang sesuai.
  - Pengujian dirancang dengan baik.
  - Pengembang menggunakan nama yang jelas untuk segala penamaan.
  - Komentar yang ditambahkan jelas dan bermanfaat. Selain itu komentar ditujukan untuk menjelaskan kode apa yang ditulis beserta alasannya.
  - Kode telah didokumentasikan dengan tepat.
  - Kode ditulis sesuai dengan panduan (style guideline) yang telah disepakati.

- Code review dilakukan ketika anggota tim/kontributor melakukan perubahan dan melakukan pull request.

- Selain mempelajari teori pada modul ini terdapat latihan-latihan yang telah dilakukan diantaranya yaitu;
  - Latihan Berkolaborasi dengan Tim: Mengajarkan bagaimana menambahkan anggota tim di dalam repository agar dapat saling berkolaborasi. Melakukan verifikasi email setelah pengelola repository mengundang sebagai kolaborator atau salah satu anggota tim kolaborasi. Kemudian melakukan melakukan perubahan dengan membuat branch baru dan menggabungkannya ke branch utama menggunakan pull request dan merge.
  - Latihan Berkolaborasi pada Public Repository: Mengajarkan bagaimana menyalin repository orang/organisasi lain dan kemudian menyimpannya ke dalam repository pribadi. Lalu melakukan perubahan pada repository salinan dan dilanjutkan dengan melakukan pull request agar perubahan yang dilakukan dapat diimplementasikan ke dalam repositori asli (original repository).
  - Latihan Revert : Mengajarkan bagaimana mengembalikan perubahan/commit yang telah dilakukan. Salah satu keuntungan menggunakan Git revert, yakni mampu menargetkan commit pada titik yang diinginkan dalam riwayat commit.
  - Latihan Squashing Changes : Mengajarkan bagaimana menggabungkan atau merekap beberapa commit menjadi satu. Kemudian menggunakan fitur Squash and Merge untuk mengirim rekap commit tersebut ke dalam branch utama (base branch). Serta melihat jalur history commit dan pull request yang telah dilakukan melalui fitur Network graph.
  - Latihan Code Review: Mengajarkan bagaimana menggunakan fitur code review dalam GitHub, seperti memberikan ulasan kode pada permintaan pull request dari anggota tim (kontributor). Serta mengirim hasil reviews yang telah dilakukan dengan memberikan status pesan reviews seperti:
    - Comment: memberikan umpan balik secara langsung tanpa menyetujui perubahan atau meminta perubahan tambahan.
    - Approve: mengirimkan umpan balik dan menyetujui penggabungan perubahan yang diusulkan dalam pull request.  
    - Request changes: mengirimkan umpan balik perbaikan yang harus ditangani sebelum pull request dapat di-merge.

Dengan mempelajari setiap materi yang ada, diharapkan Anda akan dapat memahami bagaimana berkolaborasi bersama tim, serta menghadirkan produk atau aplikasi yang berkualitas. Jika Anda masih bingung mengenai kolaborasi, kami sarankan untuk mencoba setiap latihan yang ada ya. Semangat!