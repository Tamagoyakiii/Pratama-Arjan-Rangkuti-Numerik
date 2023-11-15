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
## 8. Menjalankan Numerik
Menjalankan file yang telah diedit dengan command ‘mpirun -n <jumlah prosesor> host <daftar host> python3 <nama file>.py’
![image](https://github.com/Tamagoyakiii/Pratama-Arjan-Rangkuti-Numerik/assets/150600551/b4b63e46-0d1c-47fe-816e-3d6d9d15cfcb)
![image](https://github.com/Tamagoyakiii/Pratama-Arjan-Rangkuti-Numerik/assets/150600551/0397d74e-472a-420c-a011-fb7e0a6cd30a)

