# Rangkuman Git Branches
Sejauh ini kita telah banyak mempelajari peran penting git branch beserta fungsi-fungsinya. Selain itu kita telah melakukan latihan mulai dari membuat branch baru di GitHub, hingga mengatasi conflict ketika melakukan merge pada repository. Berikut beberapa point materi Git Branch:

- Branch bisa disebut juga percabangan. Kita dapat meminimalisir kesalahan dalam server atau aplikasi yang berjalan sehingga mempermudah developer untuk melakukan bug fixing, hingga pembuatan fitur baru di dalam repository.

- Berikut adalah alasan dari penggunaan Git Branch:

 - Tanpa git branch pekerjaan akan menjadi rumit. Ketika fitur yang telah selesai masih menjadi satu dengan fitur lain dan kemudian dijalankan, maka akan terdapat banyak bug atau kesalahan karena ada pekerjaan yang tumpang tindih.

 - Penambahan branch baru dapat meminimalisir kesalahan pada aplikasi utama.
 
 - Git branch juga berfungsi untuk mempermudah dalam berkolaborasi dalam tim. Selain itu, membuat pekerjaan menjadi lebih teratur karena setiap pekerjaan tidak saling tumpang tindih.

- Ketika pembuatan branch baru, kita memerlukan source (sumber) untuk pengembangan aplikasi, sehingga kita perlu mengambil sumbernya berdasarkan branch utama yang biasa disebut main/master.

- Selain itu kita juga telah belajar bagaimana melakukan perpindahan branch atau bisa disebut juga git checkout pada GitHub. Perintah ini berfungsi untuk membuka commit tertentu secara sementara serta membuka branch. Ketika berpindah dari branch satu ke branch lainnya, history commit dari branch tersebut akan menyesuaikan.

- Kemudian kita mempelajari merge, yang berarti penggabungan dua branch menjadi satu. Anda dapat menggunakan git merge untuk menggabungkan setiap branch yang dengan commit yang berbeda-beda menjadi satu kesatuan baru di dalam branch. Selain itu, git merge juga dapat digunakan sebagai penggabungan setiap fitur yang telah dikerjakan. Ketika salah satu branch tidak ada kesalahan, Anda dapat melakukan pull request untuk menggabungkannya ke branch utama.

- Ketika melakukan penggabungan dua branch atau merge, kita harus teliti. Sebab, jika kita melakukan kesalahan, bisa saja kita menghapus branch secara tidak sengaja. Akibatnya kita perlu melakukan pembuatan ulang branch. Oleh karena itu, perlu kehati-hatian yang lebih pada saat melakukan merge agar branch yang telah dibuat tidak terhapus. Selain itu, ketika tidak teliti juga dapat mengakibatkan conflict atau terjadinya kesalahan. Conflict terjadi karena Anda tidak memeriksa secara seksama branch utama dan sumber branch sebelum melakukan merge.

- Ketika terjadi conflict, Anda tidak perlu khawatir. Biasanya akan ada indikator ketika terjadi conflict, yakni tulisan "this branch has conflict that must be resolved". Kemudian Anda akan disuguhkan code yang menjadi penyebab conflict tersebut. Anda dapat melihat batasannya conflict dengan simbol = (sama dengan). Anda dapat mempertahankan kode/data dari ke dua branch. Setelah merasa yakin dengan kode/data yang ditulis, Anda dapat mengeklik bagian mark as resolved. Kemudian indikator conflict akan hilang. Saatnya untuk menggabungkan kedua branch dengan merge.

- Demikian hal yang dapat disampaikan dalam pada materi git branch, mulai pembuatan branch hingga mengatasi conflict pada saat merge. Mengetahui git branch menjadi hal wajib ketika Anda melakukan pengembangan aplikasi secara teratur. Tujuannya untuk memudahkan dalam mengatur pengembangan aplikasi kompleks yang telah berjalan maupun baru, sehingga Anda tidak akan mengalami kesulitan. Jika Anda masih belum paham tentang materi git branch, silakan baca-baca ulang materi dan kerjakan kembali latihan yang ada ya. Selamat belajar!