Latihan1

CARA MEMBUAT REPOSITORY PADA GitHub  SERTA CARA MEMBUAT FILE README.md 

YANG PERTAMA HARUS ANDA DILAKUKAN :

>>MEMBUAT AKUN GitHub 

>>LALU MENDOWNLOAD SOFTWARE GIT ATAU APLIKASI GIT

CARA MENDAFTAR AKUN GitHuB

1. BUAT AKUN GitHub DENGAN MEMBUKA LAMAN https://github.com
2. ISI BAGIAN USER NAME, E-MAIL, DAN PASSWORD yang akan ANDA gunakan pada akun GitHub ANDA
![Capture 1](https://user-images.githubusercontent.com/56963083/67616964-8bc6d000-f808-11e9-9c41-30a219913337.PNG)

3. LALU CEK E-MAIL YANG ANDA DAFTARKAN UNTUK MEMBUAT AKUN GitHub LALU LAKUKAN VERIFIKASI ALAMAT E-MAIL.
![Capture 5](https://user-images.githubusercontent.com/56963083/67617101-dbf26200-f809-11e9-89bd-c6c93ec40342.PNG)

4. SETELAH MELAKUKAN VERIFIKASI ANDA AKAN DIARAHKAN PADA LAMAN GitHub YANG SUDAH TERHUBUNG DENGAN AKUN ANDA, LALU SELANJUTNYA YANG ANDA LAKUKAN BUATLAH REPOSITORY BARU, MASUKAN NAMA REPOSITORY ANDA DAN KLIK "CREATE REPOSITORY"
![Capture 233](https://user-images.githubusercontent.com/56963083/67617198-e5c89500-f80a-11e9-8a30-1479774f6310.PNG)

5. TAMPILAN REPOSITORY BARU
![Screenshot (2)](https://user-images.githubusercontent.com/56963083/67617245-64253700-f80b-11e9-8afb-cc390599342c.png)

6. SETELAH MEMBUAT REPOSITORY, DOWNLOAD SOFTWARE GIT DI LAMAN https://git-scm.com, DOWLOAD SESUAI DENGAN OPERATING SYSTEM DAN SPESIFIKASI LAPTOP ANDA.
![Capture 8](https://user-images.githubusercontent.com/56963083/67617308-18bf5880-f80c-11e9-82f8-d51a517522ad.PNG)

YANG SAYA DAPATKAN ADALAH VERSI 2.23.0

7. SETELAH MENDOWNLOAD SOFTWARE GIT LAKUKAN INSTALASI PADA LAPTOP ANDA.
![Capture 21](https://user-images.githubusercontent.com/56963083/67617372-bca90400-f80c-11e9-9f58-cfdbaa294a99.PNG)

8. PASTIKAN SOFTWARE GIT TELAH TERINSTAL.
![Capture 22](https://user-images.githubusercontent.com/56963083/67617420-2a553000-f80d-11e9-94e5-12bf6eda009d.PNG)

9. SETELAH TERINSTAL UNTUK MENCOBANYA SILAHKAN ANDA GUNAKAN CMD KEMUADIAN KETIK PERINTAH git --version, jika muncul ersi git maka proses yang dilakukan sudah berjalan dengan baik. dan git siap digunakan
![Capture cmd](https://user-images.githubusercontent.com/56963083/67617486-cbdc8180-f80d-11e9-813b-3768f620a619.PNG)

10. LALU BUKA DOCUMENT DAN BUAT FOLDER BARU, LALU KLIK KANAN PADA FOLDER LALU PILIH "GIT BASH HERE"
![GITBASH](https://user-images.githubusercontent.com/56963083/67617603-d9463b80-f80e-11e9-9bf9-cc61ff45bf43.png)

11. LALU PADA SAAT MENGGUNAKAN GIT LAKUKAN KONFIGURASI user.name dan user.email dengan perintah || $ git config --global user.name "nama_user"||$ git config --global user.email "nama_user" ||
![Capture git config](https://user-images.githubusercontent.com/56963083/67617664-98025b80-f80f-11e9-97a4-939e01121257.png)

 12. BUATLAH DIRECTORY DENGAN MENGGUNAKAN PERINTAH || $ mkdir latihan1 || sehingga terbentuk 1 direktori baru lalu ketik perintah selanjutnya dibawahnya || $ cd latihan1||
![Capture mkdir lat1](https://user-images.githubusercontent.com/56963083/67617746-8d949180-f810-11e9-9dc2-5adedeead4ed.png)

13. LALU JALANKAN PERINTAH SELANJUTNYA || $ git init || untuk membuat repository local
![Capture git init](https://user-images.githubusercontent.com/56963083/67617755-a69d4280-f810-11e9-84c7-8a3a93360c92.png)

14. BUAT 1 FILE BERNAMA README.md DENGAN MEMASUKAN PERINTAH || $ echo "latihan1" >>README.md || lalu  ketik perintah || $ ls -l || untuk melihat file 
![Capture echo dan ls-l](https://user-images.githubusercontent.com/56963083/67617905-43acab00-f812-11e9-9983-19f6ddd6d2c2.png)

15. UNTUK MENAMBAHKAN FILE YANG BARU SAJA DIBUAT GUNAKAN PERINTAH || $ git addd README.md || file README.MD  BERHASIL DITAMBAHKAN.
![Capture git add](https://user-images.githubusercontent.com/56963083/67617945-b74eb800-f812-11e9-933e-34c2d1c72b30.png)
![Capture git status](https://user-images.githubusercontent.com/56963083/67618071-414b5080-f814-11e9-8535-244a9cf371ad.png)

 16. UNTUK MENYIMPAN PERUBAHAN YANG ADA KEDALAM DATABASE REPOSITORY GUNAKAN PERINTAH || $ git commit -m "komentar saya" || $ I commit -m " File pertama saya" ||
 ![Capture git commit](https://user-images.githubusercontent.com/56963083/67618063-28429f80-f814-11e9-9327-a28589f18c46.png)
 
17. MASUK KE LAMAN GitHub YANG SUDAH ANDA BUAT PADA BAGIAN QUICK SETUP  TERDAPAT URL GitHub ANDA INI NANTINYA AKAN DIJADIKAN SEBUAH PERINTAH  || $ git remote add origin [URL].|
![capture https](https://user-images.githubusercontent.com/56963083/67619439-e7ec1d00-f825-11e9-86bd-17298dc735ff.png)

 18. UNTUK MENGIRIM PERUBAHAN LOCAL REPOSITORY  KE SERVER GUNAKAN PERINTAH || $ git push -u origin master ||
![Capture git remote   push](https://user-images.githubusercontent.com/56963083/67619415-ae1b1680-f825-11e9-8ef4-8e39f0346875.png)

19. JIKA ANDA INGIN MELAKUKAN CLONING GUNAKAN PERINTAH ||$ git clone [URL] ||
