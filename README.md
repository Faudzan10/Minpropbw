# Personal Portfolio Website - Muhammad Irdhan Nur Faudzan

## 📌 Deskripsi Project
Website portfolio pribadi bertema abu-abu elegan yang dibuat menggunakan HTML dan CSS.  
Website terdiri dari Navbar, Hero Section, About Me, Skills, Certificates, dan Footer.

---

# 🧱 PENJELASAN HTML

---

1. Struktur Dasar HTML
<img width="726" height="192" alt="image" src="https://github.com/user-attachments/assets/d80563e3-b98f-4ede-bc24-d59f30b7c639" />

Penjelasan:

<!DOCTYPE html> → Menentukan bahwa dokumen menggunakan HTML5.

<html lang="id"> → Bahasa website Indonesia.

<meta charset="UTF-8"> → Mendukung karakter khusus.

viewport → Agar responsive di perangkat mobile.

link rel="stylesheet" → Menghubungkan file CSS.


2️. Navbar

<img width="633" height="245" alt="image" src="https://github.com/user-attachments/assets/9a2e3228-6d5e-4deb-bca0-088aa9a2863c" />

Penjelasan:

<nav> → Elemen navigasi.

.logo → Identitas website.

<ul> → Daftar menu.

href="#home" → Navigasi ke section dengan id "home"


3. Hero Section (Home)

<img width="987" height="286" alt="image" src="https://github.com/user-attachments/assets/6a1bf39b-8668-4871-a512-28ace613bfc4" />

Penjelasan:

id="home" → Target navigasi navbar.

<h1> → Judul utama.

<img> → Menampilkan foto profil.

alt → Deskripsi alternatif gambar.


4️. About Me & Skill

<img width="1243" height="730" alt="image" src="https://github.com/user-attachments/assets/8dad43e1-231d-4b45-9b7c-169f8c002351" />

Penjelasan:

Section <section id="about" class="about"> digunakan untuk menampilkan bagian About Me dan menjadi target navigasi dari navbar melalui id="about". Di dalamnya terdapat <h2> sebagai judul dan <p> yang berisi deskripsi diri mengenai latar belakang, minat di bidang teknologi, serta ketertarikan pada sepak bola.

Bagian Skills dibuat menggunakan <div class="skill"> sebagai container setiap kemampuan. Teks persentase ditampilkan menggunakan <span>, sedangkan progress bar dibuat dengan <div class="progress"> sebagai background dan <div class="bar ..."> sebagai isi bar. Class tambahan seperti .programming, .sport, dan .soft digunakan untuk mengatur lebar bar sesuai persentase (70%, 80%, 90%) melalui CSS.


5.Pengalaman

<img width="706" height="179" alt="image" src="https://github.com/user-attachments/assets/c27824d3-c83e-4897-9952-c78cd3582a49" />

Penjelasan:

- Tag <h3> digunakan sebagai subjudul “Pengalaman” untuk membedakan dari judul utama sebelumnya. Elemen <ul> (unordered list) digunakan untuk membuat daftar pengalaman dalam bentuk poin, sedangkan setiap <li> berisi satu pengalaman, seperti partisipasi di Arema FC Piala Soeratin U-17, mini project visualisasi data, dan kegiatan futsal kampus.

Struktur list ini membantu menampilkan informasi secara rapi, terstruktur, dan mudah dibaca.


6.Certificated

<img width="813" height="770" alt="image" src="https://github.com/user-attachments/assets/5797970f-d6d9-4a75-8537-595b9770df56" />


Bagian <section id="certificates" class="certificates"> digunakan untuk menampilkan daftar sertifikat atau pencapaian. Atribut id="certificates" berfungsi sebagai target navigasi dari navbar, sedangkan class="certificates" digunakan untuk styling melalui CSS.

Tag <h2> digunakan sebagai judul utama section dengan teks “Certificates”. Di dalamnya terdapat <div class="cards"> yang berfungsi sebagai container untuk menampung beberapa card sertifikat agar bisa diatur menggunakan CSS Grid atau Flexbox.

Setiap sertifikat dibuat menggunakan <div class="card"> sebagai wadah. Di dalam card terdapat <img> untuk menampilkan gambar sertifikat atau dokumentasi, <h4> untuk judul atau nama pencapaian, dan <p> untuk menampilkan tahun perolehan. Struktur ini membuat tampilan lebih terorganisir dan mudah dibaca.

Bagian <footer> digunakan sebagai penutup halaman website. Elemen <p> di dalamnya menampilkan informasi hak cipta (copyright) sebagai identitas pemilik website.

Tag </body> dan </html> menandakan akhir dari dokumen HTML.


**CSS**

1.Global Styling

<img width="560" height="298" alt="image" src="https://github.com/user-attachments/assets/3cb79dcd-85dd-4266-937a-f2f002e0fb45" />

Bagian * { ... } disebut universal selector, artinya aturan ini berlaku untuk semua elemen HTML. Fungsinya untuk menghapus margin dan padding bawaan browser, mengatur perhitungan ukuran dengan box-sizing: border-box, serta menentukan font utama.

Bagian body { ... } digunakan untuk mengatur tampilan keseluruhan halaman seperti warna background, warna teks, dan jarak antar baris agar lebih rapi dan nyaman dibaca.


2. Navbar

<img width="582" height="732" alt="image" src="https://github.com/user-attachments/assets/9d38e6f8-f7dc-4a66-8703-8fe5f427c2af" />

Penjelasan:

CSS ini digunakan untuk mengatur tampilan navbar agar tersusun horizontal menggunakan display: flex. Logo dan menu dipisahkan dengan justify-content: space-between, serta diratakan tengah secara vertikal dengan align-items: center.

Warna background dibuat abu-abu gelap, teks logo berwarna putih dan tebal. Menu dibuat tanpa bullet, tersusun sejajar, dan link akan berubah warna saat di-hover agar terlihat interaktif.


3. Hero Section

<img width="511" height="456" alt="image" src="https://github.com/user-attachments/assets/39c505c1-c939-4936-a64e-a7b41991b4a7" />

Penjelasan:

.hero memakai display: flex agar teks dan gambar tersusun sejajar, dengan jarak menggunakan justify-content: space-between dan rata tengah vertikal memakai align-items: center. Background dibuat abu-abu gelap dengan teks putih, serta flex-wrap: wrap agar tetap rapi saat layar mengecil.

.hero img mengatur ukuran foto menjadi 280x280px, menggunakan border-radius: 50% agar berbentuk lingkaran, diberi border abu-abu, dan box-shadow untuk efek bayangan agar terlihat lebih modern.


4. Button

<img width="326" height="350" alt="image" src="https://github.com/user-attachments/assets/53a71b06-dc18-4d9d-b03f-c07056fac30d" />

penjelasan:

CSS ini digunakan untuk styling tombol (.btn).

.btn dibuat seperti tombol menggunakan display: inline-block, diberi jarak atas, padding agar lebih besar, background abu-abu, teks putih, tanpa garis bawah, serta sudut membulat dengan border-radius. Properti transition memberi efek animasi halus saat berubah.

.btn:hover mengubah warna background menjadi lebih terang saat kursor diarahkan ke tombol agar terlihat interaktif.


5. About


<img width="390" height="868" alt="image" src="https://github.com/user-attachments/assets/d7dbc117-e4bd-4630-9ff8-3d8c27e7f03a" />

Penjelasan:

.about mengatur jarak dalam (padding), membuat teks rata tengah, dan memberi background abu-abu terang.

.skill mengatur jarak antar skill, lebar 70% agar tidak terlalu penuh, dan teks rata kiri.

.progress adalah background progress bar dengan tinggi 15px dan sudut membulat.
.bar adalah isi dari progress bar.

.programming, .sport, dan .soft mengatur lebar bar sesuai persentase (70%, 80%, 90%) serta memberi warna berbeda untuk tiap kategori skill.


6. Certificated


<img width="637" height="794" alt="image" src="https://github.com/user-attachments/assets/714428ed-5e92-49eb-87ea-e1e006ff4a0a" />

Penjelasan:

.certificates mengatur jarak dalam (padding), background abu-abu terang, dan teks rata tengah.

.cards menggunakan CSS Grid untuk menyusun card secara responsif dengan jarak antar card (gap).

.card mengatur tampilan setiap sertifikat dengan background putih, sudut membulat, bayangan (box-shadow), dan efek transisi.

.card img mengatur gambar menjadi ukuran 70x70px, berbentuk lingkaran dengan border-radius: 50%, serta diberi border.

.card:hover memberikan efek card naik sedikit saat disentuh agar terlihat interaktif.


7. Footer


<img width="306" height="447" alt="image" src="https://github.com/user-attachments/assets/f82cda2a-6856-49d0-a690-d740bd618c35" />

Penjelasan:

footer → background gelap, teks putih, rata tengah, padding 20px.

@media (max-width: 768px) → aturan untuk layar kecil (HP/tablet).

.hero → jadi kolom (atas-bawah) dan teks rata tengah saat layar kecil.

.hero img → kasih jarak atas 30px biar nggak mepet.

===================================================================================================

**OUTPUT**

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d34c1aca-6d3e-4c25-9ce1-9123576cd301" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bbf7cc48-96fc-4aa1-be05-47d9d98a6ff3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d81eb534-f93a-4940-ae65-6695e747d29f" />
