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

      Command cp (copy) digunakan untuk menyalin file atau direktori. Anda cukup menuliskan cp diikuti dengan nama file atau direktori yang ingin Anda salin, diikuti dengan lokasi tempat Anda ingin menyimpan salinannya.

mv: Command mv (move) digunakan untuk memindahkan atau mengubah nama file/direktori. Misalnya, Anda bisa menuliskan mv file1.txt Documents/ untuk memindahkan file1.txt ke dalam direktori "Documents".

sudo -su: Command sudo -su digunakan untuk beralih ke akun superuser (root) dengan menggunakan hak akses sudo. Ini memungkinkan Anda untuk menjalankan perintah sebagai superuser, memberi Anda akses penuh ke sistem.

cat: Command cat digunakan untuk menggabungkan dan menampilkan isi file. Ini sering digunakan untuk menampilkan isi file teks ke layar, atau untuk menggabungkan beberapa file menjadi satu.

echo: Command echo menampilkan teks ke layar atau mengirimnya ke file. Ini adalah cara sederhana untuk mencetak teks atau variabel ke terminal.

touch: Command touch digunakan untuk membuat file kosong atau mengubah timestamp file yang ada. Jika file yang ditunjuk belum ada, touch akan membuat file kosong. Jika file sudah ada, touch akan mengubah waktu akses dan modifikasi file.

passwd: Command passwd digunakan untuk mengubah kata sandi pengguna. Setelah menjalankan perintah ini, pengguna diminta untuk memasukkan kata sandi lama, kemudian memasukkan kata sandi baru.

useradd: Command useradd digunakan untuk menambahkan pengguna baru ke dalam sistem. Ini akan membuat entri baru dalam file konfigurasi pengguna dan membuat direktori pengguna baru di /home.

adduser: Command adduser mirip dengan useradd, digunakan untuk menambahkan pengguna baru ke dalam sistem. Namun, adduser memiliki antarmuka yang lebih ramah pengguna dan melakukan beberapa langkah tambahan seperti menetapkan shell default dan membuat direktori pengguna.

sudo dnf update: Command sudo dnf update digunakan untuk memperbarui paket di sistem menggunakan manajer paket DNF (Dandified Yum) di distribusi Linux Fedora dan sejenisnya.

ssh@ip: Command ssh digunakan untuk mengakses mesin jarak jauh melalui Secure Shell (SSH). Formatnya adalah ssh username@hostname atau ssh username@ip_address. Ini memungkinkan Anda untuk terhubung ke mesin lain dan menjalankan perintah atau mengelola file dari jarak jauh.

whoami: Command whoami menampilkan nama pengguna saat ini yang sedang login.

lsblk: Command lsblk menampilkan informasi tentang blok penyimpanan sistem seperti disk dan partisi.

grep: Command grep digunakan untuk mencari pola teks dalam sebuah file. Ini dapat digunakan untuk pencarian teks yang kompleks dan pencocokan pola menggunakan ekspresi reguler.

pwd: Command pwd menampilkan alamat direktori kerja saat ini (Path Working Directory). Ini adalah alat yang berguna untuk mengetahui lokasi Anda dalam struktur direktori.

vim: Command vim adalah editor teks yang kuat dan fleksibel yang sering digunakan dalam pengembangan perangkat lunak dan administrasi sistem.

nvim: Command nvim adalah varian dari editor teks vim yang ditingkatkan (NeoVim) dengan banyak fitur tambahan dan perbaikan.

python: Command python digunakan untuk menjalankan interpreter Python, yang memungkinkan Anda mengeksekusi perintah Python secara interaktif atau menjalankan skrip Python dari terminal.

../: Command ../ digunakan untuk merujuk ke direktori induk (parent directory) dari direktori saat ini.

cd ..: Command cd .. digunakan untuk berpindah ke direktori induk (parent directory) dari direktori saat ini.

cd ~: Command cd ~ digunakan untuk berpindah ke direktori home (direktori utama) pengguna saat ini.

sl: Command sl menampilkan animasi kereta yang lewat di terminal. Ini sering digunakan sebagai lelucon untuk pengguna yang salah mengetikkan perintah ls.

lsd: Command lsd adalah alternatif untuk ls yang menampilkan daftar file dan direktori dalam tata letak yang lebih bersih dan berwarna.

htop: Command htop adalah utilitas monitor sistem interaktif yang menampilkan daftar proses yang sedang berjalan dan penggunaan sumber daya sistem dalam tampilan yang lebih ramah pengguna dibandingkan top.

nvtop: Command nvtop adalah utilitas monitor sistem interaktif yang menampilkan penggunaan GPU NVIDIA dalam tampilan yang lebih ramah pengguna.

bpytop: Command bpytop adalah utilitas monitor sistem interaktif yang menampilkan penggunaan sumber daya sistem dalam tampilan yang lebih ramah pengguna dan interaktif.

xdg-open: Command xdg-open digunakan untuk membuka file atau URL menggunakan aplikasi default yang terkait dengan jenis file atau URL tersebut.

kwrite: Command kwrite adalah editor teks sederhana yang tersedia di lingkungan desktop KDE.

libreoffice: Command libreoffice digunakan untuk membuka atau membuat dokumen menggunakan suite produktivitas LibreOffice.

diff: Command diff digunakan untuk membandingkan isi dua file dan menampilkan perbedaan di antara keduanya.

rm: Command rm digunakan untuk menghapus file. Jika Anda ingin menghapus direktori, Anda perlu menggunakan opsi -r (misalnya, rm -r) untuk menghapus secara rekursif.

rm -r: Command rm -r digunakan untuk menghapus direktori secara rekursif bersama dengan semua file dan subdirektori di dalamnya.

rmdir: Command rmdir digunakan untuk menghapus direktori kosong dari sistem.

ping: Command ping digunakan untuk menguji koneksi jaringan dengan mengirimkan paket ke host tertentu dan menunggu balasan.

wget: Command wget digunakan untuk mengunduh file dari internet menggunakan protokol HTTP, HTTPS, atau FTP.

curl: Command curl digunakan untuk mendapatkan atau mengirim data menggunakan berbagai protokol seperti HTTP, HTTPS, FTP, dan banyak lagi.

nano: Command nano adalah editor teks sederhana yang sering digunakan untuk mengedit file konfigurasi atau skrip kecil.

echo >: Command echo > digunakan untuk membuat file kosong atau mengganti konten file yang ada dengan teks yang ditentukan. Misalnya, echo "Hello, world!" > file.txt akan menulis teks "Hello, world!" ke dalam file.txt.




