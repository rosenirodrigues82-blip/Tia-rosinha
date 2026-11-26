# Tia-rosinha
Atividades tia Rosinha 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Tia Rosinha 🌸</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(180deg, #FFE6F2 0%, #FFF0F5 100%);
            min-height: 100vh;
            color: #5C2347;
            text-align: center;
            padding: 20px;
        }

        .container {
            max-width: 420px;
            margin: 0 auto;
        }

        h1 {
            font-size: 2.2rem;
            color: #B83B7C;
            margin: 20px 0;
        }

        .emoji-header {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .card {
            background: #fff;
            border-radius: 20px;
            padding: 25px;
            margin: 25px 0;
            box-shadow: 0 4px 15px rgba(184, 59, 124, 0.15);
        }

        .avatar-placeholder {
            width: 100px;
            height: 100px;
            background: #FED6E3;
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 50px;
        }

        h2 {
            font-size: 1.6rem;
            color: #B83B7C;
            margin-bottom: 15px;
        }

        p {
            font-size: 1.1rem;
            line-height: 1.7;
            margin-bottom: 25px;
        }

        input {
            width: 100%;
            padding: 14px;
            font-size: 1.1rem;
            border: 2px solid #FED6E3;
            border-radius: 12px;
            margin-bottom: 15px;
            text-align: center;
        }

        button {
            background: linear-gradient(135deg, #B83B7C, #D85A9B);
            color: white;
            border: none;
            padding: 14px 35px;
            font-size: 1.1rem;
            border-radius: 12px;
            cursor: pointer;
            font-weight: bold;
            transition: transform 0.2s;
        }

        button:hover {
            transform: scale(1.05);
        }

        .features {
            text-align: left;
            margin-top: 25px;
        }

        .features li {
            list-style: none;
            padding: 10px 0;
            border-bottom: 1px dashed #FED6E3;
            font-size: 1rem;
            line-height: 1.6;
        }

        .features li:last-child {
            border-bottom: none;
        }

        .tips {
            background: #E8F5E9;
            border-radius: 12px;
            padding: 15px;
            margin-top: 20px;
            font-size: 0.95rem;
            line-height: 1.6;
            color: #2E7D32;
        }

        .install-guide {
            background: #E3F2FD;
            border-radius: 12px;
            padding: 18px;
            margin-top: 20px;
            font-size: 0.95rem;
            line-height: 1.8;
            color: #1565C0;
        }

        .flower {
            font-size: 1.3rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="emoji-header">🌸✨🌷⭐</div>
        
        <h1>Tia Rosinha</h1>

        <div class="card">
            <div class="avatar-placeholder">👩🏫</div>
            
            <h2>Oi! Eu sou a Tia Rosinha 🌸</h2>
            
            <p>Sou psicopedagoga e adoro ajudar crianças a estudar brincando: leitura, contas, lição de casa e muitos desafios divertidos!</p>

            <h3>Como você se chama?</h3>
            <input type="text" placeholder="Seu nome" id="nomeInput">
            <br>
            <button onclick="enviarNome()">✨ Vamos lá!</button>

            <ul class="features">
                <li>📚 Ajuda na lição sem dar a resposta pronta</li>
                <li>🧩 Desafios, rimas e adivinhas</li>
                <li>💗 Paciência e muit
