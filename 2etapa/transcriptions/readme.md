# YouTube Transcription Videos

Este projeto permite baixar e transcrever automaticamente áudios de vídeos do YouTube utilizando `yt-dlp` e `openai-whisper`.

## Requisitos

- Python 3.8 ou superior
- `ffmpeg` instalado no sistema (veja instruções abaixo)

## Instalação

1. Crie e ative um ambiente virtual:
   ```sh
   python -m venv transcription_venv
   source transcription_venv/bin/activate  # Linux/macOS
   transcription_venv\Scripts\activate  # Windows
   ```

2. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```

## Observações importantes

- O `ffmpeg` é um requisito do `openai-whisper` e precisa estar instalado separadamente:
  - **Linux (Ubuntu/Debian):** `sudo apt update && sudo apt install ffmpeg`
  - **Windows (Chocolatey):** `choco install ffmpeg`
  - **MacOS (Homebrew):** `brew install ffmpeg`