# pengenalan Cloud Computing

Client-Server merupakan konsep arsitektur perangkat lunak atau software yang menghubungkan dua objek berupa sistem client dan sistem server yang saling berkomunikasi, baik melalui jaringan komputer maupun satu komputer yang sama. 

Client merupakan pengguna yang ingin mengakses aplikasi Anda.

Server akan memberikan informasi yang dibutuhkan oleh client dan menyediakan pengelolaan aplikasi, data, serta keamanan data. 

Data center adalah tempat di mana Anda mengelola server.

infrastruktur on-premise adalah jenis infrastruktur di mana Anda memiliki dan mengelola server fisik sendiri. Anda bertanggung jawab penuh terhadap kemampuan komputasi dan konfigurasi server, seperti seberapa banyak CPU, RAM, dan hard drive (penyimpanan file) yang dibutuhkan.

Cloud computing (komputasi awan) adalah layanan yang menyediakan sumber daya komputasi berdasarkan permintaan melalui internet. Ini dapat mempersingkat berbagai kebutuhan kita untuk mendapatkan, mengonfigurasi, dan mengelola sumber daya sendiri. Anda hanya membayar layanan yang sedang digunakan.

Dibandingkan dengan on-premise data center yang harus membeli dan mengonfigurasi server terlebih dahulu agar dapat diakses oleh pengguna, cloud computing mengatasi masalah tersebut dengan menawarkan sumber daya komputasi sebagai layanan yang dapat disesuaikan kapasitasnya (scalable). Bahkan, Anda dapat menyesuaikan sumber daya sesuai permintaan.

Keuntungan menggunakan cloud computing antara lain: 

- Fleksibel
- Efisien
- Menawarkan Strategi Bisnis yang Bernilai Lebih
- Aman
- Hemat Biaya

## Model Layanan Cloud

- Infrastructure as a Service (IaaS)
  Pada IaaS, cloud provider memberikan fleksibilitas untuk penggunanya dalam menyewa infrastruktur yang dibutuhkan, seperti server, jaringan, hingga storage (ruang penyimpanan file). Model layanan seperti ini sangat memudahkan pengguna dalam memenuhi kebutuhan infrastruktur karena kemampuan skalabilitas yang ditawarkan hampir tidak terbatas dan kita hanya perlu membayar sesuai apa yang digunakan (pay as you go).

- Platform as a Service (PaaS)
  PaaS merupakan model layanan cloud yang akan menyesuaikan sumber daya yang tepat untuk aplikasi Anda. Sehingga, Anda tidak perlu lagi memikirkan soal infrastruktur. Layanan PaaS bahkan bisa melakukan scaling to zero (penyesuaian kapasitas sampai tidak ada instance yang berjalan) sehingga Anda tidak perlu membayar apa pun ketika tidak ada permintaan traffic ke aplikasi Anda.

- Software as a Service (SaaS)
  SaaS adalah bentuk layanan cloud yang disediakan dalam bentuk software atau perangkat lunak yang dijalankan dan diatur oleh cloud provider. SaaS memberikan kemudahan kepada Anda untuk dapat memanfaatkan sumber daya perangkat lunak dengan cara berlangganan.

Anda tidak perlu memikirkan bagaimana layanannya dikelola atau infrastrukturnya diatur, Anda hanya perlu berlangganan dan tahu bagaimana cara menggunakan software tersebut.


- Model Pembagian Tanggung Jawab
Ketika kita menggunakan layanan cloud, Anda akan berbagi tanggung jawab dengan penyedia layanan cloud tergantung model layanan yang digunakan.

- Google sebagai penyedia layanan Google Cloud Platform bertanggung jawab terhadap pengelolaan infrastruktur, seperti keamanan, ketersediaan (Availability), dan keandalan (Reliability); sedangkan pengguna bertanggung jawab dalam mengamankan data yang akan disimpan. Google sebagai provider telah menyediakan praktik terbaik (best practices) bagaimana cara data Anda disimpan di GCP dengan baik dan benar. Jadi, Anda sebagai pengguna memiliki andil besar dalam pengelolaan aplikasi ataupun data yang disimpan.

## CapEx vs OpEx
Capital Expenditure alias pembelanjaan modal adalah pengeluaran untuk membeli atau memiliki aset agar bisnis dapat berjalan dengan baik. Aset seperti server, perangkat jaringan, dan peralatan komputer merupakan contoh dari CapEx yang akan memiliki nilai yang semakin menurun (depresiasi) seiring dengan umur dari aset tersebut.

Di sisi lain, Operating Expenditure alias pembelanjaan operasional adalah pengeluaran yang dilakukan oleh sebuah bisnis untuk memenuhi kebutuhan operasional seperti gaji karyawan, listrik, pajak, dan hal-hal lainnya yang merupakan pengeluaran rutin atau bisa dikategorikan sebagai pengeluaran sehari-hari sebuah bisnis.

Jika OpEx diadopsi ke dalam bisnis, pengeluaran perusahaan menjadi lebih mudah diprediksi dan dialokasikan karena Anda tidak perlu biaya di awal untuk membeli aset, melainkan hanya perlu menyewa layanan atau produk yang ingin dipakai. Anda hanya akan ditagih sesuai dengan layanan yang digunakan.

## Estimasi Biaya
Anda dapat mengestimasi biaya layanan di GCP menggunakan Pricing Calculator yang merupakan tools dari GCP yang berfungsi untuk mengestimasi total biaya (total cost) yang  dikeluarkan oleh pengguna untuk menggunakan layanan tertentu.

Total Cost Ownership (TCO) adalah total biaya untuk memiliki dan menggunakan sebuah aset selama masa penggunaan yang diharapkan. 

Anda dapat menggunakan tools Pricing Calculator untuk mengkaji total biaya yang akan dikeluarkan untuk aplikasi bisnis sehingga Anda dapat melakukan perbandingan biaya untuk setiap layanan dan memilih mana yang tepat sesuai kebutuhan Anda.

## Hierarki Sumber Daya pada Google Cloud Platform
- Hierarki sumber daya GCP jika diurutkan dari atas ke bawah maka urutannya adalah Organization -> Folders -> Projects -> Resources.
- Semakin tinggi hierarki, maka akan semakin memiliki kontrol terhadap resource yang berada di bawahnya.
- Semua sumber daya alias Resources yang Anda gunakan, baik itu mesin virtual, storage, database, atau apa pun di GCP, mereka dikelompokkan ke dalam Projects. 
- Jika Anda memiliki beberapa projects dan ingin mengelompokkannya ke satu tempat, Anda dapat menggunakan Folders.
- Project yang berada di dalam suatu Folder akan mewarisi policy dari Folder tersebut.
- Semua Folders dan Projects yang digunakan oleh perusahaan Anda dapat disatukan di bawah Organization.
- Baik Projects, Folders, maupun Organization adalah tempat-tempat di mana policy (kebijakan) dapat didefinisikan. 
- Policy dalam lingkungan GCP akan diwariskan ke bawah dalam hierarki.