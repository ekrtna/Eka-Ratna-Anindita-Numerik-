# Numerik
## 1. Upgrade OS
Menggunakan command ‘sudo apt update && sudo apt upgrade’ untuk memperbarui OS pada setiap device.
## 2. Install Net-Tools 
Melakukan penginstalan net-tools dengan menggunakan command ‘sudo apt install net-tools vim’ untuk cek IP, vim sebagai teks editor.
## 3. Konfigurasi File  
Membuka file /etc/hosts menggunakan command ‘sudo nano /etc/hosts’.
## 4. Konfigurasi SSH
Melakukan konfigurasi SSH, SSH(Secure Shell) digunakan untuk otentikasi dan pertukaran data aman antara node dalam cluster MPI. Melakukan penginstallan SSH dengan command ‘sudo apt install openssh-server’.
## 5. Install NFS Client
Konfigurasi NFS (Network File System) merupakan proses mengatur dan mengkonfigurasi sistem berkas yang memungkinkan berbagi sistem berkas antara komputer dalam jaringan.
## 6. Install MPI
MPI adalah singkatan dari "Message Passing Interface." Ini adalah standar komunikasi yang digunakan dalam pemrograman paralel, terutama dalam pemrograman terdistribusi untuk sistem berbasis kluster atau superkomputer. Melakukan instalasi MPI dengan command ‘sudo apt install openmpi-bin libopenmpidev’.
## 7. Konfigurasi Python
Melakukan instalasi python versi 3 dengan menggunakan command ‘sudo apt install python3-pip’ dan python versi 2 dengan menggunakan command ‘sudo apt install python-pip’.
## 8. Testing
Melakukan uji coba untuk menghasilkan perintah dasar python pada setiap device dengan hasil output “Hello, World!” dengan menggunakan command ‘mpirun -np 
<jumlah prosesor> -host <daftar host> python3 test.py’.
![image](https://github.com/ekrtna/Eka-Ratna-Anindita-Numerik-/assets/150004277/917f32c6-04e7-4390-b98c-ed7758f13d69)

## Eliminasi Gaussian 
![image](https://github.com/ekrtna/Eka-Ratna-Anindita-Numerik-/assets/150004277/46a8574c-47e3-4500-a51d-ceede38fc869)
![image](https://github.com/ekrtna/Eka-Ratna-Anindita-Numerik-/assets/150004277/64159ec4-aeb1-40d8-9716-6cd27716c955)

## Newton – Raphson
![image](https://github.com/ekrtna/Eka-Ratna-Anindita-Numerik-/assets/150004277/0b0c5b7f-b487-40bb-9e36-c11898342ce3)
