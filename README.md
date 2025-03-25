# song-player
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music Playlist</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: #111;
            color: white;
        }
        .player-container {
            width: 300px;
            margin: auto;
            padding: 20px;
            background: #222;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
        }
        button {
            margin: 10px;
            padding: 10px 15px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background: #007BFF;
            color: white;
        }
        button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>

    <h1>🎶 My Music Playlist</h1>
    
    <div class="player-container">
        <h3 id="song-title">AUR - SHIKAYAT</h3>
        <audio id="audio-player" controls>
            <source src="AUR - SHIKAYAT - Raffey - Usama - Ahad (Official Music Video)(MP3_160K).mp3" type="audio/mpeg">
            Your browser does not support the audio tag.
        </audio>
    </div>

    <div class="player-container">
        <h3 id="song-title">Pehla Tere Nain Dekhe</h3>
        <audio id="audio-player" controls>
            <source src="pehla tere nain dekhe fer dekhya tenu ni lofi lyrics song(MP3_160K).mp3" type="audio/mpeg">
            Your browser does not support the audio tag.
        </audio>
    </div>

    <div class="player-container">
        <h3 id="song-title">Premika Ne Pyar Se - Slowed And Reverb</h3>
        <audio id="audio-player" controls>
            <source src="Premika Ne Pyar Se -(Slowed And Reverb) _ Humse Hai Muqabala _ AR Rahman _ SP Balasubramaniam(MP3_160K).mp3" type="audio/mpeg">
            Your browser does not support the audio tag.
        </audio>
    </div>
  
</body>
</html>
