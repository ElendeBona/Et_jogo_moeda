# Jogo Et Contador de Moedas – Game Project in Python

![Autora: Elen de Bona](https://img.shields.io/badge/Autora-Elen%20de%20Bona-1e90ff?style=for-the-badge&logo=github)
![Python](https://img.shields.io/badge/Python-3.x-ffd43b?style=for-the-badge&logo=python)

Este projeto apresenta um jogo desenvolvido com **Pygame**, onde o jogador controla um alien verde em tempo real para coletar moedas geradas dinamicamente na tela. O objetivo é recolher o máximo de moedas antes de atingir o limite de 10 moedas na tela.

---

## Propósito do Projeto

A aplicação foi construída para demonstrar controle de sprites, manipulação de eventos de mouse, geração dinâmica de objetos e detecção de colisões. Um projeto educacional que evidencia os fundamentos essenciais do desenvolvimento de jogos 2D com Python e Pygame.

---

## Conceitos Técnicos Aplicados

- **Sprites personalizados** para jogador (alien) e moedas interativas
- **Eventos customizados** para geração de moedas em intervalos controlados e dinâmicos
- **Controle de taxa e dificuldade** com ajustes automáticos na velocidade de criação
- **Detecção de colisões baseada em retângulos** através de grupos de sprites
- **Renderização em múltiplas camadas** usando Pygame
- **Pontuação reativa**, atualizada em tempo real conforme moedas são coletadas
- **Laço principal estruturado**, garantindo lógica limpa e previsível
- **Gerenciamento de recursos externos**, como imagens PNG e efeitos sonoros WAV

---

## Como executar

1. Instale o Pygame:
```bash
pip install pygame
```

2. Execute o arquivo do projeto:
```bash
python Et_moedas.py
```

3. Use o **mouse** para controlar o ET e coletar as moedas!

---

### Dinâmica do Jogo

- **Objetivo**: Coletar moedas geradas aleatoriamente na tela
- **Pontuação**: Cada moeda coletada vale 10 pontos
- **Fim do jogo**: Quando 10 moedas estão simultaneamente na tela
- **Dificuldade**: A velocidade de aparecimento de moedas aumenta automaticamente conforme você coleta
- **Tempo**: Você tem +- 1 minuto para coletar o máximo de moedas possível, seja rápido!


---

Desenvolvido como projeto educacional. Se este jogo ajudou você a aprender, deixe uma ⭐ e compartilhe o conhecimento!
