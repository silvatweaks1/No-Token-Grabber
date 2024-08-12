<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Protegendo-se contra Grabbers de Token</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #007bff;
        }
        h2 {
            border-bottom: 2px solid #007bff;
            padding-bottom: 10px;
            margin-bottom: 20px;
            color: #333;
        }
        ul {
            margin: 0;
            padding: 0;
            list-style-type: disc;
            margin-left: 20px;
        }
        img {
            width: 100%;
            max-width: 800px;
            height: auto;
            display: block;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Protegendo-se contra Grabbers de Token</h1>
        <p>Obviamente, ninguém quer ser "grabbado", então aqui está um rápido tutorial para ajudar quem precisa. Vamos ser rápidos e práticos. Primeiramente, é importante entender como um grabber funciona:</p>
        
        <h2>Distribuição do Malware</h2>
        <p>Normalmente, os grabbers estão escondidos em arquivos piratas, cheats, spoofers, ou até mesmo em aplicativos de uso cotidiano, mas hospedados em sites maliciosos.</p>
        
        <h2>Execução</h2>
        <p>Ao executar ou instalar esse arquivo malicioso, ele pode fechar aplicativos como Discord e navegadores, entre outros, para injetar o código e roubar tokens, cookies, etc.</p>
        
        <h2>Captura do Token</h2>
        <p>O token grabber busca capturar os tokens de autenticação armazenados no PC da vítima, especificamente na pasta do Discord.</p>
        
        <h2>Envio das Informações</h2>
        <p>Esses dados são normalmente enviados para uma central, muitas vezes para uma webhook de um servidor específico. No entanto, como o Discord tenta mitigar essas práticas, muitos servidores são derrubados. Muitas centrais de grabber são armazenadas no Telegram, e o envio é geralmente feito via HTTP ou FTP.</p>
        
        <h2>Uso do Token</h2>
        <p>Com o token em mãos, o atacante pode contornar a verificação de IP (verificação por email de novo endereço), podendo fazer login sem precisar de um código adicional. No entanto, não é possível alterar a senha apenas com o token. Por isso, muitos grabbers também roubam os cookies do navegador para acessar o e-mail da vítima e realizar a troca da senha.</p>
        
        <h2>Como Posso Evitar?</h2>
        <ul>
            <li>Não clique em links desconhecidos.</li>
            <li>Use verificação de dois fatores (2FA).</li>
            <li>Utilize um antivírus.</li>
            <li>Use extensões para não salvar cookies.</li>
        </ul>
        
        <h2>Como Funciona a Extensão?</h2>
        <p>Existem vários tipos de extensões de "Password Manager", mas as mais conhecidas são LastPass e DashLane. Sinceramente, eu prefiro o DashLane (é pessoal). Ele funciona da seguinte maneira: ao salvar uma senha de qualquer lugar onde você fizer login, ela será armazenada no banco de dados deles (OBS: É TOTALMENTE SIGILOSO), em vez de ser salva nos cookies do seu computador. Assim, se você for "grabbado", seus cookies estarão totalmente limpos!</p>
        
        <!-- Imagem do GitHub -->
        <img src="https://github.com/user-attachments/assets/9cd2da97-1e2f-4c40-b8b4-4e5663a3eadf" alt="Segurança Digital">
    </div>
</body>
</html>
