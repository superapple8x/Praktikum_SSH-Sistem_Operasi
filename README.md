# Praktikum_SSH-Sistem_Operasi
Mengontrol komputer lain secara remote menggunakan SSH

## Langkah-langkah

1. Perbarui semua package dan mirror demi memastikan bahwa package di system adalah yang terbaru dan package yang akan diinstal kedepannya juga yang terbaru

   ![Perbarui package dan mirror](https://github.com/superapple8x/Praktikum_SSH-Sistem_Operasi/blob/main/praktikum-ssh/1.png)

2. Instal package openssh untuk mengontrol komputer lain secara remote

   ![Instal OpenSSH](https://github.com/superapple8x/Praktikum_SSH-Sistem_Operasi/blob/main/praktikum-ssh/2.png)

3. Memastikan service ssh telah berjalan dan dapat berjalan secara otomatis tiap boot 

   ![Cek service SSH](https://github.com/superapple8x/Praktikum_SSH-Sistem_Operasi/blob/main/praktikum-ssh/3.png)

4. Memberi akses firewall pada service ssh agar dapat menerima dan mengirim koneksi ke komputer lain

   ![Konfigurasi firewall](https://github.com/superapple8x/Praktikum_SSH-Sistem_Operasi/blob/main/praktikum-ssh/4.png)

5. Mencari IP Address komputer yang kemudian bisa digunakan untuk disambungkan dari komputer lain

   ![Cari IP Address](https://github.com/superapple8x/Praktikum_SSH-Sistem_Operasi/blob/main/praktikum-ssh/5.png)

6. Menyambungkan ke komputer lain menggunakan ssh, diikuti dengan username akun Linux dan IP Address komputer yang dituju

   ![Koneksi SSH](https://github.com/superapple8x/Praktikum_SSH-Sistem_Operasi/blob/main/praktikum-ssh/6.png)
