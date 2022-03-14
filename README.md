# Lab2Web
Dasar - dasar CSS
### Pengantar CSS
Cascading Style Sheet (CSS) merupakan aturan untuk mengatur beberapa komponen dalam sebuah web sehingga akan lebih terstruktur dan seragam. CSS bukan merupakan bahasa pemograman. CSS memudahkan dalam mengubah tampilan di berbagai halaman. Hanya dengan mengubah fungsi style di file CSS maka seluruh tampilan yang menggunakan fungsi tersebut akan berubah secara otomatis. CSS mempunyai atribut lebih beragam dibandingkan dengan HTML CSS memungkinkan konten dapat dioptimasi di lebih dari satu perangkat. Hampir seluruh website yang ada di internet menggunakan CSS di dalamnya. Selain tampilannya yang lebih menarik, kebanyakan browser populer saat ini juga mendukung CSS.


## Praktikum 2

1. buatlah sturuktur dasar `HTML` 

        <!DOCTYPE html>
        <html lang="en">
        <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Document</title>
        </head>
        <body>
  
        </body>
        </html>

2. membuat dokumen `HTML`

        <header>
          <h1>CSS Internal dan <i>Inline CSS</i></h1>
        </header>
        <nav>
          <a href="lab2_css_dasar.html">CSS Dasar</a>
          <a href="lab2_css_eksternal.html">CSS Eksternal</a>
          <a href="lab1_tag_dasar.html">HTML Dasar</a>
        </nav>

        <!-- CSS ID Selector -->
        <div id="intro">
          <h1>Hello World</h1>
            <p style="text-align: center; color: #ccd8e4;">Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman Web</b> di <i>Universitas Pelita
            Bangsa</i>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
            tag-tag dasar HTML dan CSS.</p>

           <!-- CSS Class Selector -->
           <a class="button btn-primary" href="#intro">Informasi
            selengkapnya.</a>
        </div>

maka akan tampil sebagai berikut

![02.png](img/02.png)