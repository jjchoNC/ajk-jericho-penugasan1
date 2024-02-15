# Level1 : Back To Basic

## Penugasan

1. Buat sebuah repository di GitHub. Nama repository dalam format ajk-[nama panggilan]-penugasan1. Repository ini juga sebagai tempat menaruh laporan pengerjaan untuk level selanjutnya.
Contoh: ajk-nur-penugasan1
Struktur: 
```
/src			(Berisi kode pengerjaan level 1 kalian)
README.md		(Readme utama)
level-1.md		(Laporan level 1)
level-2.md		(Laporan level 2)
level-3.md		(Laporan level 3)
level-4.md		(Laporan level 4)
```
2. Implementasikan penggunaan branching yang terdiri dari master, development, featureA, dan featureB. Codebase dibebaskan.
Implementasikan intruksi git untuk push, pull, stash, reset, diff, dan merge. Adanya tambahan intruksi git selain yang disebutkan akan lebih baik.

3. Implementasikan sebuah penanganan conflict di branch development ketika setelah merge dari branch featureA lalu merge dari branch featureB. 
Catatan: conflict bisa terjadi jika kedua branch mengerjakan di file dan line code yang sama. Buatlah skenario sendiri.

4. Gunakan merge no fast forward.

Buat dokumentasi pengerjaan kalian (level-1.md) yang setidaknya meliputi:
- Alur pengerjaan (sesuai dengan nomor soal)
- Penjelasan dari setiap alur
- Screenshot (atau record)
- Kondisi git graph (git log)
- Kendala atau kesulitan

---------------------
## Pengerjaan
### 1. Pembuatan Repository GitHub
Untuk membuat repository git, kita perlu menginisialisasi git didalam direktori yang akan digunakan sebagai _local repository_ dengan perintah `git init`.  Setelah itu tambahkan direktori dan files sesuai dengan struktur file pada perintah soal.

Setelah melakukan inisialisasi dan penambahan files dan direktori, gunakan `git add .` untuk menambahkan perubahan ke _stagging area_ lalu commit menggunakan `git commit -m "message"` dengan commit message sesuai dengan [_conventional commit message_](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13). Maka file sudah ditambahkan ke repositori lokal, selanjutnya untuk membuat _remote repository_ kita bisa langsung membuatnya pada [GitHub](https://github.com/new). Setelah itu jalankan perintah yang ada. Untuk selengkapnya bisa dilihat pada gambar dibawah ini.

![init](media/level-1/init.png)