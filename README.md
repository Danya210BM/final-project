<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lexi!</title>
  <style>
    body {
      background: linear-gradient(to right, #00b4db, #0083b0);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: white;
      text-align: center;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }
    h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    p {
      font-size: 20px;
      margin-bottom: 40px;
    }
    a.button {
      background-color: white;
      color: #0083b0;
      padding: 15px 30px;
      border-radius: 30px;
      font-size: 18px;
      transition: 0.3s;
    }
    a.button:hover {
      background-color: #e0f7fa;
    }
  </style>
</head>
<body>

  <h1>👋 <em>Welcome to Lexi !</em></h1>
  <img src="https://www.teacheracademy.eu/wp-content/uploads/2019/02/LANG.1.HACK_-608x405.jpg"width="400" style=" border-radius: 50%; box-shadow: 0 2px 6px rgba(0,0,0,0.2);">
  <p>Learn new words, discover languages, and have fun!</p>
  <a href="french.html" class="button">Start Learning</a>

</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Quiz de Français</title>
  <style>
    body {
    font-family: Arial, sans-serif;
    background-image: url('https://www.lingoda.com/wp-content/webp-express/webp-images/uploads/2021/11/french-speaking-countries-bis-1-2048x1366.jpg.webp');
    background-size: cover;
    text-align: center;
    padding: 60px;
    color: white;
    min-height: 100vh;
    }

    .container {
    background: rgba(0, 0, 0, 0.6);
    padding: 30px;
    border-radius: 15px;
    display: inline-block;
    margin-top: 30px;
    }

    .word-card {
    background-color: rgba(255, 255, 255, 0.85);
    color: black;
    border-radius: 10px;
    padding: 15px;
    margin: 10px auto;
    max-width: 350px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }

    .word {
      font-size: 30px;
      font-weight: bold;
    }

    .translation {
      font-size: 25px;
      font-style: italic;
      margin: 5px 0;
    }

    .audio-button {
      margin-top: 10px;
      background-color: #0083b0;
      border: none;
      color: white;
      padding: 8px 12px;
      border-radius: 8px;
      cursor: pointer;
    }

    .audio-button:hover {
      background-color: #00b4db;
    }

    #quiz {
      margin-top: 40px;
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.2);
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
      color: black;
    }

    .option-button {
      display: block;
      margin: 10px auto;
      padding: 10px 20px;
      background-color: #0083b0;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }

    .option-button:hover {
      background-color: #00b4db;
    }
  </style>
</head>
<body>
  <h1>Learn French Basics</h1>
  <img src="https://upload.wikimedia.org/wikipedia/en/c/c3/Flag_of_France.svg" width="100">

  <div class="word-card">
    <div class="word">Bonjour</div>
    <div class="translation">Good morning</div>
    <audio id="audio-bonjour" src="pronunciation_fr_bonjour.mp3"></audio>
  <button onclick="document.getElementById('audio-bonjour').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Au revoir</div>
    <div class="translation">Goodbye</div>
    <audio id="audio-au revoir" src="pronunciation_fr_au_revoir.mp3"></audio>
  <button onclick="document.getElementById('audio-au revoir').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Merci</div>
    <div class="translation">Thank you</div>
    <audio id="audio-merci" src="pronunciation_fr_merci.mp3"></audio>
  <button onclick="document.getElementById('audio-merci').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Oui</div>
    <div class="translation">Yes</div>
    <audio id="audio-oui" src="pronunciation_fr_oui.mp3"></audio>
  <audio id="audio-" src="pronunciation_fr_.mp3"></audio>
  <button onclick="document.getElementById('audio-oui').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Non</div>
    <div class="translation">No</div>
    <audio id="audio-non" src="pronunciation_fr_non.mp3"></audio>
  <button onclick="document.getElementById('audio-non').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Homme</div>
    <div class="translation">Man</div>
    <audio id="audio-homme" src="pronunciation_fr_homme.mp3"></audio>
  <button onclick="document.getElementById('audio-homme').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Femme</div>
    <div class="translation">Woman</div>
    <audio id="audio-femme" src="pronunciation_fr_femme.mp3"></audio>
  <button onclick="document.getElementById('audio-femme').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Stylo</div>
    <div class="translation">Pen</div>
    <audio id="audio-stylo" src="pronunciation_fr_stylo.mp3"></audio>
  <button onclick="document.getElementById('audio-stylo').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Rouge</div>
    <div class="translation">Red</div>
    <audio id="audio-rouge" src="pronunciation_fr_rouge.mp3"></audio>
  <button onclick="document.getElementById('audio-rouge').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Lundi</div>
    <div class="translation">Monday</div>
    <audio id="audio-lundi" src="pronunciation_fr_lundi.mp3"></audio>
  <button onclick="document.getElementById('audio-lundi').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Dix</div>
    <div class="translation">Ten</div>
    <audio id="audio-dix" src="pronunciation_fr_dix.mp3"></audio>
  <button onclick="document.getElementById('audio-dix').play()">🔊 Listen</button>
  </div>

  <div class="container">
    <div id="quiz">
      <h2>Quiz: What does "Merci" mean?</h2>
      <button class="option-button" onclick="checkAnswer(this, false)">Please</button>
      <button class="option-button" onclick="checkAnswer(this, true)">Thank you</button>
      <button class="option-button" onclick="checkAnswer(this, false)">Hello</button>
    </div>
  </div>
  <br>
<div class="container">
  <p style="margin-top: 40px;">
    If you want to learn some Spanish, 
    <a href="spanish.html" style="color: #00b4db; text-decoration: none; font-weight: bold;">click here</a>.
  </p>
</div>
  <script>
    function playAudio(word) {
      const audio = new Audio(`audio/${word}.mp3`);
      audio.play();
    }

    function checkAnswer(button, isCorrect) {
      if (isCorrect) {
        alert("✅ Correct!");
      } else {
        alert("❌ Try again!");
      }
    }
  </script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Mini Language Learning - Spanish</title>
<style>
    body {
    font-family: Arial, sans-serif;
    background-image: url('https://www.trade.gov.pl/wp-content/uploads/2025/03/45864399_m-2048x1365.jpg');
    background-size: cover;
    text-align: center;
    padding: 60px;
    color: white;
    min-height: 100vh;
    }
    h1 {
    color: #333;
    }
    .container {
    background: rgba(0, 0, 0, 0.6);
    padding: 30px;
    border-radius: 15px;
    display: inline-block;
    margin-top: 30px;
    }
    .word-card {
    background-color: rgba(255, 255, 255, 0.85);
    color: black;
    border-radius: 10px;
    padding: 15px;
    margin: 10px auto;
    max-width: 350px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }
    .word {
    font-size: 30px;
    font-weight: bold;
    }
    .translation {
    font-size: 25px;
    font-style: italic;
    color: #666;
    margin-top: 10px;
    }
    .audio-button {
      margin-top: 10px;
      background-color: #0083b0;
      border: none;
      color: white;
      padding: 8px 12px;
      border-radius: 8px;
      cursor: pointer;
    }
    .audio-button:hover {
      background-color: #00b4db;
    }
    #quiz {
      margin-top: 40px;
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.2);
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
      color: black;
    }
    .option-button {
      display: block;
      margin: 10px auto;
      padding: 10px 20px;
      background-color: #0083b0;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .option-button:hover {
    background-color: #00b4db;
    }
</style>
</head>
<body>
<h1> Learn Spanish Basics</h1>
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/9/9a/Flag_of_Spain.svg/800px-Flag_of_Spain.svg.png" width="100">
<div class="word-card">
    <div class="word">Perro</div>
    <div class="translation">Dog </div>
    <audio id="audio-perro" src="pronunciation_es_perro.mp3"></audio>
  <button onclick="document.getElementById('audio-perro').play()">🔊 Listen</button>
</div>

<div class="word-card">
    <div class="word">Gato</div>
    <div class="translation">Cat </div>
    <audio id="audio-gato" src="pronunciation_es_gato.mp3"></audio>
  <button onclick="document.getElementById('audio-gato').play()">🔊 Listen</button>
</div>

<div class="word-card">
    <div class="word">Manzana</div>
    <div class="translation">Apple </div>
    <audio id="audio-manzana" src="pronunciation_es_manzana.mp3"></audio>
  <button onclick="document.getElementById('audio-manzana').play()">🔊 Listen</button>
</div>

<div class="word-card">
    <div class="word">Plátano</div>
    <div class="translation">Banana </div>
  <audio id="audio-plátano" src="pronunciation_es_plátano.mp3"></audio>
  <button onclick="document.getElementById('audio-plátano').play()">🔊 Listen</button>
</div>

  <div class="word-card">
    <div class="word">Escuela</div>
    <div class="translation">School </div>
  <audio id="audio-escuela" src="pronunciation_es_escuela.mp3"></audio>
  <button onclick="document.getElementById('audio-escuela').play()">🔊 Listen</button>
</div>

  <div class="word-card">
    <div class="word">Parque</div>
    <div class="translation">Park </div>
  <audio id="audio-parque" src="pronunciation_es_parque.mp3"></audio>
  <button onclick="document.getElementById('audio-parque').play()">🔊 Listen</button>
</div>

  <div class="word-card">
    <div class="word">¿Cómo te llamas?</div>
    <div class="translation">What is your name? </div>
    <audio id="audio-¿Cómo te llamas" src="pronunciation_es_¿cómo_te_llamas_.mp3"></audio>
  <button onclick="document.getElementById('audio-¿Cómo te llamas').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">¿De dónde eres?</div>
    <div class="translation">Where are you from? </div>
    <audio id="audio-¿De dónde eres?" src="pronunciation_es_¿de_dónde_eres_.mp3"></audio>
  <button onclick="document.getElementById('audio-¿De dónde eres?').play()">🔊 Listen</button>
  </div>
  <div class="container">
    <div id="quiz">
    <h2>Quiz: What does "Perro" mean?</h2>
    <button class="option-button" onclick="checkAnswer(this, false)">Cat</button>
    <button class="option-button" onclick="checkAnswer(this, true)">Dog</button>
    <button class="option-button" onclick="checkAnswer(this, false)">Banana</button>
  </div>
  </div>
  <script>
    function checkAnswer(button, isCorrect) {
      if (isCorrect) {
        alert("✅ Correct!");
      } else {
        alert("❌ Try again!");
      }
    }
  </script>
  <br>
  <div class="container">
  <p style="margin-top: 40px;">
  If you want to learn some German, <a href="german.html" style="color: #0083b0; text-decoration: none; font-weight: bold;">click here</a>.
  </p>


</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mini Language Learning - German</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    background-image: url('https://constitutionnet.org/sites/default/files/pexels-ingo-109629_1.jpg');
    background-size: cover;
    text-align: center;
    padding: 60px;
    color: white;
    min-height: 100vh;
}
    h1 {
      color: #333;
    }
    .container {
    background: rgba(0, 0, 0, 0.6);
    padding: 30px;
    border-radius: 15px;
    display: inline-block;
    margin-top: 30px;
    }
    .word-card {
    background-color: rgba(255, 255, 255, 0.85);
    color: black;
    border-radius: 10px;
    padding: 15px;
    margin: 10px auto;
    max-width: 350px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }
    .word {
      font-size: 30px;
      font-weight: bold;
    }
    .translation {
    font-size: 25px;
    font-style: italic;
    color: #666;
    margin-top: 10px;
    }
    .audio-button {
      margin-top: 10px;
      background-color: #0083b0;
      border: none;
      color: white;
      padding: 8px 12px;
      border-radius: 8px;
      cursor: pointer;
    }
    .audio-button:hover {
      background-color: #00b4db;
    }
    #quiz {
      margin-top: 40px;
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.2);
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
      color: black;
    }
    .option-button {
      display: block;
      margin: 10px auto;
      padding: 10px 20px;
      background-color: #0083b0;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .option-button:hover {
    background-color: #00b4db;
    }
  </style>
</head>
<body>
  <h1>Learn German Basics</h1>
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/b/ba/Flag_of_Germany.svg/1200px-Flag_of_Germany.svg.png" width="100" >
  <div class="word-card">
    <div class="word">Hallo</div>
    <div class="translation">Hello </div>
    <audio id="audio-hallo" src="pronunciation_de_hallo.mp3"></audio>
  <button onclick="document.getElementById('audio-hallo').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Ja</div>
    <div class="translation">Yes </div>
    <audio id="audio-ja" src="pronunciation_de_ja.mp3"></audio>
  <button onclick="document.getElementById('audio-ja').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Nein</div>
    <div class="translation">No </div>
    <audio id="audio-nein" src="pronunciation_de_nein.mp3"></audio>
  <button onclick="document.getElementById('audio-nein').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Oder</div>
    <div class="translation">Or </div>
    <audio id="audio-oder" src="pronunciation_sl_oder.mp3"></audio>
  <button onclick="document.getElementById('audio-oder').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Und</div>
  <div class="translation">And </div>
  <audio id="audio-und" src="pronunciation_de_und.mp3"></audio>
  <button onclick="document.getElementById('audio-und').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Tschüss</div>
    <div class="translation">Bye </div>
    <audio id="audio-tschüss" src="pronunciation_de_tschüss.mp3"></audio>
  <button onclick="document.getElementById('audio-tschüss').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Danke</div>
    <div class="translation">Thank you </div>
    <audio id="audio-danke" src="pronunciation_de_danke.mp3"></audio>
  <button onclick="document.getElementById('audio-danke').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Bitte</div>
    <div class="translation">Please  </div>
    <audio id="audio-bitte" src="pronunciation_de_bitte.mp3"></audio>
  <button onclick="document.getElementById('audio-bitte').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Wasser</div>
    <div class="translation">Water </div>
    <audio id="audio-wasser" src="pronunciation_de_wasser.mp3"></audio>
  <button onclick="document.getElementById('audio-wasser').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Brot</div>
    <div class="translation">Bread </div>
    <audio id="audio-brot" src="pronunciation_de_brot.mp3"></audio>
  <button onclick="document.getElementById('audio-brot').play()">🔊 Listen</button>
  </div>
  <div class="container">
  <div id="quiz">
    <h2>Quiz: What does "Danke" mean?</h2>
    <button class="option-button" onclick="checkAnswer(this, false)">Please</button>
    <button class="option-button" onclick="checkAnswer(this, true)">Thank you</button>
    <button class="option-button" onclick="checkAnswer(this, false)">Goodbye</button>
  </div>
  </div>
<script>
    function checkAnswer(button, isCorrect) {
      if (isCorrect) {
        alert("✅ Correct!");
      } else {
        alert("❌ Try again!");
      }
    }
  </script>
  <br>
<div class="container">
  <p style="margin-top: 40px;">
  If you want to learn some Italian, <a href="italian.html" style="color: #0083b0; text-decoration: none; font-weight: bold;">click here</a>.
  </p>
  </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mini Language Learning - Italian</title>
  <style>
    body {
    font-family: Arial, sans-serif;
    background-image: url('https://cdn.bannerbuzz.ca/media/catalog/product/n/0/n0_bbitf01_2_us.jpg');
    background-size: cover;
    text-align: center;
    padding: 60px;
    color: white;
    min-height: 100vh;
    }
    h1 {
      color: #333;
    }
    .container {
    background: rgba(0, 0, 0, 0.6);
    padding: 30px;
    border-radius: 15px;
    display: inline-block;
    margin-top: 30px;
    }
    .word-card {
    background-color: rgba(255, 255, 255, 0.85);
    color: black;
    border-radius: 10px;
    padding: 15px;
    margin: 10px auto;
    max-width: 350px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }
    .word {
      font-size: 30px;
      font-weight: bold;
    }
    .translation {
    font-size: 25px;
    font-style: italic;
    color: #666;
    margin-top: 10px;
    }
    .audio-button {
      margin-top: 10px;
      background-color: #0083b0;
      border: none;
      color: white;
      padding: 8px 12px;
      border-radius: 8px;
      cursor: pointer;
    }
    .audio-button:hover {
      background-color: #00b4db;
    }
    #quiz {
      margin-top: 40px;
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.2);
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
      color: black;
    }
    .option-button {
      display: block;
      margin: 10px auto;
      padding: 10px 20px;
      background-color: #0083b0;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .option-button:hover {
    background-color: #00b4db;
    }
  </style>
</head>
<body>
  <h1>Learn Italian Basics</h1>
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/03/Flag_of_Italy.svg/250px-Flag_of_Italy.svg.png"width="100">
  <div class="word-card">
    <div class="word">Ciao</div>
    <div class="translation">Hi / Bye</div>
    <audio id="audio-ciao" src="pronunciation_it_ciao.mp3"></audio>
<button onclick="document.getElementById('audio-ciao').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">Piacere</div>
    <div class="translation">Nice to meet you</div>
    <audio id="audio-piacere" src="pronunciation_it_piacere.mp3"></audio>
<button onclick="document.getElementById('audio-piacere').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">Scusa</div>
    <div class="translation">Excuse me / Sorry</div>
    <audio id="audio-scusa" src="pronunciation_it_scusa.mp3"></audio>
  <button onclick="document.getElementById('audio-scusa').play()">🔊 Listen</button>
  </div>

  <div class="word-card">
    <div class="word">Salve</div>
    <div class="translation">Hello (formal)</div>
    <audio id="audio-Salve" src="pronunciation_it_salve.mp3"></audio>
<button onclick="document.getElementById('audio-Salve').play()">🔊 Listen </button>
    
  </div>

  <div class="word-card">
    <div class="word">Arrivederci</div>
    <div class="translation">Goodbye</div>
    <audio id="audio-arrivederci" src="pronunciation_it_arrivederci (1).mp3"></audio>
<button onclick="document.getElementById('audio-arrivederci').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">Grazie</div>
    <div class="translation">Thank you</div>
    <audio id="audio-grazie" src="pronunciation_it_grazie.mp3"></audio>
<button onclick="document.getElementById('audio-grazie').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">Per favore</div>
    <div class="translation">Please</div>
    <audio id="audio-per favore" src="pronunciation_it_per_favore.mp3"></audio>
<button onclick="document.getElementById('audio-per favore').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">Un</div>
    <div class="translation">A / One</div>
    <audio id="audio-un" src="pronunciation_it_un.mp3"></audio>
<button onclick="document.getElementById('audio-un').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">Latte</div>
    <div class="translation">Milk</div>
    <audio id="audio-latte" src="pronunciation_it_latte.mp3"></audio>
<button onclick="document.getElementById('audio-latte').play()">🔊 Listen </button>
  </div>

<div class="word-card">
    <div class="word">Zucchero</div>
    <div class="translation">Sugar</div>
    <audio id="audio-zucchero" src="pronunciation_it_zucchero.mp3"></audio>
<button onclick="document.getElementById('audio-zucchero').play()">🔊 Listen </button>
</div>
<div class="container">
<div id="quiz">
    <h2>Quiz: What does "Grazie" mean?</h2>
    <button class="option-button" onclick="checkAnswer(this, false)">Sorry</button>
    <button class="option-button" onclick="checkAnswer(this, true)">Thank you</button>
    <button class="option-button" onclick="checkAnswer(this, false)">Please</button>
  </div>
</div>
  <script>
    function checkAnswer(button, isCorrect) {
      if (isCorrect) {
        alert("✅ Correct!");
      } else {
        alert("❌ Try again!");
      }
    }
  </script>
  <br>
  <div class="container">
<p style="margin-top: 40px;">
    If you want to learn some Japanese, <a href="japanese.html" style="color: #0083b0; font-weight: bold;">click here</a>.
</p>
</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mini Language Learning - Japanese</title>
  <style>
    body {
    font-family: Arial, sans-serif;
    background-image: url('https://www.state.gov/wp-content/uploads/2019/04/Japan-2107x1406.jpg');
    background-size: cover;
    text-align: center;
    padding: 60px;
    color: white;
    min-height: 100vh;
    }
    h1 {
      color: #222;
    }
    .container {
    background: rgba(0, 0, 0, 0.6);
    padding: 30px;
    border-radius: 15px;
    display: inline-block;
    margin-top: 30px;
    }
    .word-card {
    background-color: rgba(255, 255, 255, 0.85);
    color: black;
    border-radius: 10px;
    padding: 15px;
    margin: 10px auto;
    max-width: 350px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }
    .word {
      font-size: 30px;
      font-weight: bold;
    }
    .translation {
      font-size: 25px;
    font-style: italic;
    color: #666;
    margin-top: 10px;
    }
    .audio-button {
      margin-top: 10px;
      background-color: #0083b0;
      border: none;
      color: white;
      padding: 8px 12px;
      border-radius: 8px;
      cursor: pointer;
    }
    .audio-button:hover {
      background-color: #00b4db;
    }
    #quiz {
      margin-top: 40px;
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.2);
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
      color: black;
    }
    .option-button {
      display: block;
      margin: 10px auto;
      padding: 10px 20px;
      background-color: #0083b0;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .option-button:hover {
    background-color: #00b4db;
    }
    footer {
      margin-top: 40px;
      text-align: center;
      font-size: 20px;
      color: hwb(0 6% 94%);
    }
  </style>
</head>
<body>
  <h1> Learn Japanese Basics</h1>
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/9/9e/Flag_of_Japan.svg/330px-Flag_of_Japan.svg.png"width="100">
  <div class="word-card">
    <div class="word"> と  </div>
    <div class="translation">and</div>
    <audio id="audio-と " src="pronunciation_ja_と.mp3"></audio>
<button onclick="document.getElementById('audio-と ').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">みず</div>
    <div class="translation">water</div>
    <audio id="audio-みず" src="pronunciation_ja_みず.mp3"></audio>
<button onclick="document.getElementById('audio-みず').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">ごはん</div>
    <div class="translation">rice / meal</div>
    <audio id="audio-ごはん" src="pronunciation_ja_ごはん.mp3"></audio>
<button onclick="document.getElementById('audio-ごはん').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">ください</div>
    <div class="translation">please (give me)</div>
    <audio id="audio-ください" src="pronunciation_ja_ください.mp3"></audio>
<button onclick="document.getElementById('audio-ください').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">おちゃ</div>
    <div class="translation">tea (green tea)</div>
    <audio id="audio-おちゃ" src="pronunciation_ja_ocha.mp3"></audio>
<button onclick="document.getElementById('audio-おちゃ').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">どうぞよろしく</div>
    <div class="translation">Nice to meet you</div>
    <audio id="audio-どうぞよろしく" src="pronunciation_ja_どうぞよろしく.mp3"></audio>
<button onclick="document.getElementById('audio-どうぞよろしく').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">またあした</div>
    <div class="translation">See you tomorrow</div>
    <audio id="audio-またあした" src="pronunciation_ja_またあした.mp3"></audio>
<button onclick="document.getElementById('audio-またあした').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">学生</div>
    <div class="translation">student</div>
    <audio id="audio-学生" src="pronunciation_ja_学生.mp3"></audio>
<button onclick="document.getElementById('audio-学生').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">ひと</div>
    <div class="translation">person</div>
    <audio id="audio-ひと" src="pronunciation_ja_ひと.mp3"></audio>
<button onclick="document.getElementById('audio-ひと').play()">🔊 Listen </button>
  </div>

  <div class="word-card">
    <div class="word">おいしい</div>
    <div class="translation">delicious</div>
    <audio id="audio-おいしい" src="pronunciation_ja_おいしい.mp3"></audio>
<button onclick="document.getElementById('audio-おいしい').play()">🔊 Listen </button>
  </div>
  <div class="container">
  <div id="quiz">
  <h2>Quiz: What does 「みず」 mean?</h2>
  <button class="option-button" onclick="checkAnswer(this, false)">Tea</button>
  <button class="option-button" onclick="checkAnswer(this, true)">Water</button>
  <button class="option-button" onclick="checkAnswer(this, false)">Rice</button>
</div>
</div>
<script>
  function checkAnswer(button, isCorrect) {
    if (isCorrect) {
      alert("✅ Correct!");
    } else {
      alert("❌ Try again!");
    }
  }
</script>

  <strong></b><footer>Thank you for visiting our site!</footer></strong>
</body>
</html>
