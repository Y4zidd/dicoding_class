## Management Identitas dan Akses

Cloud  Identity and Access Management (IAM) adalah sistem yang dibangun untuk mengelola hak akses pengguna dalam  sumber daya di GCP. Pengelolaan ini ditujukan untuk mengidentifikasi “siapa” yang dapat melakukan “apa” pada sumber daya “mana”.

Cloud IAM akan mengatur tiga komponen penting yakni:

 - 1. Identity: Pengelolaan “siapa” dalam hal ini akun mana yang dapat mengelola sumber daya.
 - 2. Role: Kumpulan hak akses (permission) yang bisa kita tetapkan (assign) pada sebuah akun.
 - 3. Resource: Merujuk pada sumber daya yang bisa diatur berdasarkan rol yang dimiliki oleh sebuah akun.
     Banyak perusahaan menggunakan prinsip least-privilege, di mana setiap orang dalam organisasi Anda diberikan hak akses seminimal mungkin yang diperlukan untuk melakukan pekerjaan mereka.

Penggunaan roles pada praktik terbaiknya adalah memberikan peran secara terperinci (fine-grained) sesuai dengan hak akses yang akan digunakan. Anda disarankan menggunakan predefined roles atau custom roles agar penetapan peran tidak terlalu luas seperti pada beberapa peran yang dimiliki oleh basic roles.

*Permission* adalah perizinan yang perlu kita miliki agar dapat mengakses dan mengelola berbagai resource di GCP.

*Policy*, Cloud IAM memungkinkan Anda menetapkan kebijakan (policy) di semua level hierarki resources Google Cloud yang terdiri dari organization, folder, project dan resources. Di mana kebijakan berisi sekumpulan peran dan anggota di dalamnya. Sumber daya di GCP akan mewarisi policy dari induknya berdasarkan hierarki.

*Members* mempresentasikan akun pengguna dan memungkinkan kita untuk memberikan roles kepadanya.
Terdapat lima jenis members, yakni:

 - 1. Google Accounts, akun jenis ini merepresentasikan developer, administrator atau siapa pun orang yang  berinteraksi di lingkungan Google Cloud menggunakan akun Google-nya. Setiap alamat email yang terasosiasi dengan akun Google bisa menjadi Identity (identitas). 

 - 2. Service Accounts, service account adalah sebuah akun yang ditetapkan pada sebuah resource. Service account tidak memiliki password. Fungsi dari akun ini adalah untuk memberikan hak akses pada sebuah resource agar satu resource dapat mengakses resource lainnya, seperti interaksi antaraplikasi, layanan, ataupun mesin virtual.

 - 3. Google Group, cara pengelompokan berbagai akun yang terdiri dari kumpulan akun Google atau service account. 

 - 4. Google Workspace Domains, domain custom yang bisa Anda atur sebagai identitas email domain organisasi atau perusahaan dalam menggunakan berbagai layanan yang tersedia,seperti pengelolaan email organisasi, penyimpanan Google Drive, dan berbagai aplikasi produktivitas seperti Docs, Spreadsheet, ataupun Slides.

 - 5. Cloud Identity Domains, solusi Identity as a Service (IDaaS) yang mengelola pengguna dan grup secara t  erpusat. Anda dapat mengonfigurasi Cloud Identity untuk menggabungkan identitas antara Google dan penyedia identitas lainnya, seperti Active Directory dan Azure Active Directory.

## Enkripsi
*Enkripsi* (Encryption) adalah metode mengubah sebuah informasi atau data dari plaintext (teks biasa yang terbaca manusia) menjadi ciphertext (teks yang tidak bisa dibaca dan dimengerti manusia) menggunakan algoritma tertentu sehingga metode ini dapat mencegah pihak yang tidak berwenang mengetahui informasi yang Anda kirim, terima, ataupun simpan.

*Dekripsi* (Decryption) adalah metode yang mengubah informasi atau data dari ciphertext menjadi plaintext.

Dalam menutup maupun membuka informasi, kita membutuhkan kunci. Biasanya, terdapat dua sistem penguncian brankas ini, yakni:

 - 1. Symmetric Cipher, yakni enkripsi yang menggunakan single key atau kunci yang sama. Sehingga client maupun server memiliki kunci yang sama untuk mengenkripsi dan mendekripsi informasi.

 - 2. Asymmetric Cipher, yakni enkripsi yang menggunakan dua kunci yang berbeda terdiri dari private key dan public key dalam proses enkripsi dan dekripsinya.

Intinya, kita harus memiliki kunci (key) untuk mengamankan data dan melihat informasi kita.

Di bawah ini adalah ringkasan opsi enkripsi yang tersedia untuk Anda dengan studi kasus pada layanan Google Cloud Storage: 

- Enkripsi sisi server (server-side encryption)
Saat Anda mengunggah data ke Cloud Storage, Google akan mengenkripsinya terlebih dahulu sebelum data tersebut ditulis ke disk. Mekanisme seperti ini membuat Google tidak bisa melihat isi konten dari data Anda. Inilah yang disebut sebagai enkripsi di sisi server atau server-side encryption.
Google Cloud menyediakan layanan tambahan untuk meningkatkan keamanan kunci enkripsi untuk berbagai layanan Anda. Beberapa diantaranya sebagai berikut:

- Customer-supplied encryption keys (CSEK)
Kunci enkripsi yang disediakan oleh pelanggan. Anda dapat membuat dan mengelola kunci enkripsi secara mandiri. Kunci ini bertindak sebagai lapisan enkripsi tambahan di atas enkripsi standar dari Cloud Storage.

- Customer-managed encryption keys (CMEK)
Pada mekanisme ini, Anda mengelola kunci enkripsi yang dibuat untuk Anda dan disimpan di Cloud Key Management Service.

- Enkripsi sisi klien (client-side encryption)
Enkripsi yang terjadi sebelum data dikirim ke Cloud Storage. Jadi, data tersebut dienkripsi terlebih dahulu di sisi klien sebelum diunggah ke Cloud Storage. Data tersebut juga mengalami enkripsi tambahan karena adanya enkripsi di sisi server.

- Google Cloud menawarkan solusi pengelolaan kunci enkripsi ini dengan berbagai pilihan yang dapat disesuaikan dengan kebutuhan Anda. Google Cloud memiliki layanan untuk untuk menyimpan dan mengelola encryption keys bernama Cloud Key Management Service (Cloud KMS).

- Layanan Cloud Key Management (KMS) memungkinkan Anda membuat, mengimpor, dan mengelola kunci kriptografi dan melakukan operasi kriptografi dalam satu layanan cloud terpusat. Anda dapat menggunakan kunci dan melakukan operasi kriptografi dengan menggunakan Cloud KMS secara langsung, atau dengan menggunakan integrasi Customer-Managed Encryption Keys (CMEK) dalam layanan Google Cloud lainnya.

## Compliance
Compliance (kepatuhan) adalah sebuah upaya yang dilakukan oleh suatu usaha untuk memenuhi peraturan hukum (regulasi), prosedur, dan standar yang ada pada layanan yang disediakan ke masyarakat luas di suatu wilayah. 

Kepatuhan atas segala peraturan yang ada di wilayah berwenang di mana bisnis Anda berada itu sangat penting bagi sebuah bisnis karena

kepatuhan bersifat wajib sehingga harus dilakukan;
menunjukkan kredibilitas sebuah bisnis;
menciptakan kepercayaan kepada semua pemangku kepentingan; dan
membantu upaya pengelolaan risiko untuk bisnis Anda.
Berikut beberapa contoh compliance yang harus dipatuhi oleh berbagai pelaku bisnis, di antaranya:

- General Data Protection Regulation (GDPR)
  GDPR adalah peraturan yang mengatur perlindungan data pribadi pengguna yang ada di seluruh negara Uni Eropa (EU). Pelaku bisnis yang memiliki pengguna di wilayah EU tidak boleh semena-mena mengolah data dalam bentuk apa pun tanpa seizin pemegang regulasi (regulator).

- Health Insurance Portability and Accountability Act (HIPAA)
  Peraturan ini mewajibkan pelaku bisnis untuk melindungi informasi kesehatan pasien seperti nama, alamat, riwayat sakit, informasi pembayaran dan lain-lain yang tidak boleh dipublikasikan ke publik atau diakses oleh pihak yang tidak berwenang di negara Amerika Serikat (AS).

- Payment Card Industry Data Security (PCI-DS)
  Semua pihak baik pengguna maupun pelaku bisnis yang menyimpan, memproses, atau meneruskan data, termasuk lembaga keuangan, merchant, serta penyedia layanan wajib mematuhi Standar Keamanan Data Industri Kartu Pembayaran (Payment Card Industry Data Security).