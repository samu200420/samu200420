from flask import Flask, render_template_string

app = Flask(__name__)


html_code = '''
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Para Mi noviecita preciosa  💖</title>
    <style>
      body {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: #ffccf9;
        font-family: 'Arial', sans-serif;
        color: #333;
        height: 100vh;
        margin: 0;
      }
      .heart {
        font-size: 8em;
        color: #ff66b2;
        margin-bottom: 20px;
      }
      .message {
        font-size: 1.5em;
        text-align: center;
        max-width: 500px;
      }
    </style>
  </head>
  <body>
    <div class="heart">❤️</div>
    <div class="message">Hola mi vida solo quieres decirte queres lo mas bonito y hermoso que tengo en la vida, nunca olvide que me vas a tener a tu lado simpre eres mi razon por la que cada dia me siento motivado y la razon por la que estoy feliz y sonrio no olvide que nunca va estar solo y no sabe cuanto estoy enamorado de ti que haria cualquier cosa para que este feliz y amor que hermosa eres esa carita toda preciosa y ese cuerpecito que me tiene loco, nunca de los nunca olvides lo muchisimo que te amo y lo que mas quiero es que te cases conmigo TE AMOOOOOOOOOOOOO ❤️</div>
  </body>
</html>
'''

