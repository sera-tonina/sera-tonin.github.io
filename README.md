<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seratonina</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=OCR+A+Std&display=swap');
        
        body {
            background-color: black; /* Solid black background */
            font-family: 'OCR A Std', monospace;
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
            background-color: transparent; /* Transparent background */
            border: 2px solid red; /* Red outline */
            padding: 30px; /* Larger padding */
            margin: 20px; /* Larger margin */
            width: 300px; /* Larger width */
            text-align: center;
            cursor: pointer;
            border-radius: 15px; /* Rounded edges */
            color: red; /* Red text */
            font-size: 24px; /* Larger text */
        }
        .box:hover {
            background-color: rgba(255, 0, 0, 0.1); /* Slightly red background on hover */
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
