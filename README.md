# stromdeslebens.io
strom des lebens

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Мой сайт</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #fff;
            color: #333;
        }
        header {
            background: #121212;
            color: #fff;
            padding: 25px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 30px;
        }
        nav a {
            color: #fff;
            margin: 0 12px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 60px 20px;
            text-align: center;
        }
        .hero {
            background: #eee;
        }
        .services {
            background: #fafafa;
        }
        .services .item {
            display: inline-block;
            width: 280px;
            margin: 10px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
        .btn-main {
            display: inline-block;
            background: #0077cc;
            color: white;
            padding: 12px 28px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }
        footer {
            background: #121212;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <h1>Название сайта</h1>
    <nav>
        <a href="#about">О нас</a>
        <a href="#services">Услуги</a>
        <a href="#contact">Контакты</a>
    </nav>
</header>

<section class="hero">
    <h2>Привет! Это мой сайт</h2>
    <p>Здесь краткое описание того, чем вы занимаетесь</p>
    <a class="btn-main" href="#services">Узнать больше</a>
</section>

<section id="about">
    <h2>О нас</h2>
    <p>Пара предложений о твоём проекте или бизнесе</p>
</section>

<section id="services" class="services">
    <h2>Наши услуги</h2>
    <div class="item">
        <h3>Услуга 1</h3>
        <p>Краткое описание услуги</p>
    </div>
    <div class="item">
        <h3>Услуга 2</h3>
        <p>Краткое описание услуги</p>
    </div>
    <div class="item">
        <h3>Услуга 3</h3>
        <p>Краткое описание услуги</p>
    </div>
</section>

<section id="contact">
    <h2>Контакты</h2>
    <p>Email: example@mail.com</p>
    <p>Телефон: +49 123 456 789</p>
</section>

<footer>
    &copy; 2026 Мой сайт
</footer>

</body>
</html>
