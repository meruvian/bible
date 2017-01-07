# Meruvian Bible {#meruvian-bible}

**Setting Pre-Workshop WEBAPI**

**DAFTAR ISI**

**1. Installasi Java Development Kit (JDK)**

**2. Installasi dan Konfigurasi Maven**

**3. Installasi IDE Eclipse**

**4. Installasi MYSQL**

**5. Installasi Node.js**

6. Installasi NPM

7. Installasi Bower

8. Installasi Grunt Cli

9. Installasi Nexus

10\. Menjalankan Yama

y

**1\. Installasi Java Development Kit (JDK)**

**1.1 Ubuntu**

1.  Buka terminal lalu ketikkan perintah berikut ini :
2.  _sudo add-apt-repository ppa:webupd8team/javasudo apt-get update_

*   _sudo apt-get install oracle-java8-installer_

**1.2 Windows**

1.  Download Software JDK melalui link berikut : [_http://www.oracle.com/technetwork/java/javase/downloads/jdk8-download_](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

[_s-2133151.html_](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

B. Klik 2x pada file instalasi yang sudah kamu donwload dan akan membuka dialog installer java

C. Klik Next, kemudian membaca dan menerima lisensi.

D. Pada layar berikutnya Anda akan melihat proses instalasi java jdk sedang berjalan dan melihat status instalasi sedang melakukan extracting installer. Tunggu hingga proses ini selesai.

E. Setelah selesai java akan memunculkan pemberitahuan bahwa Java SE Development Kit Successfully instaled. Klik pada tombol close untuk menyelesaikan.

**2\. Installasi Maven**

**2.1 Ubuntu**

1.  Masuk ke terminal ( **ctrl + alt + t** ) masukkan kode berikut :

$ sudo apt-get install maven

B. Untuk mengecek versi maven, ketikkan :

$ mvn -v

**2.2 Windows**

1.  Sebelum anda menginstall Maven pastikan download dulu Maven di[https://maven.apache.org/download.cgi](https://maven.apache.org/download.cgi)
2.  Extract file tersebut dan rename menjadi maven

C. Masuk ke properties

D. Advance system setting

**E. Environment Variables**

F. Buat Variabel baru

G. Java home

H. Path

1.  Cek versi

**3\. Installasi IDE Eclipse**

1.  Download Software Eclipse sesuai dengan OS yang digunakan melalui link berikut:

B. Setelah selesai extract dan jalankan Eclipse.exe

[https://www/](https://www.eclipse.org/downloads/)

[.eclipse.org/downloads](https://www.eclipse.org/downloads/)

**4\. Installasi MYSQL**

**4.1 Ubuntu**

1.  MBuka terminal. Lalu ketik kode berikut :

*   sudo apt-get update
*   sudo apt-get install mysql-server
*   sudo mysql_secure_installation

B. Setelah semua proses sukses, anda bisa membuka MySql menggunakan perintah

$ mysql -u root -p pada terminal

**5\. Installasi Node.js**

**5.1 Ubuntu**

Pada distribusi Ubuntu, Fedora, dan Centos anda dapat menginstal Node.js dan npm melalui package manager.

curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -sudo apt-get install -y nodejs

| # Mengatasi masalah conflict node dan nodejs di ubuntu |
| --- |