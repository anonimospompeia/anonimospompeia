<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jogo do Bonito ou Feio - Anônimos Pompéia</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Anônimos Pompéia - Jogo do Bonito ou Feio</h1>
  </header>
  <main>
    <p>Vote de forma anônima e descubra o resultado final!</p>
    <div class="votacao">
      <button onclick="votar('bonito')">Bonito</button>
      <button onclick="votar('feio')">Feio</button>
    </div>
    <p id="resultado"></p>
  </main>
  <footer>
    <p>&copy; 2025 Anônimos Pompéia</p>
  </footer>
  <script src="script.js"></script>
</body>
</html>
