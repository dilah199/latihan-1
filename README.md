#latihan 
#cara penggunaan GIT, dan langkah-langkahnya
1. Instal GIT
- Download GIT, buka website resminya GIT (git-scm.com)
- Lalu download seusai spek komputer kita, RAM 64bit unduh yang 64bit
- Setelah terinstal, lalu buka CMD atau Powershell, kemudian ketik perintah
2. Menambahkan Global Config
git config --global user.name "John Smith"
git config --global user.email "example@email.com"
![picture config](https://github.com/dilah199/latihan-1/blob/master/picture/userrrr.PNG)
3. Membuat Reposiory Local
Buat direktory project praktikum pertama dengan nama latiha1
• Buat direktory project praktikum pertama dengan nama latihan1
$ mkdir latihan1
$ cd latihan1
Setelah direktory aktivnya jadi: d/lab_pemograman/latihan1
4. Membuat repository local
jalankan Git init, perintah untuk membuat repository local.
$ git init
pada direktory tersebut, semua perubahan pada working direktory akan disimpan
5. Menambahkan File baru pada repository
• Untuk membuat file dapat menggunakan text editor, lalu filenya disimpan direktori aktif (repository)
.contoh file bernama README.md
$ echo “#Latihan 1” >> README.md
• File README.md berhasil dibuat.
6. Untuk menambahkan File yang baru saja di buat tersebut menggunakan git add
$ git add README.md
• File README.md berhasil ditambahkan.
7. Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
$ git add README.md
• File README.md berhasil ditambahkan.
8. Server repository yang kita gunakan adalah https://github.com lalu anda harus membuat akun terlebih dahulu
9. Untuk menambahkan Remmote repository server gunakan perintah git remote add origin [url]
10. Untuk mengirim perubahan pada local repository ke server gunakan perintah git push
11. Untuk masuk ke nano
    1. $ cd /d
    2. $ cd lab_pemograman/
    3. $ cd latihan1/
    4. $ nano README.md
