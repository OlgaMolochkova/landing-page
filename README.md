<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Публичные выступления в Торревьехе</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            text-align: center;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        .header h1 {
            font-size: 2.5rem;
            color: #2c3e50;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }

        .header .emoji {
            font-size: 3rem;
            margin-bottom: 20px;
            display: block;
        }

        .header p {
            font-size: 1.2rem;
            color: #555;
            margin-bottom: 0;
        }

        .dates {
            background: linear-gradient(45deg, #ff6b6b, #ffa500);
            color: white;
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 30px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        .dates h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .dates .date-item {
            font-size: 1.3rem;
            font-weight: bold;
            margin: 10px 0;
        }

        .card {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 25px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h2 {
            color: #2c3e50;
            font-size: 1.8rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .card h3 {
            color: #e74c3c;
            font-size: 1.3rem;
            margin: 20px 0 10px 0;
        }

        .program-item {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 10px;
            margin-bottom: 15px;
            border-left: 4px solid #3498db;
        }

        .program-item h4 {
            color: #2c3e50;
            margin-bottom: 8px;
        }

        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .benefit-item {
            background: linear-gradient(45deg, #56ab2f, #a8e6cf);
            color: white;
            padding: 15px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
            font-weight: 500;
            transition: transform 0.3s ease;
        }

        .benefit-item:hover {
            transform: scale(1.05);
        }

        .approach-card {
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 25px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
        }

        .approach-card h2 {
            color: white;
            margin-bottom: 15px;
        }

        .contact-section {
            background: linear-gradient(45deg, #ff4757, #ff6b6b);
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
        }

        .contact-section h2 {
            color: white;
            margin-bottom: 20px;
        }

        .contact-item {
            background: rgba(255, 255, 255, 0.2);
            padding: 15px;
            border-radius: 10px;
            margin: 10px 0;
            font-size: 1.1rem;
            font-weight: 500;
        }

        .price {
            font-size: 2rem;
            font-weight: bold;
            color: #fff;
            background: linear-gradient(45deg, #f39c12, #e67e22);
            padding: 15px;
            border-radius: 10px;
            margin: 20px 0;
            text-align: center;
        }

        .footer {
            text-align: center;
            color: white;
            margin-top: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            backdrop-filter: blur(10px);
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }
            
            .header p {
                font-size: 1rem;
            }
            
            .container {
                padding: 10px;
            }
            
            .card {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <span class="emoji">🎤</span>
            <h1>ПУБЛИЧНЫЕ ВЫСТУПЛЕНИЯ В ТОРРЕВЬЕХЕ</h1>
            <p>Приглашаем русскоязычных жителей Торревьехи и близлежащих городов на увлекательную встречу-практикум по искусству публичных выступлений!</p>
        </div>

        <div class="dates">
            <h2>📅 ДАТЫ ПРОВЕДЕНИЯ</h2>
            <div class="date-item">16 августа</div>
            <div class="date-item">30 августа</div>
            <div style="margin-top: 15px;">
                <div>📍 Место: г. Торревьеха (точное место уточняется)</div>
                <div>⏰ Продолжительность: 2,5-3 часа активной работы</div>
            </div>
        </div>

        <div class="approach-card">
            <h2>🎯 ОСОБЕННОСТИ ПОДХОДА</h2>
            <p><strong>Используем коучинговые методики для самообучения:</strong> вместо оценок и критики учимся анализировать свои ощущения, отслеживать изменения и находить собственные решения для роста в публичных выступлениях.</p>
        </div>

        <div class="card">
            <h2>👤 ДЛЯ КОГО?</h2>
            <p>Для всех русскоязычных жителей Испании, кто хочет:</p>
            <ul style="margin-top: 15px; padding-left: 20px;">
                <li>Провести время интересно и с пользой</li>
                <li>Пообщаться с единомышленниками</li>
                <li>Попрактиковать навыки публичных выступлений</li>
                <li>Преодолеть страх перед аудиторией</li>
                <li>Освоить новые методики самопрезентации</li>
            </ul>
        </div>

        <div class="card">
            <h2>📋 ПРОГРАММА ВСТРЕЧИ</h2>
            
            <div class="program-item">
                <h4>🗣️ Разминка (15 минут)</h4>
                <p>Артикуляционная гимнастика и упражнения для дикции</p>
            </div>

            <div class="program-item">
                <h4>🎭 Практика 1: "Рассказ о себе" (40-45 минут)</h4>
                <p>• 10 минут: объяснение методики на примере<br>
                • 30 минут: отработка в тройках<br>
                • Учимся рассказывать о себе интересно и запоминающе</p>
            </div>

            <div class="program-item">
                <h4>💬 Практика 2: "Фраза дня" (40-45 минут)</h4>
                <p>• 10-15 минут: разбор подхода на примере<br>
                • 30 минут: работа в тройках<br>
                • Выберите любимую цитату великих людей или получите случайную - и научитесь подавать её ярко!</p>
            </div>

            <div class="program-item">
                <h4>🎪 Мини-спичи на всю аудиторию (30-40 минут)</h4>
                <p>2-3 минутные выступления каждого участника с обратной связью</p>
            </div>

            <div class="program-item">
                <h4>🤸 Активные перерывы</h4>
                <p>После каждой практики - 10 минут подвижной гимнастики с пальчиковой зарядкой для снятия напряжения</p>
            </div>

            <div class="program-item">
                <h4>💭 Завершение (10-15 минут)</h4>
                <p>Обмен впечатлениями через коучинговые вопросы: анализируем свои ощущения, отмечаем изменения и определяем конкретные шаги для применения навыков в жизни</p>
            </div>
        </div>

        <div class="card">
            <h2>🌟 ЧТО ВЫ ПОЛУЧИТЕ?</h2>
            <div class="benefits">
                <div class="benefit-item">✅ Практические навыки уверенного выступления</div>
                <div class="benefit-item">✅ Преодоление страха публичных выступлений</div>
                <div class="benefit-item">✅ Новые знакомства и интересное общение</div>
                <div class="benefit-item">✅ Освоение разных методик самопрезентации</div>
                <div class="benefit-item">✅ Активное и полезное времяпрепровождение</div>
                <div class="benefit-item">✅ Заряд позитивной энергии</div>
                <div class="benefit-item">✅ Опыт работы в команде</div>
                <div class="benefit-item">✅ Развитие навыков самоанализа и рефлексии</div>
                <div class="benefit-item">✅ Умение понимать свои ощущения во время выступления</div>
                <div class="benefit-item">✅ Конкретные шаги для применения полученных навыков в жизни</div>
            </div>
        </div>

        <div class="card">
            <h2>👩‍🏫 ВЕДУЩАЯ</h2>
            <p><strong>Молочкова Ольга</strong> - основатель проекта "Публичные выступления на планете Земля"</p>
        </div>

        <div class="card">
            <h2>👥 КОЛИЧЕСТВО УЧАСТНИКОВ</h2>
            <p>До 30 человек (регистрация обязательна)</p>
        </div>

        <div class="contact-section">
            <h2>💰 СТОИМОСТЬ И КОНТАКТЫ</h2>
            <div class="price">20 евро</div>
            <p>Оплата через подписку на закрытый телеграм-канал</p>
            
            <div class="contact-item">
                📱 Telegram: @olga_earth
            </div>
            <div class="contact-item">
                💳 Оплата: подписка на канал @Torreveha_PS
            </div>
            
            <p style="margin-top: 20px; font-size: 1.2rem; font-weight: bold;">
                Не упустите возможность провести время с пользой, найти новых друзей и прокачать свои навыки общения!
            </p>
        </div>

        <div class="footer">
            <p><em>Встреча проводится на русском языке в дружеской атмосфере. Приходите - будет интересно!</em> 🌟</p>
        </div>
    </div>
</body>
</html>
