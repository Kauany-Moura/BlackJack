# ♠️ Blackjack Game

Este projeto é uma demonstração de um jogo de Blackjack com uma IA (Inteligência Artificial) em Python, usando o micro-framework web Flask. O objetivo é ilustrar como conceitos de **Probabilidade** e **Inteligência Artificial** podem ser aplicados na prática.

A aplicação separa a lógica do jogo (no back-end, em Python) da interface visual (no front-end, com HTML, CSS e JavaScript), usando uma API REST para comunicação.

<img src="Captura de tela 2025-11-03 225258.png" alt="Imagem do jogo" width="1000">

---

## 🎲 Funcionalidades

- **Jogo de Blackjack**: Lógica completa do jogo para um jogador contra o dealer.
- **IA com Múltiplos Níveis de Dificuldade**:
    - **Fácil**: A IA segue uma estratégia conservadora.
    - **Médio**: A IA segue a estratégia padrão do Blackjack (para em 17).
    - **Difícil**: A IA usa uma estratégia mais avançada, considerando a carta visível do jogador.
    - **Impossível**: A IA joga de forma perfeita, tornando o jogo praticamente imbatível.
- **Interface Web Interativa**: Uma interface simples e intuitiva para o jogo, com botões para "Comprar Carta" e "Parar".

---

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem de programação principal para a lógica do jogo e a IA.
- **Flask**: Micro-framework web para criar o servidor e a API.
- **HTML/CSS/JavaScript**: Para a interface do usuário (front-end).

---

## 🚀 Como Rodar o Projeto

1. Clone este repositório para sua máquina local:
   `git clone https://github.com/Kauany-Moura/BlackJack.git`
2. Abra o terminal e instale:
   `pip install flask`
3. Rode o Flask diretamente com Python:
   `python -m flask run`
4. Abra seu navegador e acesse:
   `http://127.0.0.1:5000`

---

## 📄 Estrutura do Projeto

- `app.py`: Contém o servidor Flask e a lógica do jogo.
- `requirements.txt`: Lista todas as dependências do Python.
- `static/`:
    - `style.css`: Estilização da interface.
    - `script.js`: Lógica do front-end e comunicação com a API.
- `templates/`:
    - `index.html`: A página principal do jogo.
