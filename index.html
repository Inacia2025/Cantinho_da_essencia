
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cantinho da Essência</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdf7f0;
      color: #3e2f2f;
    }
    header {
      background: linear-gradient(to right, #7e57c2, #d1a954);
      padding: 20px;
      text-align: center;
      color: white;
    }
    h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      background-color: #f3e5f5;
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #5e35b1;
      font-weight: bold;
    }
    .hero {
      background-image: url('https://images.unsplash.com/photo-1511988617509-a57c8a288659');
      background-size: cover;
      background-position: center;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2rem;
      font-weight: bold;
      text-shadow: 2px 2px 5px #000;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 30px;
    }
    .produto {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    .produto img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }
    .produto h3 {
      margin: 10px 0 5px;
    }
    .produto p {
      margin: 0 0 10px;
      color: #8d6e63;
    }
    .produto button {
      padding: 10px;
      background-color: #7e57c2;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .carrinho {
      padding: 20px;
      background-color: #f3e5f5;
    }
    .checkout {
      background-color: #fff3e0;
      padding: 20px;
      margin: 20px;
      border-radius: 10px;
    }
    input, textarea {
      width: 100%;
      padding: 8px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button.finalizar {
      background-color: #d1a954;
      color: white;
      font-weight: bold;
      margin-top: 10px;
    }
    footer {
      background-color: #7e57c2;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Cantinho da Essência</h1>
    <p>Onde a delicadeza encontra o rústico</p>
  </header>

  <nav>
    <a href="#">Início</a>
    <a href="#">Produtos</a>
    <a href="#carrinho">Carrinho</a>
    <a href="#">Contato</a>
  </nav>

  <div class="hero">
    Bem-vinda ao seu cantinho especial!
  </div>

  <section class="produtos">
    <div class="produto">
      <img src="https://images.unsplash.com/photo-1585386959984-a4155224e1c1" alt="Produto 1">
      <h3>Sabonete Artesanal</h3>
      <p>R$ 15,00</p>
      <button onclick="adicionarCarrinho('Sabonete Artesanal', 15)">Adicionar ao carrinho</button>
    </div>
    <div class="produto">
      <img src="https://images.unsplash.com/photo-1610465293449-2022c2849f98" alt="Produto 2">
      <h3>Velas Aromáticas</h3>
      <p>R$ 22,00</p>
      <button onclick="adicionarCarrinho('Velas Aromáticas', 22)">Adicionar ao carrinho</button>
    </div>
    <div class="produto">
      <img src="https://images.unsplash.com/photo-1587300003388-59208cc962cb" alt="Produto 3">
      <h3>Óleo Essencial</h3>
      <p>R$ 30,00</p>
      <button onclick="adicionarCarrinho('Óleo Essencial', 30)">Adicionar ao carrinho</button>
    </div>
  </section>

  <section id="carrinho" class="carrinho">
    <h2>Carrinho de Compras</h2>
    <ul id="lista-carrinho"></ul>
    <p><strong>Total: R$ <span id="total">0.00</span></strong></p>
    <button class="finalizar" onclick="mostrarCheckout()">Finalizar Pedido</button>
  </section>

  <section id="checkout" class="checkout" style="display:none;">
    <h2>Pagamento via Pix (Nubank)</h2>
    <p>Chave Pix: <strong>cantinho@nubank.com.br</strong></p>
    <p>Valor total: R$ <span id="total-pix">0.00</span></p>
    <p>Após o pagamento, preencha seus dados abaixo:</p>
    <input type="text" placeholder="Seu nome completo">
    <input type="text" placeholder="Endereço completo para entrega">
    <input type="text" placeholder="WhatsApp para contato">
    <label>Comprovante de pagamento:</label>
    <input type="file">
    <button class="finalizar">Confirmar Pedido</button>
  </section>

  <footer>
    &copy; 2025 Cantinho da Essência - Todos os direitos reservados
  </footer>

  <script>
    let carrinho = [];

    function adicionarCarrinho(produto, preco) {
      carrinho.push({ produto, preco });
      atualizarCarrinho();
    }

    function atualizarCarrinho() {
      const lista = document.getElementById("lista-carrinho");
      const totalSpan = document.getElementById("total");
      lista.innerHTML = "";
      let total = 0;

      carrinho.forEach(item => {
        const li = document.createElement("li");
        li.textContent = `${item.produto} - R$ ${item.preco.toFixed(2)}`;
        lista.appendChild(li);
        total += item.preco;
      });

      totalSpan.textContent = total.toFixed(2);
    }

    function mostrarCheckout() {
      document.getElementById("checkout").style.display = "block";
      document.getElementById("total-pix").textContent = document.getElementById("total").textContent;
    }
  </script>
</body>
</html>
