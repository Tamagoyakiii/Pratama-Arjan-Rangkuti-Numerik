# MPI-Numerik
This repository contains how to execute a numeric program in python using MPI with an Ubuntu Master & 3 Ubuntu Slave.
## Topology
![image](https://github.com/Tamagoyakiii/Pratama-Arjan-Rangkuti-Numerik/assets/150600551/72cec987-4c08-4b4c-9d2c-024e3f87b8fc)
## 1. Upgrade OS
Using the 'sudo apt update && sudo apt upgrade' command to update the operating system on every device.
## 2. Install Net-Tools 
Performing the installation of net-tools using the command 'sudo apt install net-tools' to check the IP address.
## 3. Konfigurasi File  
Opening the file /etc/hosts using the command 'sudo nano /etc/hosts'.
## 4. Konfigurasi SSH
Configuring SSH (Secure Shell) is used for secure authentication and data exchange between nodes in an MPI cluster. Installing SSH can be done using the command 'sudo apt install openssh-server'.
## 5. Install NFS Client
Configuration of NFS (Network File System) involves the process of setting up and configuring a file system that allows sharing files between computers in a network.
## 6. Install MPI
MPI stands for "Message Passing Interface." It is a communication standard used in parallel programming, especially in distributed programming for cluster-based or supercomputer systems. Installing MPI can be done using the command 'sudo apt install openmpi-bin libopenmpi-dev'.
## 7. Konfigurasi Python
Installing Python version 3 using the command 'sudo apt install python3'.
## 8. Menjalankan Numerik
Running the edited file using the command 'mpirun -n <number of processes> -hostfile <host list> python3 <filename>.py'.
![image](https://github.com/Tamagoyakiii/Pratama-Arjan-Rangkuti-Numerik/assets/150600551/b4b63e46-0d1c-47fe-816e-3d6d9d15cfcb)
![image](https://github.com/Tamagoyakiii/Pratama-Arjan-Rangkuti-Numerik/assets/150600551/0397d74e-472a-420c-a011-fb7e0a6cd30a)

