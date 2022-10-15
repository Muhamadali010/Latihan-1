# Latihan_1
CARA MENGGUNAKAN GIT
1.Download Git, buka website resminya Git (git-scm.com).

2.Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

3.setelah terinstall,Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah

git --version.

![image](SC/1.png)

Menambahkan Global Config
1.Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
2.konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.
apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit
    
Config Global Repository
$ git config --global user.name “nama_user”
$ git config --global user.email “nama_user”


Membuat Reposiory Local
• Buka direktory aktif, misal: /d/Latihan VCS (buka menggunakan Windows Explorer)
• Buat direktory project praktikum pertama dengan nama <strong>Tugas1
