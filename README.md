<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahashivratri Divine Blessings</title>
    <style>
        body {
            background: #0d0d0d;
            color: #fff;
            font-family: 'Georgia', serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            overflow-x: hidden;
        }

        .container {
            text-align: center;
            background: rgba(20, 20, 20, 0.8);
            padding: 30px;
            border-radius: 15px;
            border: 2px solid #f0a500;
            box-shadow: 0 0 20px #f0a500;
            max-width: 500px;
            width: 90%;
        }

        .marriage-img {
            width: 100%;
            border-radius: 10px;
            border: 1px solid #f0a500;
            margin-bottom: 20px;
            box-shadow: 0 0 15px rgba(240, 165, 0, 0.5);
        }

        h1 {
            color: #f0a500;
            text-shadow: 2px 2px 4px #000;
        }

        .om-btn {
            background: #f0a500;
            color: #000;
            border: none;
            padding: 15px 30px;
            font-size: 1.1rem;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(240, 165, 0, 0.4);
            transition: 0.3s;
        }

        .om-btn:hover {
            transform: scale(1.05);
            background: #ffcc00;
        }

        #blessing-content {
            display: none;
            margin-top: 20px;
            animation: fadeIn 2.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <audio id="divineAudio" loop>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <div class="container">
        <img src="https://img.freepik.com/premium-photo/wedding-lord-shiva-goddess-parvati-vibrant-colors-intricate-details-mythological-art_1263595-3490.jpg" 
             alt="Shiva Parvati Marriage" class="marriage-img">
        
        <h1>Har Har Mahadev</h1>
        <p>Experience the divine union of Shiva and Shakti.</p>
        
        <button class="om-btn" onclick="startExperience()">Click for Blessings 🕉️</button>

        <div id="blessing-content">
            <h2 style="color: #ffcc00;">ॐ नमः शिवाय</h2>
            <p>"May the divine marriage of Shiva and Parvati fill your life with love, strength, and spiritual wisdom."</p>
            <p><strong>Happy Mahashivratri!</strong></p>
        </div>
    </div>

    <script>
        function startExperience() {
            // Play the audio
            var audio = document.getElementById('divineAudio');
            audio.play();

            // Reveal the content
            document.getElementById('blessing-content').style.display = 'block';
            document.querySelector('.om-btn').style.display = 'none';
        }
    </script>

</body>
</html>
