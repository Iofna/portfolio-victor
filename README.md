<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio - Victor Iofna Caba</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #ffecd2, #fcb69f);
      color: #333;
    }

    header {
      background-color: #ff5722;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #fff3e0;
      display: flex;
      justify-content: center;
      padding: 15px 0;
      gap: 30px;
    }

    nav a {
      text-decoration: none;
      color: #ff5722;
      font-weight: bold;
      font-size: 18px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 40px 20px;
      text-align: center;
    }

    .botao-contato {
      display: inline-block;
      margin: 15px;
      padding: 15px 25px;
      background-color: #ff5722;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-size: 18px;
      font-weight: bold;
      transition: 0.3s;
    }

    .botao-contato i {
      margin-right: 10px;
    }

    .botao-contato:hover {
      background-color: #e64a19;
    }

    footer {
      background-color: #ff5722;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Victor Iofna Caba</h1>
    <p>Engenharia de Computação | Design Gráfico | Automação Industrial</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#projetos">Projetos</a>
    <a href="#contato">Contato</a>
  </nav>

  <main>
    <section id="sobre">
      <h2>Sobre Mim</h2>
      <p>Sou estudante da UFSC e IFSC com foco em design gráfico, projetos técnicos e programação.</p>
    </section>

    <section id="projetos" style="margin-top: 60px;">
      <h2>Projetos em Destaque</h2>
      <p>Artes visuais, identidades visuais e projetos técnicos de destaque.</p>
    </section>

    <section id="contato" style="margin-top: 60px;">
      <h2>Entre em Contato</h2>
      <div class="contato-container">
        <a class="botao-contato" href="https://wa.me/5548999397911" target="_blank">
          <i class="fab fa-whatsapp"></i> WhatsApp
        </a>
        <a class="botao-contato" href="mailto:victor.caba@grad.ufsc.br">
          <i class="fas fa-envelope"></i> E-mail
        </a>
        <a class="botao-contato" href="https://www.instagram.com/victor_iofna_caba" target="_blank">
          <i class="fab fa-instagram"></i> Instagram
        </a>
        <a class="botao-contato" href="https://www.linkedin.com/in/victor-iofna-caba-a06a832a2" target="_blank">
          <i class="fab fa-linkedin"></i> LinkedIn
        </a>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Victor Iofna Caba. Todos os direitos reservados.</p>
  </footer>
</body>
</html>

