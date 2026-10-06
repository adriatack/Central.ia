<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Central de IAs</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0b0b0f;
      color: white;
      min-height: 100vh;
      padding: 20px;
    }

    .container {
      max-width: 700px;
      margin: auto;
    }

    h1 {
      text-align: center;
      font-size: 32px;
      margin-top: 25px;
    }

    .subtitle {
      text-align: center;
      color: #999;
      margin: 10px 0 30px;
    }

    .ai-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
    }

    .ai {
      background: #17171d;
      border: 1px solid #292932;
      border-radius: 16px;
      padding: 20px;
      text-align: center;
      cursor: pointer;
      transition: 0.2s;
    }

    .ai:hover {
      transform: translateY(-3px);
      border-color: #555;
    }

    .icon {
      font-size: 32px;
      margin-bottom: 8px;
    }

    .name {
      font-weight: bold;
      font-size: 18px;
    }

    .status {
      color: #777;
      font-size: 12px;
      margin-top: 5px;
    }

    .chat {
      margin-top: 25px;
      background: #17171d;
      border: 1px solid #292932;
      border-radius: 16px;
      padding: 15px;
    }

    textarea {
      width: 100%;
      height: 100px;
      resize: none;
      background: #0d0d11;
      color: white;
      border: 1px solid #30303a;
      border-radius: 12px;
      padding: 12px;
      outline: none;
    }

    button {
      width: 100%;
      margin-top: 10px;
      padding: 14px;
      border: none;
      border-radius: 12px;
      background: white;
      color: black;
      font-weight: bold;
      font-size: 16px;
    }

    .notice {
      text-align: center;
      color: #666;
      font-size: 12px;
      margin-top: 20px;
    }
  </style>
</head>

<body>

  <div class="container">

    <h1>🤖 Central de IAs</h1>

    <p class="subtitle">
      5 inteligências. Uma central.
    </p>

    <div class="ai-grid">

      <div class="ai">
        <div class="icon">🟢</div>
        <div class="name">ChatGPT</div>
        <div class="status">Conexão pendente</div>
      </div>

      <div class="ai">
        <div class="icon">🟠</div>
        <div class="name">Claude</div>
        <div class="status">Conexão pendente</div>
      </div>

      <div class="ai">
        <div class="icon">🔵</div>
        <div class="name">Gemini</div>
        <div class="status">Conexão pendente</div>
      </div>

      <div class="ai">
        <div class="icon">⚫</div>
        <div class="name">Grok</div>
        <div class="status">Conexão pendente</div>
      </div>

      <div class="ai">
        <div class="icon">🟣</div>
        <div class="name">Meta AI</div>
        <div class="status">Conexão pendente</div>
      </div>

    </div>

    <div class="chat">

      <textarea
        placeholder="Digite uma pergunta para as IAs..."
      ></textarea>

      <button>
        🚀 Enviar para as IAs
      </button>

    </div>

    <p class="notice">
      Central de IAs • Projeto experimental
    </p>

  </div>

</body>
</html>
