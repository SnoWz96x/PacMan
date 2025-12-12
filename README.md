# 🟡 Pacman PYGames

<p align="center">
  <img src="https://github.com/SnoWz96x/PacMan/blob/main/pacman-removebg-preview.png" width="500" alt="Pacman Gameplay"/>
</p>

<p align="center">
  <strong>Clone do clássico Pac-Man desenvolvido em Python com PyGame</strong>
</p>

---

## 🎮 Sobre o Projeto

Este projeto é uma **implementação completa do jogo Pac-Man**, desenvolvida **do zero em Python utilizando a biblioteca PyGame**.

O jogo reproduz fielmente:
- Sistema de **labirinto baseado em grid**
- **Comportamento individual dos fantasmas**
- **Power-ups**, colisões e sistema de pontuação
- Animações, vidas, vitória e game over

Todo o tabuleiro é controlado por uma **matriz numérica**, permitindo fácil modificação de mapas e níveis.

---

## 🧱 Estrutura do Tabuleiro (board.py)

<p align="center">
  <img src="pacman pieces.PNG" width="600" alt="Board Mapping"/>
</p>

### 📌 Legenda dos blocos

| Código | Elemento |
|------|---------|
| 0 | Espaço vazio |
| 1 | Ponto pequeno |
| 2 | Ponto grande (Power Pellet) |
| 3 | Parede vertical |
| 4 | Parede horizontal |
| 5 | Curva superior direita |
| 6 | Curva superior esquerda |
| 7 | Curva inferior esquerda |
| 8 | Curva inferior direita |
| 9 | Portão da casa dos fantasmas |

---

## 👻 Fantasmas e Inteligência

Cada fantasma possui **lógica de movimentação própria**, inspirada no comportamento clássico do jogo.

Durante o **power-up**, os fantasmas fogem do jogador e podem ser derrotados.

---

## 🕹️ Controles

| Tecla | Ação |
|-----|------|
| ↑ | Mover para cima |
| ↓ | Mover para baixo |
| ← | Mover para esquerda |
| → | Mover para direita |
| Espaço | Reiniciar |

---

## 📁 Estrutura do Projeto

```
Pacman_PYGames/
├── assets/
│   ├── ghost_images/
│   └── player_images/
├── board.py
├── pacman.py
├── pacman pieces.PNG
├── pacmanlvl1.jpg
└── README.md
```

---

## 🚀 Como Executar

```bash
pip install pygame
python pacman.py
```

---

## 🛠️ Tecnologias

<p align="center">
  <img src="https://img.shields.io/badge/Python-111111?style=for-the-badge&logo=python&logoColor=3776AB"/>
  <img src="https://img.shields.io/badge/PyGame-111111?style=for-the-badge&logo=pygame&logoColor=white"/>
</p>

---

## 👤 Autor

**SnoWz96x (Allan)**

<p align="center">
  <em>“Clássico, lógico e atemporal.” 🟡👻</em>
</p>
