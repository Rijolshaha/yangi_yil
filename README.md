# yangi_yil
sayt
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yangi Yil Tabriknomasi</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden;
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: white;
        }

        .container {
            position: relative;
            width: 100%;
            height: 100%;
            overflow: hidden;
        }

        .background {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-size: cover;
            background-position: center;
            animation: slideBackground 20s infinite;
        }

        @keyframes slideBackground {
            0% { background-image: url('https://media.giphy.com/media/3E2ORcVHto9H8HMi2h/giphy.gif'); }
            33% { background-image: url('https://media.giphy.com/media/dXtpREchVgDiEWp1TA/giphy.gif'); }
            66% { background-image: url('https://media.giphy.com/media/cjVpja6OJKRJN9ZfXf/giphy.gif'); }
            100% { background-image: url('https://media.giphy.com/media/xqhXpqqZaUxbmcZUZC/giphy.gif'); }
        }

        .text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            z-index: 10;
            animation: textAnimation 3s ease-in-out infinite;
        }

        @keyframes textAnimation {
            0% { transform: translate(-50%, -50%) scale(1); }
            50% { transform: translate(-50%, -50%) scale(1.1); }
            100% { transform: translate(-50%, -50%) scale(1); }
        }

        .text h1 {
            font-size: 3rem;
            font-weight: bold;
            margin: 0;
            text-shadow: 0 0 15px #fff, 0 0 30px #ffcc00;
            color: #151ed1;
        }

        .text p {
            font-size: 4.8rem;
            margin-top: 10px;
            color: #d50e6b;
            text-shadow: 0 0 15px #fff, 0 0 30px #ffcc00;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="background"></div>
        <div class="text">
            <h1>11-maktab jamoasi sizlarni "Yangi yil" bilan tabriklayman kirib keyayotgan 2025-yil barchangizga qutlug va barokotli bo'lsin!!!</h1>
            <p> hurmat bilan  Feruzaxon Xoldarbekovna</p>
        </div>
    </div>
</body>
</html>
