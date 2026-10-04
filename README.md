# 🎙️ Assistente Virtual com PLN em Python
 
## 📌 Descrição
 
Este projeto consiste no desenvolvimento de uma Assistente Virtual utilizando técnicas de Processamento de Linguagem Natural (PLN) em Python.
 
A aplicação é capaz de:
 
- Converter texto em áudio (Text-to-Speech);
- Converter fala em texto (Speech-to-Text);
- Interpretar comandos de voz;
- Realizar pesquisas na Wikipedia;
- Abrir o YouTube automaticamente;
- Localizar farmácias próximas utilizando o Google Maps.
 
O projeto foi desenvolvido utilizando bibliotecas de reconhecimento de voz e síntese de fala, com destaque para a biblioteca SpeechRecognition.
 
---
 
## 🚀 Funcionalidades
 
### ✅ Text-to-Speech (TTS)
 
Transforma texto em fala através da biblioteca Pyttsx3.
 
Exemplo:
 
```
Olá, eu sou sua assistente virtual.
```
 
---
 
### ✅ Speech-to-Text (STT)
 
Captura a voz do usuário e converte em texto utilizando reconhecimento de fala.
 
Exemplo:
 
```
Usuário: Abra o YouTube
```
 
Resultado:
 
```
Você disse: abra o youtube
```
 
---
 
### ✅ Pesquisa na Wikipedia
 
Comandos:
 
```
Pesquise inteligência artificial
```
 
A assistente realiza uma busca na Wikipedia e retorna um resumo do assunto.
 
---
 
### ✅ Abrir YouTube
 
Comandos:
 
```
Abra o YouTube
```
 
A aplicação abre automaticamente o navegador na página do YouTube.
 
---
 
### ✅ Encontrar Farmácia Próxima
 
Comandos:
 
```
Onde fica a farmácia mais próxima?
```
 
A aplicação abre o Google Maps com a pesquisa por farmácias próximas.
 
---
 
## 🛠️ Tecnologias Utilizadas
 
- Python 3.10+
- SpeechRecognition
- Pyttsx3
- PyAudio
- Wikipedia
- WebBrowser
 
---
 
## 📂 Estrutura do Projeto
 
```
assistente-virtual/
│
├── main.py
├── requirements.txt
├── README.md
│
├── voz/
│ ├── speech_to_text.py
│ └── text_to_speech.py
│
├── comandos/
│ ├── wikipedia_search.py
│ ├── youtube.py
│ └── farmacia.py
│
└── utils/
└── processador.py
```
 
---
 
## ⚙️ Instalação
 
### 1. Clone o repositório
 
```bash
git clone https://github.com/seuusuario/assistente-virtual.git
```
 
### 2. Acesse a pasta do projeto
 
```bash
cd assistente-virtual
```
 
### 3. Crie um ambiente virtual
 
Windows:
 
```bash
python -m venv venv
venv\Scripts\activate
```
 
Linux/Mac:
 
```bash
python3 -m venv venv
source venv/bin/activate
```
 
### 4. Instale as dependências
 
```bash
pip install -r requirements.txt
```
 
---
 
## ▶️ Executando o Projeto
 
```bash
python main.py
```
 
---
 
## 🎤 Exemplos de Comandos
 
### Abrir YouTube
 
```
Abra o YouTube
```
 
### Pesquisar na Wikipedia
 
```
Pesquise Nikola Tesla
```
 
### Procurar Farmácia
 
```
Onde fica a farmácia mais próxima?
```
 
### Encerrar Assistente
 
```
Sair
```
 
---
 
## 🔮 Melhorias Futuras
 
- Integração com ChatGPT
- Reconhecimento avançado de intenções
- Previsão do tempo
- Controle de aplicativos do sistema
- Reprodução de músicas
- Integração com WhatsApp Web
- Interface gráfica com Tkinter
- Ativação por palavra-chave ("Olá Assistente")
 
---
 
## 👨‍💻 Autor
 
Projeto desenvolvido para fins acadêmicos e de aprendizado em Processamento de Linguagem Natural (PLN).
 
---
 
## 📚 Referências
 
- SpeechRecognition
- Pyttsx3
- Wikipedia API
- Python Documentation
Mostrar mais linhas
