# Protegendo-se Contra Grabbers de Token

Obviamente, ninguém quer ser "grabbado", então aqui está um rápido tutorial para ajudar quem precisa. Vamos ser rápidos e práticos. Primeiramente, é importante entender como um grabber funciona:

<p style="color: #007bff; font-weight: bold;">Distribuição do Malware:</p>

Normalmente, os grabbers estão escondidos em arquivos piratas, cheats, spoofers, ou até mesmo em aplicativos de uso cotidiano, mas hospedados em sites maliciosos.

<p style="color: #28a745; font-weight: bold;">Execução:</p>

Ao executar ou instalar esse arquivo malicioso, ele pode fechar aplicativos como Discord e navegadores, entre outros, para injetar o código e roubar tokens, cookies, etc.

<p style="color: #ffc107; font-weight: bold;">Captura do Token:</p>

O token grabber busca capturar os tokens de autenticação armazenados no PC da vítima, especificamente na pasta do Discord.

<p style="color: #dc3545; font-weight: bold;">Envio das Informações:</p>

Esses dados são normalmente enviados para uma central, muitas vezes para uma webhook de um servidor específico. No entanto, como o Discord tenta mitigar essas práticas, muitos servidores são derrubados. Muitas centrais de grabber são armazenadas no Telegram, e o envio é geralmente feito via HTTP ou FTP.

<p style="color: #17a2b8; font-weight: bold;">Uso do Token:</p>

Com o token em mãos, o atacante pode contornar a verificação de IP (verificação por email de novo endereço), podendo fazer login sem precisar de um código adicional. No entanto, não é possível alterar a senha apenas com o token. Por isso, muitos grabbers também roubam os cookies do navegador para acessar o e-mail da vítima e realizar a troca da senha.

<p style="color: #6f42c1; font-weight: bold;">Como Posso Evitar?</p>

- Não clique em links desconhecidos.
- Use verificação de dois fatores (2FA).
- Utilize um antivírus.
- Use extensões para não salvar cookies.

<p style="color: #e83e8c; font-weight: bold;">Como Funciona a Extensão?</p>

Existem vários tipos de extensões de "Password Manager", mas as mais conhecidas são LastPass e DashLane. Sinceramente, eu prefiro o DashLane (é pessoal). Ele funciona da seguinte maneira: ao salvar uma senha de qualquer lugar onde você fizer login, ela será armazenada no banco de dados deles (OBS: É TOTALMENTE SIGILOSO), em vez de ser salva nos cookies do seu computador. Assim, se você for "grabbado", seus cookies estarão totalmente limpos!

![SilvaTweaksSalvaKID](https://github.com/user-attachments/assets/9cd2da97-1e2f-4c40-b8b4-4e5663a3eadf)
