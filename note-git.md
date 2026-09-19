langkah langkah belajar git
1. Instal Git dan buat akun GitHub. cek versi git = **git --version** . Setelah itu atur identitas dengan **git config --global user.name "Nama Kamu"** dan **git config --global user.email "email@kamu.com"**.
2. Daftar gratis di github.com, lalu buat repository baru dengan tombol New. Beri nama, misalnya latihan-git, dan jangan centang opsi tambah README dulu supaya repository awalnya kosong.
3. Buat folder proyek, masuk ke dalamnya lewat terminal, lalu jalankan **git init**. Buat satu file (misalnya index.js), lalu **git add .** dan **git commit -m "commit pertama"**.
4. Sambungkan dengan git remote add origin <url-repository-kamu>, lalu **git branch -M main** dan **git push -u origin main**. Saat pertama kali push, Git Credential Manager (ikut terpasang di Git for Windows) akan membuka jendela browser untuk login GitHub, jadi tidak perlu mengatur token secara manual.
5. ** git status** = melihat status dari repository di folder.
6. **git branch** = untuk melihat saat ini berada di cabang mana 
7. **git switch -c ubah-judul** = Perintah ini membuat branch ubah-judul sekaligus memindahkanmu ke sana.
8. **git diff** (dijalankan sebelum git add) menampilkan baris mana yang berubah.
9. git switch main = pindah ke branch main
Buka lagi index.html, dan isinya kembali seperti semula. Perubahanmu aman tersimpan di branch ubah-judul. Pindah bolak-balik dengan git switch ubah-judul dan git switch main untuk melihatnya sendiri.
10. git branch -d ubahJudul-tambahParagraf atau git branch -d versi-pertama versi-kedua
= menghapus branch yang sudah tidak diperlukan
11. git log --oneline = Ini menampilkan daftar commit-mu secara ringkas.
12. catatan kecil 
Jalankan git status kapan saja kamu ragu. Di tengah konflik, Git menampilkan file mana yang masih bermasalah dan apa langkah berikutnya.
Kalau merasa berantakan, git merge --abort selalu bisa mengembalikan keadaan seperti sebelum merge atau membatalkan merge dan mengembalikan semuanya seperti sebelum git merge dijalankan.
Sebelum git add, pastikan tanda <<<<<<<, =======, dan >>>>>>> sudah hilang dari file.
13. pull request (PR). PR adalah cara mengajukan perubahan dari sebuah branch untuk digabung ke main lewat GitHub. Di dunia kerja, hampir semua perubahan kode masuk lewat PR, karena ada kesempatan meninjau dulu sebelum digabung. Meskipun repository ini milikmu sendiri, kamu tetap bisa berlatih alurnya.

Sekalian kita buat file README.md, yaitu halaman depan repository yang menjelaskan proyekmu.