1. Jelaskan apa yang dimaksud dengan container pada docker !
   Jawab :
   Wadah untuk mengemas dan menjalankan aplikasi. Wadah ini mencakup kode, runtime, system tools
   dan pengaturan. Container hanya bisa mengakses resource yang telah ditentukan dalam docker image.

2. Jelaskan apa perbedaan antara konsep container dengan virtual machine !
   Jawab :
   Container melakukan virtualisasi pada host OS-nya sedangkan VM bekerja sebaliknya. VM memakan banyak waktu
   dan resource karena melakukan virtualisasi pada host hardwarenya.

3. Apa yang dimaksud dengan docker file ?
   Jawab :
   Docker file adalah blueprint untuk membuat image atupun custom dalam pembuatan image

4. Apa yang dimaksud dengan docker registery ?
   Jawab :
   Docker registery adalah tempat untuk mengupload dan mendownload image

5. Jelaskan bagaimana cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung !
   Jawab : cara menajalankan lebih dari 1 container secara bersamaan dan saling terhubung adalah sebagai berikut :
6. buat file NAMA_FILE,yaml di dalam project yang kamu buat
7. Tulis beberapa perintah
   3.Jalankan menggunakan perintah -> docker-compose NAMA_FILE.yaml up
