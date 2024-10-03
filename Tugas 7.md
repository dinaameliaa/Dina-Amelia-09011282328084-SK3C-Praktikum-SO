# LAPORAN PRAKTIKUM
## SISTEM OPERASI
### TUGAS 7

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

# CARA MEMASANG DAN MENGONFIGURASI SSH DI UBUNTU

## Langkah 1 : Siapkan Ubuntu
   1. Hal yang perlu dilakukan sebelum menginstal SSH di ubuntu adalah memperbarui semua apt paket ke versi terbaru, dengan menggunakan perintah berikut ini    
      ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%201.png)

## Langkah 2 : Install SSH di Ubuntu
   2. Untuk melakukan penginstalan pada sistem, gunakan perintah berikut    
      ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%203.png)
      
   3. Instalasi semua komponen yang  diperlukan akan dimulai, klik OK dan tunggu hingga instalasi selesai dilakukan    
      ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%202.png)

## Langkah 3 : Mulai SSH
   4. Aktifkan layanan yang baru saja diinstal menggunakan perintah di bawah ini
      ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%204.png)

   5. Untuk memverifikasi bahwa layanan diaktifkan dan berjalan dengan sukses, ketik perintah di bawah ini. Jika outputnya berisi Active:active (running) maka layanan berhasil dijalankan 
      ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%205.png)

   6. Apabila kita ingin menonaktifkan layanan, jalankan perintah ini
      ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%206.png)

## Langkah 4 : Konfigurasikan Firewall
   7. Sebelum menghubungkan server melalui SSH, periksa firewall untuk memastikannya dikonfigurasikan dengan benar dengan menggunakan perintah ini    
      ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%208.png)

   8. Jika outputnya belum diizinkan/inactive seperti di atas, maka perlu melakukan perizinan koneksi SSH yang masuk
      ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%207.png)

## Langkah 5 : Hubungkan ke Server
   9.  Setelah menyelesaikan langkah-langkah sebelumnya, maka kita dapat masuk ke server menggunakan protokol SSH. Disini kita memerlukan username dan IP address yang dibuat di server    
       ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%209.png)

## Langkah 6 : Konfigurasi SSH
   10. Selain itu, kita juga dapat lebih meningkatkan keamanan koneksi dengan mengubah port koneksi default ke yang lain atau mengubah autentikasi kata sandi menjadi autentikasi kunci.    
       Pengaturan server OpenSSH utama disimpan dalam berkas konfigurasi utama sshd_config (lokasi:/etc/ssh)                    
       ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%2010.png)

       ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%207/P7%2011.jpg)
