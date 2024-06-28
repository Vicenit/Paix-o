<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amo tu, Lena</title>
    <style>
        body {
            background-color: #cce7ff;
            color: #ff6699;
            font-family: 'Arial', sans-serif;
            text-align: center;
            padding: 50px;
            position: relative;
        }
        .message {
            font-size: 3em;
            margin-top: 20%;
            text-shadow: 2px 2px 4px #ff99cc;
        }
        .decorations {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            pointer-events: none;
        }
        .heart, .sunflower {
            position: absolute;
        }
        .heart {
            width: 20px;
            height: 20px;
            background: #ff6699;
            transform: rotate(45deg);
        }
        .heart::before,
        .heart::after {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background: #ff6699;
            border-radius: 50%;
        }
        .heart::before {
            top: -10px;
            left: 0;
        }
        .heart::after {
            left: 10px;
            top: 0;
        }
        .sunflower {
            width: 50px;
            height: 50px;
            background: url('https://cdn.pixabay.com/photo/2017/08/30/23/15/sunflower-2699940_960_720.png') no-repeat center center;
            background-size: cover;
        }
    </style>
</head>
<body>
    <div class="message">Amo tu, Lena</div>
    <div class="decorations">
        <!-- Hearts -->
        <div class="heart" style="top: 10%; left: 15%;"></div>
        <div class="heart" style="top: 20%; left: 25%;"></div>
        <div class="heart" style="top: 30%; left: 35%;"></div>
        <div class="heart" style="top: 40%; left: 45%;"></div>
        <div class="heart" style="top: 50%; left: 55%;"></div>
        <div class="heart" style="top: 60%; left: 65%;"></div>
        <div class="heart" style="top: 70%; left: 75%;"></div>
        <div class="heart" style="top: 80%; left: 85%;"></div>
        <div class="heart" style="top: 90%; left: 95%;"></div>
        <!-- Sunflowers -->
        <div class="sunflower" style="top: 15%; left: 20%;"></div>
        <div class="sunflower" style="top: 25%; left: 30%;"></div>
        <div class="sunflower" style="top: 35%; left: 40%;"></div>
        <div class="sunflower" style="top: 45%; left: 50%;"></div>
        <div class="sunflower" style="top: 55%; left: 60%;"></div>
        <div class="sunflower" style="top: 65%; left: 70%;"></div>
        <div class="sunflower" style="top: 75%; left: 80%;"></div>
        <div class="sunflower" style="top: 85%; left: 90%;"></div>
    </div>
</body>
</html>
