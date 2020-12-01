# for-archive-flying-fish-
/*飛的魚*/

<html>

<head>
    <style>
        .square:hover {
            width: 200px;
            height: 200px;
            background-color: lightblue;
        }

        .fish-animation-block {
            width: 300px;
            height: 300px;
        }

        .fish {
            margin-left: 300px;
            margin-top: 300px;

            animation-name: fish-swimming;
            animation-duration: 1s;
            animation-delay: 0s;
            animation-timing-function: ease;
            animation-iteration-count: 0s;
            animation-fill-mode: forwards;
            animation-direction: alternate;
            animation-play-state: running;
            animation-iteration-count: infinite;
        }

        @keyframes fish-swimming {
            from {
                margin-top: 300px;
                margin-left: 300px;
            }

            to {
                margin-top: 0px;
                margin-left: 0px;
            }
        }
    </style>
</head>

<body>
    <img class="fish" src="http://i.imgur.com/BaWzqYf.jpg" width="300"></div>
</body>

</html>
