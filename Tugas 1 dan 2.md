# LAPORAN PRAKTIKUM
## SISTEM OPERASI
### TUGAS 1 & TUGAS 2

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
Sistem operasi Linux adalah jenis sistem operasi komputer yang bebas dan sumber terbuka, didistribusikan di bawah lisensi GNU General Public License (GPL) yang memungkinkan pengguna untuk mengunduh, menginstal, dan mengubah kode sumber sistem operasi secara gratis. OS Linux terdiri dari kernel Linux yang dikembangkan oleh Linus Torvalds dan berbagai perangkat lunak yang dikembangkan oleh komunitas open-source. Karena linux adalah kernel dari sistem operasi yang bersifat open source yang dapat dimodifikasi siapa saja, maka dari itu ada banyak jenis sistem operasi linux. Salah satu diantaranya yaitu Linux Mint seperti yang akan saya gunakan untuk menginstal sistem operasi linux pada praktikum ini.

## 1.2 TUJUAN 
1. Mengetahui prosedur instalasi pada sistem operasi linux
2. Mampu menjalankan instalasi melalui Graphic User Interface (GUI) maupun Command Line Linux
3. Mampu menganalisis proses instalasi   

## 1.3 ALAT YANG DIGUNAKAN
1. Laptop
2. Virtual Machine VirtualBox
3. Sistem Operasi Linux (Linux Mint)

# BAB II PEMBAHASAN

## 2.1 PROSES INSTALISASI
1. Download VitualBox di web dan pilih Windows hots (atau sesuaikan dengan laptop masing-masing)
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/virtual%20box_download.png)
2. Setelah aplikasi VirtualBox terpasang pada laptop, buka dan pilih buat project sesuai dengan kebutuhan masing-masing
3. Apabila telah selesai, maka tampilan project akan menjadi seperti di bawah ini
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/vitual%20box_tampilan.png)
4. Selanjutnya, download sistem operasi Linux Mint
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/linuxmint_download.png)
5. Kemudian tambahkan Linux Mint ke dalam project VirtualBox pada bagian storage
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/virtual%20box_storage.png)
6. Jika sudah ditambahkan, pilih start untuk memulai project Linux
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/vitual%20box_tampilan.png)
7. Lalu, tunggu hingga tampilan menjadi seperti ini
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Linux_AMELL_29_08_2024_14_46_34.png)
8. Lalu klik Install Linux Mint
9. Kemudian pilih bahasa dan klik "pasang codec multimedia"
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_18_31.png)
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_20_31.png)
10. Berikutnya pilih “sesuatu yang lain”
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_21_09.png)
11. Pada tampilan berikutnya klik Tambahkan Partisi Baru, kemudia klik Continu. Maka tampilan berikutnya akan menampilkan partisi/dev/sda yang sudah terbuat
12. Selanjutnya pilih tanda + untuk membuat partisi swap dan berikan ukuran harddisk 1024 MB, serta pilih Ruang Swap. Klik OK
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_28_23.png)
13. Selanjutnya pilh tanda + dan berikan ukuran 5291 MB atau lebih serta pilih format “sistem berkas berjurnal ext4” dan pilih /home pada Mount Point. Klik OK
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_29_24.png)
14. Selanjutnya pilih tanda + dan berikan space harddisk sebesar 13000, kemudian pilih format “sistem berkas berjurnal ext4” dan pilih / (root) pata Mount Point. Klik OK
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_30_16.png)
15. Partisi harddisk siap dilakukan instalisasi sistem operasi linux, setelah itu klik "Pasang Sekarang"
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_31_26.png)
16. Kemudian proses instalisasi ke harddisk akan dilakukan, setting untuk zona waktu yang digunakan. Klik "Lanjutkan"
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_34_14.png)
17. Tampilan berikutnya merupakan input username dan password untuk verifikasi saat masuk atau login ke sistem operasi. Apabila telah selesai klik "Lanjutkan"
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_35_22.png)
18. Setelah itu akan memasukki proses peng-copy-an file dan instalasi ke filesystem
![Contoh Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/VirtualBox_AMELL_29_08_2024_18_38_25.png)
19. Tunggu sampai selesai, maka Sistem Operasi Linux pun telah berhasil diinstall

## 2.2  ANALISIS "/" PADA MOUNT POINT
(/) disebut sebagai root directory, yang merupakan direktori tertinggi dalam struktur sistem file Linux. Semua file dan direktori lainnya berada di bawah root directory ini. Dengan memilih (/) pada Mount Point, maka dapat memberi tahu installer untuk memasang seluruh sistem operasi di bawah direktori root ini. Ini termasuk file sistem inti, direktori pengguna, aplikasi, dan semua komponen lainnya yang dibutuhkan agar sistem Linux bisa berjalan.

## 2.3 PENJELASAN MENGENAI EXT4, EXT3, SWAP, NTFS, FAT32, BTRFS

### 2.3.1 EXT4 (Fourth Extended Filesystem)
- **Deskripsi:** EXT4 adalah versi terbaru dari sistem berkas EXT (Extended Filesystem) yang digunakan dalam sistem operasi Linux. Ini adalah pengembangan dari EXT3 dan dirancang untuk mengatasi beberapa keterbatasan dan meningkatkan kinerja.   
- **Keunggulan:** Mendukung volume besar, fitur journaling, alokasi ruang lebih efisien, dan backward compatibility dengan EXT3   
- **Penggunaan:** Linux (Debian, Ubuntu, Fedora, CentOS, dan distribusi Linux lainnya)  

### 2.3.2 EXT3 (Third Extended Filesystem)
- **Deskripsi:** EXT3 adalah pendahulu EXT4 dan juga merupakan sistem berkas yang banyak digunakan dalam distribusi Linux sebelum EXT4 dikembangkan
- **Keunggulan:** Fitur journaling untuk meningkatkan keandalan, mudah di-upgrade dari EXT2 tanpa memformat ulang partisi
- **Penggunaan:** Linux (Sistem operasi Linux yang lebih tua atau untuk backward compatibility)

### 2.3.3 SWAP
- **Deskripsi:** SWAP bukanlah sistem berkas, melainkan partisi khusus yang digunakan oleh sistem operasi untuk memperluas RAM secara virtual
- **Keunggulan:** Menyediakan ruang tambahan untuk proses yang membutuhkan lebih banyak memori daripada yang tersedia di RAM fisik
- **Penggunaan:** Linux (Debian, Ubuntu, Fedora, CentOS, dan distribusi Linux lainnya), Unix

### 2.3.4 NTFS (New Technology File System)
- **Deskripsi:** NTFS adalah sistem berkas yang dikembangkan oleh Microsoft dan digunakan sebagai sistem berkas utama untuk sistem operasi Windows
- **Keunggulan:** Mendukung file dan volume besar, fitur journaling, keamanan file tingkat lanjut, enkripsi, dan kompresi
- **Penggunaan:** Windows (Windows NT, Windows 2000, Windows XP, Windows Vista, Windows 7, 8, 10, 11), dukungan terbatas di Linux dan macOS

### 2.3.5 FAT32 (File Allocation Table 32)
- **Deskripsi:** AT32 adalah sistem berkas yang lebih tua dan sederhana dibandingkan NTFS, mendukung berbagai platform termasuk Windows, Linux, dan macOS
- **Keunggulan:** Sangat kompatibel dengan hampir semua sistem operasi, ideal untuk perangkat penyimpanan portabel
- **Pengguanaan:** Windows, macOS, Linux, dan hampir semua perangkat penyimpanan portabel seperti USB flash drive, kartu SD

### 2.3.6 BTRFS (B-Tree File System)
- **Deskripsi:** BTRFS adalah sistem berkas canggih yang dirancang untuk fitur-fitur seperti snapshotting, checksumming data, dan manajemen volume yang efisien
- **Keunggulan:** Mendukung snapshotting, rollback, RAID, balancing otomatis, dan fitur self-healing yang dapat mendeteksi dan memperbaiki data yang korup   
- **Penggunaan:** Linux (openSUSE, Fedora, Ubuntu Server, dan beberapa distribusi Linux lainnya yang mendukung fitur canggih)

