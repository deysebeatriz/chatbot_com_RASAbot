# Chatbot com Rasa – Trilha para ELAS: Introdução à Inteligência Artificial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/deysebeatriz/chatbot_com_RASAbot/HEAD)


Este é um chatbot desenvolvido com [Rasa](https://rasa.com/) com o objetivo de responder dúvidas frequentes (FAQ) sobre o **programa [TIC em Trilhas](https://ticemtrilhas.org.br/).**

As informações utilizadas no chatbot foram extraídas diretamente da seção oficial de FAQ da plataforma TIC em Trilhas:  🔗 https://ticemtrilhas.org.br/

---


##  Como usar?

Você pode executar o projeto no ambiente Binder clicando no botão abaixo:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/deysebeatriz/chatbot_com_RASAbot/HEAD)

Ou, para rodar localmente:

**1. Clone o repositório:**
   ```bash
   git clone https://github.com/deysebeatriz/chatbot_com_RASAbot.git
   cd chatbot_com_RASAbot
   ```

**2. Crie um ambiente virtual e ative:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # ou venv\Scripts\activate no Windows
   ```

**3. Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

**4. Treine o modelo Rasa:**
   ```bash
   rasa train
   ```

**5. Execute o bot:**
   ```bash
   rasa shell
   ```

---

## 🧠 Intenções do chatbot

O chatbot responde perguntas como:

- Qual o diferencial das trilhas?
- Posso cursar mais de uma trilha?
- As trilhas possuem certificado?
- Por quanto tempo terei acesso?
- Posso fazer módulos separadamente?

---

## 🛠️ Estrutura do projeto

- `nlu.yml` – Intenções do usuário e exemplos de frases
- `domain.yml` – Respostas, intents e entidades
- `stories.yml` – Fluxos de conversas
- `test_stories.yml` – Testes automatizados
- `rules.yml` – Regras simples de diálogo
- `actions.py` – Ações customizadas (se necessário)

---

## 🤝 Contribuição

Sinta-se à vontade para contribuir com melhorias, correções ou expansão do FAQ!  
Basta criar um fork, realizar alterações e enviar um pull request.

---

## 🧾 Licença

Este projeto é open source e pode ser usado livremente para fins educacionais.

---

Projeto desenvolvido como parte da iniciativa **Trilha para ELAS – Introdução à Inteligência Artificial**.  
Inspirado no conteúdo da plataforma TIC em Trilhas.
