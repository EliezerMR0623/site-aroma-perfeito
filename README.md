# site-aroma-perfeito
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cafeteria Aroma Perfeito</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f4f0;
      color: #3e2f1c;
    }
    header {
      background-color: #6f4e37;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .cardapio, .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .item {
      background-color: #fff;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #3e2f1c;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    img {
      width: 100%;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Cafeteria Aroma Perfeito</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#cardapio">Cardápio</a>
      <a href="#galeria">Galeria</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section id="sobre">
    <h2>☕ Sobre Nós</h2>
    <p>Bem-vindo à Cafeteria Aroma Perfeito! Um espaço acolhedor no coração da cidade para você relaxar e apreciar cafés especiais, doces artesanais e lanches deliciosos.</p>
  </section>

  <section id="cardapio">
    <h2>📜 Nosso Cardápio</h2>
    <div class="cardapio">
      <div class="item">
        <h3>Espresso</h3>
        <p>Café puro, intenso e cheio de sabor.</p>
      </div>
      <div class="item">
        <h3>Cappuccino</h3>
        <p>Feito com leite vaporizado e toque de canela.</p>
      </div>
      <div class="item">
        <h3>Pão de Queijo</h3>
        <p>Quentinho, crocante por fora e macio por dentro.</p>
      </div>
      <div class="item">
        <h3>Bolo de Cenoura</h3>
        <p>Com cobertura de chocolate, perfeito para o café da tarde.</p>
      </div>
    </div>
  </section>

  <section id="galeria">
    <h2>📸 Galeria</h2>
    <div class="galeria">
      <img src="https://source.unsplash.com/400x300/?coffee" alt="Xícara de café" />
      <img src="https://source.unsplash.com/400x300/?bakery" alt="Doces artesanais" />
      <img src="https://source.unsplash.com/400x300/?cafe" alt="Interior da cafeteria" />
    </div>
  </section>

  <section id="contato">
    <h2>📞 Contato</h2>
    <p>📍 Rua das Flores, 123 - Centro, Angélica - MS</p>
    <p>📱 WhatsApp: (67) 9 9999-9999</p>
    <p>📧 Email: contato@aromaperfeito.com.br</p>
  </section>

  <footer>
    <p>🌐 Siga-nos nas redes sociais: @cafearomaperfeito</p>
    <p>&copy; 2025 Cafeteria Aroma Perfeito. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
