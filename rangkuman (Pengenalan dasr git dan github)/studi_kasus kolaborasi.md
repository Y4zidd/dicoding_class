# Rangkuman Studi Kasus Kolaborasi dengan Tim

- GitHub memungkinkan kita mengembangkan project atau aplikasi dengan banyak orang dalam waktu yang bersamaan.

- Ketika Anda memiliki akses untuk melakukan perubahan dalam sebuah repository, Anda tidak perlu melakukan forking atau penyalinan repository orang/organisasi lain ke repository pribadi. Sehingga cukup membuat branch baru untuk menampung perubahan yang akan dilakukan, kemudian lakukan Pull Request pada branch tujuan.

- Lalu jika Anda tidak memiliki akses pada repository orang/organisasi lain, maka dapat mengikuti langkah-langkah berikut:
 - Sebagai seorang kontributor, Anda perlu melakukan forking atau menyalin repository tersebut.
 - Melakukan perubahan pada hasil salinan repository (forked repository) dan menyimpannya menggunakan commit.
 - Melakukan pull request / meminta izin kepada kolaborator untuk mengimplementasikan perubahan dilakukan.
 - Sebagai seorang kolaborator, mereka akan memastikan perubahan yang Anda lakukan sesuai dengan seharusnya. Jika tidak, mereka bisa memberi saran baik melalui forum diskusi atau langsung pada baris kode. Proses ini dinamakan code review.
 - Jika perubahan sudah sesuai, kolaborator akan menyetujui (approve) pull request yang telah Anda lakukan. Sehingga perubahan yang dilakukan sudah ada dalam repository utama.

- Dengan melakukan PR, kita dapat meninjau terlebih dahulu apakah kode yang akan diimplementasikan sudah sesuai atau belum. Sehingga kita bisa menghindari terjadinya bug atau masalah. Selain itu, Anda juga bisa berdiskusi dengan rekan tim atau orang lain dalam PR tersebut.

- Terdapat beberapa kolom yang bisa Anda isi pada halaman pull-request dalam GitHub.

 - Message Merge : Digunakan untuk memberikan pesan singkat mengenai PR yang dilakukan.
 - Description Commit : Digunakan untuk memberikan informasi yang lebih detail mengenai PR yang dilakukan.
 - Reviewer : Digunakan untuk meminta orang lain untuk mereviu perubahan yang telah dilakukan.
 - Assignees : Digunakan untuk menginformasikan siapa yang memberikan tugas untuk melakukan PR.
 - Label : Digunakan untuk memberikan kategori pada sebuah PR, contohnya pembetulan suatu masalah (bug), penambahan fitur (enhancement), penambahan dokumentasi (documentation), atau yang lainnya.

- Ketika berkolaborasi, kita bisa mengubah satu file yang sama dengan orang lain. Namun, sebelum melakukan PR Anda perlu memastikan kembali apa yang diubah tidak menimbulkan conflict. Conflict terjadi biasa ketika Anda menggabungkan branch satu ke branch lainnya terdapat masalah dalam satu baris yang sama pada suatu file.

- Jika terjadi conflict, Anda perlu memilih bagian mana yang dipertahankan. Anda dapat memilih apakah mempertahankan teks/kode yang ada dalam PR terbaru, atau menggunakan teks/kode dalam repository utama.