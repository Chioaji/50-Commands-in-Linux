# 50 commands

Note:Untuk mencoba command ini bisa menggunakan OS linux, Virtual machine basis Linux, atau bisa menggunakan Lab virtual terminal di website RedHat.com 

1.     ls
   
    Command `ls` (list) digunakan untuk menampilkan daftar file dan direktori dalam direktori saat ini. Ini adalah salah satu command yang paling sering digunakan untuk navigasi file sistem. Tanpa argumen tambahan, `ls` akan menampilkan daftar file dan direktori secara vertikal.
     
2.     cd

   
    Command `cd` (change directory) digunakan untuk berpindah dari satu direktori ke direktori lain dalam sistem file. Anda cukup menulis `cd` diikuti dengan nama direktori yang ingin Anda masuki. Misalnya, `cd Document` akan membawa Anda ke dalam direktori "Documents".

3.     mkdir

   
    Command `mkdir` (make directory) digunakan untuk membuat direktori baru dalam sistem file. Anda hanya perlu menuliskan `mkdir` diikuti dengan nama direktori yang ingin Anda buat. Misalnya, `mkdir Photos` akan membuat direktori baru bernama "Photos" di dalam direktori saat ini.

4.     ls -l

   
    Command `ls -l` menampilkan daftar file dan direktori dalam format panjang. Ini memberikan informasi detail seperti hak akses, pemilik, grup, ukuran, dan waktu modifikasi untuk setiap entri dalam direktori. Misalnya, `ls -l` akan menampilkan informasi tersebut dalam format kolom yang rapi.

5.     ls -a

    
   Command `ls -a` menampilkan semua file dan direktori dalam direktori saat ini, termasuk yang diawali dengan titik (biasanya file rahasia). Ini berguna untuk melihat file-file yang biasanya disembunyikan. Misalnya, `ls -a` akan menampilkan semua file, termasuk yang diawali dengan titik seperti `.bashrc`.

6.     pwd

    
    Command `pwd` (print working directory) menampilkan alamat direktori kerja saat ini (Path Working Directory). Ini berguna ketika Anda ingin tahu di mana Anda berada dalam struktur direktori sistem.

7.     ps

    
    Command `ps` (process status) menampilkan daftar proses yang sedang berjalan di sistem. Ini berguna untuk melihat proses-proses apa saja yang sedang berjalan, serta ID proses (PID), pemilik, dan informasi lainnya.

8.     chmod
   
    Command `chmod` (change mode) digunakan untuk mengubah hak akses (permissions) file atau direktori. Ini memungkinkan pengguna untuk mengontrol siapa yang dapat membaca, menulis, atau mengeksekusi file atau direktori tersebut.

9.     usermod

    
    Command `usermod` digunakan untuk mengubah pengaturan pengguna yang ada di sistem. Ini mencakup pengubahan nama pengguna, grup, shell, dan lainnya.

10.     unzip
    
     Command `unzip` digunakan untuk mengekstrak file yang dikompresi dalam format zip. Anda hanya perlu menulis `unzip` diikuti dengan nama file zip yang ingin Anda ekstrak.


11.     tar -xf
    
      Command `tar -xf` digunakan untuk mengekstrak file dari arsip tar. Pilihan `-xf` digunakan untuk menunjukkan bahwa Anda ingin mengekstrak file dari arsip tanpa kompresi tambahan.


12.     tar -xzf

      Command `tar -xzf` digunakan untuk mengekstrak file dari arsip tar yang dikompresi dengan gzip. Pilihan `-xzf` menunjukkan bahwa Anda ingin mengekstrak file dari arsip yang telah dikompresi dengan gzip.


13.     cp

      Command `cp` (copy) digunakan untuk menyalin file atau direktori. Anda cukup menuliskan cp diikuti dengan nama file atau direktori yang ingin Anda salin, diikuti dengan lokasi tempat Anda ingin menyimpan salinannya.

14.     mv

       Command `mv` (move) digunakan untuk memindahkan atau mengubah nama file/direktori. Misalnya, Anda bisa menuliskan `mv file1.txt Documents/` untuk memindahkan file1.txt ke dalam direktori "Documents".

15.     sudo -su

       Command `sudo -su` digunakan untuk beralih ke akun superuser (root) dengan menggunakan hak akses sudo. Ini memungkinkan Anda untuk menjalankan perintah sebagai superuser, memberi Anda akses penuh ke sistem.

16.     cat

     Command `cat` digunakan untuk menggabungkan dan menampilkan isi file. Ini sering digunakan untuk menampilkan isi file teks ke layar, atau untuk menggabungkan beberapa file menjadi satu.


17.     echo
    
     Command `echo` menampilkan teks ke layar atau mengirimnya ke file. Ini adalah cara sederhana untuk mencetak teks atau variabel ke terminal.


18.     touch

      Command `touch` digunakan untuk membuat file kosong atau mengubah timestamp file yang ada. Jika file yang ditunjuk belum ada, touch akan membuat file kosong. Jika file sudah ada, touch akan mengubah waktu akses dan modifikasi file.

19.     passwd
    
      Command `passwd` digunakan untuk mengubah kata sandi pengguna. Setelah menjalankan perintah ini, pengguna diminta untuk memasukkan kata sandi lama, kemudian memasukkan kata sandi baru.

20.     useradd

    Command `useradd` digunakan untuk menambahkan pengguna baru ke dalam sistem. Ini akan membuat entri baru dalam file konfigurasi pengguna dan membuat direktori pengguna baru di /home.

21.     adduser
    
    Command `adduser` mirip dengan `useradd`, digunakan untuk menambahkan pengguna baru ke dalam sistem. Namun, adduser memiliki antarmuka yang lebih ramah pengguna dan melakukan beberapa langkah tambahan seperti menetapkan shell default dan membuat direktori pengguna.

22.     sudo dnf update
        sudo apt update

  Command `sudo dnf update atau sudo apt update` digunakan untuk memperbarui paket di sistem menggunakan manajer paket DNF (Dandified Yum) di distribusi Linux Fedora dan sejenisnya. Lalu pada `apt` digunakan pada sistem operasi seperti Ubuntu atau linux yang lainnya.

23.     ssh@ip
    
    Command `ssh` digunakan untuk mengakses mesin jarak jauh melalui Secure Shell (SSH). Formatnya adalah ssh 'username@hostname' atau 'ssh 'username@ip_address.' Ini memungkinkan Anda untuk terhubung ke mesin lain dan menjalankan perintah atau mengelola file dari jarak jauh.


24.     whoami
    
    Command `whoami` menampilkan nama pengguna saat ini yang sedang login.


25.     lsblk

    Command `lsblk` menampilkan informasi tentang blok penyimpanan sistem seperti disk dan partisi.

26.     grep
                      
     Command `grep` digunakan untuk mencari pola teks dalam sebuah file. Ini dapat digunakan untuk pencarian teks yang kompleks dan pencocokan pola menggunakan ekspresi reguler.

28.     pwd
    
      Command `pwd` menampilkan alamat direktori kerja saat ini (Path Working Directory). Ini adalah alat yang berguna untuk mengetahui lokasi Anda dalam struktur direktori.

30.     vim

      Command `vim` adalah editor teks yang kuat dan fleksibel yang sering digunakan dalam pengembangan perangkat lunak dan administrasi sistem.

31.     nvim

      Command `nvim` adalah varian dari editor teks vim yang ditingkatkan (NeoVim) dengan banyak fitur tambahan dan perbaikan.

32.     python

       Command `python` digunakan untuk menjalankan interpreter Python, yang memungkinkan Anda mengeksekusi perintah Python secara interaktif atau menjalankan skrip Python dari terminal.

33.     ../ 

       Command `../` digunakan untuk merujuk ke direktori induk (parent directory) dari direktori saat ini.

34.     cd ..

   Command `cd ..` digunakan untuk berpindah ke direktori induk (parent directory) dari direktori saat ini.

35.     cd ~
   
    Command `cd ~` digunakan untuk berpindah ke direktori home (direktori utama) pengguna saat ini.

36.     sl

    Command `sl` menampilkan animasi kereta yang lewat di terminal. Ini sering digunakan sebagai lelucon untuk pengguna yang salah mengetikkan perintah ls.

37.     lsd
   
      Command `lsd` adalah alternatif untuk ls yang menampilkan daftar file dan direktori dalam tata letak yang lebih bersih dan berwarna.

38.     htop
   
       Command `htop` adalah utilitas monitor sistem interaktif yang menampilkan daftar proses yang sedang berjalan dan penggunaan sumber daya sistem dalam tampilan yang lebih ramah pengguna dibandingkan top.

39.     nvtop

      Command `nvtop` adalah utilitas monitor sistem interaktif yang menampilkan penggunaan GPU NVIDIA dalam tampilan yang lebih ramah pengguna.

40.     bpytop

       Command `bpytop` adalah utilitas monitor sistem interaktif yang menampilkan penggunaan sumber daya sistem dalam tampilan yang lebih ramah pengguna dan interaktif.

41.     xdg-open

     Command `xdg-open` digunakan untuk membuka file atau URL menggunakan aplikasi default yang terkait dengan jenis file atau URL tersebut.

42.     kwrite
    
      Command `kwrite` adalah editor teks sederhana yang tersedia di lingkungan desktop KDE.

43.     libreoffice

      Command `libreoffice` digunakan untuk membuka atau membuat dokumen menggunakan suite produktivitas LibreOffice.

44.     diff
  
      Command `diff` digunakan untuk membandingkan isi dua file dan menampilkan perbedaan di antara keduanya.

45.     rm
  
     Command `rm` digunakan untuk menghapus file. Jika Anda ingin menghapus direktori, Anda perlu menggunakan opsi -r (misalnya, `rm -r`) untuk menghapus secara rekursif.

46.     rm -r

     Command `rm -r` digunakan untuk menghapus direktori secara rekursif bersama dengan semua file dan subdirektori di dalamnya.

47.     rmdir

     Command `rmdir` digunakan untuk menghapus direktori kosong dari sistem.

48.     ping
 
     Command `ping` digunakan untuk menguji koneksi jaringan dengan mengirimkan paket ke host tertentu dan menunggu balasan.

49.     wget

     Command `wget` digunakan untuk mengunduh file dari internet menggunakan protokol HTTP, HTTPS, atau FTP.

50.     curl
  
     Command `curl` digunakan untuk mendapatkan atau mengirim data menggunakan berbagai protokol seperti HTTP, HTTPS, FTP, dan banyak lagi.

51.     nano
  
    Command `nano` adalah editor teks sederhana yang sering digunakan untuk mengedit file konfigurasi atau skrip kecil.

52.     echo >
 
     Command `echo >` digunakan untuk membuat file kosong atau mengganti konten file yang ada dengan teks yang ditentukan. Misalnya, `echo "Hello, world!" > file.txt` akan menulis teks "Hello, world!" ke dalam file.txt.

53.     last

      Command `last`digunakan untuk melihat login terakhir user



