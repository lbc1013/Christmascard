<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2020 Chrismast Card</title>
    <link rel="shortcut icon"
        href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQyTd9i3K1EVke5rZghc8H0Zny6xZBKyaMExQ&usqp=CAU">
    <meta property="og:image"
        content="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0gyC0Q93_lSFxb7A7avxRhNaD-KGVHAWiuw&usqp=CAU">
    <meta property="og:title" content="Christmas Card">
    <meta property="og:description" content="병찬&규리">
    <script src="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/snow.js"></script>
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Poor+Story&display=swap" rel="stylesheet">
    <style>
        * {
            font-family: 'Poor Story', cursive;
        }

        body {
            background-position: center;
            background-size: cover;

        }


        .envelope {
            width: 400px;
            height: 400px;
            background-image: url(https://cdn.dribbble.com/users/1003944/screenshots/14810411/media/9dfef999d29e966952a888444e9b36f9.gif);
            border-radius: 1000px;
            background-size: cover;
            background-position: center;
            margin: 200px auto 0px auto;
            cursor: pointer;
            box-shadow: inset 0px 0px 15px 15px white;        }

        .letter {
            text-align: center;
            margin: 0px auto 0px auto;
        }

        .letter-close {
            display: block;
        }

        .letter-open {
            display: none;

        }

        .image {
            width: 195px;
            height: 190px;
            background-image: url(https://cdn.hipwallpaper.com/i/67/23/iaZqKm.jpg);
            background-size: cover;
            background-position: center;
            margin: 50px auto 0px auto;
            border-radius: 100px;
            border: 3px solid white;
            box-shadow: 0px 0px 50px 0px white;
        }

        h1 {
            color: white;
            text-align: center;


        }

        .message-box {
            background-color: white;
            border-radius: 30px;
            margin: auto;
            width: 350px;
            background-size: cover;
            background-position: center;
            color: red;
            padding: 20px 10px 10px 10px;
            text-align: center;
            line-height: 20px;
            box-shadow: 0px 0px 10px 0px white;
        }

        .from {
            text-align: right;
        }

        @media screen and (max-width: 760px) {
            .message-box {
                width: 300px;
                padding: 5px;
            }

            .image {
                width: 150px;
                height: 150px;
            }

        }
        }
    </style>
    <script>
        function open_letter() {
            document.getElementsByClassName("letter-close")[0].style.display = 'none'
            document.getElementsByClassName("letter-open")[0].style.display = 'block'
        }
    </script>
</head>

<body>
    <div class="letter-close">
            <div class="envelope" onclick="open_letter()"></div>
            <h2 class="letter">Click the Tree</h2>
    </div>
    <div class="letter-open">
        <div class="image"> </div>
        <h1>Merry Christmas !</h1>
        <div class="message-box">
            지극히 높은 곳에서는 하나님께 영광이요<br />
            땅에서는 하나님이 기뻐하신 <br />
            사람들 중에 평화로다 하니라 <br />
            누가복음 2:14 <br />
            <p class="from">2020.12.25</p>
        </div>
    </div>

</body>

</html>
