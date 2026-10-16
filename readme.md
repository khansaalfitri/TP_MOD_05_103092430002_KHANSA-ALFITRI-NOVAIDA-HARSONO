1. Pengertian Bootstrap [10 poin]
   Jelaskan apa itu Bootstrap dan apa kegunaannya!
   Bootstrap adalah sebuah framework CSS (dan JavaScript) open-source yang sangat populer dan digunakan untuk mendesain situs web yang responsif serta mobile-first secara cepat.
   Kegunaannya: Mempermudah dan mempercepat proses pembuatan tampilan website karena kita tidak perlu menulis kode CSS dari nol. Bootstrap menyediakan berbagai komponen siap pakai (seperti tombol, navbar, card, form) dan sistem grid yang otomatis menyesuaikan ukuran layar perangkat.

2. Memasang Bootstrap [10 poin]
   Ada beberapa cara untuk mengimpor atau menggunakan Bootstrap pada project. Sebutkan cara-caranya!
   • Menggunakan CDN (Content Delivery Network): Menyisipkan tautan (link) CSS dan script JS dari CDN resmi Bootstrap langsung ke dalam tag <head> dan sebelum penutup tag <body> di file HTML. Cara ini paling praktis karena tidak perlu mengunduh file.
   • Mengunduh Berkas (Local / Compiled CSS & JS): Mengunduh file CSS dan JS Bootstrap langsung dari situs resminya, lalu menyimpannya di dalam folder proyek web kita dan menghubungkannya secara lokal menggunakan tag <link> dan <script>.
   • Menggunakan Package Manager (CLI): Menginstal Bootstrap melalui manajer paket seperti npm atau Yarn pada proyek berbasis build tool (seperti Vite atau Webpack).

3. Grid dan Breakpoint [10 poin]
   Jelaskan mengenai class grid dan kegunaan breakpoint!
   Class Grid: Sistem tata letak berbasis kolom dan baris (.container, .row, dan .col) yang memanfaatkan flexbox. Sistem ini membagi halaman web menjadi 12 bagian kolom per baris, sehingga kita bisa mengatur posisi elemen dengan rapi dan fleksibel. Breakpoint: Titik acuan ukuran layar tertentu (seperti sm, md, lg, xl, xxl) yang digunakan pada class grid untuk menentukan bagaimana tata letak elemen web akan berubah atau menyesuaikan diri pada ukuran layar perangkat yang berbeda (misalnya HP, tablet, laptop, atau PC).

4. Class Bootstrap [10 poin]
   Sebutkan minimal lima class yang disediakan oleh Bootstrap beserta kegunaannya!
   • container / container-fluid: Digunakan untuk membungkus konten agar berada di tengah halaman dengan lebar yang terstruktur atau selebar penuh layar (full-width).
   • row: Digunakan sebagai wadah pembungkus kolom (.col) dalam sistem grid agar elemen di dalamnya berjajar rapi secara horizontal.
   • btn dan btn-primary: Kombinasi class untuk mengubah elemen HTML (seperti <button> atau <a>) menjadi tombol interaktif dengan gaya utama (biasanya berwarna biru atau hijau sesuai kustomisasi).
   • shadow / shadow-sm / shadow-lg: Digunakan untuk memberikan efek bayangan (drop shadow) pada suatu elemen (seperti kotak card atau form), memberikan kesan elemen tersebut melayang atau memiliki kedalaman.
   • d-flex: Digunakan untuk mengaktifkan properti Flexbox pada suatu elemen, memudahkan pengaturan tata letak anak elemen di dalamnya (seperti perataan posisi atau jarak antar item).

5. Gambar Responsif [10 poin]
   Bagaimana cara agar foto atau gambar pada website responsif menyesuaikan ukuran layar perangkat?
   Agar foto atau gambar pada website bisa responsif dan otomatis menyesuaikan ukuran layar perangkat, kita bisa menambahkan class img-fluid pada tag <img>. Class ini akan memberikan pengaturan CSS max-width: 100% dan height: auto, sehingga gambar tidak akan pecah atau keluar dari wadahnya saat dibuka di layar HP maupun laptop.
"# TP_MOD_05_103092430002_KHANSA-ALFITRI-NOVAIDA-HARSONO" 
"# TP_MOD_05_103092430002_KHANSA-ALFITRI-NOVAIDA-HARSONO" 
