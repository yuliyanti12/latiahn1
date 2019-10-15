#latihan1
#mengenal version control system (vcs)
vcs adalahsebuah system yang mencatat semua perubahan yang terjadi pada file atau sekumpulan file seiring dengan waktu, jadi dengan demikian kamu dapat memanggil versi spesifiknya dilain waktu
langkah-langkah menggunakan git
1. membuat repository dengan perintah `git init`
2. membuat file dengan perintah contoh `echo "#latihan1" > Readme.md`
3. mengedit isi file tersebut dengan perintah `nano <nama_file>`
4. menggunakan perintah "git add" untuk menambah file baru, atau perubahan perubahan pada file contoh `git add README`
5. menyimpan perubahan yang ada kedalam database repository local, gunakan perintah contoh `git commit -m "file pertama saya"`
6. membuat repository server dengan http://github.com, pada laman tersebut klik tombol start a project, klik icon + klik New Repository
7. isi nama repository contoh `lab_pemprograman` 
8. nemanbahkan remote repository, gunakan perintah `git remote add origin http://github.com/yuliyanti12/latihan1.git
9. mengirim perubahan pada local repository ke server gunakan perintah `git push` 
10. untuk masuk ke nano 
	1. $ cd /d
	2. $ lab_pemprograman
	3. $ cd latihan1
	4. $ nano README.md
#latihan2
