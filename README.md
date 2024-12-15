<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text-to-Speech</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Text-to-Speech Converter</h1>
        <textarea id="text-input" placeholder="Enter your text here..."></textarea>
        <div class="controls">
            <label for="voice-select">Choose Voice:</label>
            <select id="voice-select"></select>
            <label for="speed">Speed:</label>
            <input type="range" id="speed" min="0.5" max="2" value="1" step="0.1">
        </div>
        <button id="speak-button">Speak</button>
        <button id="stop-button">Stop</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
