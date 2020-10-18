# Latihan 1
### APA ITU GIT ?
* Git adalah salah satu sistem pengontrol versi (Version ControlSystem) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.
* Pengontrol versi bertugas mencatat setiap perubahan pada fileproyek yang dikerjakan oleh banyak orang maupun sendiri.
* Git dikenal juga dengan distributed revision control (VCS terdistribusi),artinya penyimpanan database Git tidak hanya berada dalam satutempat saja.


### INSTALASI GIT
* Download *Git*, buka website resminya Git `(git-scm.com)`.
* Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
* Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka *CMD* atau *PowerShell*, kemudian ketik perintah

``git --version``

![Anotasi 2020-10-18 131620](https://user-images.githubusercontent.com/72904723/96360755-04c1e480-114a-11eb-8e1a-2e259ae5f836.png)

Menambahkan Global Config
Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email

konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.

apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit

Config Global Repository

$ git config --global user.name “nama_user"

$ git config --global user.email “nama_user”

![Anotasi 2020-10-18 132356](https://user-images.githubusercontent.com/72904723/96360854-f7f1c080-114a-11eb-856a-fcadabe70f4f.png)
