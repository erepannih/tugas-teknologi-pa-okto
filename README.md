
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Reifan Syahlevi Regni</title>
    
    <!-- Bagian CSS digabung di sini -->
    <style>
        /* Mengatur margin bawaan */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: "Times New Roman", Times, serif;
            background-color: #ffffff;
        }

        /* Desain Menu Navigasi Hijau Tua */
        .navbar {
            background-color: #4b7b2b; 
            padding: 12px 0;
        }

        .navbar ul {
            list-style-type: none;
            display: flex;
            justify-content: space-around;
            max-width: 1000px;
            margin: 0 auto;
        }

        .navbar ul li a {
            text-decoration: none;
            color: #ffffff;
            font-size: 15px;
            text-transform: uppercase;
        }

        /* Desain Wadah Konten */
        .post-container {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .post-title {
            font-size: 34px;
            font-weight: bold;
            color: #000000;
            margin-bottom: 20px;
        }

        /* Desain Kotak Hijau Muda untuk Penulis & Tanggal */
        .post-meta {
            display: flex;
            gap: 5px; /* Jarak antar kotak */
            margin-bottom: 25px;
        }

        .post-meta span {
            background-color: #b9ce5c;
            color: #ffffff;
            padding: 5px 12px;
            font-size: 16px;
            text-transform: uppercase;
        }

        /* Desain Gambar dan Paragraf */
        .post-content {
            overflow: hidden;
        }

        .post-image {
            float: left; /* Membuat gambar berada di kiri teks */
            width: 320px;
            height: auto;
            margin-right: 20px;
            margin-bottom: 10px;
            border: 2px solid #ccc; /* Bingkai tipis agar mirip foto */
        }

        .post-content p {
            font-size: 21px;
            text-align: justify; /* Rata kanan-kiri */
            line-height: 1.4;
            color: #000000;
        }

        /* Desain Tombol Read More Merah */
        .read-more-container {
            text-align: right;
            margin-top: 30px;
            clear: both;
        }

        .read-more {
            text-decoration: none;
            color: #d32f2f;
            font-size: 22px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <!-- Menu Atas -->
    <nav class="navbar">
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">PROFILE</a></li>
            <li><a href="#">ACADEMICS</a></li>
            <li><a href="#">TECH AND HOBBIES</a></li>
            <li><a href="#">PICTURE</a></li>
            <li><a href="#">CONTACT</a></li>
        </ul>
    </nav>

    <!-- Konten Artikel -->
    <article class="post-container">
        
        <h1 class="post-title">"Pemimpin Di Kelas, Eksplorator Di Dunia Digital"</h1>

        <div class="post-meta">
            <!-- JANGAN LUPA GANTI INI DENGAN NAMA KAMU -->
            <span>POSTED BY Reifan Syahlevi </span>
            <span>ON 19 JUNE 2026 | NO COMMENT</span>
            <span>311251390027</span>
        </div>

        <div class="post-content">
            <!-- Gambar dari internet supaya langsung muncul -->
            <img src="Reifan.jpeg" alt="Reifan.jpeg" class="post-image">
            <p>Halo! Perkenalkan, nama saya Reifan Syahlevi, mahasiswa aktif di Universitas Mitra Bangsa (UMIBA). Selain fokus pada aktivitas perkuliahan, saya juga memegang amanah sebagai Ketua Kelas, yang banyak mengajarkan saya tentang tanggung jawab, <em>public speaking</em>, dan manajemen teman-teman satu angkatan Di luar kesibukan kampus, saya memiliki ketertarikan yang besar terhadap dunia teknologi. Waktu luang saya biasanya diisi dengan mengeksplorasi spesifikasi dan optimasi hardware PC, serta bermain game bergenre action-adventure dan survival horror. Saat ini, saya juga sedang antusias mempraktikkan dasar-dasar web development seperti HTML dan CSS ini untuk mengembangkan kreativitas di dunia digital......</p>
            
            <div class="read-more-container">
                <a href="#" class="read-more">Read More</a>
            </div>
        </div>

    </article>

</body>
</html>
