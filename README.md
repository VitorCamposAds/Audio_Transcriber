<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Audio Transcriber</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
    }
    h1 {
      color: #333;
      border-bottom: 1px solid #ccc;
      padding-bottom: 5px;
    }
    p {
      margin-top: 10px;
    }
    .badge {
      display: inline-block;
      padding: 5px 10px;
      font-size: 0.8em;
      font-weight: bold;
      color: #fff;
      background-color: #007bff;
      border-radius: 3px;
      text-transform: uppercase;
    }
    .code {
      font-family: Consolas, monospace;
      background-color: #f8f9fa;
      padding: 5px;
      border-radius: 5px;
      margin-top: 10px;
      overflow-x: auto;
    }
    .section {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1><img src="https://example.com/favicon.ico" style="vertical-align: middle;"> Audio Transcriber</h1>
  
  <p>Este é um aplicativo de desktop construído com PyQt5 para extrair áudio de vídeos e transcrevê-los para texto, que é então salvo em um arquivo DOCX.</p>
  
  <div class="section">
    <h2><img src="https://example.com/icons/requirements.png" style="vertical-align: middle;"> Requisitos</h2>
    <ul>
      <li><strong>Python 3.6+</strong></li>
      <li><strong>PyQt5</strong>: Para a interface gráfica.</li>
      <li><strong>FFmpeg</strong>: Para manipulação de áudio e vídeo.</li>
      <li><strong>Whisper</strong>: Para transcrição de áudio para texto.</li>
    </ul>
  </div>
  
  <div class="section">
    <h2><img src="https://example.com/icons/installation.png" style="vertical-align: middle;"> Instalação e Uso</h2>
    <ol>
      <li><strong>Clonar o Repositório</strong></li>
      <div class="code">git clone https://github.com/seu_usuario/audio-transcriber.git<br>cd audio-transcriber</div>
      
      <li><strong>Instalar Dependências</strong></li>
      <div class="code">pip install -r requirements.txt</div>
      
      <li><strong>Executar o Aplicativo</strong></li>
      <div class="code">python main.py</div>
    </ol>
  </div>
  
  <div class="section">
    <h2><img src="https://example.com/icons/usage.png" style="vertical-align: middle;"> Como Usar</h2>
    <ol>
      <li><strong>Selecionar Vídeo</strong>: Clique em "Selecionar Vídeo e Extrair Áudio" para escolher um arquivo de vídeo.</li>
      <li><strong>Processamento</strong>: Aguarde até que o áudio seja extraído e transcrevido.</li>
      <li><strong>Resultados</strong>: Após a transcrição, um arquivo "Transcrição.docx" será salvo no desktop do usuário.</li>
    </ol>
  </div>
  
  <div class="section">
    <h2><img src="https://example.com/icons/contributing.png" style="vertical-align: middle;"> Contribuição</h2>
    <ul>
      <li>Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.</li>
      <li>Para grandes alterações, por favor, abra uma issue primeiro para discutir o que você gostaria de mudar.</li>
    </ul>
  </div>
  
  <div class="section">
    <h2><img src="https://example.com/icons/license.png" style="vertical-align: middle;"> Licença</h2>
    <p>Este projeto está licenciado sob a Licença MIT - veja o arquivo <strong>LICENSE</strong> para mais detalhes.</p>
  </div>
</body>
</html>
