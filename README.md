<!DOCTYPE html>
<html>

<head lang="en">
    <meta charset="UTF-8">
    <title>贪吃蛇</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .map {
            width: 800px;
            height: 600px;
            margin: 60px auto;
            background-color: #cccccc;
            position: relative;
        }

        .map div {
            position: absolute;
        }
    </style>
</head>

<body>
    <div class="map"></div>

    <!-- 引用第三方 函数 -->
    <script src="./underscore.js"></script>
    <script src="./Food.js"></script>
    <script src="./Snake.js"></script>
    <script src="./Game.js"></script>
    <script>
       new Game()
    </script>
</body>

</html>
