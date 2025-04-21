- 👋 Hi, I’m @gds1999
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MG Style</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fffaf5;
      color: #333;
    }

    header {
      background-color: #d32f2f; /* Vermelho intenso */
      color: #fff;
      padding: 40px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    header h1 {
      font-size: 3em;
      letter-spacing: 2px;
      text-transform: uppercase;
      font-weight: bold;
    }

    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    nav {
      background-color: #ffcb05; /* Amarelo */
      padding: 12px 0;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    nav a {
      color: #d32f2f; /* Vermelho */
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      text-transform: uppercase;
    }

    nav a:hover {
      color: #fff;
      background-color: #d32f2f;
      border-radius: 4px;
      padding: 5px 10px;
    }

    .produtos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 50px 20px;
      gap: 40px;
    }

    .produto {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
      width: 220px;
      padding: 20px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .produto:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    }

    .produto img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .produto h3 {
      margin-top: 10px;
      font-size: 1.2em;
      color: #d32f2f; /* Vermelho */
      font-weight: bold;
    }

    .produto p {
      margin: 5px 0;
      color: #888;
    }

    .produto button {
      background-color: #ffcb05; /* Amarelo */
      border: none;
      padding: 12px 25px;
      margin-top: 15px;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1.1em;
      transition: background-color 0.3s ease;
    }

    .produto button:hover {
      background-color: #d32f2f; /* Vermelho */
      color: white;
    }

    footer {
      background-color: #d32f2f; /* Vermelho */
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      font-size: 1em;
    }

  </style>
</head>
<body>

  <header>
    <h1>MG Style</h1>
    <p>Moda com atitude. Estilo que te representa.</p>
  </header>

  <nav>
    <a href="#">Início</a>
    <a href="#">Masculino</a>
    <a href="#">Feminino</a>
    <a href="#">Contato</a>
  </nav>

  <section class="produtos">
    <div class="produto">
      <img src="https://i.pinimg.com/736x/47/94/0c/47940c852c7f3d7f576e7393b80bc8da.jpg" alt="Camisa Estilosa">
      <h3>Camisa Estilosa</h3>
      <p>R$ 89,90</p>
      <button>Comprar</button>
    </div>

    <div class="produto">
      <img src="https://i.pinimg.com/736x/96/a8/21/96a82174c128f29b74a61bc7686117c1.jpg" alt="Jaqueta Casual">
      <h3>Jaqueta Casual</h3>
      <p>R$ 149,90</p>
      <button>Comprar</button>
    </div>

    <div class="produto">
      <img src="https://i.pinimg.com/736x/76/9a/85/769a8534a21a778576b05361e38547eb.jpg" alt="Vestido Floral">
      <h3>Vestido Floral</h3>
      <p>R$ 129,90</p>
      <button>Comprar</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 MG Style. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
<!---
gds1999/gds1999 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
