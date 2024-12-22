[Uploading futurewell_style
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #1a1a1a;
    color: #ffffff;
}
.header {
    background: #111111;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.header .logo {
    font-size: 24px;
    font-weight: bold;
    color: #00d1ff;
}
nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
}
nav ul li a {
    color: #ffffff;
    text-decoration: none;
}
.section {
    padding: 40px 20px;
    text-align: center;
    border-bottom: 1px solid #333;
}
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px;
}
.card {
    background: #222;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
}
form {
    display: flex;
    flex-direction: column;
    gap: 10px;
    max-width: 400px;
    margin: 0 auto;
}
form input, form textarea, form button {
    padding: 10px;
    border: none;
    border-radius: 5px;
}
form button {
    background-color: #00d1ff;
    color: #fff;
    cursor: pointer;
}
footer {
    text-align: center;
    padding: 10px 20px;
    background: #111111;
}
.css…]()

[Uploa
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FutureWell - Saúde e Bem-estar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <div class="logo">FutureWell</div>
        <nav>
            <ul>
                <li><a href="#produtos">Produtos</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#pagamentos">Pagamentos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="produtos" class="section">
            <h1>Produtos</h1>
            <p>Explore nossa linha futurística de produtos para saúde e bem-estar.</p>
            <div class="grid">
                <div class="card">Produto 1</div>
                <div class="card">Produto 2</div>
                <div class="card">Produto 3</div>
            </div>
        </section>
        <section id="servicos" class="section">
            <h1>Serviços</h1>
            <p>Descubra nossos serviços personalizados para sua saúde e bem-estar.</p>
            <div class="grid">
                <div class="card">Serviço 1</div>
                <div class="card">Serviço 2</div>
                <div class="card">Serviço 3</div>
            </div>
        </section>
        <section id="pagamentos" class="section">
            <h1>Formas de Pagamento</h1>
            <p>Escolha entre Pix, cartões de crédito ou carteiras digitais para facilitar suas compras.</p>
        </section>
        <section id="contato" class="section">
            <h1>Contato</h1>
            <p>Entre em contato conosco para mais informações ou suporte.</p>
            <form>
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 FutureWell. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
ding futurewell_site.html…]()
