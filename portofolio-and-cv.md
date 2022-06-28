1. Membuat sebuah folder kosong dnegan namamu sendiri. (mkdir jakii)
2. Membuat sebuah file didalam folder tersebut dengan nama README.md, isi file tersebut dengan kalimat "Halo perkenalkan aku halaman utama" (cd jakii, touch README.md, vim README.md)
3. Inisialisasi folder tersebut dengan Git, kemudian simpan perubahan menggunkan commit dengan pesan "First commit" (git init, git add README.md, git commit -m "First commit")
4. Ganti teks sebelumnya dengan "Hello world" (vim README.md)
5. Tampilkan isi teks tersebut pada command line menggunakan cat (cat README.md)
6. Ternyata kamu tidak ingin perubahan tersebut, dan tidak ingin kembali ke perubahan seperti commit yang terakhir. Lakukan teknik git backtracking untuk mengembalikan ke perubahan commit yang terakhir (git checkout README.md)
7. Buat branch baru dengan nama cv,hal ini berguna agar history kita tidak tercampur (git branch cv)
8. Pindah branch ke dalam cv, kemudian buat file dengan nama cv.txt dan isi file tersebut dengan kalimat : "Ini adalah file CV" (git checkout cv, touch cv.txt, vim cv.txt)
9. Kemudian simpan perubahan menggunakan commit dengan pesan "Initial CV" (git add cv.txt, git commit -m "Initial CV")
10. Tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi dan menyimpan perubahan menggunakan commit 
(vim cv.txt, git add cv.txt, git commit -m "menambahkan perusahaan pertama"
vim cv.txt, git add cv.txt, git commit -m "menambahkan perusahaan kedua"
vim cv.txt, git add cv.txt, git commit -m "menambahkan perusahaan ketiga")
11. Kembali ke branch master (git checkout master)
12. Ubah file README.md menjadi 
Halo perkenalkan aku halaman utama
Ini adalah updtae pertama pada branch
jangan lupa untuk menyimpan perubahan menggunakan commit dengan pesan "update master pertama" (vim README.md, git commit -m "update master pertama")
13. Gabungkan branch cv ke dalam branch master menggunakan perintah git merge (git merge cv)
14 Unggah Git Repository project tersebut kedalam GitHub (git remote add origin https://github.com/Jaki971/Version-Control-with-Git-GitHub, git push -u origin master)
