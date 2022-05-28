# 02_Version Control and Branch Management (Git)

Sebelum membahas mengenai Github,kita harus mengetahui terlebih dahulu bahwa Github sendiri memiliki induk versinya,yaitu "Git". Git sendiri merupakan sebuah software VCS (Version Controlled System) yang dilakukan secara offline.
Nah apa yang dimaksud dengan Github? Github merupakan layanan hos web bersama untuk proyek pengembangan perangkat lunak yang mengggunakan sistem kendali versi Git dan layanan hosting internet.Hal ini banyak digunakan untuk kode komputer.Github juga memberikan layanan cloud untuk menyimpan dan mengelola project/repository git. Karena bersifat online,kita mengedit sebuah repository/project secara bersamaan dengan orang lain di tempat yang berbeda. Oleh karena itu platform ini sangat membantu tim project dalam menyusun suatu folder yang berisikan file terkait pemrograman.
Pengistalan Git
Penginstalan git dapat dilakukan di OS, MAC, WINDOWS, dan LINUX. 
⦁	Setingg Up Git
⦁	Congfit : git congfit –global user .name  “isi _username”
: git congfit –global user .name  “isi _email”
⦁	Ada 2 cara untuk menset secara global, username dan email yang terdaftar di platform github, gitlab dan lainnya.
⦁	Git init merupakan  perintah yang berfungsi untuk membuat folder local include dengan config git secara global.
 Github menyediakan banyak sekali fitur bagi penggunanya,salah satunya ialah integrasi dengan aplikasi Git yang dapat memudahkan kita untukmelakukan proses clone ataupun duplikasi sebuah konten pada repository Github.
Sebelumnya sebelum melalukan clone terlebih dahulu kita harus memastikan bahwa Git telah terinstal pada sistem operasi kita.

⦁	Clone : git clone <link ssh/link hhtp_github>
: git clone -b <nama _branch> <link ssh/link hhtp_github>
Yang berfungsi untuk mengclone repository online ke local dengan nama folder sesuai nama repo.
⦁	Git staged Area, area disini biasa disebut perubahan. File-file atau perubahan yang kita lakukan akan diatur seperti melakukan commit dan push.
⦁	git add  untukmenambahkan file ke area siap untuk di commit
⦁	git commit untuk melakukan commit di branch yang kita lakukan perubahan, setiap commit ada history untuk mempermudah kita .
⦁	git commit –m “message” dalam melakukan commit harus meninggalkan pesan berupa informasi terkait apa yang sudah dilakukan didalam branch, seperti perubahan dan lainnya. Untuk memperjelas status log commit kita. Karena itu pesan atau message kita harus jelas.
⦁	git push origin <nama_branch> adlah untuk melakukan push branch local ke branch online dan mengupdatesemua perubahannya.
⦁	Git diff dan stash
⦁	git diff --staged untuk melakukan check terhadap perubahan apa saja yang dilakukan di area staged.
⦁	git stash untuk melakukan pengambilan code yang di lakukan perubahan.
⦁	git stash pop adalah untuk melakukan paste atau meletakan code kita yang masuk ke stash. Stash juga punya log dan di urut berdasarkan stash terakhir.
⦁	Perintah git lainnya 
⦁	git pull origin <nama_branch> untuk melakukan sinkrosinasi antara local dengan online branch, yang nantinya akan melakukan get branch online tersebut danmelakukan pembaharuan di local.
⦁	git log --oneline
⦁	git log --graph 
untuk melihat log dan history commit yang dilakukan dibranch , semua log akan terlihat.
⦁	git checkout <nama_branch>
⦁	git checkout  -b <nama_branch>
untuk melakukan perpindahan branch atau posisi branch. Flag –b untuk melakukan pidah sekaligus membuat branch baru di local.
⦁	git reset  --soft 
⦁	git reset  --hard 
untuk melakukan reset commit berdasarkan flagnya. Biasanya jarang digunakan karena baerbahaya untuk branch, sebaiknya kembali menggunakan reset soft.
⦁	git add <ssh/http_github> :untuk melakukan sinkronisasi link repo yang diambil.
⦁	git remote –v :untuk melakukan check agar mengetahui link atau posisi link repository online.

