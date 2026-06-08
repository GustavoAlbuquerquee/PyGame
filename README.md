# Flapy - Protótipo Inicial

**Trabalho de Introdução à Programação - Semana 2**

Jogo inspirado em Flappy Bird, desenvolvido em Python usando Pygame.

## 📋 Descrição

O jogador controla um pássaro amarelo que precisa desviar de canos verdes. Ao pressionar ESPAÇO, o pássaro sobe, mas a gravidade constantemente o puxa para baixo. O jogo termina quando o pássaro colide com um cano ou toca o chão.

## 🎮 Como Jogar

1. Execute o jogo: `python main.py`
2. Pressione **ESPAÇO** para fazer o pássaro pular
3. Evite colidir com os canos e o chão
4. Pressione **ESC** para sair após o Game Over

## 📁 Estrutura do Projeto

```
PyGame/
├── main.py           # Ponto de entrada do jogo
├── README.md         # Este arquivo
└── src/
    ├── __init__.py   # Torna src um pacote Python
    ├── game.py       # Loop principal e lógica do jogo
    ├── player.py     # Classe do pássaro jogável
    └── pipes.py      # Classe dos obstáculos (canos)
```

## 🎯 Requisitos Cumpridos

✅ Jogo abre corretamente usando Pygame
✅ Loop principal funcional
✅ Jogador controla o personagem (tecla ESPAÇO)
✅ Elemento interativo na tela (cano móvel)
✅ Código organizado em múltiplos arquivos e funções
✅ Uso de classes e objetos
✅ Uso de condicionais e laços de repetição
✅ Modularização clara e didática

## 🔧 Conceitos Demonstrados

- **Funções**: `run_game()`, `jump()`, `update()`, `draw()`
- **Classes**: `Player`, `Pipe`
- **Objetos**: Instâncias de player e pipe
- **Condicionais**: Verificação de colisões, game over
- **Laços**: Loop principal do jogo (`while running`)
- **Modularização**: Separação em múltiplos arquivos

## 🎨 Elementos Visuais

- **Pássaro**: Retângulo amarelo (40x40 pixels)
- **Cano**: Retângulo verde (80x300 pixels)
- **Fundo**: Azul claro (céu)
- **Chão**: Marrom
- **Tela**: 800x600 pixels, 60 FPS

## 🚀 Próximos Passos (Entregas Futuras)

- Sistema de pontuação
- Múltiplos canos com espaçamento variável
- Tela de menu inicial
- Restart após Game Over
- Animações e efeitos sonoros
- Dificuldade progressiva

## 📦 Dependências

```bash
pip install pygame
```

## 👨‍🎓 Observações Acadêmicas

Este é um protótipo inicial simples e funcional. O código está abundantemente comentado para facilitar o entendimento de alunos iniciantes. Cada classe tem responsabilidades bem definidas, demonstrando boas práticas de organização de código.
