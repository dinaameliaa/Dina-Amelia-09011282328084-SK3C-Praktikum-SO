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
  Shell adalah Command executive, artinya program yang menunggu instruksi dari pemakai, memeriksa sintak dari instruksi yang diberikan, kemudian mengeksekusi perintah tersebut. 
Shell ditandai dengan prompt. Untuk pemakai menggunakan prompt $ dan untuk superuser menggunakan prompt #.  
  History diadaptasi dari C-Shell, yaitu catatan dari semua instruksi yang sejauh ini telah dilakukan. Catatan ini dapat dilihat sebagai history, kemudian dapat dipilih kembali, diedit dan 
dieksekusi. History memudahkan pemakai untuk mengedit kembali instruksi kompleks dan panjang, terutama bila terjadi kesalahan pada penulisan instruksi maupun parameter.  
  Job adalah sebuah eksekusi program yang diberikan kepada kernel. Sebuah Job dianggap selesai, bila eksekusi program tersebut berakhir. Eksekusi Job adalah sama dengan eksekusi 
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
   ![Gambar]()
   
   b.  Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu:   
   /home/stD02001/.bash_profile   
   /home/. stD02001/.bash_login   
   /home/mahasiswa/.profile   
   /home/mahasiswa/.bashrc   
   Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/mahasiswa/.bash_profile :   
   echo “Profile dari .bash_profile”   
   Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.   
   ![Gambar]()
   
   c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:   
   $ su mahasiswa   
   $ exit   
   ![Gambar]()
   
   kemudian gunakan opsi – sebagai berikut :   
   $ su – mahasiswa   
   $ exit   
   ![Gambar]()
   
   Jelaskan perbedaan kedua utilitas tersebut.

2. Prompt String (PS)   
   a.  Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell   
   PS1='> '   
   export PS1   
   ![Gambar]()
   
   b.  Eksperimen hasil PS1 :   
   ![Gambar]()

3. Logout   
   Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout   
   ![Gambar]()

4. Bash script   
   a.  Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
   ![Gambar]()
    
   b.  Jalankan script tersebut :   
   ![Gambar]()

5. Jobs   
   a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.   
   ![Gambar]()
   
   b.  Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut :   
   ![Gambar]()
   
   c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background  :   
   ![Gambar]()
   
   d.  Stop program background dengan utilitas kil :   
   ![Gambar]()

7. History   
   a. Ganti nilai HISTSIZE dari 1000 menjadi 20   
   ![Gambar]()
   
   b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan   
   ![Gambar]()   
   
   c. Ulangi instruksi yang terakhir.  Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer   
   ![Gambar]()
   
   d.  Ulangi instruksi pada history bufer nomor 150   
   ![Gambar]()   
   
   e.  Ulangi instruksi dengan prefix “ls”   
   ![Gambar]()
