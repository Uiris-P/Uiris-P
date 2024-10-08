<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Culinária Prática</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Receitas Culinárias</h1>
    </header>
    <main>
        <section>
            <h2>Formulário de Contato</h2>
            <form action="https://formsubmit.co/seuemail@dominio.com" method="POST">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Receitas Culinárias. Todos os direitos reservados.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
