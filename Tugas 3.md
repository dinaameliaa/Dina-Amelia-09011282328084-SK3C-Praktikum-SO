# LAPORAN PRAKTIKUM
## SISTEM OPERASI
### TUGAS 3

---

### Disusun oleh:
**Nama**: Dina Amelia  
**NIM**: 09011282328084   
**Kelas**: SK3C  
**Dosen Pengampu**: Adi Hermansyah, M. T.

---

### PROGRAM STUDI SISTEM KOMPUTER  
### FAKULTAS ILMU KOMPUTER  
### UNIVERSITAS SRIWIJAYA  
**2024**

---

# BAB I PENDAHULUAN

## 1.1 LATAR BELAKANG
Perintah dasar linux atau linux command essential adalah aplikasi linux berbasis console yang disertakan oleh semua distro linux sebagai aplikasi console standar yang berfungsi sebagai tool untuk melakukan navigasi dan mengelola sistem. Pada dasarnya perintah linux adalah sebuah aplikasi,hanya saja aplikasi ini tidak mempunyai tampilan grafis dan hanya mempunyai tampilan berbasis text. Jadi perintah linux sebenarnya adalah jenis aplikasi console yang cara menjalankannya harus menggunakan shell, terminal, command line interface (CLI). Perintah linux ini bisa digunakan untuk melihat dan menampilkan isi folder, mencari file, membuat file, hapus file, memindah, copy, paste hingga bisa menginstall, menghapus, update dan upgrade aplikasi dengan mengetikan perintah linux di terminal.

## 1.2 TUJUAN
1. Mengetahui perintah-perintah dasar untuk informasi user
2. Mengetahui format instruksi pada system operasi Linux
3. Dapat menggunakan perintah-perintah dasar pada system operasi Linux
4. Dapat menggunakan utilitas dasar pada system operasi Linux

## 1.3 ALAT YANG DIGUNAKAN
1. Laptop
2. Virtual Machine VirtualBox
3. Sistem Operasi Linux (Linux Mint)

# BAB II PEMBAHASAN

## 2.1 HASIL
1. cd : (cd Desktop) mengubah direktori kerja ke Desktop
2. pwd : menampilkan direktori kerja saat ini
3. mkdir : (mkdir my_directory) membuat direktori bernama my_directory
4. ls : (ls -1) menampilkan daftar file dan direktori dengan detail
5. rmdir : (rmdir my_directory) menghapus direktori my_directory yang kosong
6. rm : (rm file.txt) menghapus file bernama file.txt
7. touch : (touch myfile.txt) membuat file kosong
8. cp : menyalin file atau direktori
9. mv : (mv newfile.txt job.txt) mengganti nama file dari newfile ke job
10. cat : menampilkan isi file
11. more : menampilkan isi file satu kayar penuh pada satu waktu
12. head : menampilkan baris pertama dari file
13. tail : menampilkan baris terakhir dari file
14. echo : Mencetak teks ke terminal
15. man : (man ls) menampilkan manual untuk perintah ls
16. chown :(chown user:group job.txt) mengubah kepemilikan job.txt menjadi user dan group
17. df : menampilkan informasi penggunaan disk
18. du : menampilkan ukuran penggunaan disk oleh file dan direktori
19. ps : menampilkan daftar proses yang sedang berjalan
20. uname : menampilkan informasi sistem lengkap
21. hostname : menampilkan nama host sistem
22. wget : mengunduh file dari internet
23. curl : (curl http://youtube.com) menampilkan konten halaman http://youtube.com
24. gzip : mengompresi file menjadi gzip
25. gunzip : mengekstrak gzip menjadi file
26. top : menampilkan proses yang berjalan secara real-time
27. zip : mengompresi file menjadi zip
28. unzip : mengekstrak zip menjadi file
29. find : mencari file atau direktori di sistem
30. grep : mencari teks dalam file
31. awk : memproses dan memformat teks dalam file
32. sed : memproses dan mengedit teks secara batch
33. ssh : masuk ke komputer lain melalui jaringan menggunakan Secure Shell
34. scp : menyalin file antara komputer secara aman
35. sudo : menjalankan perintah dengan hak akses superuser
36. apt-get : (sudo apt-get packagename) menginstal packagename pada distribusi berbasis Debian
37. yum : (sudo yum install package_name) menginstal package_name pada distribusi berbasis Red Hat
38. systemct1 : (sudo systemctl restart apache2) memulai ulang layanan apache2
39. service : (sudo service apache2 status) memeriksa status layanan apache2
40. df : (df -h) menampilkan informasi penggunaan disk
41. mount : (sudo mount /dev/sdb1 /mnt/usb) memasang sistem file sdb1 ke /mnt/usb
42. umount : (sudo umount /mnt/usb) melepas sistem file /mnt/usb
43. alias : membuat alias untuk perintah
44. whoami : menampilkan nama pengguna saat ini
45. hostnamect1 : mnampilkan informasi tentang hostname dan sistem operasi
46. date : menampilkan tanggal dan waktu saat ini
47. uptime : menampilkan lama waktu sistem telah berjalan serta jumlah pengguna yang masuk
48. env : menampilkan semua variabel lingkungan (environment variables) yang saat ini aktif
49. tr : mengonversi huruf kecil menjadi huruf besar dalam teks "data mining", menghasilkan "DATA MINING"
50. wc : (wc -1 job.txt) menghitung jumlah baris dalam job.txt
51. history : menampilkan daftar perintah yang telah dijalankan sebelumnya
52. clear : membersihkan layar terminal
53. exit : keluar dari sesi terminal
