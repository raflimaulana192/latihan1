
Tutorial penggunaan git
1.	Buka website resminya Git  (git-scm.com) , lalu download Git sesuai dengan arsitektur masing-masing yaitu 64bit atau 32bit.
 
 ![1](https://user-images.githubusercontent.com/56399268/67160133-ba105100-f2d8-11e9-8f23-cd421408089e.jpg)

2.	Buka apliikasi git bash yang sudah didownload dan diinstal.

![2](https://user-images.githubusercontent.com/56399268/67160134-baa8e780-f2d8-11e9-8236-a4ae1bab3505.jpg) 

3.	Jika sudah masuk ke Git Bash ketik perintah : git config --global user.name “nama user”

 ![3](https://user-images.githubusercontent.com/56399268/67160135-bb417e00-f2d8-11e9-8b76-b382894d806f.jpg)

4.	Setelah itu ketik : git config --global user.email “nama user”

![4](https://user-images.githubusercontent.com/56399268/67160136-bb417e00-f2d8-11e9-814e-d2caeff61ce3.jpg) 

5.	Selanjutnya ketik : mkdir latihan1 . dan juga ketik : cd latihan1

 ![5](https://user-images.githubusercontent.com/56399268/67160137-bbda1480-f2d8-11e9-9792-bb4ecc9b172a.jpg)

6.	Selanjutnya ketik : git init untuk membuat repository local

 ![6](https://user-images.githubusercontent.com/56399268/67160138-bbda1480-f2d8-11e9-8266-b184baee1011.jpg)

7.	Berikutnya untuk membuka file readme.md dan isi dengan teks latihan1 dengan menjalankan perintah  echo”#latihan1”README.md
 
![7](https://user-images.githubusercontent.com/56399268/67160139-bc72ab00-f2d8-11e9-9f52-03e8e0ffb61d.jpg)

8.	Apabila anda telah berhasil  menjalankan perintahnya maka akan muncul file README.md di dalam folder latihan1

![8](https://user-images.githubusercontent.com/56399268/67160141-bc72ab00-f2d8-11e9-978c-83103803b5ba.jpg)

![9](https://user-images.githubusercontent.com/56399268/67160143-bd0b4180-f2d8-11e9-943c-0dcce795dbc9.jpg)

9.	Setelah itu ketik git add README.md di git bash.dan juga ketik perintah git commit –m ”file pertama” untuk membuat file.
→ saya membuat file bernama “file pertama” seperti dibawah ini :
 
![10](https://user-images.githubusercontent.com/56399268/67160322-833b3a80-f2da-11e9-8009-94922b8942cc.jpg)

TUTORIAL MEMBUAT REPOSITORY SERVER

1.	Server repository yang akan kita gunakan adalah http://github.com
2.	Anda harus membuat akun git hub terlebih dahulu
3.	Pada halaman github klik ( icon + ) klik new repository

![11](https://user-images.githubusercontent.com/56399268/67160323-833b3a80-f2da-11e9-8110-e236d62d7e53.jpg)

4.	Isi nama repository misal : Latihan1, lalu klik buat repository

![12](https://user-images.githubusercontent.com/56399268/67160325-83d3d100-f2da-11e9-8589-7b1951e46d1c.jpg)

 MENAMBAHKAN REMOTE REPOSITORY
1.	Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
2.	Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url] pada git bash.
 
![13](https://user-images.githubusercontent.com/56399268/67160326-83d3d100-f2da-11e9-90b0-7ed13b8f212c.jpg)

PUSH ( MENGIRIM PERUBAHAN KE SERVER )
1.	Untuk mengirim perubahan pada local repository ke server gunakan perintah git push -u origin master
(untuk menaruh file README.md yang tadi sudah dibuat). Perintah ini akan meminta memasukkan username dan password pada akun github.com, dan akan muncul tampilan seperti ini.

 ![14](https://user-images.githubusercontent.com/56399268/67160327-846c6780-f2da-11e9-869f-4ff451c40a09.jpg)

MELIHAT HASILNYA PADA SERVER REPOSITORY
1.	Buka halaman github.com arahkan pada repositorynya, maka perubahan akan terlihat pada tampilan berikut. ( Jika berhasil akan muncul gambar dibawah,dan file README.md sudah berada di repository latihan1 di github.com yang telah dibuat.
 
![15](https://user-images.githubusercontent.com/56399268/67160328-8504fe00-f2da-11e9-90d9-681a09f62a88.jpg)

# Sekian pembahasan dari saya terimakasih #
