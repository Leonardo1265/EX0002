<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Pesquisa de Satisfação</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      padding: 30px;
    }
    .card {
      background: white;
      border-radius: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      padding: 20px;
      width: 300px;
      margin: 10px;
      text-align: center;
    }
    .emojis {
      font-size: 24px;
      display: flex;
      justify-content: space-between;
      margin: 20px 0;
    }
    .range-labels {
      display: flex;
      justify-content: space-between;
      font-size: 12px;
      color: #666;
    }
    .input-box {
      width: 100%;
      height: 100px;
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 10px;
      resize: none;
    }
    .footer-text {
      margin-top: 20px;
      font-size: 12px;
      color: #777;
    }
    .logo {
      margin: 10px 0;
    }
    .audio-icon {
      font-size: 12px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <!-- Card 1 -->
  <div class="card">
    <h3>Olá, tudo bem ?</h3>
    <p>Queremos saber sua opinião<br>
        <div></div>
    Sobre sua última experiência em loja.</p>
    <img src="hering.jpg"  width="50"></label>

    <div class="emojis">
        <img src="muito_ruim-removebg-preview.png"  width="50"></label>
        <img src="ruim-removebg-preview.png"  width="50"></label>
        <img src="mais_ou_menor-removebg-preview.png"  width="50"></label>
        <img src="bom-removebg-preview.png"  width="50"></label>
        <img src="muito_bom-removebg-preview.png"  width="50"></label>
    </div>

    <div class="range-labels">
      <span>Não Recomendaria</span>
      <span>Recomendaria</span>
    </div>

    <img src="áudio.jpg"  width="15"></label> Audio</div>
  </div>

  <!-- Card 2 -->
  <div class="card">
    <img src="hering.jpg"  width="50"></label>
    <p>Deixe um comentário sobre o atendimento</p>
    <textarea class="input-box" maxlength="500" placeholder="R: 500 caracteres"></textarea>
    <img src="homem.jpg"  width="50"></label>
    <div class="footer-text">Hering agradece a preferência</div>
  </div>

</body>
</html>
