
Project Week 1

PT. HIKAYAT GLOBAL AMARTA
    

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
digunakan adalah google drive . tool ini membantu dalam manajemen otomatis dan pemantauan sistem server didukung dengan kapasitas penyimpanan online yang cukup besar terintegrasi dengan layanan google lainnya , dapat menyimpat dengan berbagai format, multiplatform dengan sistem keamanan terbaik

2. code 

Pada tahap ini Tim Development melakukan coding secara bersamaan di workstation masing masing dan akan dikirimkan kepada Repository di cloud, 
QA akan melihat dan menganalis code yang sudah sesuai dan tidak ada bug, lalu setelah itu akan di gabungkan ke dalam main/master atau
aplikasi utama yang sudah melewati tahap analisis. tools yang digunakan adalah gitlab . layanan mirip github yang digunakan untuk menyediakan 
manajemen internal git repositories. Menyediakan versi GitLab Community Edition bagi pengguna untuk menemukan di mana server kode mereka present.
GitLab menyediakan public repositories dan private tanpa batas secara gratis.

3. Continuous Integration ( CI ) 
   
Tahap ini melakukan build dan testing pada aplikasi web HIMALL dan disini perusahaan menggunakan jenkins untuk build dan testing secara otomatis,
jenkins adalah tools continuous integration andalan untuk para DevOps engineer . Developer akan lebih mudah mengintegrasikan berbagai perubahan 
pada proyek sebelum akhirnya meluncurkan software.

4. Continuous Delivery and Deployment

Tools Amazone Web Service , fitur yang dimiliki oleh Dev Tools AWS devops bisa di rollback aplikasi yang telah di deploy untuk dengan aplikasi sebelumnya,
untuk mengatasi masalah blue and green deployment . layanan cloud yang aman, AWS menawarkan tenaga komputasi, ruang penyimpanan database. HIMALL 
menggunakan AWS dalam menerapkan kedalam cloud. Dengan aws kami dapat memilih produk yang memudahkan dalam membangun bisnis, infrastructure as a service 
adalah istilah yang tepat untuk AWS, Setelah docker sudah di install di dalam amazon web service 
                                                                                                      
                                                                                                                                        
<p align="center">
  <img src="https://user-images.githubusercontent.com/90564871/134093500-d6833605-8bc1-4b90-b5f4-cafbb69494de.png"Sublime's custom image" height="1000" width="850" />
</p>



