<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Game</title>
    <style>
        /* CSS стили */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            max-width: 600px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        h1 {
            margin-bottom: 20px;
        }

        canvas {
            border: 1px solid #000;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>My Game</h1>
        <canvas id="gameCanvas" width="400" height="300"></canvas>
    </div>

    <script>
        // JavaScript код
        const canvas = document.getElementById('gameCanvas');
        const ctx = canvas.getContext('2d');

        // Пример игровой логики
        ctx.fillStyle = 'green';
        ctx.fillRect(10, 10, 50, 50);
    </script>
</body>
</html>
