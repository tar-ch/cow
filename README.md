<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بقرة مووو</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; }
        img { cursor: pointer; width: 300px; }
    </style>
</head>
<body>
    <h1>اضغط على البقرة!</h1>
    <img src="cow.png" alt="بقرة" onclick="playMoo()">
    <audio id="mooSound" src="moo.mp3"></audio>

    <script>
        function playMoo() {
            document.getElementById("mooSound").play();
        }
    </script>
</body>
</html># cow