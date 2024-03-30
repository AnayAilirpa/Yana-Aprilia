# Laporan Praktikum Pemograman WEB 1

## Identitas Diri
* Nama : Yana Aprilia
* NiM : 230202047
* Kelas : TI-1B

## Materi Pembahasan
Materi yang dipelajari dalam Praktikum Pemograman WEB 1

### 1. HTML 
HTML (Hypertext Markup Language) adalah sebuah markup language yang menentukan struktur dasar dari halaman web.
Berikut adalah contoh program HTML:

![HTML input](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/5f1202cd-d868-4d09-a940-b6e42dd3b249)

Dengan hasil output:

![HTML output](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/8e5f381d-56e4-4198-8e24-9bf5e10863c4)

#### Penjelasan 
* `<!DOCTYPE html>`: Ini adalah deklarasi untuk jenis dokumen HTML.

* `<html>`: Ini adalah elemen utama dari dokumen HTML. Semua elemen HTML akan berada di dalam elemen ini. Dengan `</html>` sebagai penutup dari elemen ini, yang menandakan berakhirnya dokumen HTML.

* `<head>` : Ini adalah bagian dari dokumen HTML yang berisi informasi tentang dokumen, seperti judul halaman, tautan ke stylesheet, tautan ke script JavaScript, metadata, dan lain-lain. Dengan `</head>` sebagai penutup dari elemen ini, yang menandakan berakhirnya informasi tentang dokumen.

* `<title>`: Ini adalah elemen yang menentukan judul halaman web yang akan ditampilkan di bilah judul atau tab browser. Dengan `</title>` sebagai penutup dari elemen ini, yang menandakan berakhirnya judul halaman web.

* `<body>`: Ini adalah elemen yang berisi konten dari halaman web, seperti teks, gambar, tautan, dan elemen-elemen lainnya yang akan ditampilkan kepada pengguna akhir. Dengan `</body>` sebagai penutup dari elemen ini, yang menandakan berakhirnya konten dari halaman web.

* `</h1>`: Ini adalah elemen untuk menampilkan judul yang berukuran besar (Heading 1). Dengan `</h1>` sebagai penutup dari elemen ini, yang menandakan berakhirnya judul.

* `<p>`: Ini adalah elemen untuk menampilkan teks paragraf. Dengan `</p>` sebagai penutup dari elemen ini, yang menandakan berakhirnya paragraf.


### 2. CSS
CSS (Cascading Style Sheets) adalah sebuah markup language yang memberikan gaya atau styling pada halaman web. Berikut adalah contoh program CSS:

![CSS input](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/7cb6fc8c-cd44-4548-9ba0-6c355782589a)

Dengan hasil output:

![CSS output](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/43414cdd-47f0-40da-8d28-a970286047fc)

#### Penjelasan 
* `<style>`: Digunakan untuk menulis kode CSS di dalam dokumen HTML. Dengan `</style>` sebagai penutup dari blok kode CSS. 

* `body { background-color: lightblue; }`: Digunakan untuk mengatur warna latar belakang halaman web menjadi biru muda (lightblue).

* `h1 { color: white; text-align: center; }`: Digunakan untuk menetapkan gaya untuk tag `<h1` di mana teksnya akan berwarna putih dan akan ditengahkan.

* `p { font-family: verdana; font-size: 20px; }`: Digunakan untuk menetapkan gaya untuk tag `<p>` di mana jenis hurufnya akan menggunakan font Verdana dan ukuran fontnya adalah 20 piksel.

### 3. JavaScript
JavaScript adalah sebuah markup language yang biasanya digunakan untuk meningkatkan interaktivitas pada halaman web. Berikut adalah contoh program JavaScript:

![JavaScript input](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/8e29505b-00bb-4482-821c-5a858e7a4136)

Dengan hasil output sebelum tombol "Click me to display Date and Time." diklik:

![JavaScript output-before](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/3435a80a-dcfb-4b24-a9a2-e3705015a5a6)

Dengan hasil output setelah tombol "Click me to display Date and Time." diklik:

![JavaScript output-after](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/366f54e8-11ad-406f-b7f1-4a54f4373cee)

#### Penjelasan 
* `<button>`: adalah sebuah tombol yang menampilkan teks "Click me to display Date and Time.". Ketika tombol ini diklik, JavaScript akan dieksekusi. Dengan `</button>` sebagai penutup dari element tersebut.

* `type`: pada elemen `<button>` merupakan atribut yang digunakan untuk menentukan tipe dari sebuah tombol. Selain nilai `button` (default) bisa juga memberikan nilai `submit` pada atribut `type` ini.

* `onclick`: adalah atribut yang digunakan untuk menetapkan tindakan yang akan dilakukan ketika elemen tersebut diklik oleh pengguna.

* `<p id="demo">`: Elemen `<p>` dengan id `demo` adalah paragraf kosong yang akan digunakan oleh JavaScript untuk menampilkan tanggal dan waktu saat tombol diklik. Dengan `</p>` sebagai penutup dari paragraf.

  * `id`:adalah sebuah atribut yang digunakan untuk memberikan identifikasi unik kepada sebuah elemen HTML.

  * `"demo"`: adalah nilai yang diberikan kepada atribut `id` pada elemen tertentu. Dalam hal ini, `"demo"` adalah nilai yang digunakan sebagai identifikasi unik untuk sebuah elemen HTML tertentu dalam halaman tersebut.

* `document.getElementById('demo').innerHTML = Date()`: adalah kode JavaScript yang akan dijalankan saat tombol diklik. Ini akan menetapkan isi dari elemen dengan id `"demo"` ke tanggal dan waktu saat itu menggunakan fungsi `Date()`.
  
  * `document.getElementById()`: adalah sebuah metode dalam JavaScript yang digunakan untuk mendapatkan referensi elemen HTML tertentu berdasarkan nilai atribut `id`-nya. Dalam kasus diatas `id`-nya adalah `"demo"`, sehingga ini akan menetapkan isi dari element `<p>` dengan id `"demo"`.
    
  * `innerHTML`: adalah sebuah properti JavaScript yang dimiliki oleh objek elemen HTML yang digunakan untuk mengatur atau mengambil isi HTML dari sebuah elemen HTML.
 
  * `Date()`: Sedangkan `Date()` adalah sebuah objek JavaScript bawaan yang merepresentasikan tanggal dan waktu saat ini ketika dipanggil tanpa argumen.

## Pembahasan Tambahan
1. CSS
Dalam HTML, kode CSS biasanya disisipkan di antara tag `<style>` dan `</style>`. Biasanya diletakkan di bagian paling bawah dalam tag `<head>` dan `</head>`.

Namun, bisa juga CSS berada di file yang berbeda dengan file HTML. Dengan itu, setiap halaman HTML harus menyertakan referensi ke file style sheet eksternal di dalamnya elemen `<link>`, di dalam bagian head.

Contoh: 

![CSS eksternal](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/8f380410-4386-45d6-afb8-5ae49f591547)

Berikut isi file mystyle.css:

![mystyle css](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/c3cd061a-1a74-4e06-9dea-883566d56feb)

3. JavaScript
Dalam HTML, kode JavaScript biasanya disisipkan di antara tag `<script>` dan `</script>`. Biasanya diletakkan di bagian paling bawah dalam tag `<body>` dan `</body>`.

Contoh program JavaScript dengan tag `<script>` dan `</script>`:
![JavaScript input0](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/3f18a73b-0329-48cb-9c7e-846bbe5275b5)

Dengan hasil output:

![JavaScript output0](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/9d7ac2a8-7936-471d-a14b-ff869425c7bd)

Namun, bisa juga JavaScript berada di file yang berbeda dengan file HTML. Dengan itu, setiap halaman HTML harus menyertakan referensi ke file JavaScript eksternal di dalamnya elemen `src <script>`, di dalam bagian body.

Contoh:

![JavaScript eksternal](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/005b03b8-3e4f-4550-803c-01b2b182de92)

Berikut isi file myScript js:

![myScript js](https://github.com/AnayAilirpa/Yana-Aprilia/assets/165096298/f3a2fd03-f74e-4c76-a055-0b4388110a9b)

## Sumber Pembelajaran 
https://www.w3schools.com
