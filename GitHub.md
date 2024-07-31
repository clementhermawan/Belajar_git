# membuat repository
***[[Langkah pertama]]***
Masuk ke dalam github pada web browser (chrome,bing,firefox,safari dll)
Link github : 
[[https://github.com/]]

Gambar 0.1
![[Pasted image 20240731233207.png]]

***[[Langkah kedua]]***
klik pada bagian avatar dan klik ***"Your Repository"***

Gambar 0.2
![[Pasted image 20240731233857.png]]

***[[Langkah 3]]***
klik tombol ***"New***" yang berwarna hijau

Gambar 0.3
![[Pasted image 20240731234212.png]]

***[[Langkah 4]]***
masukan ***"Repository Name"**** dan Klik tombol ***"Create Repository"*** berwarna hijau

Gambar 0.4
![[Pasted image 20240731234502.png]]

***[[Langkah Terakhir]]***
selesai sudah pembuatan ***"New Repository"*** Dalam Github

Gambar 0.5
![[Pasted image 20240731234734.png]]

# version github
code 1.1
```bash
git --version
```
Penjelasan : 
perintah yang digunakan di terminal atau command line untuk menampilkan versi dari program Git yang terinstal pada sistem

Gambar 1.1
![[Pasted image 20240731225432.png]]

# list
code 2.1
```shell
git config --list
```
Penjelasan:
perintah yang digunakan di terminal atau command line untuk menampilkan semua konfigurasi yang sedang berlaku untuk Git di sistem

Gambar 2.1
![[Pasted image 20240731225816.png]]



# user.name && user.mail
## user.name
code 3.1
```shell
git config --global user.name "Nama Username Github"
=======================================================
git config --global user.name "clementhermawan"
```
 Penjelasan:
 perintah yang digunakan di terminal atau command line untuk mengatur nama pengguna Git di tingkat global.

Gambar 3.1
![[Pasted image 20240731230252.png]]

## user.mail
code 3.2
```shell
git config --global user.mail (Nama email github)
=======================================================
git config --global user.name clementhermawan2021@gmail.com
```
 Penjelasan:
perintah yang digunakan di terminal atau command line untuk mengatur alamat email pengguna Git di tingkat global.

Gambar 3.2
![[Pasted image 20240731230458.png]]

# pwd
code 4.1
```shell
pwd
```
Penjelasan: 
perintah yang digunakan di terminal atau command line untuk menampilkan direktori kerja saat ini.

Gambar 4.1
![[Pasted image 20240731230703.png]]


# Change direktori
code 5.1
```shell
cd K:/obsidian
cd belajarGit/
```
Penjelasan: 
perintah yang digunakan di terminal atau command line untuk mengubah direktori kerja saat ini.

Gambar 5.1
![[Pasted image 20240731231622.png]]

# list
code 6.1
```shell
ls
```
Penjelasan : 
perintah yang digunakan di terminal atau command line untuk menampilkan daftar file dan direktori di dalam direktori kerja saat ini.

Gambar 6.1
![[Pasted image 20240731231745.png]]

# konfigurasi git ke github
code 7.1
```shell
git init
```
Penjelasan : 
perintah yang digunakan di terminal atau command line untuk menginisialisasi sebuah repositori Git baru dalam direktori saat ini.

Gambar 7.1
![[Pasted image 20240731232011.png]]

code 7.2
```shell
git remote add origin "link repository github"
=================================================
git remote add origin https://github.com/clementhermawan/Belajar_git.git
```
Penjelasan:
perintah yang digunakan di terminal atau command line untuk menambahkan remote repository ke repositori Git lokal

Gambar 7.2
![[Pasted image 20240731232154.png]]

code 7.3
```shell
git add.
```
Penjelasan: 
perintah yang digunakan di terminal atau command line untuk menambahkan semua file dan perubahan di direktori kerja saat ini ke staging area di Git.

Gambar 7.3
![[Pasted image 20240731232839.png]]

code 7.4
```shell
git commit -m "Awal belajar"
```
Penjelasan: 
perintah yang digunakan di terminal atau command line untuk membuat commit baru dalam repositori Git.

Gambar 7.4
![[Pasted image 20240731232852.png]]

code 7.5
```shell
git push origin master 
```
Penjelasan: 
perintah yang digunakan di terminal atau command line untuk mengirimkan commit dari repositori Git lokal Anda ke remote repository di server (seperti GitHub) pada cabang tertentu.

Gambar 7.5
![[Pasted image 20240731232908.png]]


