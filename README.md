# Fluxo do Aplicativo
<i>Favor fazer um fork do repositório</i>

Na primeira tela teremos um formulario de login.

Após o login ser efetuado no endpoint **https://lucasapp.000webhostapp.com/captest/login.php** o aplicativo encaminha para a segunda tela.
Ao efetuar o login, deve ser gravado a sessão para que não passe pelo login na próxima vez que o usuário abrir o aplicativo. Somente se o usuário apagar os dados do aplicativo deve pedir novamente email e senha para logar.

Os dados que devem ser enviados por método <b>POST</b> para a API logar são:

<b>email</b> -> cap@test.com

<b>password</b> -> cap123

Na segunda tela temos uma WebView e uma View Nativa.

Exiba o nome do usuário retornado da API na Tela

Na WebView é exibida uma página HTML com Javascript que contém o código de integração para a a View Nativa.

Quando o botão que está na webview for pressionado, ele deve enviar o texto do campo na webview para o campo nativo.
Da mesma forma, quando o botão nativo for pressionado, o texto no campo nativo deve enviar para a webview.

<b>Obrigatórios:</b><br>
<li>Java ou Kotlin</li><br>
<li>O app deve funcionar a partir do android 6 (Marshmallow)</li><br>

<b>Diferenciais</b>

<li>Testes unitários, pode usar a ferramenta que você tem mais experiência.</li>

<li>Arquitetura a ser utilizada: Android Clean Code <br>
https://github.com/kmmraj/android-clean-code<br>
https://medium.com/@kmmraj/android-clean-code-part-1-c66da6551d1
</li>

## Home

![Login2.png](https://lucasapp.000webhostapp.com/captest/celular.jpg)
