
<!DOCTYPE html>
<html>
<head>
    <title>Клуб Вулкан</title>
    <meta charset="utf-8">
    <meta name="viewport" content="user-scalable=no, width=device-width, initial-scale=1, maximum-scale=1">
    <link type="image/x-icon" rel="shortcut icon" href="img/favicon.ico">
    <link rel="stylesheet" href="css/slick.css"/>
    <link rel="stylesheet" href="css/style.css"/>
    <script src="js/jquery-3.2.1.min.js"></script>
    <script src="js/jquery.animateNumber.min.js"></script>
    <script src="js/slick.min.js"></script>
</head>
<body>

<div class="layout">
    <div class="top">
        <div id="logo"><img src="img/logo.png" alt=""></div>
        <div class="neon-txt"><img src="img/neon-txt.png" alt=""></div>
    </div>
    <div class="slider_wrap">
        <div class="carusel-slide slide-1">
            <div class="slide-txt-1">Каждую секунду</div>
            <div class="slide-txt-2">в Клубе Вулкан</div>
            <div class="slide-txt-2">выигрывают более</div>
            <div class="slide-txt-3"><span class="slide-txt-num"></span> рублей</div>
        </div>
        <div class="carusel-slide slide-2">
            <div class="slide-txt-1">Самые крупные</div>
            <div class="slide-txt-4">джекпоты</div>
            <div class="slide-txt-3"><span class="slide-txt-num"></span> рублей</div>
        </div>
        <div class="carusel-slide slide-3">
            <div class="slide-txt-1">Быстрый вывод</div>
            <div class="slide-txt-4">всех</div>
            <div class="slide-txt-4">выигрышей</div>
        </div>
        <div class="carusel-slide slide-4">
            <div class="slide-txt-1">В клубе Вулкан</div>
            <div class="slide-txt-2">Самый высокий процент</div>
            <div class="slide-txt-2">отдачи всех автоматов</div>
            <div class="slide-txt-3"><span class="slide-txt-num">97</span> %</div>
        </div>
        <div class="carusel-slide slide-5">
            <div class="slide-txt-1">Приветственный</div>
            <div class="slide-txt-5">бонус</div>
            <div class="slide-txt-3"><span class="slide-txt-num">500</span> рублей</div>
        </div>
    </div>
    <div class="btn-wrap"><a href="https://go4wincash.com/?s=35&ref=wp_w16796p268_&encoded_url=I3BvcHVwLXJlZw==" class="btn-play"></a></div>
    <script type="text/javascript">
        $(document).ready(function(){
            $('.slider_wrap').slick({
                infinite: true,
                autoplay: true,
                speed: 600,
                autoplaySpeed: 2500,
                arrows: true,
                useTransform: false,
                swipeToSlide: true,
                pauseOnHover: false,
                pauseOnFocus: false,
                verticalSwiping: false,
                swipe: false,
                prevArrow: '<div class="slick-prev"></div>',
                nextArrow: '<div class="slick-next"></div>'
            });
            var comma_separator_number_step = $.animateNumber.numberStepFactories.separator(',');
            $(".slider_wrap").on("beforeChange", function () {
                restartCounter();
                startCounter();
            });
            startCounter();

            function startCounter() {
                $('.slide-1 .slide-txt-num').animateNumber({
                    number: 9185,
                    numberStep: comma_separator_number_step
                }, 500 );
                $('.slide-2 .slide-txt-num').animateNumber({
                    number: 3866867,
                    numberStep: comma_separator_number_step
                }, 500 );
                $('.slide-4 .slide-txt-num').animateNumber({ number: 97 }, 750 );
                $('.slide-5 .slide-txt-num').animateNumber({ number: 500 }, 750 );
            }

            function restartCounter() {
                $('.slide-1 .slide-txt-num').animateNumber({ number: 1, numberStep: comma_separator_number_step },350);
                $('.slide-2 .slide-txt-num').animateNumber({ number: 1, numberStep: comma_separator_number_step },350);
                $('.slide-4 .slide-txt-num').text('0');
                $('.slide-5 .slide-txt-num').text('0');
            }
        });
    </script>
</div>

<img style="position:absolute" src="https://stats.welcomepartners.com/pixel.png?site_id=35&refCode=wp_w16796p268_&is_unique=0&rnd=15534591985c97e7fea6ce4"></body>

</html>