# 📌 Criando um Chatbot Baseado em Conteúdo de PDFs 🤖📚

## 🚀 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio "**Criando um Chatbot Baseado em Conteúdo de PDFs**" da DIO.  
O objetivo foi criar um sistema inteligente capaz de ler, interpretar e responder perguntas com base no conteúdo de documentos PDF, utilizando técnicas modernas de IA generativa, embeddings e busca vetorizada.

---

## 🧩 Cenário

Imagine que você é um estudante de Engenharia de Software e precisa revisar diversos artigos científicos para o seu TCC.  
Com o grande volume de PDFs, torna-se difícil extrair e conectar informações de maneira eficiente. 😵‍💫

Para resolver isso, foi criado um **Chatbot Inteligente** que:

- Lê e interpreta o conteúdo dos PDFs 📄
- Indexa as informações de forma vetorizada 📈
- Responde perguntas específicas baseadas nos textos carregados 🎯

---

## 🎯 Objetivos do Projeto

✅ Carregar e processar múltiplos arquivos PDF.

✅ Implementar um sistema de **busca vetorial** para indexar o conteúdo.

✅ Utilizar **IA generativa** para criar respostas contextuais.

✅ Desenvolver um **chat interativo** para consulta dos documentos.

---

## 🗂️ Estrutura do Repositório

```bash
📁 inputs
    ↳ Documentos de texto ou PDFs utilizados nos testes.
📁 src
    ↳ Scripts de processamento de PDFs, criação de embeddings e sistema de chat.
📄 README.md
    ↳ Este documento.
```

---

## 🔥 Processo de Desenvolvimento

1. **Preparação do Ambiente**  
   - Configuração no **Azure Foundry**.
   - Instalação de bibliotecas para lidar com PDFs e embeddings.

2. **Processamento dos PDFs**  
   - Extração de textos.
   - Limpeza e divisão em chunks para melhor indexação.

3. **Criação dos Embeddings**  
   - Geração de representações vetoriais dos textos.

4. **Implementação da Busca Vetorial**  
   - Armazenamento dos vetores em uma base de dados otimizada para buscas.

5. **Construção do Chatbot**  
   - Recebimento de perguntas.
   - Busca dos textos mais relevantes.
   - Geração de respostas utilizando IA.

---

## 📸 Prints do Projeto

### 🔵 Preparando Ambiente no Azure Foundry

*Adicionar aqui print da preparação no Azure Foundry.*

### 🟠 Processamento dos PDFs

*Adicionar aqui print do carregamento e processamento dos PDFs.*

### 🟣 Testando o Chatbot

*Adicionar aqui print da interface do chat em funcionamento.*

---

## ✨ Insights e Aprendizados

- O conceito de **embeddings** é fundamental para sistemas de busca inteligente.
- A combinação de **IA generativa** e **base vetorizada** cria experiências de chatbot muito mais personalizadas e eficazes.
- Organizar os dados em chunks e vetores melhora a performance e a relevância das respostas.
- Criar seu próprio "mini ChatGPT" focado em documentos específicos é uma aplicação prática incrível de IA!

---

## 📈 Possibilidades de Melhoria

- Implementar autenticação para restringir acesso a determinados documentos.
- Melhorar a UX do chat com frameworks de frontend modernos como Streamlit, Gradio ou Dash.
- Expandir o sistema para aceitar outros tipos de documentos além de PDFs (ex: DOCX, HTML).
- Adicionar análise semântica para respostas ainda mais relevantes.

---

## 🛠️ Tecnologias Utilizadas

- Python 🐍
- Azure Foundry ☁️
- LangChain / Chroma / FAISS (para indexação vetorial)
- PyPDF2 / pdfminer
- OpenAI / HuggingFace (para geração de respostas)

---

## 🎯 Resultado

Com este projeto, consegui criar um assistente virtual que interpreta e responde com base em conteúdos específicos de PDFs, mostrando na prática o poder da **IA aplicada a informações proprietárias**.

---

**Bons estudos e sucesso na sua jornada de dados! 😉🚀**
