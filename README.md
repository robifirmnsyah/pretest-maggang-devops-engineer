# Pre-Test Bootcamp DevOps

## Knowledge Base

**1.	Apa yang anda ketahui tentang DevOps?**

DevOps merupakan sebuah prinsip developer untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien. DevOps juga bertujuan untuk meningkatkan kolaborasi antara tim development dan tim operation dari mulai perencanaan hingga aplikasi/fitur ter-deliver ke pengguna. Semua itu harus dilakukan secara otomatis dengan tujuan sebagai berikut. 
- Meningkatkan deployment frequency.
- Meningkatkan waktu pemasaran.
- Menurunkan tingkat kegagalan pada rilisan terbaru.
- Mempersingkat waktu perbaikan.
- Meningkatkan waktu pemulihan.

Alur berpikir yang dibentuk oleh DevOps adalah koordinasi antar tim yang dapat dilakukan dengan cara singkat sehingga tidak butuh banyak pertanyaan. Tim operation atau development cukup mengkonfigurasi beberapa komponen yang dibutuhkan melalui prosedur yang dibuat.

 **2.	Apa yang anda ketahui tentang Infrastructure?**
 
Infrastructure merupakan komponen dan sumber daya yang mendukung operasi dan fungsi sistem komputer dan jaringan. Hal tersebut mencakup hardware, software, SDM, serta prosedur yang diperlukan untuk menjalankan dan menjaga lingkungan IT. Dalam bidang DevOps, infrastruktur merujuk pada kombinasi alat, proses, praktik, dan lingkungan yang mendukung pengembangan perangkat lunak yang cepat, pengujian, pengiriman, dan operasional yang efisien.

**3.	Apa yang anda ketahui tentang server, sebutkan implementasi berserta contohnya?**

Server merupakan sebuah komputer atau perangkat keras yang digunakan untuk melayani permintaan, mengelola sumber daya dan memberikan layanan kepada klien dalam sebuah jaringan. Beberapa contoh implementasi dari server :
-	Web Server : digunakan untuk menyimpan dan menampilkan website kepada user melalui HTTP. Contohnya : Nginx, Apache HTTP Server.
-	Database Server : digunakan untuk menyimpan, mengelola, dan menyediakan akses data. Contohnya : MySQL, PostgreSQL.
-	File Server: digunakan untuk menyimpan dan membagikan file dalam jaringan. Ini memungkinkan pengguna untuk menyimpan dan mengakses file secara sentral. Contohnya : Windows File Server dan NFS (Network File System).
-	Print Server: digunakan untuk mengelola cetakan jaringan dan memungkinkan pengguna untuk mencetak dari berbagai perangkat dalam jaringan ke printer bersama. Contohnya : Windows Print Server, CUPS (Common Unix Printing System)
-	Proxy Server: digunakan untuk meneruskan permintaan dari klien ke server eksternal. Contohnya : Squid, HAProxy
-	DNS Server: DNS server menerjemahkan nama domain menjadi alamat IP, memungkinkan pengguna untuk mengakses situs web dengan menggunakan nama daripada angka IP. Contohnya: BIND (Berkeley Internet Name Domain)
-	Application Server: Application server menjalankan aplikasi bisnis dan menyediakan layanan kepada klien. Contohnya: Apache Tomcat
  
**4.	Mengapa server dibutuhkan dalam pengembangan/development suatu software?**

Penggunaan server dalam pengembangan software membantu memastikan bahwa aplikasi yang dikembangkan berjalan sebagaimana diharapkan ketika digunakan di dunia nyata. Server ini bermanfaat dalam berbagai hal seperti pengujian, kolaborasi, manajemen basis data, testing, keamanan, dan pengembangan berbasis jaringan, yang semuanya penting dalam menghasilkan aplikasi yang berkualitas tinggi. Secara keseluruhan, server pengembangan membantu tim pengembangan menciptakan perangkat lunak yang lebih stabil, aman, dan sesuai dengan kebutuhan pengguna.



**5.	Apa yang anda ketahui mengenai Virtualisasi dan Conetainer?**

- Virtualisasi adalah proses menciptakan versi virtual dari sumber daya fisik, seperti server, jaringan, dan penyimpanan. Ini memungkinkan satu fisik server (host) untuk menjalankan beberapa mesin virtual (VM) yang berjalan secara independen. Setiap VM memiliki sistem operasi dan aplikasi sendiri, sehingga dapat melayani fungsi yang berbeda. Virtualisasi membantu mengoptimalkan penggunaan perangkat keras dan mengisolasi lingkungan, sehingga mengurangi biaya dan meningkatkan efisiensi. VirtualBox merupakan salah satu contoh dari teknologi virtualisasi. 
- Containerization adalah teknologi yang memungkinkan aplikasi dan semua dependensinya (seperti perpustakaan, konfigurasi, dan lingkungan) dibungkus dalam wadah yang terisolasi. Ini memungkinkan aplikasi berjalan konsisten di berbagai lingkungan, baik di lingkungan pengembangan, tes, atau produksi. Teknologi kontainer paling terkenal adalah Docker.

**6.	Mengapa teknologi container saat ini sangat populer?**

Berikut merupakan beberapa alasan mengapa teknologi container bisa sangat populer: 
-	Skalabilitas: Kontainer memungkinkan aplikasi untuk dikloning dengan cepat dan diperluas secara horizontal. Dengan orkestrasi yang tepat (seperti Kubernetes), aplikasi dapat dijalankan pada banyak kontainer dengan otomatisasi dan manajemen yang mudah.
-	Efisiensi Sumber Daya: Kontainer berbagi kernel host dan dapat dijalankan dalam satu mesin fisik. Ini membuatnya lebih ringan daripada mesin virtual tradisional dan memungkinkan pemanfaatan sumber daya yang lebih efisien.
-	Konsistensi Lingkungan: lingkungan aplikasi terisolasi dan konsisten. Ini mengurangi masalah yang terkait dengan perbedaan lingkungan antara pengembangan, pengujian, dan produksi.
-	Microservice: memungkinkan setiap layanan atau microservice berjalan dalam kontainer tersendiri, memfasilitasi skalabilitas dan pengelolaan.
-	Dukungan Cloud: memungkinkan kita mengadopsi strategi cloud-native dan menjalankan aplikasi dalam lingkungan yang dioptimalkan untuk kontainer.
-	Automasi: memungkinkan otomatisasi tugas-tugas operasional, pengelolaan skala, dan penanganan kerentanan dengan mudah.



**7.	Apa yang anda ketahui tentang Orchestration Container System?**

Sistem orkestrasi kontainer adalah platform atau perangkat lunak yang digunakan untuk mengelola dan mengotomatisasi operasi pada lingkungan yang menjalankan kontainer. Salah satu tujuan utama dari orkestrasi container system adalah untuk mengurangi kompleksitas dalam mengelola sejumlah besar kontainer dan memudahkan tugas yang melibatkan penjadwalan, peningkatan, penerapan, pemantauan, dan pengaturan lalu lintas. Beberapa platform orkestrasi container terkenal termasuk Kubernetes, Docker Swarm, dan Apache Mesos. Platform orkestrasi container system membantu organisasi memaksimalkan manfaat dari teknologi kontainer dengan memastikan aplikasi berjalan dengan efisien, dapat diandalkan, dan mudah dikelola. Sistem ini memungkinkan kita untuk mengendalikan bagaimana kontainer dikerjakan, berkomunikasi, dikoordinasikan, dan diatur di dalam infrastruktur yang lebih besar.



## Task 1 (Virtualization)

- Buatlah sebuah VM dengan kententuan
  - username: `<github_user>` contoh `dimasm93`
  - hostname: `<email_without_at>` contoh `dimas.tabeldata.com`
  - OS: `ubuntu-20.04` atau `centos-7`
- Install webserver `nginx`
- Buatlah web profile temen-temen kemudian deploy ke webserver nginx tersebut yang telah di deploy
  
(kirimkan hasil screenshotnya simpan dalam folder `screenshot` dengan nama `task1.png`)

## Task 2 (Container)

Jika saya memiliki architecture seperti berikut:

![container-apps](docs/images/01-container.png)

Dimana berikut adalah configurasi docker image:

1. Backend container
  - image: `dimmaryanto93/udemy-springboot-app:latest`
  - port: `8080`
  - env: 
    - `DATABASE_HOST`: `<ip-domain-db>`
    - `DATABASE_PORT`: `5432` 
    - `DATABASE_NAME`: `<db-name>`
    - `DATABASE_PASSWORD`: `<db-password>`
    - `APPLICATION_PORT`: `8080`
  need:
    - Database PostgreSQL v14.2
2. Frontend container
  - image: `dimmaryanto93/udemy-angular-app:latest`
  - port: `80`
  - env:
    - `APPLICATION_PORT`: `80`
    - `NGINX_ROOT_DOCUMENT`: `/var/www/html`
    - `BACKEND_HOST`: `<ip-backend-apps>`
    - `BACKEND_PORT`: `<port-backend-apps>`
    - `BACKEND_CONTEXT_PATH`: `/`
  - need:
    - Backend container

Silahkan buat docker-compose filenya, kemudian simpan dalam folder `tasks` dengan nama `docker-compose.yaml`

