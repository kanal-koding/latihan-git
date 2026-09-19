langkah langkah belajar git
1. Instal Git dan buat akun GitHub. cek versi git = **git --version** . Setelah itu atur identitas dengan **git config --global user.name "Nama Kamu"** dan **git config --global user.email "email@kamu.com"**.
2. Daftar gratis di github.com, lalu buat repository baru dengan tombol New. Beri nama, misalnya latihan-git, dan jangan centang opsi tambah README dulu supaya repository awalnya kosong.
3. Buat folder proyek, masuk ke dalamnya lewat terminal, lalu jalankan **git init**. Buat satu file (misalnya index.js), lalu **git add .** dan **git commit -m "commit pertama"**.
4. Sambungkan dengan git remote add origin <url-repository-kamu>, lalu **git branch -M main** dan **git push -u origin main**. Saat pertama kali push, Git Credential Manager (ikut terpasang di Git for Windows) akan membuka jendela browser untuk login GitHub, jadi tidak perlu mengatur token secara manual.
5. ** git status** = melihat status dari repository di folder.
6. **git branch** = untuk melihat saat ini berada di cabang mana 
7. **git switch -c ubah-judul** = Perintah ini membuat branch ubah-judul sekaligus memindahkanmu ke sana.
