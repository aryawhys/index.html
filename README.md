<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fake bot</title>
    <link rel="stylesheet" href="style.css" />
</head>

<body>

    <div class="container">
        <div class="wrapper">
            <div class="content">
                <h1 id="pertanyaan"></h1>
                <div class="row">
                    <input id="jawaban" type="text" placeholder="silahkan jawab">
                    <button onclick="botStart()" class="button">SEND</button>
                </div>
            </div>
        </div>
    </div>
    <div id="loaders"></div>
    <script src="bot.js"></script>
</body>

</html>
