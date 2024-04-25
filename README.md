<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music Application</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Music Application</h1>
    </header>
    <main>
        <div id="player">
            <audio id="audioPlayer" controls>
                <source src="song.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <div id="controls">
                <button id="playPauseBtn">Play</button>
                <button id="stopBtn">Stop</button>
            </div>
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>

