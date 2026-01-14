ChatGPT por Voz com Whisper

Este projeto demonstra a integração de tecnologias de **Speech-to-Text** e **Text-to-Speech**, permitindo que o usuário faça perguntas por voz e receba respostas faladas utilizando inteligência artificial.

Tecnologias Utilizadas
- Python
- OpenAI Whisper (Speech-to-Text)
- OpenAI ChatGPT (Processamento de linguagem natural)
- Google Text-to-Speech (gTTS)

Funcionamento
1. O usuário fornece uma pergunta por áudio (`.mp3`)
2. O Whisper transcreve o áudio para texto
3. O ChatGPT processa a pergunta
4. A resposta é convertida em áudio usando gTTS

Como Executar o Projeto
```bash
pip install -r requirements.txt
python main.py
Projeto ChatGPT por Voz
