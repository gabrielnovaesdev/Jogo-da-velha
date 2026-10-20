<div align="center">

# Jogo da Velha

**Jogo da velha para dois jogadores no navegador, com HTML, JavaScript e jQuery**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-2.2-0769AD?style=flat-square&logo=jquery&logoColor=white)
![Ano](https://img.shields.io/badge/2023-primeiros_passos-555?style=flat-square)

</div>

---

## Sobre

Um dos meus primeiros projetos com JavaScript. Dois jogadores informam seus apelidos, começam a partida e se alternam marcando as casas do tabuleiro. A cada jogada o programa confere linhas, colunas e diagonais e anuncia o vencedor.

## Como funciona

- **Tabuleiro como matriz:** cada casa guarda `-1` para o jogador 1, `1` para o jogador 2 e `0` quando está vazia.
- **Vitória pela soma:** se uma linha, coluna ou diagonal soma `-3`, o jogador 1 venceu; se soma `3`, o jogador 2.
- **Turnos alternados:** um contador de rodadas define de quem é a vez (ímpar para o jogador 1, par para o jogador 2).
- **jQuery:** cuida dos cliques, da troca entre a tela inicial e o tabuleiro e da marcação das casas.

## Como abrir

```bash
git clone https://github.com/gabrielnovaesdev/Jogo-da-velha.git
cd Jogo-da-velha
start index.html   # Windows
open index.html    # macOS
```

## Situação atual

> [!WARNING]
> A pasta `imagens/`, com os ícones dos jogadores, o botão de iniciar e as marcações do tabuleiro, não foi enviada para o repositório. Por isso a página abre sem esses elementos e a partida não consegue começar. A lógica do jogo em `jogo.js` está completa.

Melhorias que ficaram para uma próxima versão:

- Enviar a pasta `imagens/` ou trocar as imagens por texto e CSS (`X` e `O`)
- Impedir que uma casa já marcada seja marcada de novo
- Detectar empate e oferecer uma nova partida
- Substituir o jQuery por JavaScript moderno

## Estrutura

```text
Jogo-da-velha/
├── index.html         # Tela inicial e tabuleiro
├── jogo.js            # Regras, turnos e verificação de vitória
└── jquery-2.2.1.js    # Biblioteca jQuery
```

---

<div align="center">

Feito por <a href="https://github.com/gabrielnovaesdev">Gabriel Novaes</a> em 2023 · Veja meus projetos mais recentes no <a href="https://github.com/gabrielnovaesdev">perfil</a>

</div>
