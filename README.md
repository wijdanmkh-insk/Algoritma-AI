# Algoritma-AI

## List of Folders
Search system => Wijdan\
Expert system => Tata\
Multiagent system => ?\

## Tutorial Akses Github
Untuk mengakses github dan melakukan push/pull, lakukan langkah berikut.
### Clone Repository
Silahkan clone repository ini dengan mengetik ini ke terminal komputer. Clone digunakan untuk **download file** yang ada di repository ini
```
git clone git@github.com:wijdanmkh-insk/Algoritma-AI.git
```

### Tambahkan Branch Baru
Cek semua branch (cabang) yang tersedia dengan menggunakan:
```
git branch -v
```
Nanti akan muncul tampilan seperti berikut. 
```
main         d876ecb First commit
```
Untuk mencegah konflik file yang tersedia, *pastikan membuat branch baru.** Untuk membuat branch baru, gunakan perintah: 
```
git branch [Nama Branch]
```

contoh: 
```
git branch Dev-1_Wijdan
```

### Cek Branch Saat Ini
Untuk mengecek branch saat ini, gunakan perintah: 
```
git branch -v
```
Perintah ini akan menampilkan:
```
* Dev-1_Wijdan 0c2d017 From Wijdan
  main         d876ecb First commit
```
_Jika ada tanda *, itu adalah branch saat ini_

Jika ingin pindah branch, dari main ke Dev-1_Wijdan, gunakan perintah:
```
git checkout [Nama Branch]
```

contoh:
```
git checkout Dev-1_Wijdan
```

### Edit File
Setelah pindah branch, silahkan edit file yang diinginkan sesuka hati. Selamat mencoba!

### Proses Commit dan Push
Setelah mengubah semua isi file, tambahkan semua file yang sudah diedit ke dalam branch. Gunakan perintah:
```
git add .
```
Kemudian tambahkan commit untuk memberi keterangan file apa yang sudah diubah. Gunakan perintah:
```
git commit -m "[Pesan untuk semua pekerja disini]
```
contoh:
```
git commit -m "Menambahkan search system"
```
Kemudian push semua yang sudah diubah supaya muncul di halaman github
```
git push origin [Nama Branch Saat Ini]
```
contoh: 
```
git push origin Dev-1_Wijdan
```

## Tutorial Menggabungkan semua branch
### Akses ke Web
Buka repository yang ada di github

### Buka Pull Request
Pull request digunakan untuk menggabungkan beberapa branch ke branch utama agar branch dengan fungsi berbeda dapat disatukan dalam **branch main**. Jika muncul notifikasi kuning dari github, tekan tombol hijau **Pull Request**

