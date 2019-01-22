# Tutorial Penggunaan Git <h1>
## Apa itu Git? <h2>
* Git adalah salah satu sistem pengontrol versi (Version Control
System) pada proyek perangkat lunak yang diciptakan oleh Linus
Torvalds. 
* Pengontrol versi bertugas mencatat setiap perubahan pada file
proyek yang dikerjakan oleh banyak orang maupun sendiri. 
* Git dikenal juga dengan distributed revision control (VCS terdistribusi),
artinya penyimpanan database Git tidak hanya berada dalam satu
tempat saja

## Menambahkan Global Config <h2>
* Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
user name dan user email
* konfigurasi ini bisa dilakukan untuk global repostiry atau individual
repository. 
* apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi
kegagalan saat menjalankan perintah git commit
* Lakukan "git config --global user.name dan emal " 
supaya bisa login github ketika push
![GitHub Logo](1.png) 

## Perintah Dasar Git <h2>
* git init, perintah untuk membuat repository local
* git add, perintah untuk menambahkan file baru, atau perubahan
pada file pada staging sebelum proses commit. 
* git commit, perintah untuk menyimpan perubahan kedalam database git. 
* git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository. 
* git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
* git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

## Membuat Reposiory Local <h2>
* Buka direktory aktif, misal: c:/Latihan
* Buat direktory project praktikum pertama dengan nama Latihan
* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change
directory)
* direktory aktif menjadi: c:/Latihan 
* Buatlah direktory "Latihan" kemudian masuk ke direktory tersebut
![GitHub Logo](2.png)
* Lakukan "git init" untuk menjadikan repository lokal
![GitHub Logo](3.png)
* Buat File Bernama "README.md" (text file), jika file berhasil dibuat, akan tampil seperti dlm gambar
![GitHub Logo](4.png)
* kemudian tambahkan file tersebut ke repository dengan " git add 
README.md, file yang berhasil ditambahkan akan terlihat seperti di 
gambar, dengan "git status"
![GitHub Logo](5.png)
* Untuk  Menyimpan perubahan sebuah file ke repository local gunakan 
printah " git commit -m "perubahan yang terjadi"
![GitHub Logo](6.png)
## Membuat repository server <h2>
* Server reopsitory yang akan kita gunakan adalah http://github.com
* Anda harus membuat akun terlebih dahulu. • Pada laman github, klik tombol start a project, atau
* Dari menu (icon +) klik New Repository

## Membuat repository server <h2>
* Isi nama repositorynya, misal: Latihan1.  
* lalu klik tombol **Create repository**

## Menambahkan Remote Repository <h2>
* Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository,
sehingga dapat diakses oleh banyak user. 
* Untuk menambahkan remote repository server, gunakan perintah
git remote add origin [url]
 
## Push (Mengirim perubahan ke server) <h2>
* Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
* Perintah ini akan meminta memasukkan username dan password pada akun github.com
* Gunakan printah " git push -u origin master"
![GitHub Logo](8.png)

## Melihat hasilnya pada server repository <h2>
* Buka laman github.com, arahkan pada repositori- nya. 
* Maka perubahan akan terlihat pada laman tersebut.
![GitHub Logo](9.png)
