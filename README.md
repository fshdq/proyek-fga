
# FGA 2022 FRONTEND - KELAS E - Kelompok A01
Website ini merupakan tugas dari [DIGITALENT KOMINFO](https://digitalent.kominfo.go.id) yang bekerja sama dengan [Progate](https://progate.com)
Website yang kami buat adalah portofolio dari tim kami dengan menampilkan anggota kelompok dan profil dari anggota



## Quick start

 - Clone repository ini
 ```
    https://github.com/fshdq/proyek-fga.git
```
 
 - [Buatlah branch baru](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)
 ``` 
    git checkout -b [name_of_your_new_branch]
``` 

 - Setelah melakukan beberapa perubahan, buatlah sebuah commit dengan langkah contoh berikut:
 ```
    git add .
    git commit -m "membuat navigation, melakukan perubahan pada card details"
 ```

 - Ketika commit sudah ditambahkan, push perubahan tersebut ke github
Ketika push pertama kali, maka perintah yang digunakan adalah:
 ``` 
    git push origin [name_of_your_new_branch]
 ```
 Ketika sudah sering melakukan push branch, maka cukup melakukan perintah:
 ```
    git push
 ```

## Merging

Untuk melakukan merge, gunakan perintah dibawah:

```bash
  git checkout development
  git pull
  git merge [branch-yang-anda-pilih]
```

Contoh, Anda sudah melakukan perubahan Navbar pada branch `navbar`. Maka langkah yang Anda lakukan adalah
```bash
   git checkout development
   git pull
   git merge [navbar]
```

Jika terdapat conflict, Anda dapat menghubungi saya di [Telegeram](https://t.me/fshdq) 

## Guide
- ```text-decoration.css``` digunakan untuk melakukan perubahan pada text
- ```layout.css``` digunakan untuk melakukan perubahan pada layout

