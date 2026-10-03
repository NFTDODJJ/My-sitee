<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой тестовый сайт</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            color: #ffffff;
            min-height: 100vh;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
        }
        .badge {
            display: inline-block;
            background: #ff6b6b;
            color: white;
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 13px;
            font-weight: bold;
            letter-spacing: 1px;
            margin-bottom: 15px;
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
        h1 {
            font-size: 32px;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #ff6b6b, #feca57, #48dbfb);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .subtitle {
            color: #b8b8d1;
            font-size: 16px;
            margin-bottom: 30px;
        }
        .card {
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.15);
            border-radius: 16px;
            padding: 24px;
            margin-bottom: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
        }
        .card h2 {
            font-size: 20px;
            margin-bottom: 12px;
            color: #feca57;
        }
        .card p {
            color: #d0d0e0;
            line-height: 1.6;
            font-size: 15px;
        }
        .free-banner {
            background: linear-gradient(90deg, #00b894, #00cec9);
            border-radius: 16px;
            padding: 20px;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 25px;
            box-shadow: 0 5px 20px rgba(0, 206, 201, 0.4);
        }
        .footer {
            text-align: center;
            color: #6c6c8a;
            font-size: 13px;
            margin-top: 40px;
        }
        .features {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            margin-top: 15px;
        }
        .feature-tag {
            background: rgba(255, 255, 255, 0.1);
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 13px;
            color: #a0a0c0;
        }
    </style>
</head>
<body>
    <div class="container">
        
        <!-- Метка "Тестовый сайт" -->
        <span class="badge">🧪 ТЕСТОВЫЙ САЙТ</span>
        
        <h1>Добро пожаловать!</h1>
        <p class="subtitle">Это мой первый сайт, сделанный на телефоне</p>

        <!-- Бесплатный доступ -->
        <div class="free-banner">
            🎉 Сайт доступен для всех абсолютно бесплатно!
        </div>

        <!-- Карточка 1 -->
        <div class="card">
            <h2>⏳ Скоро здесь появится информация</h2>
            <p>Я буду добавлять новые разделы, интересные материалы и полезные ссылки. Следи за обновлениями!</p>
            <div class="features">
                <span class="feature-tag">Новости</span>
                <span class="feature-tag">Обзоры</span>
                <span class="feature-tag">Полезное</span>
            </div>
        </div>

        <!-- Карточка 2 -->
        <div class="card">
            <h2>🚀 О проекте</h2>
            <p>Этот сайт создан с нуля. Я учусь делать сайты и игры прямо на телефоне. Здесь будет всё самое интересное.</p>
        </div>

        <!-- Карточка 3 -->
        <div class="card">
            <h2>💡 Что дальше?</h2>
            <p>Планирую добавить: галерею, музыкальный плеер, мини-игры и раздел с полезными советами.</p>
        </div>

        <p class="footer">© 2026 Мой тестовый сайт. Сделано на телефоне 📱</p>

    </div>
</body>
</html># My-sitee
