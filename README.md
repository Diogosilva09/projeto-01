<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Inicial</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 60px auto;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            padding: 40px;
            text-align: center;
        }
        h1 {
            color: #333;
        }
        p {
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bem-vindo ao Projeto 01</h1>
        <p>Esta é a página inicial do seu projeto.</p>
        <a href="servicos.html" style="
            display: inline-block;
            margin-top: 24px;
            padding: 12px 28px;
            background: #007bff;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.1em;
            transition: background 0.2s;
        " onmouseover="this.style.background='#0056b3'" onmouseout="this.style.background='#007bff'">
            Conheça nossos serviços
        </a>
        <br><br>
        <form action="mailto:seuemail@dominio.com" method="post" enctype="text/plain" style="margin-top: 32px; text-align: left; max-width: 400px; margin-left: auto; margin-right: auto; background: #f8f9fa; padding: 24px; border-radius: 8px; box-shadow: 0 1px 4px rgba(0,0,0,0.06);">
            <h2 style="text-align:center; color:#333; font-size:1.3em; margin-top:0;">Contato por E-mail</h2>
            <label for="nome" style="color:#333;">Nome:</label><br>
            <input type="text" id="nome" name="nome" required style="width:100%; padding:8px; margin-bottom:12px; border-radius:4px; border:1px solid #ccc;"><br>
            <label for="email" style="color:#333;">E-mail:</label><br>
            <input type="email" id="email" name="email" required style="width:100%; padding:8px; margin-bottom:12px; border-radius:4px; border:1px solid #ccc;"><br>
            <label for="mensagem" style="color:#333;">Mensagem:</label><br>
            <textarea id="mensagem" name="mensagem" rows="4" required style="width:100%; padding:8px; margin-bottom:12px; border-radius:4px; border:1px solid #ccc;"></textarea><br>
            <button type="submit" style="background:#007bff; color:#fff; border:none; border-radius:4px; padding:10px 24px; font-size:1em; cursor:pointer; transition:background 0.2s;">Enviar</button>
        </form>
        <br><br>
        <a href="quem-somos.html" style="
            display: inline-block;
            margin-top: 8px;
            padding: 12px 28px;
            background: #28a745;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.1em;
            transition: background 0.2s;
        " onmouseover="this.style.background='#1e7e34'" onmouseout="this.style.background='#28a745'">
            Quem Somos
        </a>
    </div>
</body>
</html>
