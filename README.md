# index.html
Meu primeiro projeto no GitHub
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu Primeiro Site</title>
  <style>
    body {
      background-color: #f0f4f8;
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
    }
    h1 {
      color: #2c3e50;
    }
    p {
      color: #555;
      font-size: 18px;
    }
    button {
      background-color: #3498db;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #2980b9;
    }
  </style>
</head>
<body>

  <h1>Olá, eu sou [Agta] 👋</h1>
  <p>Este é meu primeiro projeto no GitHub 🚀</p>

  <button onclick="mostrarMensagem()">Clique aqui</button>

  <p id="mensagem"></p>

  <script>
    function mostrarMensagem() {
      document.getElementById("mensagem").innerText = "Você clicou no botão! 🎉";
    }
  </script>

</body>
</html>
