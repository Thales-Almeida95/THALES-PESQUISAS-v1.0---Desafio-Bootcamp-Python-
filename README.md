# 🎙️ THALES PESQUISAS v1.0 - Assistente de Voz Inteligente

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenAI](https://img.shields.io/badge/OpenAI-Whisper-blue?style=for-the-badge&logo=openai)
![Llama](https://img.shields.io/badge/Llama_3.3-Groq-orange?style=for-the-badge)

O **Thales Pesquisas v1.0** é um assistente virtual de voz completo desenvolvido para o Bootcamp Bradesco. O projeto utiliza tecnologias de ponta para transformar fala em texto, processar perguntas através de modelos de linguagem de larga escala (LLM) e responder audivelmente ao usuário.

## 🚀 Como Funciona o Pipeline

O projeto foi construído sobre quatro pilares fundamentais de Inteligência Artificial e Processamento de Sinais:

1.  **Captura de Áudio:** Gravação em tempo real via microfone com feedback visual (barra de progresso).
2.  **Transcrição (STT):** Utiliza o **Whisper AI** da OpenAI para converter o áudio em texto com alta precisão.
3.  **Inteligência (LLM):** O texto é processado pelo modelo **Llama 3.3 (70B)** via API da Groq, garantindo respostas rápidas e contextuais.
4.  **Síntese de Fala (TTS):** A resposta é convertida em voz masculina através do motor nativo do sistema operacional.



---

## 🛠️ Tecnologias Utilizadas

* **Python 3.12:** Linguagem base do projeto.
* **OpenAI Whisper:** Modelo de reconhecimento de fala para transcrição local.
* **Groq Cloud (Llama 3.3):** API de inferência ultra-rápida para processamento da linguagem.
* **PyAudio & Wave:** Manipulação de hardware e arquivos de som binários.
* **Pyttsx3:** Motor de síntese de voz (Text-to-Speech) que funciona offline.

---

## 📋 Pré-requisitos

Antes de rodar o projeto, você precisará instalar as bibliotecas necessárias:

```powershell
pip install pyaudio wave openai-whisper groq pyttsx3
Nota: Certifique-se de ter o FFmpeg instalado no seu sistema para o processamento de áudio.

⚙️ Configuração
Obtenha sua chave de API gratuita no console da Groq Cloud.

Abra o arquivo principal e insira sua chave na variável:

Python
CHAVE_GROQ = "sua_chave_gsk_aqui"
Execute o script:

PowerShell
python projeto1.py
🖥️ Interface do Sistema
O sistema conta com uma interface de terminal estilizada (Arte ASCII) e interativa:

Menu Principal: Opções claras de iniciar busca ou sair.

Barra de Progresso: Feedback visual em tempo real durante a gravação de 6 segundos.

Transcrição Limpa: O terminal é limpo automaticamente para exibir a resposta da IA de forma organizada.

Plaintext
    ##########################################################
    #             THALES PESQUISAS v1.0                      #
    ##########################################################
[ GRAVANDO ] PROGRESSO: 100% [████████████████████]
🎓 Créditos
Este projeto foi desenvolvido por Thales como parte do Desafio de Projeto no Bootcamp Bradesco - Python AI Backend Developer.


