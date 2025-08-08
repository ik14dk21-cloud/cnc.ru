<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Школа ЧПУ Дмитрия Копылова</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #1a73e8;
            color: #fff;
            padding: 60px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2em;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        .btn {
            background: #1a73e8;
            color: #fff;
            padding: 12px 25px;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
        }
        .features {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .feature {
            flex: 1;
            min-width: 250px;
            background: #f2f2f2;
            padding: 20px;
            border-radius: 8px;
        }
        .testimonial {
            background: #f9f9f9;
            padding: 20px;
            border-left: 5px solid #1a73e8;
            margin-bottom: 20px;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        footer {
            background: #1a73e8;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
            object-fit: cover;
        }
    </style>
</head>
<body>

<header>
    <h1>Школа ЧПУ Дмитрия Копылова</h1>
    <p>Практический курс для начинающих и специалистов. Программирование, настройка, безопасность.</p>
    <a href="#contact" class="btn">Записаться на курс</a>
</header>

<section id="about">
    <h2>О курсе</h2>
    <p>Курс включает теорию, программирование, симуляции и работу с реальными ЧПУ-станками. Вы будете учиться у опытных наставников и применять знания на практике.</p>

    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1603395151744-01973fd2fba6?auto=format&fit=crop&w=800&q=80" alt="Оператор у станка">
        <img src="https://images.unsplash.com/photo-1603398938378-99d7a37d6b2b?auto=format&fit=crop&w=800&q=80" alt="Обучение у станка">
        <img src="https://images.unsplash.com/photo-1614064641938-7f5ec0978c8f?auto=format&fit=crop&w=800&q=80" alt="Девушка у оборудования">
        <img src="https://images.unsplash.com/photo-1624531910116-4ddaa26e1dfb?auto=format&fit=crop&w=800&q=80" alt="Работа с ЧПУ">
    </div>
</section>

<section id="features">
    <h2>Почему выбирают нас</h2>
    <div class="features">
        <div class="feature">
            <h3>Онлайн и офлайн</h3>
            <p>Удобный формат обучения из любой точки мира или на базе учебного центра.</p>
        </div>
        <div class="feature">
            <h3>Сертификат</h3>
            <p>По окончании курса вы получите официальный сертификат.</p>
        </div>
        <div class="feature">
            <h3>Наставники-практики</h3>
            <p>Обучение проводят специалисты с опытом работы на производстве более 10 лет.</p>
        </div>
    </div>
</section>

<section id="testimonials">
    <h2>Отзывы учеников</h2>
    <div class="testimonial">
        <p>«Очень классный курс! С нуля научился создавать управляющие программы и понял, как работает ЧПУ. Спасибо преподавателям!»<br><strong>— Иван К.</strong></p>
    </div>
    <div class="testimonial">
        <p>«Отличное сочетание теории и практики. Понравилось, что было много примеров с реального производства.»<br><strong>— Мария П.</strong></p>
    </div>
</section>

<section id="contact">
    <h2>Оставьте заявку на обучение</h2>
    <form action="#" method="POST">
        <input type="text" name="name" placeholder="Ваше имя" required>
        <input type="email" name="email" placeholder="Ваш Email" required>
        <textarea name="message" rows="5" placeholder="Ваши вопросы или пожелания..."></textarea>
        <button class="btn" type="submit">Отправить</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Школа ЧПУ Дмитрия Копылова. Все права защищены.</p>
</footer>

</body>
</html>
