<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>своя Среда - Центр психологической поддержки</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f1e8;
            color: #5d4037;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Шапка */
        header {
            background: linear-gradient(135deg, #d7ccc8, #efebe9);
            padding: 40px 0;
            text-align: center;
            border-bottom: 2px solid #bcaaa4;
        }

        .logo {
            font-size: 3.5em;
            font-weight: 300;
            color: #6d4c41;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        .tagline {
            font-size: 1.3em;
            color: #8d6e63;
            font-style: italic;
            margin-bottom: 20px;
        }

        /* Основной контент */
        .main-content {
            padding: 60px 0;
        }

        .welcome-section {
            text-align: center;
            margin-bottom: 50px;
        }

        .welcome-section h2 {
            font-size: 2.2em;
            margin-bottom: 20px;
            color: #5d4037;
            font-weight: 300;
        }

        .welcome-text {
            font-size: 1.1em;
            max-width: 800px;
            margin: 0 auto;
            color: #795548;
        }

        /* Контакты */
        .contacts-section {
            background: #efebe9;
            padding: 40px;
            border-radius: 10px;
            margin: 40px 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .contacts-section h3 {
            font-size: 1.8em;
            margin-bottom: 30px;
            text-align: center;
            color: #5d4037;
        }

        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }

        .contact-item {
            text-align: center;
            padding: 20px;
        }

        .contact-item i {
            font-size: 2em;
            color: #8d6e63;
            margin-bottom: 15px;
        }

        .contact-item h4 {
            font-size: 1.2em;
            margin-bottom: 10px;
            color: #5d4037;
        }

        /* Адрес */
        .address-section {
            background: white;
            padding: 40px;
            border-radius: 10px;
            margin: 40px 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .address-section h3 {
            font-size: 1.8em;
            margin-bottom: 20px;
            color: #5d4037;
            text-align: center;
        }

        .address-placeholder {
            background: #f5f5f5;
            border: 2px dashed #bcaaa4;
            border-radius: 8px;
            padding: 60px 20px;
            text-align: center;
            color: #8d6e63;
            font-size: 1.1em;
        }

        /* Футер */
        footer {
            background: #5d4037;
            color: #efebe9;
            text-align: center;
            padding: 30px 0;
            margin-top: 60px;
        }

        .social-links {
            margin-top: 20px;
        }

        .social-links a {
            color: #efebe9;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.1em;
        }

        /* Адаптивность */
        @media (max-width: 768px) {
            .logo {
                font-size: 2.5em;
            }
            
            .contact-info {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Шапка -->
    <header>
        <div class="container">
            <div class="logo">своя Среда</div>
            <div class="tagline">Пространство для вашего внутреннего равновесия</div>
        </div>
    </header>

    <!-- Основной контент -->
    <main class="container">
        <section class="main-content">
            <div class="welcome-section">
                <h2>Добро пожаловать в ваше пространство спокойствия</h2>
                <p class="welcome-text">
                    Мы создали уютное место, где вы можете найти поддержку, понимание и профессиональную помощь 
                    в комфортной и безопасной атмосфере. Здесь каждому найдется своя среда для роста и гармонии.
                </p>
            </div>

            <!-- Контакты -->
            <section class="contacts-section">
                <h3>Свяжитесь с нами</h3>
                <div class="contact-info">
                    <div class="contact-item">
                        <h4>📞 Телефон</h4>
                        <p>+7 (XXX) XXX-XX-XX</p>
                    </div>
                    <div class="contact-item">
                        <h4>✉️ Email</h4>
                        <p>info@svojasreda.ru</p>
                    </div>
                    <div class="contact-item">
                        <h4>🕒 Часы работы</h4>
                        <p>Пн-Пт: 9:00-21:00<br>Сб-Вс: 10:00-18:00</p>
                    </div>
                </div>
            </section>

            <!-- Адрес -->
            <section class="address-section">
                <h3>Мы находимся</h3>
                <div class="address-placeholder">
                    📍 Здесь будет ваш адрес<br>
                    <small>Опишите расположение, как добраться, ориентиры</small>
                </div>
            </section>
        </section>
    </main>

    <!-- Подвал -->
    <footer>
        <div class="container">
            <p>&copy; 2024 своя Среда. Центр психологической поддержки</p>
            <div class="social-links">
                <a href="#">VK</a>
                <a href="#">Telegram</a>
                <a href="#">Instagram</a>
            </div>
        </div>
    </footer>
</body>
</html>
