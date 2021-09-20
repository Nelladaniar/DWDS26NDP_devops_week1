
Project Week 1

PT. HIDAYATULLAH GLOBAL AMARTA
    

Salah satu perusahaan start-up dibidang e-commerce fashion yang berpusat di Jakarta Timur dengan nama HIMALL, menyediakan berbagai 
macam pakaian kekinian . 10 tahun lama nya start-up ini berpusat di bidang fashion. Seiring berjalannya waktu semakin banyak nya pengunjung di Website ,
membuat website HIMALL tidak stabil apalagi saat harbolnas Aplikasi menjadi sangat lamban , sulit untuk dipahami dan di lakukan perubahan . 
Semakin lama tim semakin banyak dikarenakan seringnya website menjadi tidak stabil sehingga menargetkan developer yang baru bergabung ke dalam 
tim untuk bisa membuat tampilan website lebih stabil , kemudian para investor juga menyarankan untuk mengganti arsitektur nya dari Monolithic 
menggunakan Microservices.

Dengan saran tersebut dan masalah yang sering muncul dengan menggunakan monolithic . Tim developer ingin mencoba mengImplemetasikan arsitektur
Microservices sehingga HIMALL membutuhkan Seorang Devops yang handal. Dengan adanya Devops HIMALL bisa mengupdate fiture dengan mudah, feedback dan
mudah dimonitor. Kaamil seorang Devops yang ingin membuat culture di Start-up e-commerce fashion tersebut. DevOps merupakan singkatan daari Development
dan Operation. Dimana DEVOPS adalah seorang profesional IT yang bertujuan memadukan proses development , deployment dan integrasi ke dalam suatu proses 
berkelanjutan. DevOps singkatan dari development dan operations , Divisi yang bekerja sama dengan devops adalah divisi operations yang mempunyai tujuan 
untuk mengetahui gambaran proses bisnis yang diharapkan . devops juga sangat menguasai software development life cycle ( SLDC ). Pola pikir yang dibentuk 
oleh DevOps adalah kordinasi antara tim yang dapat dilakukan dengan cara singkat .


<p align="center">
  <img src="https://user-images.githubusercontent.com/90564871/133935923-10bfd508-9da8-4880-b33c-d97e8a567a41.png"Sublime's custom image" height="400" width="600" />
</p>

                                                                                                                                                               
Continuous Integration (CI) dan Continuous Deployment (CD)
                                                                                                                          
Continuous Integration / integrasi berkelanjutan adalah praktik dari DevOps , seorang developer bisa mengintegrasikan kode ke dalam repositori kode
dan bisa menguji dengan cepat dan otomatis. sedangkan Continuous Deployment / penyebaran berkelanjutan adalah praktik setelah kode berhasil terintegrasi, 
aplikasi kita bisa dibangun lalu rilis secara otomatis.
                                                                                                                          
keuntungan CI/CD : 
-   Mendapatkan Feedback Lebih Cepat Menggunakan CI Tools
-   Mendeteksi Bug lebih awal
-   Visibilitas lebih baik
                             
                                                                                                                                           
                                                                                                                          
<p align="center">
  <img src="https://user-images.githubusercontent.com/90564871/134045146-3e360cfe-0e68-4469-a77f-9f532000e3df.png"Sublime's custom image" height="500" width="850" />
</p>
          
          
                                                                                                                       
Metode DevOps memiliki siklus dalam pengembangan software. Berikut adalah penjelasan tentang siklus metode DevOps :

1. Plan

Tahap perencanaan, identifikasi tujuan dan persyaratan untuk merancang perkembangan software. kegiatan lain yang dilakukan yaitu
manajemen proyek, penjadwalan, kebijakan/persyaratan, serta rencana awal untuk perbaruan dan perilisan di seluruh literasi , tools yang 
digunakan adalah saltstack . Software ini membantu dalam manajemen otomatis dan pemantauan sistem server. Menggunakan SaltStack, 
dimungkinkan untuk menginstal dan mengkonfigurasi Software 
dari komputer pusat dan menjalankan sejumlah perintah konfigurasi.

2. code 

Pada tahap ini Tim Development melakukan coding secara bersamaan di workstation masing masing dan akan dikirimkan kepada Repository di cloud, 
QA akan melihat dan menganalis code yang sudah sesuai dan tidak ada bug, lalu setelah itu akan di gabungkan ke dalam main/master atau aplikasi utama 
yang sudah melewati tahap analisis. tools yang digunakan adalah chef . Chef memiliki dukungan API dari AWS, Azure, Rackspace, yang membuatnya mudah 
digunakan dengan metodologi infrastruktur-sebagai-kode.

3. Continuous Integration ( CI ) 
   
Tahap ini melakukan build dan testing pada aplikasi web HIMALL dan disini perusahaan menggunakan Docker untuk build dan testing secara otomatis,
Docker adalah container memungkinkan para developer untuk mengisolasi kode ke dalam satu wadah sehingga membantu developer lebih mudah untuk memodifikasi
dan memperbaharui program yang ada. Membantu mengotomatiskan bagian-bagian pengembangan perangkat lunak yang terkait dengan build, testing dan deploy
dan dapat melakukan proses yang berkelanjutan. Dengan peroses integrasi yang berkelanjutan yang efesien, pengembangan lebih komitmen, yang akan membantu meningkatkan komunikasi dan meningkatkan kualitas perangkat lunak.

4. Continuous Delivery and Deployment
                                                                                                      
                                                                                                                                        
4 tools yang harus dikuasai devops


1. JENKINS
automation server yang bersifat open source dan membantu mengotomatisasi proses software development dengan CI/CD .
Jenkins populer di dunia DevOps Engineer karena lebih dari 1000 plugin bisa terintegrasi hampir semua alat DevOps.
  
2. GIT
Git juga banyak dipakai oleh DevOps Engineer. karena memiliki fungsionalitas, kinerja, keamanan, dan fleksibilitas yang dibutuhkan tim pengembang.
Git berfungsi sebagai alat Devops untuk distributed version-control yang penting. Git dapat melacak progres dari pengembangan sebuah projek 
dan melihat jika ada perubahan kode di dalam source code. Sangat membantu DevOps Engineer ketika mengimplementasikan CI/CD pipeline.

3. SELENIUM
Automation testing tool untuk web application yang bisa digunakan pada berbagai browser. Biasanya digunakan oleh tim QA untuk proses software testing.
tools ini bisa memproses pengujian berkelanjutan untuk menguji kinerja dan fungsionalitas kode yang dikembangkan.

4. DOCKER
Container management tool yang semakin berkembang dan salah satu tools penting untuk DevOps Engineer. Docker berguna ditahap deployment untuk 
kontainerisasi aplikasi sehingga aplikasi bisa bekerja efisien untuk environment yang berbeda.
