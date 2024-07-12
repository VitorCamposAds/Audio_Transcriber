# Audio Transcriber

![Icon](https://example.com/favicon.png)

Este é um aplicativo de desktop construído com PyQt5 para extrair áudio de vídeos e transcrevê-los para texto, que é então salvo em um arquivo DOCX.

## Funcionalidades

- **Extração de Áudio**: Utiliza FFmpeg para extrair o áudio de arquivos de vídeo selecionados.
- **Transcrição para Texto**: Transcreve o áudio extraído para texto utilizando o modelo de reconhecimento de fala Whisper.
- **Exportação para DOCX**: Salva a transcrição em um arquivo DOCX no desktop do usuário.

## Requisitos

- **Python 3.6+**
- **PyQt5**: Para a interface gráfica.
- **FFmpeg**: Para manipulação de áudio e vídeo.
- **Whisper**: Para transcrição de áudio para texto.

## Como Usar

1. **Selecionar Vídeo**: Clique em "Selecionar Vídeo e Extrair Áudio" para escolher um arquivo de vídeo.
2. **Processamento**: Aguarde até que o áudio seja extraído e transcrevido.
3. **Resultados**: Após a transcrição, um arquivo "Transcrição.docx" será salvo no desktop do usuário.

## Contribuição

- Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
- Para grandes alterações, por favor, abra uma issue primeiro para discutir o que você gostaria de mudar.
