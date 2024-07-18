
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seratonina</title>
    <style>
        body {
            background-color: #f0f0f0; /* Replace this with your own background */
            font-family: 'Courier New', Courier, monospace;
            color: red;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .header {
            margin-top: 20px;
            font-size: 36px;
            font-weight: bold;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 80vh;
        }
        .box {
            background-color: rgba(0, 255, 0, 0.3); /* Transparent green */
            border: 2px solid green;
            padding: 20px;
            margin: 10px;
            width: 200px;
            text-align: center;
            cursor: pointer;
        }
        .box:hover {
            background-color: rgba(0, 255, 0, 0.5);
        }
    </style>
</head>
<body>
    <div class="header">Seratonina</div>
    <div class="container">
        <div class="box" onclick="window.location.href='#infodump'">-Infodump-</div>
        <div class="box" onclick="window.location.href='#theory'">-Theory-</div>
        <div class="box" onclick="window.location.href='#experimentation'">-Experimentation-</div>
    </div>
</body>
</html>
