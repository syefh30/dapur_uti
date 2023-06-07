* Mohon maaf pak, karena codenya tidak bisa di push direpository github, jadi kami mengambil opsi mengarsipkannya dengan rar saja.

Deskripsi singkat

Dapur Uti merupakan web katering untuk masyarakat yang ingin memesan makanan secara online, dan bisa menggunakan via WhatsApp dengan metode Cash on Delivery(bayar ditempat).

Spesifikasi dan Kebutuhan Software

Laravel Framework 9.3.1, PHP 8.1.6

Instalasi

1. Download file dapur_uti.rar lalu extract to
2. Lalu masuk folder menggunakan perintah cd dari cmd, lalu ketikkan perintah "code ."
3. Import DB-nya dengan meng-copy .env.example lalu paste dan ubah namanya menjadi .env
4. Buat DB baru di phpmyadmin, lalu masuk ke file .env dan ubah nama "DB_DATABASE=..."-nya sesuai dengan DB yang baru dibuat tadi
5. Di terminal jalankan perintah "composer install", jika sudah selesai, lanjut ketikkan "php artisan key:generate", lalu ketikkan juga "php artisan migrate:fresh --seed", terakhir ketikkan "php artisan storage:link".
6. Jalankan perintah di terminal lalu ketikkan "php artisan serve" dan buka server "http://127.0.0.1:8000".

Info Credential

Admin | username: admin@example.com | password: 123

Penanggung Jawab : Yohanes | 081945441745

Nama Kelompok : Imam Abdullah_2103046 | Syefa Falih A_2103057 | Yohanes Dana Putra Panjaitan_2103060
