<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Curso de Front-End</title>
    <style>
        body {
            background-color: #f9c6d3;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        h1 {
            color: #d84b8c;
            margin-top: 30px;
        }

        .form-container {
            background-color: #f48fb1;
            width: 350px;
            margin: 30px auto;
            padding: 20px;
            border-radius: 20px;
            text-align: left;
        }

        .form-container h2 {
            text-align: center;
            color: #6a1b55;
        }

        label {
            display: block;
            margin-top: 10px;
            margin-bottom: 5px;
            color: #4a0e34;
        }

        input[type="text"],
        input[type="email"],
        input[type="password"],
        input[type="date"] {
            width: 100%;
            padding: 8px;
            border: none;
            border-radius: 5px;
        }

        .gender-container {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-top: 10px;
        }

        .gender-container label {
            margin: 0;
        }

        .terms {
            font-size: 10px;
            margin-top: 10px;
            color: #4a0e34;
        }

        .submit-button {
            display: block;
            width: 100%;
            padding: 10px;
            margin-top: 15px;
            background-color: #ec407a;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            font-size: 16px;
        }

        .submit-button:hover {
            background-color: #d81b60;
        }
    </style>
</head>
<body>

    <h1>CURSO DE FRONT-END</h1>

    <div class="form-container">
        <h2>Cadastre-se</h2>

        <label>Nome completo:</label>
        <input type="text" placeholder="">

        <label>Email:</label>
        <input type="email" placeholder="">

        <label>Senha:</label>
        <input type="password" placeholder="">

        <label>Confirmação de senha:</label>
        <input type="password" placeholder="">

        <label>Data de nascimento:</label>
        <input type="date" placeholder="">

        <label>Gênero</label>
        <div class="gender-container">
            <label><input type="radio" name="genero"> Masc</label>
            <label><input type="radio" name="genero"> Fem</label>
        </div>

        <div class="terms">
            Ao continuar, você concorda com nossos Termos de Uso e Política de Privacidade.
        </div>

        <button class="submit-button">Enviar</button>
    </div>

</body>
</html>
