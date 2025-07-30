<! DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>PsychoMode Player</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="psycho-player">
    <h1>🎧 PsychoMode Player</h1>

    <input type="file" id="audio-upload" accept="audio/*">
    <div class="controls">
      <button id="play-btn">▶️ Play</button>
      <button id="pause-btn">⏸️ Pause</button>
    </div>

    <canvas id="waveform" width="600" height="200"></canvas>

    <p class="footer">© PsychoMode Systems 2025</p>
  </div>

  <script src="script.js"></script>
</body>
</html>
