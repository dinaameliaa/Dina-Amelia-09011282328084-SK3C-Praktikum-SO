# LAPORAN PRAKTIKUM
## SISTEM OPERASI
### TUGAS 4

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
Sistem file (file system) atau sistem berkas merupakan struktur logika yang digunakan untuk mengendalikan akses terhadap data yang ada pada disk. Dengan kata lain, sistem file merupakan database khusus untuk penyimpanan, pengelolaan, manipulasi dan pengambilan data, agar mudah ditemukan dan diakses. Sistem file pada Linux menyerupai pepohonan (tree), yaitu dimulai dari root, kemudian direktori dan sub direktori. Sistem file pada Linux diatur secara hirarkhikal, yaitu dimulai dari root dengan symbol “/”.

## 1.2 TUJUAN
1. Mengenal organisasi File di Linux  
2. Menciptakan dan manipulasi direktori  
3. Mempelajari ijin akses (permission) dari file dan direktori  
4. Mengenal konsep Owner dan Group
5. Mengerti konsep Link dan symbolic link

## 1.3 ALAT YANG DIGUNAKAN
1. Laptop
2. VirtualBox
3. Sistem Operasi Linux (Linux Mint)

---

# BAB II PEMBAHASAN

## 2.1 HASIL TUGAS
1. Lihat peralatan I/O, character device, yang ada pada system komputer.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%201.png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%201%20hasil.png)
   
2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%202.png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%202%20hasil.png)
   
3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%203.png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%203%20hasil.png)

   Setelah di copy ke sub direktori februari dan maret :
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%203%20hasil%202.png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%203%20hasil%203.png)
   
4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%204.png)
   
5. Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%205.png)
   
6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%206.png)
   
7. Hapuslah direktori maret.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%207.png)

   Direktori maret pun terhapus :
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%207%20hasil.png)
   
8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%208.png)
   Disini, kita tidak dapat membuat direktori baru "haha" pada sub direktori februari, karena telah mengubah kepemilikan sehingga hanya bisa melakukan read saja

   Agar kita dapat membuat direktori baru "haha" maka kita harus merubah agar bisa melakukan read, write, dan execute
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%208%20tambahan.png)

   Direktori baru "haha" pun berhasil dibuat :
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%208%20tamb%20hasil.png)
   
9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya ?
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%209.png)
   
10. Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi ?
    ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%2010.png)
    ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%204/soal%2010%20hasil.png)
