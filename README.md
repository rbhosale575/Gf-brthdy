<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday My Love ❤️</title>
    <style>
        body {
            text-align: center;
            background: url('https://source.unsplash.com/1600x900/?birthday,celebration') no-repeat center center/cover;
            color: white;
            font-family: Arial, sans-serif;
        }
        h1 {
            font-size: 50px;
            animation: glow 1.5s infinite alternate;
        }
        @keyframes glow {
            from { text-shadow: 0 0 10px pink, 0 0 20px red; }
            to { text-shadow: 0 0 20px red, 0 0 30px pink; }
        }
        .message {
            font-size: 24px;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
            display: inline-block;
            border-radius: 10px;
            margin-top: 20px;
        }
        .music {
            margin-top: 20px;
        }
        button {
            font-size: 20px;
            padding: 10px;
            background: red;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>🎉 Happy Birthday My Love! 🎂</h1>
    <div class="message">
        <p>Meri jaan, tum meri zindagi ki sabse pyari insan ho! ❤️</p>
        <p>Is din tumhara har sapna pura ho, aur tum hamesha khush raho! 🎁🎈</p>
        <p>Love you forever! 😘</p>
    </div>

    <div class="music">
        <button onclick="playMusic()">Click to Play Surprise Music 🎶</button>
        <audio id="birthdaySong" src="https://www.myinstants.com/media/sounds/happy-birthday-to-you.mp3"></audio>
    </div>

    <script>
        function playMusic() {
            document.getElementById('birthdaySong').play();
        }
    </script>
</body>
</html>
