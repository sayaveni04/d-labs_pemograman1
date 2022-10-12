# CARA PENGUNAAN GIT

 ## Instalasi GIT

### - Download GIT, buka website resminya Git (git-scm-com). 
### - Kemudian untuk git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
### - Selamat, Git sudah terinstal di Windows, Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah
```
git --version
```
![Gambar1](gambar/git1.png)

### - Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi *user.name* dan *user.email*'
### - Konfigurasi ini bisa dilakukan untuk global repository atau individual repository
### - Apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perint globah git commit


### - Config Global Repository
```
$ git config -- global user.name "nama_user"
```
```
$ git config -- global user.email "nama_user"
```

## Perintah Dasar Git


### - git init, perintah untuk membuat repository lokal.
### - gti add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
### - git commit, perintah untuk meyimpan perubahan kedalam database git.
### - git push -u origin master, perintah untuk mengirim perubahan pada repository lokal menuju server repository.
### - git clone [url], perintah untuk membuat working directory yang diambil dari repository server.
### - git remote add origin[url], perintah untuk menambahkan remote server/repository server pada lokal repository (*working directoty*)
### - git pull, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke lokal repository.

## Membuat Repository Lokal

### - 
