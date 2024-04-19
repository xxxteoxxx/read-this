<!doctype html>
<html lang="en">

<head>
    <title id="titleWeb"></title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/spinload.css">
    <link rel="stylesheet" type="text/css" href=" https://fonts.googleapis.com/css?family=Pacifico" />
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
</head>

<body onload="loadSound()">
    <div class="wrapper">
        <!-- Preloader -->
        <div id="preloader">
            <div class="spinner">
                <div class="rect1"></div>
                <div class="rect2"></div>
                <div class="rect3"></div>
                <div class="rect4"></div>
                <div class="rect5"></div>
            </div>
        </div>
        <div id="bg"></div>
        <div class="content">
            <header>
                <h2 id="title"></h2>
                <h4 id="desc"></h4>
            </header>
            <p>
                Hello, yuhji! I hope this letter finds you well. There’s something I’ve been carrying on my conscience, and I believe it’s important to address it openly and honestly. I can’t handle this feeling any longer. Yuhji, I like you to the point that every night I can’t sleep thinking about you, to the point that when I wake up in the morning, you're the first thing on my mind. I don't know why I feel this way, but it's not voluntary and it's not forced. I've evaluated my feelings and come to the conclusion that what I’m feeling for you is not obsession, infatuation, admiration, etc., but something more than that. I know it's still early, but I just want you to know that I have genuine and good intentions for you. I want to know you more, I want to be with you, spend more time with you. Honestly, I might be crazy for you. I'm not pressuring you, I just wanted to express my genuine feelings for you. I also don't want you to be confused or uncomfortable. Please do tell me if you find me annoying or if my constant messaging bothers you or if my presence is bothering your peace of mind.
            </p>
            <button id="yes" type="button" class="btn btn-danger btn-lg"> </button>
            <button id="no" type="button" class="btn btn-info btn-lg"></button>
        </div>
    </div>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.js" integrity="sha256-WpOohJOqMqqyKL9FccASB9O0KwACQJpFTUBLTYOVvVU=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@9"></script>
    <script src="./config.js"></script>
    <script src="./js/main.js"></script>

    <script>
        function loadSound() {
            var audio = new Audio('sound/sound.mp3');
            audio.play();
        }
    </script>
</body>

</html>
