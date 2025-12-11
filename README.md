# Pong - Nand2Tetris (2 Jogadores)

Projeto da disciplina de Elementos de Sistemas Computacionais, desenvolvido em Jack como extensão do Pong original.

Funcionalidades:
- 2 jogadores (barra superior e inferior)
- Controles independentes por teclado
- Sistema de pontuação
- Game Over individual
- Reinício da partida sem reset
- HUD com título, score e instruções

Controles:
- Jogador 1 (embaixo): <-  ->
- Jogador 2 (em cima): A / D
- R: reiniciar
- ESC: sair

---
## **Estrutura do Projeto**
```

PongGame_Jack/
├── PongGame.jack     # Lógica principal do jogo: HUD, controles, colisões, placar e reinício
├── Bat.jack          # Implementação da barra (bat); quase igual ao original, com pequenas adaptações
├── Ball.jack         # Classe da bola; mantida igual ao projeto original, apenas limites ajustados
├── Main.jack         # Ponto de entrada do jogo; carrega e executa PongGame
├── README.md         # Documentação do projeto
└── imagens/          # Prints de tela
    ├── TelaInicial.png
    ├── TelaInicial2.png
    ├── Jogador1Perdeu.png
    └── Jogador2Perdeu.png

```
---