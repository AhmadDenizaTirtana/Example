Pengertian dan Manfaat Git

Pengertian
Git adalah version control system yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Fungsi utama git yaitu mengatur versi dari source code program anda dengan mengasih tanda baris dan code mana yang ditambah atau diganti.

Git ini sebenernya memudahkan programmer untuk mengetahui perubahan source codenya daripada harus membuat file baru seperti Program.java, ProgramRevisi.java,  ProgramRevisi2.java, ProgramFix.java. Selain itu, dengan git kita tak perlu khawatir code yang kita kerjakan bentrok, karena setiap developer bias membuat branch sebagai workspacenya.Fitur yang tak kalah keren lagi, pada git kita bisa memberi komentar pada source code yang telah ditambah/diubah, hal ini mempermudah developer lain untuk tahu  kendala apa yang dialami developer lain.

Manfaat

Fungsi utamanya adalah untuk mengatur versi dari source code anda, menambahkan tanda/checkpoint ketika terjadi perubahan pada kode Anda dan tentunya akan mempermudah Anda untuk tetap mengetahui apa saja yang berubah dari source code Anda.
Untuk mengetahui bagaimana menggunakan git, berikut perintah-perintah dasar git:

    Git init : untuk membuat repository pada file lokal yang nantinya ada folder .git
    Git status : untuk mengetahui status dari repository lokal
    Git add : menambahkan file baru pada repository yang dipilih
    Git commit : untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository.
    Git push : untuk mengirimkan perubahan file setelah di commit ke remote repository.
    Git branch : melihat seluruh branch yang ada pada repository
    Git checkout : menukar branch yang aktif dengan branchyang dipilih
    GIt merge : untuk menggabungkan branch yang aktif dan branch yang dipilih
    Git clone : membuat Salinan repository lokal

Contoh dari software version control system adalah github, bitbucket, snowy evening, dan masih banyak lagi. Jika anda sebagai developer belum mengetahui fitur git ini, maka anda wajib mencoba dan memakainya. Karena banyak manfaat yang akan didapat dengan git ini.
SSH GIT Composer 2
Sebagai contoh, misalkan Anda sedang membangun sebuah website, dan anda akan menambahkan beberapa fitur dalam website anda. Agar tidak membingungkan nantinya anda membuat sebuah catatan terhadap apa yang telah anda lakukan seperti :

01-04-2014 Memulai Project Website, File HTML & CSS Dasar
02-04-2014 Penambahan Menu Utama
03-04-2014 Penambahan Layout Standar
04-04-2014 Penambahan Fitur Pengubah Layout



Pada contoh diatas kita menggunakan tanggal sebagai tanda akan apa yang telah kita lakukan, dengan demikian kita bisa tahu kapan perubahan terjadi dan apa perubahan yang dilakukan. Dan dalam Git semua itu bisa dilakukan dengan mudah dan asyiknya jika Anda merusak kode sehingga membuat aplikasi error, maka anda dapat mengembalikan kode tersebut berdasarkan pada tanda/tanggal dimana kode masih normal, lebih mirip seperti restore point.

Git juga tidak hanya digunakan untuk perorangan, beberapa orang pun dapat bekerja secara bersamaan mengerjakan kode Anda dan Anda masih memiliki kontrol penuh terhadap kode Anda, Anda bisa menambahkan kode yang ditambahan oleh orang lain atau mengabaikannya sama sekali. oleh karena itu Git sering digunakan sebagai pengatur dalam projek kolaborasi dimana tidak hanya satu orang yang mengerjakan sebuah kode tapi beberapa orang sekaligus yang mengerjakan kode tersebut.


Kamu dapat merequest GIT secara GRATIS di IDCloudHost, silahkan menghubungi Tim Customer Service IDCoudHost untuk melakukan permintaan aktifasi, permintaan berlaku untuk pake Business Pro & Advance Pro.

Kesimpulan
Git merupakan alat bantu untuk pembuatan software dengan cepat , walaupun kita ditempat yang jauh Git bisa mempermudah kita dalam mengkoding.

Pembuat
Dibangun oleh Linus Torvald, orang yang sama dibalik Linux, Awalnya git ini dibuat untuk mengatur kode kernel Linux. Sebelumnya beliau mencari aplikasi SCM yang telah ada namun menurutnya tidak ada SCM yang dapat bekerja dengan cepat dan efisien.

