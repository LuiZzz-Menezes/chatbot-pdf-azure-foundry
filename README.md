# 🤖 Chatbot com PDFs usando Azure AI Foundry

Este projeto faz parte do desafio da DIO: construir um chatbot inteligente que responde perguntas com base em PDFs, utilizando o Azure AI Studio (Foundry).

## 🚀 Tecnologias Usadas
- **Azure OpenAI (GPT-4o-mini)**
- **Azure AI Search / Knowledge Bases**
- **Azure AI Studio (Playground Chat)**

## ⚙️ Etapas Realizadas
1. Criação do projeto no Azure AI Studio.
2. Upload dos PDFs de artigos científicos.
3. Geração automática de embeddings e índice vetorial.
4. Configuração do Chat Playground conectado à base de conhecimento.
5. Teste interativo e deploy como Web App.
    1. “Durante o deploy do Web App, o serviço foi publicado com sucesso, mas o Azure AI Foundry apresentou uma limitação de identidade gerenciada (erro 400) ao tentar acessar a base de conhecimento. Isso ocorre porque o ambiente usa Key Vault protegido e não há identidade atribuída. Mesmo assim, o projeto foi totalmente configurado e testado dentro do Playground antes do deploy.”

## 🧠 Insights
Com o Azure AI Foundry, é possível montar um sistema de RAG completo **sem escrever código**. 
A IA busca as respostas diretamente nos PDFs carregados, permitindo consultas acadêmicas, resumos e cruzamento de informações.

## 📸 Prints
- Tela do upload dos PDFs.
- Tela do Chat respondendo perguntas.
- Tela de deployment.

## 🧩 Estrutura
inputs/

└── exemplo.txt

## 🌐 Demonstração
[Link do Chat publicado no Azure AI Studio](https://ai.azure.com)

