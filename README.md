# Personal Portfolio Website - Muhammad Irdhan Nur Faudzan

Deskripsi Project

Website portfolio pribadi bertema abu-abu elegan yang dibuat menggunakan HTML dan CSS.
Website terdiri dari Navbar, Hero Section, About Me, Skills, Certificates, dan Footer.

1. Navbar

<img width="633" height="245" alt="image" src="https://github.com/user-attachments/assets/9a2e3228-6d5e-4deb-bca0-088aa9a2863c" />

Penjelasan :

- nav → Elemen navigasi

- logo → Identitas website
 
- ul → Daftar menu

- hrefhome → Navigasi ke section dengan id "home"


2. Hero Section (Home)
   
<img width="987" height="286" alt="image" src="https://github.com/user-attachments/assets/6a1bf39b-8668-4871-a512-28ace613bfc4" />

- id="home" → Target navigasi navbar.

- h1 → Judul utama.

- img → Menampilkan foto profil.

- alt → Deskripsi alternatif gambar.

3. About Me & Skill

<img width="1243" height="730" alt="image" src="https://github.com/user-attachments/assets/8dad43e1-231d-4b45-9b7c-169f8c002351" />

- section id="about" menampilkan About Me, berisi h2 dan p tentang diri dan minat.

- Skills memakai div class="skill", span untuk persen, dan progress bar (.progress + .bar). Class tambahan mengatur lebar sesuai persentase lewat CSS.

4. Pengalaman

<img width="706" height="179" alt="image" src="https://github.com/user-attachments/assets/c27824d3-c83e-4897-9952-c78cd3582a49" />

- Tag h3 digunakan sebagai subjudul “Pengalaman” untuk membedakan dari judul utama sebelumnya.

- Elemen ul (unordered list) digunakan untuk membuat daftar pengalaman dalam bentuk poin, sedangkan setiap li berisi satu pengalaman, seperti partisipasi di Arema FC Piala Soeratin U-17, mini project visualisasi data, dan kegiatan futsal kampus.

- Struktur list ini membantu menampilkan informasi secara rapi, terstruktur, dan mudah dibaca.

5. Certificated

<img width="813" height="770" alt="image" src="https://github.com/user-attachments/assets/5797970f-d6d9-4a75-8537-595b9770df56" />


- Bagian section id="certificates" class="certificates" digunakan untuk menampilkan daftar sertifikat atau pencapaian. Atribut id="certificates" berfungsi sebagai target navigasi dari navbar, sedangkan class="certificates" digunakan untuk styling melalui CSS.

Tag <h2> digunakan sebagai judul utama section dengan teks “Certificates”. Di dalamnya terdapat div class="cards" yang berfungsi sebagai container untuk menampung beberapa card sertifikat agar bisa diatur menggunakan CSS Grid atau Flexbox.

Setiap sertifikat dibuat menggunakan div class="card" sebagai wadah. Di dalam card terdapat img untuk menampilkan gambar sertifikat atau dokumentasi, h4 untuk judul atau nama pencapaian, dan p untuk menampilkan tahun perolehan. Struktur ini membuat tampilan lebih terorganisir dan mudah dibaca.

Bagian <footer> digunakan sebagai penutup halaman website. Elemen p di dalamnya menampilkan informasi hak cipta (copyright) sebagai identitas pemilik website.

Tag /body dan /html menandakan akhir dari dokumen HTML.

=================================================================================================

**CSS**

1.Global Styling

<img width="560" height="298" alt="image" src="https://github.com/user-attachments/assets/3cb79dcd-85dd-4266-937a-f2f002e0fb45" />

- Bagian * { ... } disebut universal selector, artinya aturan ini berlaku untuk semua elemen HTML. Fungsinya untuk menghapus margin dan padding bawaan browser, mengatur perhitungan ukuran dengan box-sizing: border-box, serta menentukan font utama.

Bagian body { ... } digunakan untuk mengatur tampilan keseluruhan halaman seperti warna background, warna teks, dan jarak antar baris agar lebih rapi dan nyaman dibaca.


