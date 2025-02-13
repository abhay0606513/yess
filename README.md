<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <div class="container">
        <h1 class="message">Hey, [sunshine] 💖</h1>
        <p class="question">Will you be my Valentine? 😘</p>
        <div class="gif-container">
            <img src="https://media.giphy.com/media/xT0GqYwJY8mMQG7FZC/giphy.gif" alt="Valentine's Day GIF" class="gif">
        </div>
        <button onclick="showLove()">Yes, I will be your Valentine! 💕</button>
    </div>

    <script>
        function showLove() {
            alert('Yay! I\'m so happy! ❤️');
        }
    </script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #f8f0f2;
    text-align: center;
    color: #333;
    padding: 20px;
}

.container {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1);
}

.message {
    font-size: 2em;
    color: #FF69B4;
}

.question {
    font-size: 1.5em;
    color: #FF1493;
}

.gif-container {
    margin: 20px 0;
}

.gif {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
}

button {
    background-color: #FF1493;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 1.2em;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #FF69B4;
}
