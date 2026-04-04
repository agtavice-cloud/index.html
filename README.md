# index.html
Meu primeiro projeto no GitHub
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu Portfólio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background: #f0f4f8;
      color: #333;
      text-align: center;
      padding: 50px;
    }

    .avatar {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid #3498db;
      margin-bottom: 20px;
    }

    h1 {
      color: #2c3e50;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      color: #555;
      max-width: 600px;
      margin: 10px auto 20px auto;
    }

    .button {
      background-color: #3498db;
      color: white;
      border: none;
      padding: 12px 25px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
      margin: 5px;
      transition: 0.3s;
    }

    .button:hover {
      background-color: #2980b9;
    }

    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #888;
    }

    a {
      color: #3498db;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <!-- Foto de perfil -->
  <img src="https://via.placeholder.com/150" alt="Minha Foto" class="avatar">

  <!-- Apresentação -->
  <h1>Olá, eu sou [Agta] 👋</h1>
  <p>Este é meu primeiro projeto no GitHub. Aqui você pode conhecer um pouco sobre mim e meus contatos.</p>

  <!-- Botões de ação -->
  <button class="button" onclick="mostrarMensagem()">Clique aqui</button>
  <p id="mensagem"></p>

  <button class="button" onclick="window.location.href='https://www.linkedin.com/'">Meu www.linkedin.com/in/agta-silva>
  <button class="button" onclick="window.location.href='https://github.com/'">Meu GitHub<agtavice-cloud/index.html>

  <footer>
    &copy; 2026 [SEU NOME]. Todos os direitos reservados.
  </footer>

  <script>
    function mostrarMensagem() {
      document.getElementById("mensagem").innerText = "Você clicou no botão! 🎉";
    }
  </script>

</body>
</html>
