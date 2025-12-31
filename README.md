<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: #0f0c29;
            background: linear-gradient(to bottom, #24243e, #302b63, #0f0c29);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 3rem;
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            text-align: center;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
            max-width: 400px;
            animation: fadeIn 2s ease-in;
        }

        h1 {
            color: #fff;
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 0 0 10px #ff007f, 0 0 20px #ff007f;
        }

        .year {
            display: block;
            font-size: 4rem;
            color: #ffd700;
            font-weight: bold;
            margin: 10px 0;
        }

        p {
            color: #e0e0e0;
            font-size: 1.2rem;
            line-height: 1.5;
        }

        .heart {
            color: #ff4d4d;
            font-size: 3rem;
            animation: heartbeat 1.5s infinite;
            margin-top: 20px;
        }

        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
    <title>Happy New Year Love</title>
</head>
<body>

    <div class="card">
        <h1>Happy New Year</h1>
        <span class="year">2026</span>
        <p>To my favorite person in the world. May our love grow even stronger in this new chapter.</p>
        <p>I love you! 💗</p>
        <div class="heart">❤</div>
    </div>

</body>
</html>
