
# 🎮 Projeto Jogo Silvio Santos

Este é um jogo de adivinhação inspirado no estilo de jogos do programa do Silvio Santos, desenvolvido com **React**. O objetivo do jogador é adivinhar palavras com base em dicas de categorias.  

## 🚀 Tecnologias Utilizadas

- React.js ⚛️
- CSS para estilização 
- Gerenciamento de estado com `useState` e `useEffect` 
- Lógica de manipulação de palavras e categorias 📖

---

## 🛠️ Como Executar o Projeto

### ✅ **Pré-requisitos**

Antes de começar, certifique-se de ter instalado:  
- [Node.js](https://nodejs.org/) 
- npm

### 📌 **Passo a Passo**

1. **Clone o repositório**  
   ```bash
   git clone https://github.com/GabrielRibeiroRodrigues/Projeto_Jogo_Silvio_Santos.git
   ```

2. **Acesse a pasta do projeto**  
   ```bash
   cd PROJETO_JOGO_SILVIO_SANTOS/secretword
   ```

3. **Instale as dependências**  
   ```bash
   npm install
   ```
   ou, se estiver usando Yarn:
   ```bash
   yarn install
   ```

4. **Inicie o servidor de desenvolvimento**  
   ```bash
   npm start
   ```
   ou:
   ```bash
   yarn start
   ```

5. **Abra no navegador**  
   Acesse:  
   ```
   http://localhost:3000
   ```

---

## 🎯 Como Jogar

- O jogo inicia na **tela inicial**. Clique em "Começar" para iniciar.  
- Você verá uma palavra oculta e uma dica da **categoria** correspondente.  
- Digite letras no campo de entrada para tentar adivinhar a palavra.  
- Você pode errar até **três vezes** antes de perder o jogo.  
- Se acertar todas as letras, a pontuação aumenta e uma nova palavra é sorteada.  

---

## 📂 Estrutura do Projeto

```
📂 PROJETO_JOGO_SILVIO_SANTOS
 ├── 📂 src
 │   ├── 📂 components  # Componentes do jogo
 │   │   ├── StartScreen.js
 │   │   ├── Game.js
 │   │   ├── GameOver.js
 │   ├── 📂 data
 │   │   ├── words.js  # Lista de palavras do jogo
 │   ├── App.js  # Lógica principal do jogo
 │   ├── App.css  # Estilização global
 │   ├── index.js  # Entrada principal do React
 ├── package.json  # Dependências do projeto
 ├── README.md  # Documentação do projeto
```

---

## 📌 Funcionalidades Principais

- ✅ **Escolha aleatória de palavras** e categorias  
- ✅ **Verificação de letras digitadas**  
- ✅ **Contagem de tentativas restantes**  
- ✅ **Pontuação baseada no desempenho do jogador**  

---


