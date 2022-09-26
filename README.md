# **Tugas Writing Week 1** 

<!---
SyifaAulia0/SyifaAulia0 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
CLI (Command Line Interface)
- 
- CLI : hanya ada teks, tidak ada tampilannya.  
- Perbedaan GUI (Graphic User Interface) dengan CLI yaitu GUI berupa tampilan, CLI hanya teks.
- Shell : perintah2 yg digunakan untuk menginstruksikan system operasi
- Contoh cli : cmd, bash 
- Perintah-perintah yang ada di CLI :
1. Pwd : untuk melihat dimana posisi kita berada
2. Ls : untuk melihat isi file apa saja yang ada didalamnya
3. Cd : untuk berpindah direktori/folder. Untuk keluar dari folder : (nama folder) cd..
4. Clear : untuk menghapus
5. Mkdir : untuk membuat folder baru
6. Nano : untuk mengisi file di folder baru
7. Cat : untuk melihat isi dari file
8. Head : menampilkan beberapa isi dari baris atas
9. Tail : menampilkan beberapa isi dari baris bawah
10. Cp : untuk mencopy/menyalin file
11. Rm : untuk menghapus file

Git dan Github 
- 
- Git adalah tools untuk programmer
- Git : software berbasis version control system.
- berfungsi sebagai control system untuk menjalankan proyek pengembangan software.
- repository : direktor proyek yang kita buat
- Perintah yang ada di Git :
1. git init : untuk membuat file di repository lokal
2. git status : untuk memgetahui status dari sebuah repository
3. git add : untuk menambahkan file baru di repository 
4. git commit : untuk menyimpan perubahan yang sudah dilakukan, tetapi tidak pada remote repository
5. git log : untuk melihat catatan-catatan revisi yang sudah dilakukan
6. git push : untuk mengirimkan perubahan file setelah di commit ke remote repository
7. git branch : untuk melihat semua cabang di repository
8. git checkout: sebuah perintah yang digunakan untuk menukar branch yang aktif dengan branch yang sudah dipilih.
9. git merge: perintah yang digunakan untuk menggabungkan cabang aktif serta cabang yang dipilih
10. git clone: adalah perintah yang digunakan untuk mengkloning repository lokal

- Github : Sebuah aplikasi untuk mengupload codingan

HTML (Hypertext Markup Language)
- 
- Html digunakan untuk menampilkan konten pada web browser
- Tools yang digunakan untuk html : browser dan visual studio code 
- Html element terdiri dari opening tag, content, closing tag
```html
<p>Hello World</p>
```

- Attribute : sebuah properti dari html element
```html
    <h1 id="header"></h1>
    <img src="image.png">
```

- image
```html
<img src="aku.jpeg">
```

Output

![WhatsApp Image 2021-09-28 at 21 51 49 (2)](https://user-images.githubusercontent.com/114098894/192248734-13c593d6-eeb2-48af-b988-174fb18e6a70.jpeg)

- video
- controls : untuk play, stop, atau menit suatu video
```html
<video controls>
 <source src="" type="type/mp4">
</video>
```

- Ordered List
```html
<ol type="a">
        <li>Twitter</li>
        <li>Instagram</li>
        <li>Linked in</li>
</ol>
```

output

![Screenshot (2521)](https://user-images.githubusercontent.com/114098894/192248228-33cc4082-022d-4e82-896e-2e334ca7a4c4.png)

- section
```html
<section>
            <h2>Contact me</h2>
            <form action="">
                <label for="">name</label>
                <input type="text" name="" id=""/>
                <label for="">email</label>
                <input type="email" name="" id=""/>
                <button>send</button>
            </form>
</section>
```

output

![Screenshot (2522)](https://user-images.githubusercontent.com/114098894/192248569-8e65fd96-961a-456d-9764-b48459615c6a.png)

CSS (Cascading Style Sheet)
- 
- CSS untuk memperindah tampilan html
- Cara menggunakan CSS ada 3, yaitu :
    1. Inline CSS
    ```
    //pada html
    <h1 style="background-color: aqua">Halo Aku <span>Syifa</span></h1>
    ```
    Output
    
    ![Screenshot (2524)](https://user-images.githubusercontent.com/114098894/192273276-19bbaf87-09ce-478c-8aa4-ffab72fa272a.png)

    2. Internal CSS
    ```
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title> 
    </head>
    <body>
    <style>
        h1 {
         border: black 3px solid;
        }
    </style>
    
    <h1>Halo Saya Syifa</h1>
    </body>
   </html>
    ```
    Output
    ![Screenshot (2527)](https://user-images.githubusercontent.com/114098894/192275070-17968d3f-7e50-4cd1-9da8-ad8b00e47125.png)

    3. Eksternal CSS


