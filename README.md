!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Messages</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <div class="container">
        <h1>Love Messages for My baby ❤️</h1>
        <div class="message-box" id="message-box">
            <p id="love-message">Click the button to receive a love message.</p>
        </div>
        <button onclick="generateMessage()">Get a Love Message</button>
    </div>

    <script>
        const messages = [
            "You are the sunshine that lights up my world.",
            "Every moment with you is a beautiful memory.",
            "You are my heart, my soul, my greatest love.",
            "Loving you is the easiest and most beautiful thing I've ever done.",
            "My love for you grows stronger with each passing day.",
            "I love you so much baby. My REYNA."
        ];

        function generateMessage() {
            const randomIndex = Math.floor(Math.random() * messages.length);
            document.getElementById('love-message').innerText = messages[randomIndex];
        }
    </script>
</body>
</html>
