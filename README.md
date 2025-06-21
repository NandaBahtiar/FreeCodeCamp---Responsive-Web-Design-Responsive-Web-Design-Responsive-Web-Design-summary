# Responsive Web Design
---
## **Building Cat Foto**

Mengenalkan dasar dasar `HTML` dalam membangun halaman web sederhana

### Materi yang dipelajari
-   **Struktur Html**:
     - Tag pembuka dan penutup `<html>,<head>,<body>`
     - melakukan komentar Html `<!-- komentar -->`
-   **Teks dan Heading**:
    -   Tag `<h1>` sampai `<h6>` untuk judul
    -   Tag `<p>` untuk membuat paragraf
-   **Menambahkan gambar**
    - Tag `<img>` dan atribut `src` dan `alt`
    - Contoh: 
    ```
    <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute cat">
    ```


-   **Link**:
    - Tag `<a>` dan atribut `href` 
    - Contoh:
    ```
    <a href="https://freecatphotoapp.com">Cat Photos</a>

    ``` 
-   **List**:
    - Ordered list `<ol>` + `<Li>` menghasilkan numerical atau alpabetical list
    - Unordered list: `<ul>` + `<li>` menghasilkan bulet list

-  **Form**:
    - Tag `<form>`, `<input>`, `<button>`
    - Tipe input: `text`,`radio`,dan `checkbox
    - Tag lable untuk input:`<lable>`
-  **Grouping dan Layout**:
    - Tag `<div>` dan `<section>` untuk mengelompokkan konten
-  **Atribut Global**
    - Contoh atribut: `id`, `class`, `name`, `placeholder`

## Learn Basic CSS by Building a Cafe Menu
Memahami konsep dasar CSS

### Materi yang dipelajari

- **Menambahkan CSS ke Html**:
    - Menggunakan tag `<style>` di `<head>`
    - Contoh:
    ```
        <head>

            <style>
                selector {
                    property: value;
                }
            </style>
        <head>
    ```
- **Selektor dan Properti Dasar**:
    - Selektor tag `(p, h1, ul, dll.)`
    - Properti umum:
        - color: warna teks
        - background-color: warna latar
        - font-family: jenis font
        - text-align: rata kiri/tengah/kanan
        - padding dan margin: ruang dalam & luar
        - border: garis tepi elemen

- **Box Model**:
    - Memahami bagaimana elemen HTML memiliki: `margin`, `border`, `padding`, dan `content`
    - Mengatur ukuran dan ruang antar elemen

- **Kelas dan ID**:
    - Menggunakan `class` dan `id` di HTML
    - Menargetkan elemen tertentu di CSS:
```
.class-name { ... } //untuk class
#id-name { ... } //untuk id

```

- **Layout Sederhana**:
    - Membuat layout menu dengan `<div>`, `<h1>`, `<section>`, dan list item
    - Menyusun item menu dengan styling rapi dan terstruktur
- **Teks dan Font**:
    - Mengatur jenis huruf, ukuran font (`font-size`), gaya teks (`font-style`), dan huruf tebal (`font-weight`)

## **Learn CSS Colors by Building a Set of Colored Markers**    
Mempelajari bagaimana Menggunakan warna di CSS 

### Materi yang dipelajari
- **Memberi Warna pada Elemen**:
    - Menggunakan properti:
        - color: untuk warna teks
        - background-color: untuk warna latar belakang

- **Format Warna CSS**:
    - Belajar berbagai cara menuliskan warna:
        - Nama warna:
            - Contoh: `red`, `blue`, `green`,`cyan`,dan `coral`

        - Kode Hexadecimal:
            - Contoh: `#FF0000 (merah)`, `#00FF00 (hijau)`

        - RGB (Red Green Blue):
            - Contoh: rgb(255, 0, 0)

        - HSL (Hue Saturation Lightness):
        - Contoh: hsl(0, 100%, 50%)
- **Opacity dan Transparansi**

   - Menggunakan rgba() dan hsla() untuk memberi warna transparan
        - Contoh: `rgba(255, 0, 0, 0.5) (merah setengah transparan)`
- **Efek Bayangan**
    - Properti `box-shadow` untuk menambah efek 3D/bayangan agar spidol tampak realistis

---
## **Learn HTML Forms by Building a Registration Form**
Memahami bagaimana membuat formulir HTML yang dapat menerima input dari pengguna
### Materi yang Dipelajari:
- **Tag `<form>`**:
    - Digunakan untuk membungkus semua input
    - Properti `action` dan `method` (biasanya digunakan di aplikasi backend)

- **Input Dasar**:
    - Tag `<input>`:

        - `type="text"` → nama
        - `type="email"` → alamat email
        - `type="password"` → kata sandi
        - `type="number"` → angka

    - Atribut penting:

        - `placeholder`: teks bayangan di dalam input
        - `required`: wajib diisi
- **Label**:
    - Tag `<label>` digunakan untuk menjelaskan input
    - Dikaitkan dengan input menggunakan `for` dan `id`:
    ```
    <label for="email">Email:</label>
    <input id="email" type="email">
    ```
- **Radio Button dan Checkbox**:
    - `Radio`: pilih satu dari beberapa opsi
    ```
    <input type="radio" name="gender" value="male">
    ```
   - `Checkbox`: bisa pilih lebih dari satu
    ```
    <input type="checkbox" name="hobby" value="reading">
    ```
- **Dropdown / Select Menu**:
   - Menggunakan tag `<select>` dan `<option>`
    ```
    <select name="age">
    <option value="18">18</option>
    <option value="19">19</option>
    </select>

    ```
- **Text Area**:
    - Tag `<textarea>` untuk input teks panjang (komentar, deskripsi, dll.)
- **Tombol Submit**:
    - Menggunakan `<button type="submit">` atau `<input type="submit">` untuk mengirim form
- **Grup dan Struktur**:
    - `<fieldset>` dan `<legend>` untuk mengelompokkan bagian form
    - Digunakan untuk aksesibilitas dan kejelasan




## **Learn the CSS Box Model by Building a Rothko Painting**
Memahami konsep CSS Box Model melalui proyek visual
### Materi yang Dipelajari:
- **CSS Box Model**:
    - Setiap elemen HTML adalah sebuah kotak yang memiliki 4 bagian utama:
        - `content`: isi elemen (teks, gambar, dll.)
        - `padding`: ruang antara isi dan border
        - `border`: garis tepi
        - `margin`: ruang luar antara elemen dan elemen lainnya

- **Properti Box Model**:
    - Setiap elemen HTML adalah sebuah kotak yang memiliki 4 bagian utama:
       - `width` dan `height`: ukuran kotak konten
       - `padding`: ruang di dalam border
       - `border`: ketebalan, gaya, dan warna garis tepi
       - `margin`: ruang di luar border
- **Box Sizing**:
    - `box-sizing: content-box` (default): `width` hanya menghitung isi
    - `box-sizing: border-box`: `width` mencakup isi + padding + border
- **Border Style dan Warna**:
    - Properti border-style, border-color, border-width
    - Contoh:
    ```
    border: 10px solid black;

    ```
- **Penataan Elemen Secara Vertikal**:
    - Menggunakan margin-bottom atau margin-top untuk memberi jarak antar kotak
---
## **Learn CSS Flexbox by Building a Photo Gallery**

Memahami cara menyusun elemen dengan **Flexbox**, sistem layout CSS modern yang fleksibel dan responsif

### Materi yang Dipelajari:

* **Konsep Flexbox**:

  * Flexbox adalah sistem layout satu dimensi yang digunakan untuk menyusun elemen secara **horizontal atau vertikal**
  * Digunakan dengan properti `display: flex`

* **Properti Dasar Flexbox**:

  * `display: flex`: mengaktifkan flex container
  * `flex-direction`: menentukan arah item (row, column)
  * `justify-content`: mengatur posisi item secara horizontal

    * `flex-start`, `center`, `space-between`, `space-around`, dll.
  * `align-items`: mengatur posisi item secara vertikal

    * `flex-start`, `center`, `stretch`, `baseline`
  * `flex-wrap`: memungkinkan item pindah ke baris berikutnya jika tidak cukup ruang

    * `nowrap` (default), `wrap`, `wrap-reverse`

* **Penggunaan Gap**:

  * `gap`: memberi jarak antar item tanpa perlu margin manual
  * Lebih bersih dan rapi dibandingkan menggunakan `margin`

* **Flex Item Properties**:

  * Properti tambahan pada elemen anak (item di dalam flex container):

    * `flex-grow`: seberapa besar item boleh membesar
    * `flex-shrink`: seberapa besar item boleh mengecil
    * `flex-basis`: ukuran awal item sebelum space dibagi
    * `flex`: shorthand dari ketiganya → `flex: 1`

* **Membuat Galeri Foto Responsif**:

  * Gambar-gambar akan tersusun secara otomatis dan rapi meskipun ukuran layar berubah
  * Kombinasi `flex-wrap` dan `gap` menjaga tampilan tetap enak dilihat di berbagai device
  * Setiap gambar bisa diatur dengan `max-width`, `height: auto`, dan `object-fit`

* **Contoh Struktur HTML Galeri**:

  ```html
  <div class="gallery">
    <img src="photo1.jpg" alt="Photo 1" />
    <img src="photo2.jpg" alt="Photo 2" />
    <img src="photo3.jpg" alt="Photo 3" />
  </div>
  ```

* **Contoh CSS Flexbox untuk Galeri**:

  ```css
  .gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
  }

  .gallery img {
    max-width: 300px;
    height: auto;
    border-radius: 8px;
  }
  ```

 
---
## **Learn CSS Grid by Building a Magazine Layout**

Memahami cara membuat layout dua dimensi menggunakan **CSS Grid**, cocok untuk tampilan seperti majalah atau halaman web kompleks

### Materi yang Dipelajari:

* **Dasar CSS Grid**:

  * `display: grid`: mengubah elemen menjadi grid container
  * Grid bekerja dengan **baris (rows)** dan **kolom (columns)**
  * Grid cocok untuk **layout dua dimensi**, berbeda dengan Flexbox yang satu dimensi

* **Membuat Grid**:

  * `grid-template-columns`: mendefinisikan jumlah dan ukuran kolom
  * `grid-template-rows`: mendefinisikan jumlah dan ukuran baris
  * Ukuran bisa dalam `px`, `fr`, `%`, atau `auto`
  * Contoh:

    ```css
    display: grid;
    grid-template-columns: 1fr 2fr;
    grid-template-rows: auto 100px;
    ```

* **Gap antar elemen**:

  * `gap`: jarak antar baris dan kolom (pengganti `grid-row-gap` dan `grid-column-gap`)
  * Bisa ditentukan satu nilai (`gap: 20px`) atau dua (`gap: 10px 20px`)

* **Penempatan Elemen di Grid**:

  * Gunakan:

    * `grid-column-start`, `grid-column-end`
    * `grid-row-start`, `grid-row-end`
  * Shorthand:

    * `grid-column: 1 / 3;`
    * `grid-row: 2 / 4;`

* **Menentukan Area Layout dengan Nama**:

  * Gunakan `grid-template-areas` untuk membuat tata letak mudah dibaca
  * Elemen anak menggunakan `grid-area: name;`
  * Contoh:

    ```css
    grid-template-areas:
      "header header"
      "sidebar content"
      "footer footer";
    ```

* **Align dan Justify**:

  * `justify-items`: mengatur perataan horizontal item di dalam sel
  * `align-items`: perataan vertikal dalam sel
  * `justify-content` & `align-content`: mengatur seluruh grid dalam container

* **Responsive Grid**:

  * Gunakan unit `fr` dan `auto-fit`/`auto-fill` untuk responsivitas
  * Contoh:

    ```css
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    ```


    Berikut adalah rangkuman **Learn Accessibility by Building a Quiz** dalam struktur yang konsisten dengan materi-materi sebelumnya:

---

##   **Learn Accessibility by Building a Quiz**

Memahami prinsip-prinsip **aksesibilitas (accessibility)** pada web dengan membuat kuis interaktif yang dapat digunakan oleh semua pengguna, termasuk pengguna pembaca layar (screen reader) dan perangkat bantu lainnya.

###   Materi yang Dipelajari:

* **Apa itu Aksesibilitas (a11y)**:

  * Aksesibilitas adalah praktik membuat situs web dapat digunakan oleh semua orang, termasuk penyandang disabilitas.
  * Termasuk dukungan untuk navigasi keyboard, screen reader, kontras warna, dan struktur HTML yang benar.

* **Elemen Formulir yang Ramah Aksesibilitas**:

  * Gunakan `<label>` yang dikaitkan langsung dengan input menggunakan `for` dan `id`:

    ```html
    <label for="q1">What is 2 + 2?</label>
    <input id="q1" type="text">
    ```
  * Setiap input harus memiliki label yang jelas agar bisa dikenali oleh screen reader.

* **Penggunaan `fieldset` dan `legend`**:

  * Digunakan untuk mengelompokkan beberapa input terkait, seperti pertanyaan kuis.
  * `legend` memberikan judul yang terbaca oleh screen reader.

    ```html
    <fieldset>
      <legend>Math Question</legend>
      <label for="q1">2 + 2 =</label>
      <input id="q1">
    </fieldset>
    ```

* **Menggunakan `aria-*` Attributes**:

  * Properti khusus untuk membantu pembaca layar.
  * Contoh:

    * `aria-describedby`: memberi deskripsi tambahan pada elemen.
    * `aria-label`: memberikan label aksesibilitas jika tidak menggunakan `<label>` biasa.

* **Navigasi dengan Keyboard**:

  * Semua elemen penting harus dapat diakses dengan `Tab`, `Enter`, dan `Space`.
  * Hindari penggunaan elemen interaktif yang hanya bisa digunakan dengan mouse.

* **Kontras Warna dan Fokus**:

  * Pastikan teks cukup kontras terhadap latar belakang agar mudah dibaca.
  * Gunakan `:focus` state di CSS agar elemen yang sedang aktif terlihat jelas saat navigasi keyboard.

* **Struktur HTML yang Semantik**:

  * Gunakan elemen seperti `<main>`, `<section>`, `<h1>`–`<h6>`, `<form>`, `<button>` untuk meningkatkan pemahaman konten bagi screen reader.

* **Feedback untuk Pengguna**:

  * Berikan umpan balik (feedback) seperti "Benar!" atau "Jawaban salah" setelah input.
  * Bisa juga ditampilkan dengan `aria-live` agar pembaca layar membacakannya secara otomatis.

 
 ---
## **Learn More About CSS Pseudo Selectors by Building a Balance Sheet**

Memahami dan mempraktikkan penggunaan **CSS pseudo-selectors** untuk menata tampilan elemen berdasarkan kondisi tertentu, dengan proyek membangun lembar keuangan (balance sheet).

### Materi yang Dipelajari:

* **Apa itu Pseudo Selector**:
  Pseudo-selector digunakan untuk menargetkan elemen berdasarkan **status**, **posisi**, atau **kondisi tertentu**.
  Ditulis setelah selector biasa dan diawali dengan titik dua `:`.

---

### Pseudo-class yang Dipelajari:

* `:hover`:
  Mengubah gaya elemen saat kursor berada di atasnya.
  Contoh:

  ```css
  tr:hover {
    background-color: #f0f0f0;
  }
  ```

* `:nth-child(n)`:
  Menargetkan elemen berdasarkan urutan ke-n dalam parent.
  Dapat berupa angka (`2`), keyword (`odd`, `even`), atau formula (`2n+1`).
  Contoh:

  ```css
  tr:nth-child(even) {
    background-color: #fafafa;
  }
  ```

* `:last-child`:
  Menargetkan elemen terakhir dari parent.
  Contoh:

  ```css
  tr:last-child {
    font-weight: bold;
    color: green;
  }
  ```

* `:first-child`:
  Menargetkan elemen pertama dalam parent.

* `:not(selector)`:
  Menargetkan semua elemen **kecuali** yang sesuai dengan selector di dalamnya.
  Contoh:

  ```css
  tr:not(:last-child) {
    border-bottom: 1px solid #ddd;
  }
  ```

 ---
 

## **Learn Intermediate CSS by Building a Cat Painting**

Mempelajari teknik CSS tingkat menengah dengan membangun ilustrasi lukisan kucing hanya menggunakan HTML dan CSS. Fokus pada penataan elemen, posisi, warna, dan bentuk.

### Materi yang Dipelajari:

* **Mengatur Warna dengan `background-color`**

  * Mengatur warna latar belakang elemen dengan kode warna (`hex`, `rgb`, `color name`).
  * Contoh:

    ```css
    .cat-face {
      background-color: #f2c2a0;
    }
    ```

* **Lebar dan Tinggi Elemen (`width` & `height`)**

  * Digunakan untuk menentukan ukuran bentuk kucing (kepala, mata, telinga, dll).
  * Ukuran bisa dalam `px`, `%`, atau `em`.

* **Membuat Bentuk dengan `border-radius`**

  * Membuat lingkaran atau sudut membulat.
  * Contoh:

    ```css
    .eye {
      border-radius: 50%;
    }
    ```

* **Penataan Posisi dengan `position` dan `top/right/bottom/left`**

  * Menggunakan `position: relative` dan `position: absolute` untuk mengatur letak elemen.
  * Elemen dengan `absolute` ditempatkan relatif terhadap elemen parent yang `relative`.

* **Z-Index untuk Layering**

  * Mengatur lapisan tampilan elemen (mana di atas, mana di bawah).
  * Contoh:

    ```css
    .whisker {
      z-index: 1;
    }
    ```

* **Transformasi Visual dengan `transform`**

  * Mengubah bentuk atau orientasi elemen:

    * `rotate()`
    * `scale()`
    * `translate()`
  * Contoh:

    ```css
    .ear {
      transform: rotate(30deg);
    }
    ```

* **Pewarnaan Latar dengan Gradien (`background: linear-gradient`)**

  * Untuk membuat transisi warna lembut pada elemen.
  * Contoh:

    ```css
    background: linear-gradient(to right, orange, yellow);
    ```

 ---
 

## **Learn Responsive Web Design by Building a Piano**

Belajar membuat desain web yang responsif menggunakan HTML dan CSS, dengan membangun tampilan piano digital yang menyesuaikan ukuran layar.

### Materi yang Dipelajari:

* **Pengertian Responsive Web Design**

  * Desain yang dapat **beradaptasi** dengan berbagai ukuran layar: desktop, tablet, dan smartphone.
  * Tujuannya adalah agar tampilan tetap **nyaman dibaca dan digunakan** di berbagai perangkat.

---

### Materi yang Dipelajari:

* **Media Queries**

  * Digunakan untuk mengatur gaya berbeda berdasarkan ukuran layar (viewport).
  * Sintaks:

    ```css
    @media (max-width: 600px) {
      .key {
        width: 30px;
      }
    }
    ```

* **Flexbox untuk Layout**

  * `display: flex` digunakan untuk menyusun tuts piano secara horizontal.
  * Properti seperti `justify-content`, `align-items`, dan `flex-wrap` membantu menjaga struktur tetap rapi saat ukuran layar berubah.

* **Menggunakan Unit Fleksibel**

  * Unit seperti `%`, `vw`, dan `vh` digunakan agar elemen dapat menyesuaikan ukuran layar.
  * Contoh:

    ```css
    width: 10vw;
    ```

* **Tombol Responsif (Tuts Piano)**

  * Setiap tuts dibuat dari elemen `<div>` dan distilisasi agar menyerupai tuts putih dan hitam.
  * Gunakan `border-radius`, `box-shadow`, dan `hover` effect untuk memberi kesan 3D dan interaktif.

* **Menggunakan Relative Units (`em`, `rem`)**

  * Untuk membuat elemen lebih fleksibel terhadap perubahan font-size.
  * Memberikan skalabilitas terhadap desain secara keseluruhan.

* **Penerapan `max-width` dan `min-width`**

  * Untuk menghindari elemen terlalu besar atau terlalu kecil pada resolusi ekstrem.

* **Aksesibilitas Dasar**

  * Menyediakan `aria-label` atau `title` pada elemen agar pengguna dengan pembaca layar tetap bisa memahami fungsi tombol piano.
 ---

## **Learn CSS Variables by Building a City Skyline**

Belajar menggunakan **CSS variables (variabel CSS)** untuk membuat kode lebih mudah diatur dan konsisten, dengan proyek membangun ilustrasi cakrawala kota (city skyline).

### Materi yang Dipelajari:

* **Apa itu CSS Variables**

  * Variabel dalam CSS digunakan untuk menyimpan nilai seperti warna, ukuran, atau jarak agar bisa digunakan berulang-ulang.
  * Dideklarasikan menggunakan tanda `--` di dalam selector (biasanya `:root`).
  * Contoh deklarasi:

    ```css
    :root {
      --main-color: #333;
      --building-height: 200px;
    }
    ```
  * Digunakan dengan fungsi `var()`:

    ```css
    color: var(--main-color);
    height: var(--building-height);
    ```

* **Kelebihan CSS Variables**:

  * **Konsistensi**: jika ingin mengubah satu warna di banyak tempat, cukup ubah variabelnya.
  * **Reusabilitas**: nilai yang sama dapat dipakai di berbagai tempat.
  * **Lebih mudah dibaca dan dirawat**, terutama untuk proyek besar.

* **Variabel Lokal dan Global**:

  * **Global**: didefinisikan di `:root`, dapat diakses di seluruh dokumen.
  * **Lokal**: didefinisikan dalam selector tertentu, hanya berlaku di dalamnya.

* **Menggunakan Variabel dalam Elemen Visual**:

  * Variabel digunakan untuk mengatur tinggi bangunan, warna langit, dan posisi matahari/bulan.
  * Contoh:

    ```css
    .building {
      background-color: var(--building-color);
      height: var(--building-height);
    }
    ```

* **Fallback Values**:

  * Jika variabel tidak ditemukan, bisa beri nilai cadangan:

    ```css
    color: var(--primary-color, blue);
    ```

* **Menyusun Elemen Kompleks dengan CSS Variabel**:

  * Bangunan, jendela, atap, dan langit malam dibentuk menggunakan `div` dan CSS styling.
  * Variabel digunakan untuk mengatur tinggi, posisi, dan warna setiap elemen.
 ---
 

## **Learn CSS Grid by Building a Magazine**

Belajar membuat layout halaman web bergaya majalah dengan **CSS Grid**, teknik layout dua dimensi yang sangat fleksibel dan cocok untuk desain yang kompleks.

### Materi yang Dipelajari:

* **Pengertian CSS Grid**
  CSS Grid adalah sistem layout dua dimensi yang memungkinkan kita untuk menyusun elemen dalam bentuk **baris dan kolom** secara bersamaan.

---

### Properti Dasar CSS Grid:

* **`display: grid`**
  Mengaktifkan grid container, memungkinkan penggunaan fitur grid.

* **`grid-template-columns` dan `grid-template-rows`**
  Menentukan jumlah dan ukuran kolom/baris pada grid.
  Contoh:

  ```css
  grid-template-columns: 1fr 2fr;
  grid-template-rows: auto 200px;
  ```

* **`fr` Unit (fractional unit)**
  Satuan untuk membagi ruang dalam grid.
  Misalnya: `1fr 2fr` berarti kolom kedua dua kali lebih lebar dari kolom pertama.

* **`gap`**
  Menentukan jarak antar baris dan kolom.
  Bisa ditulis `gap: 10px;` atau `row-gap` dan `column-gap` secara terpisah.

* **`grid-column` dan `grid-row`**
  Menentukan di kolom/baris ke berapa elemen akan mulai dan berakhir.
  Contoh:

  ```css
  grid-column: 1 / 3;
  grid-row: 2 / 4;
  ```

* **`grid-area` dan `grid-template-areas`**
  Menggunakan nama untuk membuat layout lebih mudah dibaca.
  Contoh:

  ```css
  grid-template-areas:
    "header header"
    "sidebar content"
    "footer footer";

  .header {
    grid-area: header;
  }
  ```

---

### Align dan Justify:

* **`justify-items`** dan **`align-items`**
  Mengatur perataan elemen di dalam sel (horizontal dan vertikal).

* **`justify-content`** dan **`align-content`**
  Mengatur posisi keseluruhan grid dalam container jika ada ruang kosong.
 
---
## **Learn CSS Animation by Building a Ferris Wheel**

Belajar membuat animasi menggunakan **CSS** dengan membangun proyek kincir ria (Ferris Wheel), fokus pada penggunaan properti animasi dan transformasi.

### Materi yang Dipelajari:

* **Apa itu CSS Animation**
  CSS animation digunakan untuk membuat perubahan visual secara bertahap (animasi) tanpa JavaScript.
  Terdiri dari dua bagian utama:

  * **`@keyframes`**: mendefinisikan perubahan yang terjadi selama animasi
  * **Properti animasi**: digunakan pada elemen untuk menerapkan animasi tersebut

---

### Properti Animasi yang Dipelajari:

* **`@keyframes`**
  Menentukan perubahan gaya dari awal hingga akhir animasi.
  Contoh:

  ```css
  @keyframes spin {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  ```

* **`animation-name`**
  Nama dari `@keyframes` yang digunakan.

* **`animation-duration`**
  Waktu yang dibutuhkan untuk satu siklus animasi, misalnya `5s`.

* **`animation-timing-function`**
  Mengontrol kecepatan perubahan, seperti:

  * `linear`, `ease`, `ease-in`, `ease-out`, `ease-in-out`.

* **`animation-iteration-count`**
  Berapa kali animasi diputar (misalnya `infinite` untuk terus berputar).

* **`animation-delay`**
  Menentukan jeda sebelum animasi dimulai.

* **`transform`**
  Digunakan untuk memutar, memperbesar, memindahkan, atau memiringkan elemen.

  * Contoh transformasi yang digunakan:

    * `rotate()`, `scale()`, `translate()`
 
 ---
## **Learn CSS Transforms by Building a Penguin**

Belajar menggunakan **CSS transform** untuk mengubah bentuk dan posisi elemen, dengan proyek membuat ilustrasi karakter pinguin menggunakan HTML dan CSS saja.

### Materi yang Dipelajari:

* **Apa itu CSS Transform**
  `transform` adalah properti CSS yang memungkinkan elemen diubah bentuk atau posisinya di layar tanpa mengubah dokumen HTML.
  Transformasi dapat mencakup rotasi, skala, translasi (geser), dan miring.

---

### Jenis Transformasi yang Dipelajari:

* **`transform: rotate()`**
  Memutar elemen pada sumbu pusatnya.
  Contoh:

  ```css
  transform: rotate(20deg);
  ```

* **`transform: scale()`**
  Memperbesar atau memperkecil ukuran elemen.
  Contoh:

  ```css
  transform: scale(1.2);
  ```

* **`transform: translateX()` dan `translateY()`**
  Menggeser elemen secara horizontal atau vertikal.
  Contoh:

  ```css
  transform: translateX(10px);
  ```

* **`transform: skew()`**
  Miringkan elemen secara horizontal atau vertikal.
  Contoh:

  ```css
  transform: skewY(15deg);
  ```

* **Gabungan Transformasi**
  Beberapa transformasi bisa digabung dalam satu perintah.
  Contoh:

  ```css
  transform: scale(0.8) rotate(10deg);
  ```

---

### Transform Origin:

* **`transform-origin`**
  Menentukan titik pusat transformasi. Default-nya adalah tengah elemen (`center center`), tapi bisa diubah.
  Contoh:

  ```css
  transform-origin: top left;
  ```
 
