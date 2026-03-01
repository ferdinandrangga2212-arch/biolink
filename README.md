<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bio Link - Ferdinand Rangga</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            /* Gradasi Ungu sesuai gambar */
            background: linear-gradient(180deg, #4A148C 0%, #1a0633 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            padding-top: 50px;
            color: white;
        }

        .container {
            width: 100%;
            max-width: 450px;
            text-align: center;
            padding: 20px;
        }

        /* Foto Profil */
        .profile-img {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            border: 4px solid #9c4dff;
            margin-bottom: 20px;
            object-fit: cover;
            box-shadow: 0 0 20px rgba(156, 77, 255, 0.4);
        }

        h1 {
            font-size: 1.6rem;
            margin-bottom: 5px;
            letter-spacing: 1px;
        }

        .username {
            font-size: 0.9rem;
            color: #b39ddb;
            margin-bottom: 40px;
        }

        /* Styling Tombol Opsi */
        .links-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .link-card {
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.15);
            padding: 18px 25px;
            border-radius: 15px;
            text-decoration: none;
            color: white;
            font-size: 0.95rem;
            font-weight: 500;
            transition: all 0.3s ease;
            backdrop-filter: blur(5px);
            line-height: 1.4;
        }

        .link-card:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-3px);
            border-color: rgba(255, 255, 255, 0.4);
        }

        /* Animasi Pop Up untuk tombol */
        .link-card:active {
            transform: scale(0.98);
        }

        .footer {
            margin-top: 50px;
            font-size: 0.8rem;
            color: #b39ddb;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 5px;
        }

        .icon-link {
            font-size: 1rem;
        }

        /* Responsif untuk layar kecil */
        @media (max-width: 480px) {
            .container {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="https://api.dicebear.com/7.x/avataaars/svg?seed=Ferdinand" alt="Profile" class="profile-img">

        <h1>FERDINAND RANGGA</h1>
        <p class="username">@ferdinand_rangga</p>

        <div class="links-container">
            <a href="https://wa.me/628895412992" class="link-card" target="_blank">
                💬 Hubungi Saya di WhatsApp
            </a>

            <a href="#" class="link-card" onclick="alert('FIRE EAGLE TEAM\nSebuah tim pengembang digital yang berfokus pada inovasi dan kreativitas tanpa batas.')">
                🔥 Tentang Tim FIRE EAGLE
            </a>

            <a href="#" class="link-card" onclick="alert('CARA BELAJAR CODING:\n1. Tentukan Tujuan (Web, Mobile, Game)\n2. Pelajari Dasar (HTML/CSS)\n3. Konsisten Latihan Setiap Hari\n4. Jangan Takut Error!')">
                💻 Cara Singkat Belajar Coding
            </a>
        </div>

        <div class="footer">
            <span class="icon-link">🔗</span> SELAMAT DATANG DI BIO SAYA
        </div>
    </div>

</body>
</html>
