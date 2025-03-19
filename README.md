<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HelpWave - Взаимопомощ</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .container { width: 50%; margin: auto; padding: 20px; }
        input, button { display: block; width: 100%; margin: 10px 0; padding: 10px; }
    </style>
</head>
<body>
    <h1>Добре дошли в HelpWave</h1>
    <p>Платформа за взаимопомощ</p>
    
    <div class="container">
        <h2>Регистрация</h2>
        <input type="text" placeholder="Потребителско име" id="username">
        <input type="password" placeholder="Парола" id="password">
        <button onclick="register()">Регистрирай се</button>
    </div>
    
    <script>
        function register() {
            let user = document.getElementById('username').value;
            let pass = document.getElementById('password').value;
            if (user && pass) {
                alert('Успешна регистрация!');
            } else {
                alert('Попълнете всички полета.');
            }
        }
    </script>
</body>
</html>
