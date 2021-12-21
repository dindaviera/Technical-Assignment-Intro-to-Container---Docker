1. Container adalah Wadah untuk mengemas dan menjalankan aplikasi. Wadah ini mencakup kode, runtime, system tool dan pengaturan. Container hanya bisa mengakses resource yang telah ditentukan dalam docker image.

2. Perbedaan antara konsep container dengan virtual machine adalah container melakukan virtualisasi pada host OS-nya sedangkan VM bekerja sebaliknya. VM memakan banyak waktu dan resource karena melakukan virtualisasi pada host hardwarenya.

3. Docker file adalah blueprint untuk membuat image atupun custom dalam pembuatan image

4. Docker registery adalah tempat untuk mengupload dan mendownload image

5. Cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung adalah dengan buat file NAMA_FILE,yaml di dalam project yang dibuat > tulis beberapa perintah > Jalankan menggunakan perintah -> docker-compose NAMA_FILE.yaml up
