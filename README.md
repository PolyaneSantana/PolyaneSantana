<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stranger Things - Mistérios de Hawkins</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap" rel="stylesheet">
  <style>
    /* Estilos Globais */
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-image: url('https://wallpapercave.com/wp/wp1856239.jpg');
      background-size: cover;
      background-attachment: fixed;
      background-repeat: no-repeat;
      color: white;
    }

    .overlay {
      background: rgba(0, 0, 0, 0.7);
      padding: 20px;
      min-height: 100vh;
    }

    /* Cabeçalho */
    header {
      text-align: center;
      padding: 50px;
      color: #FFD700;
      text-shadow: 2px 2px #000;
    }

    header h1 {
      font-size: 4em;
      margin: 0;
    }

    header p {
      font-size: 1.5em;
    }

    /* Seção Principal */
    main {
      max-width: 1200px;
      margin: 40px auto;
      padding: 20px;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.7);
    }

    .hero-image {
      width: 100%;
      max-width: 1000px;
      border-radius: 10px;
      margin: 20px auto;
      display: block;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    /* Seção de Personagens */
    .personagens {
      margin-top: 50px;
    }

    .personagem {
      display: inline-block;
      width: 22%;
      margin: 10px;
      text-align: center;
      background: rgba(0, 0, 0, 0.7);
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    .personagem-img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }

    .personagem h3 {
      margin: 10px 0;
      font-size: 1.5em;
      color: #FFD700;
    }

    .personagem p {
      font-size: 1em;
      line-height: 1.5;
    }

    /* História Completa */
    .historia {
      margin-top: 50px;
      font-size: 1.2em;
      line-height: 1.8;
    }

    .historia h2 {
      font-size: 2.5em;
      text-align: center;
      color: #FFD700;
      margin-bottom: 20px;
      text-shadow: 1px 1px #000;
    }

    .historia p {
      font-size: 1.2em;
      line-height: 1.8;
      color: #fff;
    }

    .historia img {
      width: 100%;
      max-width: 1000px;
      display: block;
      margin: 20px auto;
      border-radius: 10px;
    }

    /* Botão de Chamada para Ação */
    .cta-button {
      display: block;
      text-align: center;
      margin: 40px auto;
      padding: 15px 30px;
      font-size: 1.5em;
      color: #000;
      background: #FFD700;
      border: none;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.3s ease, transform 0.3s ease;
    }

    .cta-button:hover {
      background: #ffc107;
      transform: translateY(-5px);
    }

    /* Rodapé */
    footer {
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      background: rgba(0, 0, 0, 0.8);
      color: #FFD700;
    }

    footer a {
      color: #fff;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <!-- Overlay para escurecer o fundo -->
  <div class="overlay">
    <!-- Cabeçalho -->
    <header>
      <h1>Stranger Things - Mistérios de Hawkins</h1>
      <p>A série que mistura mistério, suspense e o sobrenatural. Aventure-se em Hawkins!</p>
    </header>

    <!-- Conteúdo Principal -->
    <main>
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Stranger_Things_logo.png" alt="Stranger Things Logo" class="hero-image">
      
      <h2>Personagens Principais</h2>
      <div class="personagens">
        <div class="personagem">
          <img src="https://upload.wikimedia.org/wikipedia/en/thumb/5/52/Eleven_%28Stranger_Things%29.jpg/220px-Eleven_%28Stranger_Things%29.jpg" alt="Eleven" class="personagem-img">
          <h3>Eleven</h3>
          <p>Uma jovem com habilidades psíquicas incríveis que luta contra forças sobrenaturais em Hawkins.</p>
        </div>
        <div class="personagem">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSLkOM8UVYZ9GVjH7UlYYdmHmMFY7C0MVcXgg&s" alt="Mike Wheeler" class="personagem-img">
          <h3>Mike Wheeler</h3>
          <p>Amigo leal de Eleven e um dos principais heróis na luta contra as forças do Upside Down.</p>
        </div>
        <div class="personagem">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6l_BqJDXQOXc1NmEXAtSUsqdmKNiYz4X7qnOA3ScKI2C1r3cUIdtEOaiaVFszrb_F5Ko&usqp=CAU" alt="Dustin Henderson" class="personagem-img">
          <h3>Dustin Henderson</h3>
          <p>Engraçado e inteligente, Dustin é um dos melhores amigos de Mike e faz parte do grupo central da série.</p>
        </div>
        <div class="personagem">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT57SobOoBIAFUpWK4MlKYq7desbDhxqsOu0A&s" alt="Lucas Sinclair" class="personagem-img">
          <h3>Lucas Sinclair</h3>
          <p>Outro dos amigos de Mike, Lucas é cético e sempre pronto para enfrentar qualquer perigo.</p>
        </div>
      </div>

      <h2>História Completa de Stranger Things</h2>
      <div class="historia">
        <p>Stranger Things se passa na década de 1980 na pequena cidade de Hawkins, Indiana. A história começa com o desaparecimento misterioso de um garoto chamado Will Byers, que vai desencadear uma série de eventos sobrenaturais. Enquanto seus amigos tentam encontrá-lo, eles descobrem um mundo paralelo chamado "Upside Down" e uma garota com poderes psíquicos chamada Eleven, que se torna uma aliada importante em sua busca.</p>

        <p>A história se desenrola ao longo de várias temporadas, onde os personagens enfrentam criaturas estranhas, ameaças do governo e os segredos do Upside Down. A trama explora não apenas os aspectos sobrenaturais, mas também o vínculo entre os amigos, o crescimento pessoal e os mistérios que envolvem a cidade de Hawkins.</p>
        
        <img src="[https://blogs.correiobraziliense.com.br/proximocapitulo/wp-content/uploads/sites/27/2017/02/stranger0-550x298.jpgs](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIwvyGEuCB_TpUkjXrkM3xbDnLDmNN56-hQA&s)" alt="Cena Stranger Things">

        <p>A cada temporada, os perigos aumentam, e a amizade entre os personagens é testada enquanto tentam salvar Hawkins de uma ameaça que parece nunca acabar.</p>
      </div>

      <a href="https://www.netflix.com/br/title/80057281" class="cta-button" target="_blank">Assista Agora na Netflix</a>
    </main>

    <!-- Rodapé -->
    <footer>
      <p>&copy; 2024 Stranger Things Fan Page</p>
      <p>Para mais informações,<p>Para mais informações, visite a <a href="https://www.netflix.com/br/title/80057281" target="_blank">Netflix</a>.</p>
    </footer>
  </div>
</body>
</html>
