<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botón Solicitar</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #2E8B57, #006400);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(15px);
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
            max-width: 400px;
            width: 100%;
        }

        .container h1 {
            color: #fff;
            font-size: 2.5em;
            margin-bottom: 15px;
            font-weight: 700;
        }

        .container p {
            color: #fff;
            font-size: 1.1em;
            margin-bottom: 25px;
        }

        .button {
            padding: 15px 45px;
            font-size: 22px;
            font-weight: bold;
            color: #ffffff !important; /* Color blanco para el texto del botón */
            background: linear-gradient(135deg, #4a90e2, #007bff); /* Degradado azul para el botón */
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            transition: transform 0.4s ease, box-shadow 0.4s ease, background 0.4s ease;
            display: inline-block;
            letter-spacing: 1px;
        }

        .button:hover {
            background: linear-gradient(135deg, #007bff, #4a90e2); /* Efecto de hover con degradado invertido */
            transform: translateY(-7px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Solicita Ahora</h1>
    <p>¡Obtén lo que necesitas con un solo clic!</p>
    <a href="https://sotmoney.com/" class="button" target="_blank">Solicitar</a>
</div>

</body>
</html>
