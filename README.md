<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Допомога ВПО</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #0056b3; color: white; padding: 15px; text-align: center; }
        nav { background-color: #004494; padding: 10px; text-align: center; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-size: 18px; }
        .container { padding: 20px; text-align: center; }
        footer { background-color: #002766; color: white; text-align: center; padding: 10px; margin-top: 20px; }
        .form-container { max-width: 400px; margin: auto; background: white; padding: 20px; border-radius: 10px; }
        input, textarea, button { width: 100%; padding: 10px; margin-top: 10px; border-radius: 5px; border: 1px solid #ccc; }
        button { background-color: #0056b3; color: white; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>Допомога ВПО</h1>
    </header>
    <nav>
        <a href="#about">Про нас</a>
        <a href="#support">Допомога</a>
        <a href="#contact">Контакти</a>
    </nav>
    <div class="container" id="about">
        <h2>Про нас</h2>
        <p>Рада з питань ВПО при Білгород-Дністровській районній державній (військовій) адміністрації є консультативно-дорадчим органом, що створений для участі в реалізації регіональної політики у сфері забезпечення та захисту прав та інтересів внутрішньо переміщених осіб. Ми сприяємо діяльності територіальних громад у розвитку ефективних механізмів адаптації та інтеграції ВПО.</p>
    </div>
    <div class="container" id="support">
        <h2>Отримати допомогу</h2>
        <div class="form-container">
            <form>
                <input type="text" placeholder="Ваше ім'я" required>
                <input type="email" placeholder="Ваш email" required>
                <textarea placeholder="Опишіть вашу ситуацію" rows="4" required></textarea>
                <button type="submit">Надіслати заявку</button>
            </form>
        </div>
    </div>
    <div class="container" id="contact">
        <h2>Контакти</h2>
        <p>Email: support@vpo-help.ua</p>
        <p>Телефон: +38 000 000 0000</p>
    </div>
    <footer>
        <p>&copy; 2025 Допомога ВПО. Всі права захищені.</p>
    </footer>
</body>
</html>
