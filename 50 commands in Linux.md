# 50 commands

Note:Untuk mencoba command ini bisa menggunakan OS linux, Virtual machine basis Linux, atau bisa menggunakan Lab virtual terminal di website RedHat.com 

1.     ls
   ![1 ls](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/262e79cc-d730-4a90-af98-b6857278f7f2)

    Command `ls` (list) digunakan untuk menampilkan daftar file dan direktori dalam direktori saat ini. Ini adalah salah satu command yang paling sering digunakan untuk navigasi file sistem. Tanpa argumen tambahan, `ls` akan menampilkan daftar file dan direktori secara vertikal.
     
2.     cd

   ![2 cd](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/7bb6760f-d3a7-46a6-a0c3-70892b90afde)

    Command `cd` (change directory) digunakan untuk berpindah dari satu direktori ke direktori lain dalam sistem file. Anda cukup menulis `cd` diikuti dengan nama direktori yang ingin Anda masuki. Misalnya, `cd Document` akan membawa Anda ke dalam direktori "Documents".

3.     mkdir

   ![3 mkdir](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/e3238e09-3483-48f9-8a40-ffd999a39a2d)

    Command `mkdir` (make directory) digunakan untuk membuat direktori baru dalam sistem file. Anda hanya perlu menuliskan `mkdir` diikuti dengan nama direktori yang ingin Anda buat. Misalnya, `mkdir Photos` akan membuat direktori baru bernama "Photos" di dalam direktori saat ini.

4.     ls -l

   ![4 ls-1](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/5e01d337-cc51-4699-88b1-a4ca2d670e19)

    Command `ls -l` menampilkan daftar file dan direktori dalam format panjang. Ini memberikan informasi detail seperti hak akses, pemilik, grup, ukuran, dan waktu modifikasi untuk setiap entri dalam direktori. Misalnya, `ls -l` akan menampilkan informasi tersebut dalam format kolom yang rapi.

5.     ls -a

    ![5 ls -a](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/a58d6376-c6e3-4878-b646-f0974200d129)

   Command `ls -a` menampilkan semua file dan direktori dalam direktori saat ini, termasuk yang diawali dengan titik (biasanya file rahasia). Ini berguna untuk melihat file-file yang biasanya disembunyikan. Misalnya, `ls -a` akan menampilkan semua file, termasuk yang diawali dengan titik seperti `.bashrc`.

6.     pwd

   ![6 pwd](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/9fcb0cc5-6bfb-41fe-84cd-e881d8aec7c9)

    Command `pwd` (print working directory) menampilkan alamat direktori kerja saat ini (Path Working Directory). Ini berguna ketika Anda ingin tahu di mana Anda berada dalam struktur direktori sistem.

7.     ps

    ![7 ps](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/09bbd469-ce06-4052-84f3-20ec22d82a54)

    Command `ps` (process status) menampilkan daftar proses yang sedang berjalan di sistem. Ini berguna untuk melihat proses-proses apa saja yang sedang berjalan, serta ID proses (PID), pemilik, dan informasi lainnya.

8.     chmod

   ![8 chmod](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/baef1456-14a5-4ecb-a979-1d2168384206)

    Command `chmod` (change mode) digunakan untuk mengubah hak akses (permissions) file atau direktori. Ini memungkinkan pengguna untuk mengontrol siapa yang dapat membaca, menulis, atau mengeksekusi file atau direktori tersebut.
     Untuk melakukan command chmod perlu command tambahan seperti `chmod -R 777 file/directory` dan sejenisnya, jika ingin melihat lebih lengkap operasi chmod bisa mengunjungi laman berikut https://www.rumahweb.com/journal/chmod-adalah/

9.     usermod

    ![9 usermod](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/44f4d619-86e2-482b-bc21-c336914b2a1e)

    Command `usermod` digunakan untuk mengubah pengaturan pengguna yang ada di sistem. Ini mencakup pengubahan nama pengguna, grup, shell, dan lainnya.

10.     unzip
       
    ![10 unzip](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/5904f71f-43d9-4b91-b54c-e0e8d355ebcf)

     Command `unzip` digunakan untuk mengekstrak file yang dikompresi dalam format zip. Anda hanya perlu menulis `unzip` diikuti dengan nama file zip yang ingin Anda ekstrak, `zip_nama file`


11.     tar -xf

    
      Command `tar -xf` digunakan untuk mengekstrak file dari arsip tar. Pilihan `-xf` digunakan untuk menunjukkan bahwa Anda ingin mengekstrak file dari arsip tanpa kompresi tambahan. contoh nya 


12.     tar -xzf

      Command `tar -xzf` digunakan untuk mengekstrak file dari arsip tar yang dikompresi dengan gzip. Pilihan `-xzf` menunjukkan bahwa Anda ingin mengekstrak file dari arsip yang telah dikompresi dengan gzip.


13.     cp


     ![13 cp](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/5fed478f-70a5-49d6-ab0c-f60f135cbad8)

      Command `cp` (copy) digunakan untuk menyalin file atau direktori. Anda cukup menuliskan cp diikuti dengan nama file atau direktori yang ingin Anda salin, diikuti dengan lokasi tempat Anda ingin menyimpan salinannya.

14.     mv


       ![14 mv](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/02d0ca99-74c6-401d-a4fe-b66750aca7b0)

       Command `mv` (move) digunakan untuk memindahkan atau mengubah nama file/direktori. Misalnya, Anda bisa menuliskan `mv file1.txt Documents/` untuk memindahkan file1.txt ke dalam direktori "Documents".

15.     sudo su

       ![15 sudo su](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/b888aebe-8b6d-4ae3-942b-4385edd7fb25)

       Command `sudo su` digunakan untuk beralih ke akun lain. seperti `sudo su _namaUser`

16.     cat

      ![16 cat](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/8fde208c-b68b-4686-beb6-b220d46fb477)

     Command `cat` digunakan untuk menggabungkan dan menampilkan isi file. Ini sering digunakan untuk menampilkan isi file teks ke layar, atau untuk menggabungkan beberapa file menjadi satu.


17.     echo
    
      ![17 echo](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/dc446421-f72e-4f65-9dc7-c1f0cfe71c28)

    Command `echo` menampilkan teks ke layar atau mengirimnya ke file. Ini adalah cara sederhana untuk mencetak teks atau variabel ke terminal.


18.     touch

      ![18 touch](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/501611c3-b110-4125-adcd-4ff42a2d97d3)

      Command `touch` digunakan untuk membuat file kosong atau mengubah timestamp file yang ada. Jika file yang ditunjuk belum ada, touch akan membuat file kosong. Jika file sudah ada, touch akan mengubah waktu akses dan modifikasi file.

19.     passwd

    ![19 passwd](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/24146b2f-af69-4257-bceb-a4be33913b31)

      Command `passwd` digunakan untuk mengubah kata sandi pengguna. Setelah menjalankan perintah ini, pengguna diminta untuk memasukkan kata sandi lama, kemudian memasukkan kata sandi baru.

20.     useradd

   
    Command `useradd` digunakan untuk menambahkan pengguna baru ke dalam sistem. Ini akan membuat entri baru dalam file konfigurasi pengguna dan membuat direktori pengguna baru di /home.

21.     adduser

    ![21 add user](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/1e927c98-bd0d-42c0-ac8c-0a1d59530e17)

    Command `adduser` mirip dengan `useradd`, digunakan untuk menambahkan pengguna baru ke dalam sistem. Namun, adduser memiliki antarmuka yang lebih ramah pengguna dan melakukan beberapa langkah tambahan seperti menetapkan shell default dan membuat direktori pengguna.

22.     sudo dnf update
        sudo apt update


      ![22 sudo apt](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/3232e2ea-e8f2-4f92-a8b0-645eb1491505)

      Command `sudo dnf update atau sudo apt update` digunakan untuk memperbarui paket di sistem menggunakan manajer paket DNF (Dandified Yum) di distribusi Linux Fedora dan sejenisnya. Lalu pada `apt` digunakan pada sistem operasi seperti Ubuntu atau linux yang lainnya.

23.     ssh@ip

    ![23 ssh](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/986161c4-261f-4df7-9dff-f168c039f0e0)

    Command `ssh` digunakan untuk mengakses mesin jarak jauh melalui Secure Shell (SSH). Formatnya adalah ssh 'username@hostname' atau 'ssh 'username@ip_address.' Ini memungkinkan Anda untuk terhubung ke mesin lain dan menjalankan perintah atau mengelola file dari jarak jauh.


24.     whoami

    ![24 whoami](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/7823d960-7b07-4e31-a775-79ea7e42d0ef)

    Command `whoami` menampilkan nama pengguna saat ini yang sedang login.


25.     lsblk

      ![25 lsblk](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/24f6eabf-61df-4b92-845c-95dd7303e56e)

    Command `lsblk` menampilkan informasi tentang blok penyimpanan sistem seperti disk dan partisi.

26.     grep

                      
     Command `grep` digunakan untuk mencari pola teks dalam sebuah file. Ini dapat digunakan untuk pencarian teks yang kompleks dan pencocokan pola menggunakan ekspresi reguler.

27.     zip

     ![26 zip](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/2ecd5de6-887e-49ef-9b6f-f12696366754)

      Command `zip` digunakan untuk mengkompresi suatu file menjadi bentuk `zip` , sebagai tambahan jika ingin menggunakan command tersebut bisa menggunakan `zip nama_file_zip.zip file1 file2 file3` nama_file_zip.zip: Nama untuk file zip yang akan dibuat. file1 file2 file3 ...: Daftar file yang ingin Anda kompres menjadi file zip.

28.     vim

      ![27 vim](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/da97e860-8140-4a96-b550-434e50f984b2)

      Command `vim` adalah editor teks yang kuat dan fleksibel yang sering digunakan dalam pengembangan perangkat lunak dan administrasi sistem.

29.     nvim

      Command `nvim` adalah varian dari editor teks vim yang ditingkatkan (NeoVim) dengan banyak fitur tambahan dan perbaikan.

30.     python

      ![28 py](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/adbc44a2-5db3-4e92-80d6-d541d2d1b1db)

       Command `python` digunakan untuk menjalankan interpreter Python, yang memungkinkan Anda mengeksekusi perintah Python secara interaktif atau menjalankan skrip Python dari terminal.

31.     ../ 

      ![29   pop](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/0234fe4e-92c2-4ab8-9ad3-5e4e5f2d6375)

       Command `../` digunakan untuk merujuk ke direktori induk (parent directory) dari direktori saat ini.

32.     cd ..

     ![30 cd](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/f6ff3306-1af1-4374-890d-8792f3d87ab7)

   Command `cd ..` digunakan untuk berpindah ke direktori induk (parent directory) dari direktori saat ini.

33.     cd ~
  
    ![31 cd ~](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/7b0d76d7-91e7-4e40-ac06-89a83734abe6)

    Command `cd ~` digunakan untuk berpindah ke direktori home (direktori utama) pengguna saat ini.

34.     sl

    ![32 sl](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/9f9bfb20-9359-4a48-b0e0-6ec1b8ea8af2)

    Command `sl` menampilkan animasi kereta yang lewat di terminal. Ini sering digunakan sebagai lelucon untuk pengguna yang salah mengetikkan perintah ls.

35.     lsd

     ![33 lsd](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/606861cc-5c6b-4b94-be73-471eba0d0fdf)

      Command `lsd` adalah alternatif untuk ls yang menampilkan daftar file dan direktori dalam tata letak yang lebih bersih dan berwarna.

36.     htop

      ![34 htop](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/6d48bcad-1260-4491-801a-94ba641d680a)

       Command `htop` adalah utilitas monitor sistem interaktif yang menampilkan daftar proses yang sedang berjalan dan penggunaan sumber daya sistem dalam tampilan yang lebih ramah pengguna dibandingkan top.

37.     nvtop

       ![35 nvtop](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/d5f047e6-a9a3-434d-b275-e6689760a34a)

      Command `nvtop` adalah utilitas monitor sistem interaktif yang menampilkan penggunaan GPU NVIDIA dalam tampilan yang lebih ramah pengguna.

38.     bpytop

       Command `bpytop` adalah utilitas monitor sistem interaktif yang menampilkan penggunaan sumber daya sistem dalam tampilan yang lebih ramah pengguna dan interaktif.

39.     xdg-open

      ![36 xdg](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/cd3e3148-65af-4c69-8471-3d266548db4f)

     Command `xdg-open` digunakan untuk membuka file atau URL menggunakan aplikasi default yang terkait dengan jenis file atau URL tersebut.

40.     kwrite

     ![37 kwrite](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/c803ae08-5bb4-405b-8e33-0d58899e6fdf)

      Command `kwrite` adalah editor teks sederhana yang tersedia di lingkungan desktop KDE.

41.     libreoffice

   ![38 libreoffice](https://github.com/Chioaji/50-commands-in-Linux/assets/126127582/a3dd5f31-dd84-4447-8467-8aedeafabb77)

      Command `libreoffice` digunakan untuk membuka atau membuat dokumen menggunakan suite produktivitas LibreOffice.

42.     diff

  
      Command `diff` digunakan untuk membandingkan isi dua file dan menampilkan perbedaan di antara keduanya.

43.     rm
  
     Command `rm` digunakan untuk menghapus file. Jika Anda ingin menghapus direktori, Anda perlu menggunakan opsi -r (misalnya, `rm -r`) untuk menghapus secara rekursif.

44.     rm -r

     Command `rm -r` digunakan untuk menghapus direktori secara rekursif bersama dengan semua file dan subdirektori di dalamnya.

45.     rmdir

     Command `rmdir` digunakan untuk menghapus direktori kosong dari sistem.

46.     ping
 
     Command `ping` digunakan untuk menguji koneksi jaringan dengan mengirimkan paket ke host tertentu dan menunggu balasan.

47.     wget

     Command `wget` digunakan untuk mengunduh file dari internet menggunakan protokol HTTP, HTTPS, atau FTP.

48.     curl
  
     Command `curl` digunakan untuk mendapatkan atau mengirim data menggunakan berbagai protokol seperti HTTP, HTTPS, FTP, dan banyak lagi.

49.     nano
  
    Command `nano` adalah editor teks sederhana yang sering digunakan untuk mengedit file konfigurasi atau skrip kecil.

50.     echo >
 
     Command `echo >` digunakan untuk membuat file kosong atau mengganti konten file yang ada dengan teks yang ditentukan. Misalnya, `echo "Hello, world!" > file.txt` akan menulis teks "Hello, world!" ke dalam file.txt.

51.     last

      Command `last`digunakan untuk melihat login terakhir user


52.     cmatrix

     Command `cmatrix` digunakan untuk memunculkan tampilan layar berbentuk matrix



