<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Mini App</title>

    <style>
        .img-centre {
            text-align: center;
        }
        .button-centre {
            text-align: center;
        }
        body {

            background: #808080;
        }

        h1 {
            margin-top: 50px;
            margin-bottom: 10px;
        }

        button {
            border: 0;
            border-radius: 5px:
            margin-top: 50px;
            height: 60px;
            width: 200px;
            font-size: 20px;
            font-wight: 500px;
            cursor: pointer;
            color: 'black';
            transition: all 500ms ease;
            background: #819ec7;
         }
         button:hover {
                background: #365178
         }
        p {
            color: 'red';
            margin-top: 25px;
            margin-bottom: 10px;
        }

    </style>
</head>
<body>
    <div>
        <h1 align="center">PLUSH PEPE</h1>
        <p align="center">150.000$</p>
        <div class="img-centre"> <img src="Pepe.png"> </div>
        <p>              </p>
        <div class="button-centre"> <button id ="buy">купить</button> </div>
    </div>
    <script src="https://telegram.org/js/telegram-web-app.js?59"></script>
</body>
</html>
