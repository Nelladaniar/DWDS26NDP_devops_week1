# DWDS26NDP_devops_week1
Project Week 1

DEVOPS ENGINEER adalah profesional IT yang bertujuan memadukan proses development , deployment dan integrasi ke dalam suatu proses berkelanjutan.
DevOps singkatan dari development dan operations . Divisi yang bekerja sama dengan devops adalah divisi operations , yang mempunyai tujuan untuk 
mengetahui gambaran proses bisnis yang diharapkan . devops juga sangat menguasai software development life cycle ( SLDC ).


<p align="center">
  <img src="https://user-images.githubusercontent.com/90564871/133935923-10bfd508-9da8-4880-b33c-d97e8a567a41.png"Sublime's custom image" height="400" width="600" />
</p>

                                                                                                                         
Metode DevOps memiliki siklus dalam pengembangan software. Berikut adalah penjelasan tentang siklus metode DevOps :

1. Plan

Tahap perencanaan, identifikasi tujuan dan persyaratan untuk merancang perkembangan software. kegiatan lain yang dilakukan yaitu
manajemen proyek, penjadwalan, kebijakan/persyaratan, serta rencana awal untuk perbaruan dan perilisan di seluruh literasi.

2. Develop

Pada tahap sebelumnya, tim pengembang fokus untuk mengembangkan dan meninjau kode perangkat lunak atau IaC. Pengujian integrasi dan
unit dilakukan berdasarkan build automation tools.

3. Build
                                                                                                                  
tim developer selesai menulis kode dan  memasukan kode ke dalam shared code repository dan mengirimkan permintaan penggabungan kode,
setelah mereview perubahan yang dilakukan. Jika sudah sempurna, maka developer tersebut akan menyetujui 
permintaan penggabungan kode yang telah dikirim sebelumnya.
                                                                                                                          
4.	Test
                                                                                                                          
Fase selanjutnya adalah pengujian. Jika ada masalah yang ditemukan, maka akan dikirim kembali ke tim developer untuk diselesaikan.
                                                                                                                          
5. Release
                                                                                                                          
Fase release menjadi tonggak penting dalam DevOps pipeline. Pada tahap ini, setiap perubahan kode telah melewati serangkaian pengujian dan tim IT operations telah memastikan bahwa masalah yang merusak dan regresi sudah teratasi dengan baik.

6.	Deploy
                                                                                                                          
Deploy menjadi hal terpenting dalam DevOps. Pada tahap ini, setiap perubahan kode sudah melalui test dan tim IT operations telah
memastikan bahwa masalah sudah teratasi dengan baik , dan siap di rilis.
                                                                                                                          
7. Operate

Operasi dalam siklus DevOps berhubungan dengan konfigurasi dan pengelolaan aplikasi software setelah penerapan. misalnya, 
penyediaan sumber daya dan penskalaan otomatis. Orchestrator dan metode runtime lainnya yang dapat menyesuaikan topologi dan komponen aplikasi.

8. Monitor
                                                                                                                          
Tahap terakhir , tim IT operations akan memantau infrastruktur, sistem, dan aplikasi. Untuk memastikan bahwa aplikasi yang dikembangkan berjalan lancar.
Mereka mengumpulkan data penting dari log, analitik, sistem monitoring, serta melihat feedback dari pengguna untuk mengetahui jika ada masalah 
pada kinerja aplikasi. Kinerja aplikasi dipantau dengan mengumpulkan dan menganalisis data penggunaan , dapat membantu mendeteksi error dan
memberikan umpan balik untuk peningkatan software. Penelusuran dan diagnostic masalah , penting untuk perkembangan aplikasi di seluruh siklus rilis.
                                                                                                                          
                                                                                                                          
<p align="center">
  <img src="https://user-images.githubusercontent.com/90564871/133939571-98606807-5016-4d5a-9eea-fc7391c96590.jpg"Sublime's custom image"/>
</p>
                                                                                                                                         

Continuous Integration (CI) dan Continuous Deployment (CD)
                                                                                                                          
Continuous Integration / integrasi berkelanjutan adalah praktik dari DevOps , seorang developer bisa mengintegrasikan kode ke dalam repositori kode
dan bisa menguji dengan cepat dan otomatis. sedangkan Continuous Deployment / penyebaran berkelanjutan adalah praktik setelah kode berhasil terintegrasi, 
aplikasi kita bisa dibangun lalu rilis secara otomatis.
                                                                                                                          
keuntungan CI/CD : 
-   Mendapatkan Feedback Lebih Cepat Menggunakan CI Tools
-   Mendeteksi Bug lebih awal
-   Visibilitas lebih baik
                                                                                                               
Tools untuk proses CI/CD

1. Open-Source Tools
Beberapa permintaan customer untuk bisa menyesuaikan budget maka baiknya dengan menggunakan open-source tools untuk melakukan automasi pada proses CI/CD. 
Contohnya : Jenkins

2. Cloud
Untuk melakukan self-host pada aplikasi CI/CD , membantu setup dan memonitor aplikasi lebih efektif.
Contohnya : jenkins atau cruise control

3. Build Status
Penting untuk memilih tools yang bisa memonitor keseluruhan proses (transparan).
Contohnya : melalui notifikasi, email, atau bentuk komunikasi lainnya.
                                                                                                                                         
                                                                                                                                         
<p align="center">
  <img src="https://user-images.githubusercontent.com/90564871/133939668-f01ded9d-a525-49e1-8515-ff00353c8242.png"Sublime's custom image"/>
</p>


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

