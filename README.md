# 💣 LogicBomb

> Um jogo de matemática rápida contra o relógio — resolva as contas antes que a bomba exploda!

---

## 🎮 Como Jogar

1. Na tela inicial, escolha o modo de jogo: **1 Player** ou **2 Players**
2. Clique em **JOGAR** para começar
3. Uma operação matemática aparecerá na tela (ex: `7 × 8`)
4. Digite a resposta no campo e pressione **Enter** ou clique na seta **→**
5. Responda antes que o cronômetro chegue a zero!

---

## 📋 Regras

### ⏱️ Tempo
- Cada pergunta tem um tempo limite para ser respondida
- O tempo começa em **10 segundos** e fica mais curto conforme você acerta
- Quando o timer chegar a zero, você perde uma vida automaticamente

### ❤️ Vidas
- Cada jogador começa com **3 vidas**
- Você perde uma vida ao **errar a resposta** ou ao **deixar o tempo acabar**
- Quando um jogador perde todas as vidas, o jogo termina

### ✅ Pontuação
- Cada resposta correta vale **1 ponto**
- A pontuação de cada jogador fica visível durante toda a partida

### 📈 Dificuldade
- O jogo fica progressivamente mais difícil: os números das operações aumentam conforme você pontua
- O tempo disponível por pergunta também diminui à medida que você acerta

### ➕ Operações
O jogo usa três tipos de operações matemáticas, escolhidas aleatoriamente:
- Adição `+`
- Subtração `-`
- Multiplicação `×`

---

## 👥 Modos de Jogo

### 🎮 1 Player
- Você joga sozinho contra o cronômetro
- O objetivo é pontuar o máximo possível antes de perder todas as vidas
- Ao fim, a tela de resultado exibe seus pontos, vidas restantes e o total de rodadas

### ⚔️ 2 Players
- Dois jogadores se alternam no mesmo dispositivo
- O jogador ativo é indicado pelo destaque no card e pelo badge no topo
- Perde quem ficar sem vidas primeiro
- O vencedor é exibido na tela final com 🥇, e os placares de ambos são comparados lado a lado

---

## 🏁 Tela de Resultado

Ao fim da partida, uma tela de placar exibe:

| Coluna   | Descrição                            |
|----------|--------------------------------------|
| Jogador  | Identificação do jogador e medalha   |
| Pontos   | Total de respostas corretas          |
| Vidas    | Vidas restantes (ou 💀 se zerou)     |
| Rodadas  | Número total de rodadas disputadas   |

Após o placar, você pode:
- **🔄 Jogar Novamente** — reinicia com o mesmo modo de jogo
- **🏠 Menu** — volta à tela inicial para trocar de modo

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| **HTML5** | Estrutura e marcação das telas do jogo |
| **CSS3** | Estilização, animações e responsividade |
| **JavaScript (Vanilla)** | Toda a lógica do jogo, controle de estado e manipulação do DOM |
| **Google Fonts** | Fontes [Orbitron](https://fonts.google.com/specimen/Orbitron) e [Rajdhani](https://fonts.google.com/specimen/Rajdhani) para a identidade visual |

O projeto é **100% front-end**, sem dependências externas de frameworks ou bibliotecas — apenas HTML, CSS e JS puros em um único arquivo.

---

## ✨ Destaques Visuais

- Grid animado no fundo com efeito de profundidade
- Timer com animação de pânico nos últimos 3 segundos
- Animação de **+1 flutuante** ao acertar uma resposta
- Score com efeito de salto ao ser atualizado
- Corações com animação ao serem perdidos
- Confete colorido ao final da partida no modo 2 Players

---

## 📁 Estrutura do Projeto

```
logicbomb/
└── logicbomb.html   # Arquivo único contendo HTML + CSS + JS
```

---

*Desenvolvido como um jogo de matemática rápida para um ou dois jogadores.*
