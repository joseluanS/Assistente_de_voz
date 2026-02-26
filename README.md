## Assistente de Voz Multilíngue: Whisper + ChatGPT + gTTS
Este projeto é o resultado do meu desenvolvimento no curso focado em tecnologias de Speech-to-Text (STT) e Text-to-Speech (TTS). Construí uma aplicação capaz de ouvir, processar e responder por voz em múltiplos idiomas, utilizando o estado da arte em modelos de Inteligência Artificial.

# 🚀 Sobre o Projeto
Desenvolvi um sistema que viabiliza conversas fluidas entre humanos e máquinas. A solução utiliza a sinergia entre o Whisper e o ChatGPT (OpenAI) para transcrição e inteligência, somada ao gTTS (Google Text-to-Speech) para a síntese de voz.

O fluxo do sistema funciona da seguinte forma:

Entrada de Áudio: O sistema captura a voz do usuário.

Transcrição & Tradução: Utilizo o modelo Whisper para converter a fala em texto, aproveitando sua alta precisão em diversos idiomas.

Processamento Cognitivo: O texto é enviado à API do ChatGPT, que interpreta a pergunta e gera uma resposta contextualizada e precisa.

Saída de Voz: Com a integração do gTTS, transformo o texto de retorno em áudio, permitindo que o assistente "fale" a resposta de volta para o usuário.

# 🛠️ Tecnologias Utilizadas
Python: Linguagem base para a integração de todas as ferramentas.

OpenAI Whisper: Responsável pela transcrição e tradução robusta de áudio para texto.

OpenAI ChatGPT API: O cérebro do projeto, fornecendo respostas inteligentes e adaptativas.

gTTS (Google Text-to-Speech): Biblioteca para converter as respostas textuais em fala natural.

# 🌟 Diferenciais
Multilinguismo: O projeto é capaz de compreender e responder em diferentes línguas, pavimentando o caminho para soluções de comunicação globais.

Agilidade: A integração foi pensada para ser ágil, ideal para aplicações de atendimento ou assistentes pessoais.

Acessibilidade: Ao utilizar voz como interface principal, o projeto explora novas formas de interação mais naturais e inclusivas.
