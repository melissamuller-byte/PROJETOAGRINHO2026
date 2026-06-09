# PROJETOAGRINHO2026
Markdown


# Eco-p5: Jogo de Sustentabilidade Ambiental 🌍🌱

Um jogo interativo e educativo desenvolvido em JavaScript utilizando a biblioteca **p5.js**. O objetivo do projeto é sensibilizar os utilizadores sobre a importância do cuidado com o meio ambiente através de mecânicas simples, onde o jogador deve combater a poluição e ajudar a natureza a florescer.

---

## 🎮 Como Jogar

O objetivo do jogo é preencher a barra de **Sustentabilidade** até ao máximo (100%) através de duas ações principais com o rato (mouse):

1. **Regar as Plantas:** Clica nas plantas na base do ecrã para fazê-las crescer. Cada rega aumenta o tamanho da planta e eleva a barra de sustentabilidade.
2. **Limpar a Poluição:** Clica nas nuvens cinzentas de poluição flutuantes para as eliminar do céu. Limpar a poluição dá um bónus maior na barra de sustentabilidade.

---

## 🚀 Funcionalidades

- **Mecânica de Clique (Interaction):** Interação direta com os elementos do cenário através do clique do rato.
- **Crescimento Dinâmico:** As plantas aumentam de tamanho progressivamente até atingirem o seu limite.
- **Barra de Progresso:** Feedback visual em tempo real do estado ecológico do ecossistema.
- **Programação Orientada a Objetos (POO):** Estrutura de código limpa e modular utilizando classes para gerir a `Terra`, as `Plantas` e a `Poluição`.

---

## 🛠️ Tecnologias Utilizadas

- **JavaScript (ES6+)**
- **[p5.js](https://p5js.org/):** Uma biblioteca JavaScript criada para tornar a programação acessível a artistas, designers, educadores e principiantes.

---

## 💻 Como Executar o Projeto

Existem duas formas fáceis de correr este jogo:

### Opção 1: P5.js Web Editor (Mais rápida)
1. Copia o código do ficheiro do jogo.
2. Abre o [p5.js Web Editor](https://editor.p5js.org/).
3. Cola o código na área de edição e clica no botão **Play (▶)**.

### Opção 2: Localmente no teu computador
1. Cria uma pasta no teu computador.
2. Cria um ficheiro `index.html` e inclui a biblioteca p5.js:
   ```html
   <!DOCTYPE html>
   <html lang="pt">
     <head>
       <script src="[https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js](https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js)"></script>
       <meta charset="utf-8" />
     </head>
     <body>
       <script src="sketch.js"></script>
     </body>
   </html>
