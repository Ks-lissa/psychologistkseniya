# psychologistkseniya
Просто о сложном. Психология вокруг нас. Запись на консультацию онлайн.
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Психолог Консультации</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Добро пожаловать на сайт психолога</h1>
        <nav>
            <ul>
                <li><a href="#services">Услуги</a></li>
                <li><a href="#about">Обо мне</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <section id="services">
        <h2>Мои Услуги</h2>
        <div class="service">
            <h3>Индивидуальные консультации</h3>
            <p>Предлагаю личные сессии, чтобы помочь вам преодолеть жизненные трудности.</p>
        </div>
        <div class="service">
            <h3>Групповая терапия</h3>
            <p>Групповые занятия для поддержки и обмена опытом.</p>
        </div>
    </section>

    <section id="about">
        <h2>Обо мне</h2>
        <p>Я квалифицированный психолог с более чем 10-летним опытом работы. Мое исследование и практика помогают многим людям.</p>
    </section>

    <section id="contact">
        <h2>Контакты</h2>
        <p>Свяжитесь со мной для записи на консультации:</p>
        <form>
            <input type="text" placeholder="Ваше имя" required>
            <input type="email" placeholder="Ваш email" required>
            <textarea placeholder="Сообщение" required></textarea>
            <button type="submit">Отправить</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Психолог. Все права защищены.</p>
    </footer>
</body>
</html>body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}
header {
    background: #33aaff;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}
nav ul {
    list-style: none;
    padding: 0;
}
nav ul li {
    display: inline;
    margin: 0 15px;
}
section {
    padding: 20px;
    margin-top: 20px;
}
footer {
    text-align: center;
    padding: 10px 0;
    background: #33aaff;
    color: #fff;
}
