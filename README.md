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
        .description {
            font-size: 18px;
            margin-top: 10px;
            color: red;
        }
    </style>
</head>
<body>
    <div class="header">Seratonina</div>
    <div class="container">
        <div class="box" onclick="window.location.href='#infodump'">
            -Infodump-
            <div class="description">This is where I store info I've found.</div>
        </div>
        <div class="box" onclick="window.location.href='#theory'">
            -Theory-
            <div class="description">This is where I note theoretical information I've learned.</div>
        </div>
        <div class="box" onclick="window.location.href='#experimentation'">
            -Experimentation-
            <div class="description">This is where I experiment with my new skills.</div>
        </div>
    </div>
</body>
</html>
