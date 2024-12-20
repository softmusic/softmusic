<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SOFT MUSIC INSTITUTE</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: black;
            color: white;
            text-align: center;
            padding: 20px;
        }

        header {
            background: linear-gradient(to bottom, gold, black);
            padding: 40px 20px;
            animation: fadeIn 2s ease-in-out;
        }

        header h1 {
            color: white;
            font-size: 4em;
            text-shadow: 2px 2px 8px gold;
            animation: glow 2s infinite alternate;
        }

        .container {
            padding: 40px 20px;
        }

        .section {
            background: black;
            color: white;
            margin: 20px;
            padding: 30px;
            border: 2px solid gold;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.8);
            animation: slideUp 2s ease-in-out;
        }

        .section h2 {
            color: gold;
            margin-bottom: 20px;
        }

        .section ul {
            list-style-type: none;
            padding: 0;
            font-size: 1.2em;
        }

        .section li, p {
            padding: 8px 0;
        }

        a {
            display: inline-block;
            text-decoration: none;
            color: black;
            background: gold;
            padding: 10px 20px;
            font-size: 1.2em;
            font-weight: bold;
            border-radius: 5px;
            box-shadow: 0 0 10px gold;
            animation: glow 1.5s infinite alternate;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes glow {
            from { text-shadow: 0 0 8px gold; }
            to { text-shadow: 0 0 20px white; }
        }

        @keyframes slideUp {
            from { transform: translateY(100px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>

<header>
    <h1>SOFT MUSIC INSTITUTE 🎶</h1>
</header>

<div class="container">
    <div class="section">
        <h2>About Us</h2>
        <p>Where passion meets melody. We nurture musical talent through expert training and personalized coaching.</p>
    </div>

    <div class="section">
        <h2>Our Programs</h2>
        <ul>
            <li>🎸 Instrumental Training: Guitar, Piano, Drums, Violin</li>
            <li>🎤 Vocal Coaching: Unlock your true voice</li>
            <li>🎼 Music Theory & Composition</li>
            <li>🎧 Music Production: Create, mix, and produce tracks</li>
        </ul>
    </div>

    <div class="section">
        <h2>Contact Us</h2>
        <p>📞 WhatsApp or Call: +234 903 202 2219 | +234 916 805 7385</p>
        <p>📧 Follow Us on Social Media:</p>
        <ul>
            <li>🐦 X (Twitter): <a href="https://x.com/softmusicinstit?t=YjdKha-hm3X4NU4-GLrejQ&s=09" target="_blank">@softmusicinstit</a></li>
            <li>📸 Instagram: <a href="https://www.instagram.com/softmusicinstitute/profilecard/?igsh=MThlaGZxb25hd3M0Yg==" target="_blank">@softmusicinstitute</a></li>
            <li>📘 Facebook: <a href="https://www.facebook.com/profile.php?id=100091729988463&mibextid=ZbWKwL" target="_blank">@softmusicinstitute</a></li>
            <li>🎵 TikTok: <a href="https://www.tiktok.com/@soft.music.institute" target="_blank">@soft.music.institute</a></li>
        </ul>
        <a href="#">Join Us Now!</a>
    </div>
</div>

</body>
</html>
