# LAPORAN PRAKTIKUM
## SISTEM OPERASI
### TUGAS 6

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
  - Shell adalah Command executive, artinya program yang menunggu instruksi dari pemakai, memeriksa sintak dari instruksi yang diberikan, kemudian mengeksekusi perintah tersebut.  
  - History diadaptasi dari C-Shell, yaitu catatan dari semua instruksi yang sejauh ini telah dilakukan. Catatan ini dapat dilihat sebagai history, kemudian dapat dipilih kembali, diedit dan 
dieksekusi.   
  - Job adalah sebuah eksekusi program yang diberikan kepada kernel. Sebuah Job dianggap selesai, bila eksekusi program tersebut berakhir. Eksekusi Job adalah sama dengan eksekusi 
program, baik proses Background maupun proses Foreground.

## 1.2 TUJUAN
1. Mengenal Profile   
2. Mengerti konsep history   
3. Membuat dan mengeksekusi shell script sederhana   
4. Mengerti Job control 

## 1.3 ALAT YANG DIGUNAKAN
1. Laptop
2. VirtualBox
3. Sistem Operasi Linux (Ubuntu)

---

#  BAB II PEMBAHASAN

## 2.1 HASIL TUGAS
1. Eksekusi seluruh profile yang ada :   
   a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut: echo “Profile dari /etc/profile”   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201A%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201A%20(2).png)
   
   b.  Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu:   
   /home/stD02001/.bash_profile   
   /home/. stD02001/.bash_login   
   /home/mahasiswa/.profile   
   /home/mahasiswa/.bashrc   
   Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/mahasiswa/.bash_profile :   
   echo “Profile dari .bash_profile”   
   Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.
   
   - .bash_profile 
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201B%20bash%20profile%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201B%20bash%20profile%20(2).png)
   
   - .bash_login
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201B%20bash%20login%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201B%20bash%20login%20(2).png)
   
   - .profile
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201B%20profile%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201B%20profile%20(2).png)
   
   - .bashrc
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201B%20bashrc%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201B%20bashrc%20(2).png)
   
   c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:   
   $ su mahasiswa   
   $ exit   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201C%20(a).png)
   
   kemudian gunakan opsi – sebagai berikut :   
   $ su – mahasiswa   
   $ exit   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%201C%20(b).png)
   
   Perbedaan kedua utilitas tersebut yaitu, pada penggunaan su - lebih mirip dengan login langsung sebagai pengguna tersebut tanpa mengubah semua pengaturan dan variabel yang ada. Sedangkan su hanya mengubah identitas pengguna tanpa mengubah semua pengaturan.

2. Prompt String (PS)   
   a.  Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell
   
   PS1='> '   
   export PS1   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%202%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%202%20(2).png)
   
   b.  Eksperimen hasil PS1 :   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%202%20(3).png)

4. Logout   
   Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%203A%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%203A%20(2).png)
   ![](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%203%20(3).png)

5. Bash script   
   a.  Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
   
   - p1.sh
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p1%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p1%20(2).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p1%20(3).png)
   
   - p2.sh
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p2%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p2%20(2).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p2%20(3).png)
   
   - p3.sh
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p3%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p3%20(2).png)
   ![Gamnar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p3%20(3).png)

   - ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204A%20p123.png)
    
   b.  Jalankan script tersebut :   
   - $ ./p1.sh ; ./p3.sh ; ./p2.sh   
   Program p1
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204B%20p1%20(a).png)
   Program p3
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204B%20p3%20(a).png)
   Program p2
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204B%20p2%20(a).png)

   - $./p1.sh &
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204B%20(b).png)

   - $ ./p1.sh  $ ./p2.sh & ./p3.sh &
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204B%20p1%20(c).png)

   - $ ( ./p1.sh ; ./p3.sh ) &
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%204B%20(d).png)

6. Jobs   
   a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%205A%20(1).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%205A%20(2).png)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%205A%20(3).png)
   
   b.  Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut :   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%205B.png)
   
   c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background  :   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%205C.png)
   
   d.  Stop program background dengan utilitas kil :
   $ ps x
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%205D%20(ps%20x).png)
   
   $ kill
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%205D%20(kill).png)

7. History   
   a. Ganti nilai HISTSIZE dari 1000 menjadi 20   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%206A.png)
   
   b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%206B.png)   
   
   c. Ulangi instruksi yang terakhir.  Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%206C.png)
   
   d.  Ulangi instruksi pada history bufer nomor 150   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%206D.png)
   Disini saya menggunakan history bufer nomor 278
   
   e.  Ulangi instruksi dengan prefix “ls”   
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%206/P6%206E.png)
