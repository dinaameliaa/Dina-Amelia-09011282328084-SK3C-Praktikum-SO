# LAPORAN PRAKTIKUM
## SISTEM OPERASI
### TUGAS 5

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
Sebuah proses memerlukan Input dan Output.  Instruksi (command) yang diberikan pada Linux melalui Shel disebut sebagai eksekusi program yang selanjutnya disebut proses. Setiap kali instruksi diberikan, maka Linux kernel akan menciptakan sebuah proses dengan memberikan nomor PID (Process Identity).  Proses dalam Linux selalu membutuhkan input dan menghasilkan suatu output.  
Dalam konteks Linux input/output adalah :  
•  Keyboard (input)  
•  Layar (output)  
•  Files  
•  Struktur data kernel  
•  Peralatan I/O lainnya (misalnya Network)  

## 1.2 TUJUAN
1. Mengenal konsep proses I/O dan redirection  
2. Memahami standar input, output dan error  
3. Menggunakan notasi output, append dan here document  
4. Mengenal konsep PIPE dan filter

## 1.3 ALAT YANG DIGUNAKAN
1. Laptop
2. VirtualBox
3. Sistem Operasi Linux (Ubuntu)

---

# BAB II PEMBAHASAN

## 2.1 HASIL TUGAS
1. Lihat daftar secara lengkap pada direktori aktif, belokkan tampilan standard output ke file baru. 
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%201.png)

2. Lihat daftar secara lengkap pada direktori /etc/paswd, belokkan tampilan standard output ke file baru tanpa menghapus file baru sebelumnya.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%202.png)

3. Urutkan file baru dengan cara membelokkan standard input.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%203.png)

4. Urutkan file baru dengan cara membelokkan standard input dan standard output ke file baru.urut.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%204.png)

5. Buatlah direktori latihan6 sebanyak 2 kali dan belokkan standard error ke file rmdirerror.txt.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%205.png)

6. Urutkan kalimat berikut :  
   Jakarta  
   Bandung  
   Surabaya  
   Padang
   Palembang  
   Lampung  
   Dengan menggunakan notasi here document (<@@@ …@@@)
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%206.png)

7. Hitung jumlah baris, kata dan karakter dari file baru.urut dengan menggunakan filter dan tambahkan data tersebut ke file baru.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%207.png)

8. unakan perintah di bawah ini dan perhatikan hasilnya. 
   $ cat /etc/passwd | sort | pr –n | grep tty03  
   $ find /etc –print | head  
   $ head /etc/passwd | tail –5 | sort
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%208.png)

9. Gunakan perintah $ who | cat | cat | sort | pr | head | cat | tail dan perhatikan hasilnya.
   ![Gambar](https://github.com/dinaameliaa/Dina-Amelia-09011282328084-SK3C-Praktikum-SO/blob/main/Sistem%20Operasi/Gambar%20tugas%205/tugas%209.png)


