<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>zmaxlab - Under Maintenance</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #111;
            color: white;
            font-family: Arial, sans-serif;
        }

        h1 {
            font-size: 3em;
            letter-spacing: 2px;
            text-align: center;
            color: #fff;
            text-transform: uppercase;
            margin-bottom: 20px;
            animation: flicker 1.5s infinite alternate;
        }

        @keyframes flicker {
            0% { text-shadow: 0 0 10px #f00, 0 0 20px #f00, 0 0 30px #f00, 0 0 40px #f00, 0 0 50px #f00; }
            100% { text-shadow: 0 0 10px #f00, 0 0 20px #f00, 0 0 30px #fff, 0 0 40px #fff, 0 0 50px #fff; }
        }

        .container {
            position: relative;
            perspective: 1000px;
        }

        .cube {
            width: 150px;
            height: 150px;
            position: relative;
            transform-style: preserve-3d;
            animation: rotateCube 5s infinite linear;
        }

        @keyframes rotateCube {
            from { transform: rotateX(0deg) rotateY(0deg); }
            to { transform: rotateX(360deg) rotateY(360deg); }
        }

        .cube div {
            position: absolute;
            width: 150px;
            height: 150px;
            background: rgba(255, 255, 255, 0.1);
            border: 2px solid #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.5em;
            text-shadow: 0 0 5px #fff;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
        }

        .cube .front { transform: translateZ(75px); }
        .cube .back { transform: rotateY(180deg) translateZ(75px); }
        .cube .left { transform: rotateY(-90deg) translateZ(75px); }
        .cube .right { transform: rotateY(90deg) translateZ(75px); }
        .cube .top { transform: rotateX(90deg) translateZ(75px); }
        .cube .bottom { transform: rotateX(-90deg) translateZ(75px); }

        .message {
            text-align: center;
            font-size: 1.2em;
        }

        a {
            color: #00ffff;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>zmaxlab</h1>
        <div class="cube">
            <div class="front">3D</div>
            <div class="back">Cube</div>
            <div class="left">is</div>
            <div class="right">Spinning</div>
            <div class="top">Under</div>
            <div class="bottom">Maintenance</div>
        </div>
        <div class="message">
            We are currently working on something amazing. Stay tuned! <br>
            For inquiries, contact us at <a href="mailto:info@zmaxlab.com">info@zmaxlab.com</a>
        </div>
    </div>
</body>
</html>
