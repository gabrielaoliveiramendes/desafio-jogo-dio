# Jogo Detona Ralph

Este repositório contém um jogo simples "Detona Ralph" desenvolvido como parte de um desafio do bootcamp da DIO (Digital Innovation One). O jogo desafia o jogador a acertar o Ralph que aparece aleatoriamente em quadrados na tela, dentro de um limite de tempo.

## Tecnologias Utilizadas
* **HTML:** Estrutura da página e organização dos elementos do jogo.
* **CSS:** Estilização da página, incluindo layout, cores e fontes.
* **JavaScript:** Lógica do jogo, manipulação do DOM, controle de tempo e pontuação.

## Funcionalidades

### HTML
* Estrutura básica da página com um container principal.
* Divisão do jogo em um menu superior (pontuação, tempo e vidas) e um painel de jogo com nove quadrados.
* Utilização de divs para representar os quadrados do jogo e o menu.

### CSS
* Utilização de flexbox para organizar os elementos do menu e do painel de jogo.
* Importação de fontes personalizadas do Google Fonts.
* Reset de CSS para garantir consistencia entre browsers.

### JavaScript
* **`state`**: Objeto que gerencia os elementos e dados do jogo.
* **`countDown()`**: Controla o tempo, e finaliza o jogo.
* **`playSound()`**: Reproduz sons do jogo.
* **`randomSquare()`**: Gera posições aleatórias para o inimigo.
* **`moveEnemy()`**: Inicia a movimentação do inimigo.
* **`addListenerHitBox()`**: Detecta cliques e atualiza a pontuação.
* **`initialize()`**: Inicia o jogo.
